# Functional Buttons Demo

## Overview
This project demonstrates basic interaction and state management in a simple web application using Vanilla JavaScript. It features two functional buttons: one that tracks and displays the number of times it has been clicked, and a second 'Reset' button that restores the first button to its initial state.

## Setup
No complex setup is required. Save the provided HTML content as `index.html` and open it in any modern web browser.

## Usage
1. **Click Me Button:** Click this button to see its text update, reflecting the cumulative number of clicks.
2. **Reset Button:** Click this button to revert the text of the 'Click Me' button back to its original label and reset the internal click counter to zero.

## Improvements (Round 2)
In Round 2, the application was significantly enhanced by introducing state management functionality:

1.  **Added 'Reset' Button:** A second button labeled 'Reset' was added next to the primary button.
2.  **State Control:** The 'Reset' button implements key state control by changing the primary button's displayed text back to its initial value ('Click Me').
3.  **Synchronized State:** Crucially, the internal JavaScript variable (`clickCount`) tracking the clicks is also reset, ensuring that subsequent clicks on the primary button continue the counting sequence correctly from zero.
4.  **UI Refinement:** Minor CSS adjustments were made to better style and position both buttons side-by-side using a flexible layout.

## MIT License
This project is released under the MIT License.