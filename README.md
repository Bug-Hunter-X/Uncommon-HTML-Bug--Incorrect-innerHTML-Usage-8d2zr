# Uncommon HTML Bug: Incorrect innerHTML Usage

This repository demonstrates a subtle but potentially problematic error related to the use of `innerHTML` in HTML and JavaScript.

## Bug Description
The provided `bug.html` file uses `innerHTML` to append a new paragraph to an existing div. While seemingly simple, this approach can be inefficient and lead to unexpected behavior, especially when dealing with larger amounts of content.

## Solution
The `bugSolution.html` file presents a more efficient and robust method to achieve the same outcome.  Instead of directly manipulating `innerHTML`, it uses `insertAdjacentHTML` which is generally safer and often provides better performance.

## How to Reproduce
1. Clone the repository.
2. Open `bug.html` in your browser. Observe the rendered output.
3. Open `bugSolution.html` and compare the results. Note that the solution is more efficient and prevents potential side effects.

## Lessons Learned
* Avoid unnecessary manipulation of `innerHTML`.
* Favor `insertAdjacentHTML` for better performance and security.