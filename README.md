# Inconsistent Focus Styling with :focus-visible

This repository demonstrates a common, yet subtle, issue with the CSS `:focus-visible` pseudo-class. The problem involves inconsistent focus styling across different browsers and input methods, potentially impacting accessibility.

## Bug Description

The `bug.css` file contains a simple CSS rule using `:focus-visible` to apply a focus outline.  However, the focus indicator might not reliably appear in all scenarios depending on the browser and how the element receives focus (mouse click, keyboard navigation, assistive technology). This inconsistency can lead to usability problems for users relying on visual focus cues.

## Solution

The `bugSolution.css` file presents a potential solution using a more robust focus style approach that avoids relying entirely on `:focus-visible`.  It ensures some level of focus indication in all situations. Consider using a polyfill for broader support. 