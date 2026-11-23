---
title: Data Critique
---

[Home](./)

# Data Critique

## Overview

The datasets we are working with are kids-book-animals.csv and survey-animal-stories.csv from the “Bears Will Be Boys” dataset on the Pudding GitHub page. The kids-book-animals data includes the book title, animal, animal group, pronoun, author, publication year and decade, publisher, ISBN, Goodreads link, description, cover image, rating count, average rating, and review count. This dataset gives us a comprehensive overview of the books. The dataset can illuminate which animals skew male or female in popular picture books (bears, rabbits, and mice skew male; birds, ducks, and cats skew female), whether the male skew shifts across decades, how gender patterns relate to popularity, authorship, and publishers, and the overall ratio: about 66% he/him, 31% she/her, and 2.6% other. The survey-animal-stories.csv includes information from people who participated in the Pudding survey. It has information on the animal shown in the prompt and how participants responded when gendering the creature. This dataset could tell us about people’s natural tendencies regarding gender in animals. What these datasets cannot tell us is why authors chose these genders, how children or parents read the characters, gender in illustrations or in unpronounced animals, non-binary or ambiguous representation beyond a thin “it” category, whether less-rated books look different and anything about causes, since the dataset only describes patterns. 


Although our dataset allows us to identify patterns in the gender representation of animal characters in children's books, it is important to recognize that datasets are not completely objective or representative. The books selected, information collected, and categories used to organize the data all influence the conclusions we can draw.

Our dataset contains 841 animal-character records associated with 284 unique Goodreads links, with publication years ranging from 1697 to 2023. While this provides a useful foundation for investigating gender representation in children's literature, several limitations must be considered.

## 1. Selection and Representation Bias

One limitation of our dataset is the way books were selected. The original researchers focused primarily on popular English-language children's picture books, using sources such as Goodreads, the New York Times bestseller list, and Miami University's Children's Book Database. They also aimed to include approximately 30 books per decade starting in 1950, while adding some older classics. This selection process may introduce popularity bias because less popular, independently published, and culturally underrepresented books are less likely to be included.

Additionally, the researchers excluded anthologies and collections, such as Grimm's Fairy Tales. Although they used GPT-4o and manual evaluation to identify books featuring animals, the selection process still reflects the limitations of the sources and methods used. Therefore, our findings may not represent children's literature as a whole, but rather a specific selection of popular picture books.

## 2. Gender Classification and Pronouns

The researchers primarily assigned gender to animal characters based on pronouns and other gender-specific language in the books. However, this method excludes other ways gender may be communicated, such as through illustrations, clothing, and character names. Animals referred to only in groups, such as "the birds," were also excluded, along with animals whose names already indicate biological sex, such as cows, hens, and roosters. These decisions create consistency but limit which characters are represented.

The gender categories are also relatively restrictive. Most characters are classified as either he/him or she/her, with a small "other" category that includes characters referred to as "it." This does not fully capture nonbinary or ambiguous gender representation. Additionally, pronouns reflect the language authors use rather than necessarily representing how readers interpret a character's gender.


## 3. Historical and Geographic Limitations

The books in our dataset have publication years ranging from 1697 to 2023, but they are not evenly distributed across this period. Certain decades contain considerably more records than others.

As a result, changes in gender representation over time may reflect differences in the number and types of books included rather than broader historical trends.

Our original dataset also lacks direct information about authors' nationalities, countries of publication, and story settings.

Although we created an additional geographic visualization using publisher headquarters information, headquarters locations do not necessarily indicate where books were written, originally published, or culturally situated.

These limitations make it difficult to draw conclusions about gender representation across different countries and cultures.

## 4. Data Structure and Sample Size

Although our dataset contains 841 animal-character records, these records come from only 284 unique Goodreads links. Since individual books can contain multiple animal characters, some books may contribute more observations than others. This means the records are not necessarily independent, and books with more animal characters may have a greater influence on the overall gender distribution.

The dataset also has uneven representation across animal groups, decades, and publishers, making certain comparisons less reliable. Additionally, there are missing values for 38 ISBNs, 33 decades, and 11 publication dates, which may limit some of our analyses. The survey dataset represents a separate collection of responses and should not be treated as additional book-level observations.


## 5. Missing Information and Context

Our dataset does not include important contextual information that could help explain gender representation. For example, we do not know the authors' genders, cultural backgrounds, or intentions when assigning genders to animal characters. We also lack information about the animals' personalities, appearances, and narrative roles. As a result, we cannot determine whether male and female animals are associated with different stereotypes or character roles, such as leadership, bravery, or caregiving.

Other missing information includes book sales, library circulation, reader demographics, and how children or parents interpret these characters. Although Goodreads ratings and review counts provide some indication of popularity, they do not necessarily reflect how widely books are read. Without this additional context, we can identify patterns and associations in gender representation, but we cannot explain why these patterns exist or what effects they may have on young readers.


## Conclusion

Overall, these datasets provide a useful foundation for examining gender representation in children's picture books and how people associate gender with different animals. They allow us to identify patterns across animal groups, publication periods, and book characteristics. However, the emphasis on popular English-language books, reliance on pronouns for gender classification, uneven representation, and lack of contextual information limit how broadly we can generalize our findings.

Most importantly, the datasets describe patterns rather than explain their causes or consequences. Recognizing these limitations helps us interpret our results more responsibly and highlights opportunities for future research, such as including more diverse children's literature, examining illustrations and character roles, and studying how children interpret gender in animal characters.

