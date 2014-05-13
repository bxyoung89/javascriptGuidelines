A Walrussy Guide to Javascript!
====================

Hello!  You have found the page for my personal Javascript guidelines.  As I have been doing web programming, I've tried to be very cognizant of coding standards, style guides, and best practices.  It is my intention to make this a comprehensive guide to everything I've learned, and what I tend to do day to day.

However, please take all of these guidelines with a grain of salt. Nobody is "bad" if they deviate from my way of programming. These are just meant to show my reasoning. However, no matter what you choose, you should always strive to be consistent!

## Table of Contents

  1. [Principles](#principles)
  1. [General](#general)

## Principles

I forget where I heard it or the exact phrasing but I remember JSON Discoverer, Douglas Crockford, saying that you should avoid writing code that could be construed as a bug. This is one of the founding principles that I try to abide by.


**[⬆ back to top](#table-of-contents)**

## General

  - Use tabs.

    ```javascript
    // bad
    function() {
    ∙∙∙∙var name;
    }

    // bad
    function() {
    ∙var name;
    }

    // good
    function() {
    ∙∙var name;
    }
    ```

**[⬆ back to top](#table-of-contents)**
