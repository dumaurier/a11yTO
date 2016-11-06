---
layout: default
permalink: screenreaders
---

# Terry Bray

## @gtbray

Bank of Montreal - Looking for an engineer and an analyst

Wants to make to more interactive. Become more like a11y camp is. Doesn't want to tell us what the best screen reader is. Wants to help promote the use of screen readers are at a beginner level.

Do you use it for testing?
- yes
- QA and UAT
- Should use someone with a disability for UAT
- Not all testing is done in Windows

**Voice Over**

- Not as customisable as other screen readers but must be supported.
- Consolidate what you're seeing with what you're hearing.
- Don't rely too much on what you're seeing.
- **TURN THE MONITOR OFF** when testing

Voice Over changes the gestures. Changes core functionality of the OS. Swipe and touch.

### BAD ADVICE: use the tab key to move around the elements.

This skips reading what is between the element! Links to links. Focusable element to focusable elements. Table cells. Inputs.

They changed the way we interact.

**Accelerator Keys**
Not available in  voice override

- allow you to move quickly between elements on the Page
- hotkeys for navigation
- that is how the adaptive user should be using it

When you're testing, if you want to test if all the links are properly labelled. Press insert + f7, brings all links into a list.

**Big mistake: no alt text on links!**
Oops!

We have to make sure we're doing this in single-page apps. Especially when the src is empty or void();

Make sure the alt text is meaningful.

Presents content in a way that is meaningful to the user. For the screen reader, they take that information and load it into a virtual buffer. The webpage, to the user looks like a Word document. The screen reader user ALWAYS reads a page top to bottom.

**Turn of automatic reading of the page**

## Ads - how to deal with them

Are the ads relevant to the screen reader user? If they're at meaningful you should hide them.

- try to keep the colour contrast to one that is easy to use.
- don't care what colours we use
- how we format that add
- try to text simple. keep it descriptive.
- if you want to communicate to screen reader user - put the text in the background as same colour as the background itself.
- This is information only available to screen readers.
- don't put too much of a description in the alt tag. The screen reader can't interrupt it.

## Content Order

- tabindex. if you keep the tab order correctly. as long as that is good, then it will read it in that order.

- keep it in the CSS - gives the user control
- hidden text: -9999px trick. it might read it. Anything is visibly or invisible will be loaded by the screenreader.
- overlays can confuse screen readers. it reads the new content on top of the old content.
- be careful with interactions

## Usability on a11y

- running UX tests for screenreaders
- UAT Testing - there are people that do this all the time
- Not a big fan of companies using people with disability to do UAT unless it's their job

## For People that Know Nothing about Screen readers
- take a course
- find someone in the community
- it is possible to learn you to use one of your own but it can be very frustrating.
- Disconnect the mouse and the monitor
- Always learn to use the tools fully.


### Open source tools and a11y - WordPress/Joomla
Did they bother to install the Accessibility plugins. It comes back to the developers to put in the effort to make it so.

**Solved at the development level**
