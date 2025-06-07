---
title: About
---
# About this Site

This site is part of the Programming by Stealth tutorial and podcast series co-created by [Bart Busschots](https://www.bartb.ie/) and [Allison Sheridan](https://www.podfeet.com/). You'll find the series itself at [pbs.bartificer.net](https://pbs.bartificer.net/).

{% include figure.html src="/illustrations/pbs_logo.png" alt="The silhouette of a ninja head wrapped with curly braces" caption="The _Programming by Stealth_ Logo" %}

Starting in early 2025, larger Programming by Stealh series is exploring the use of [GitHub Pages](https://pages.github.com) in general for hosting client-side web apps and statically generated websites in general, and [Jekyll](https://jekyllrb.com)-based sites in particular. This site is being built as a worked example throughout this series-within-a-series.

{% capture side_note_test -%}
Did you know that an _aside_ is a side note?
{%- endcapture %}
{%- include side_note.html content=side_note_test %}

{%- include side_note.html content=side_note_test title="Prova" %}

{%- include side_note.html content=side_note_test title="Prova con URL" more_info_url="https://pbs.bartificer.net"%}

I need additional content to understand whether the side notes are actually displayed properly. This paragraph should wrap around the side notes. And should be long enough to span a consistent height, so that the side notes have actually space enough to be displayed. I am still not happy enough, so that I have to add additional text to make sure that the paragraph is really acting as expected. And still this is not enough. I am starting to get annoyed by everything: should I continue writing all of this? Does it really make sense? The paragraph text is going below the bottom margin of the tallest side note, but the last line is still not going again full width. And now I did it! Finally the paragraph is long enough for the last lines to correctly wrap around, as expected.

{% capture bartificer_logo_alt -%}
A green lower-case letter 'b' wrapped in orange chevrons over the word 'bartificer' mostly in green except for the letters 'art' which are in orange to match the chevrons. All this is over a dashed orange line below which is the word 'creations' in green.
{%- endcapture -%}
{%- capture bartificer_logo_caption -%}
The Bartificer Creations Logo. The name *Bartificer* is a [portmanteau](https://www.wordnik.com/words/portmanteau) of *Bart* and *Artificer*, because an Artificer is a skilled craftsperson. 
{%- endcapture %}
{%- include figure.html src="/illustrations/bartificer_logo.png" alt=bartificer_logo_alt caption=bartificer_logo_caption %}