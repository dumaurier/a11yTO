---
layout: default
permalink: forms
---

# Rabab Gomaa

## Acessible and Usable Forms

To explore coding techniques that make web forms accessible and usable for all users.

### What is WAI-ARIA and when to use it?

**First rule of ARIA:**
Use a native HTML element instead of ARIA as long as it is possible.

When you change the semantics of an element you need to backfill functionality that exists by default in HTML.

Screen readers informs user when they have entered into a form "Form Mode" by playing a sound.

Don't use <div> and <span> when correct, semantic elements will work.

**Labeling Controls**

- use id/for
- use 'aria-labelledby' attribute
- use implicit labelling

**Placeholder**

-Use for short descriptions
-Never replaces the need for proper labelling

Place label above the form fields and position labels to the right of radio buttons and checkboxes.
