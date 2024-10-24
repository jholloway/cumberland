# 🌊 Cumberland

Cumberland is a simple tool to help with copyediting. It automatically highlights text in a textarea in different colors according to assigned severity levels of the issues detected using regular expression rules.

There is also a text manipulation tool that allows you to quickly lowercase or uppercase text, remove extra spaces, remove bullets and leading spaces, and more.

[Use Cumberland](https://holloway.me/cumberland)

All functions of this tool happen client-side via JavaScript. Nothing is saved to a database or sent to a server. If you wanted, you could save the `index.html` file, two `.js` files, and `.css` file to your local machine and run it completely offline.

The built-in rules are explained within the textarea and are based on the ones the Metro Nashville Information Technology Services Department's Digital Experience team uses to clean text content posted on the Nashville.gov public website. It should be easy to modify the rules to fit your needs.

This tool heavily uses the jQuery plugin **[highlight-within-textarea](https://lonekorean.github.io/highlight-within-textarea/)** by [@lonekorean](https://github.com/lonekorean).
