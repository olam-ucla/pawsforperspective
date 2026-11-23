---
layout: default
title: Home
---

<div class="collage">
<div class="collage-tile"><img src="{{ '/images/hero-1.jpg' | relative_url }}" alt="Cartoon animal character from a children's book" onerror="this.style.display='none'"></div>
<div class="collage-tile"><img src="{{ '/images/hero-2.jpg' | relative_url }}" alt="Cartoon animal character from a children's book" onerror="this.style.display='none'"></div>
<div class="collage-tile"><img src="{{ '/images/hero-3.jpg' | relative_url }}" alt="Cartoon animal character from a children's book" onerror="this.style.display='none'"></div>
<div class="collage-tile"><img src="{{ '/images/hero-4.jpg' | relative_url }}" alt="Cartoon animal character from a children's book" onerror="this.style.display='none'"></div>
<div class="collage-tile"><img src="{{ '/images/hero-5.jpg' | relative_url }}" alt="Cartoon animal character from a children's book" onerror="this.style.display='none'"></div>
</div>

<p class="photo-credit">Image credits: add the source for each picture here.</p>

# Welcome to our website

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

## About

This project was done by Olivia, Spoorthi, Madison, Vivienne, Murad and Anika. Meet the team on the [About](about) page.

## Key finding

<div class="callout"><strong>Main result:</strong> Replace this with your key finding once your analysis is done.</div>

## Explore the project

<div class="tile-grid">
<a class="tile" href="{{ '/background' | relative_url }}"><span class="tile-icon">📚</span><span class="tile-title">Background</span><span class="tile-desc">Context and related work</span></a>
<a class="tile" href="{{ '/methods' | relative_url }}"><span class="tile-icon">🔍</span><span class="tile-title">Methods</span><span class="tile-desc">How we did the research</span></a>
<a class="tile" href="{{ '/results' | relative_url }}"><span class="tile-icon">📊</span><span class="tile-title">Results</span><span class="tile-desc">What we found</span></a>
<a class="tile" href="{{ '/datacritique' | relative_url }}"><span class="tile-icon">🧐</span><span class="tile-title">Data Critique</span><span class="tile-desc">Limits and biases in our data</span></a>
<a class="tile" href="{{ '/discussion' | relative_url }}"><span class="tile-icon">💬</span><span class="tile-title">Discussion</span><span class="tile-desc">What it all means</span></a>
<a class="tile" href="{{ '/about' | relative_url }}"><span class="tile-icon">🐾</span><span class="tile-title">About</span><span class="tile-desc">Meet the team</span></a>
<a class="tile" href="{{ '/references' | relative_url }}"><span class="tile-icon">🔖</span><span class="tile-title">References</span><span class="tile-desc">Sources we used</span></a>
</div>
