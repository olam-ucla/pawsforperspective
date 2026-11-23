---
layout: default
title: Home
---

<p class="big-question">Is a bear a he or a she?</p>
<p class="subtle">And who decides?</p>

This is the website for our Digital Humanities 101 project. We look at how children's books assign pronouns to animal characters. Animals in stories usually can't tell us who they are, so the author, the illustrator, and the reader fill that in. Those small word choices can carry big assumptions.

## Our research questions

<div class="question-card"><strong>Question 1:</strong> Replace this with your first research question.</div>
<div class="question-card"><strong>Question 2:</strong> Replace this with your second research question.</div>
<div class="question-card"><strong>Question 3:</strong> Replace this with your third research question.</div>

<div class="try-it">
<strong>Try it yourself</strong>
<p>Picture a bear in a children's story. Which pronoun comes to mind first?</p>
<div class="pronoun-buttons">
<button type="button" data-pronoun="he">he</button>
<button type="button" data-pronoun="she">she</button>
<button type="button" data-pronoun="they">they</button>
<button type="button" data-pronoun="it">it</button>
</div>
<p id="pronoun-result"></p>
</div>
<script>
document.querySelectorAll('.pronoun-buttons button').forEach(function (btn) {
  btn.addEventListener('click', function () {
    document.querySelectorAll('.pronoun-buttons button').forEach(function (b) { b.classList.remove('active'); });
    btn.classList.add('active');
    document.getElementById('pronoun-result').textContent =
      'You picked "' + btn.dataset.pronoun + '". Now ask yourself why. If the story never said, where did that answer come from? That is the question this project studies.';
  });
});
</script>

## Key finding

<div class="callout"><strong>Main result:</strong> Replace this with your key finding once your analysis is done.</div>

## Image credits

- Picture 1: title, creator, and link to the source
- Picture 2: title, creator, and link to the source
- Picture 3: title, creator, and link to the source
