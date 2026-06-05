# 00 Browser Inline JS

This phase shows JavaScript in its earliest practical role: small snippets running directly inside a browser page.

There is no npm, no backend, no build tool, no module system, no framework, and no separate JavaScript file. The browser loads `index.html`, parses the HTML, and runs the JavaScript that is written directly inside the page.

## Run It

Open `index.html` directly in a browser.

No install step is needed.

## What To Notice

- JavaScript is attached directly to HTML with `onclick` attributes.
- Functions and variables live in the global scope.
- The browser is the runtime.
- The page can react to clicks without a server.
- The code is easy to start with, but it would get messy as the page grows.

## Mental Model

At this stage, JavaScript is not yet an application architecture. It is a browser scripting language used to add small interactive behaviors to otherwise static pages.

## Pain That Leads To The Next Phase

Inline JavaScript mixes structure and behavior in the same file. As interactions grow, the HTML becomes harder to read and the JavaScript becomes harder to organize.

The next phase introduces DOM events and moves toward a cleaner separation between markup and behavior.

