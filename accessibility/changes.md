// Your recommended changes go here

## Visual to the UI (CSS, visual elements)

## Technical changes: HTML, CSS, Javascript, ARIA attributes

## Content
violation: Ensures all ARIA attributes have valid values
HTML: <button class="btn btn-green btn-md btn-block btn-success
zipBtn" aria-describedby="zip-code-form" aria-controls="zip-results"
aria-flowto="zip-search-results">CONTINUE</button>

Summary: • Invalid ARIA attribute values: aria-controls="zip-results"
aria-flowto="zip-search-results"

Violation: Ensures the contrast between foreground and background
colors meets WCAG 2 AA contrast ratio thresholds

HTML: <h2 class="accessibility">Footer</h2>

Summary:  Element has insufficient color contrast of 1.00 (foreground
color: #f7f7f7, background color: #f7f7f7, font size: 18.0pt, font
weight: normal)

Violation: Ensures every id attribute value is unique
HTML: <div id="prefix-overlay-form-div">
Summary: Document has multiple elements with the same id attribute:
prefix-overlay-form-div

Violation: Ensures every form element has a label
HTML: <select name="q_23536" class="prefix-questionId">

Summary: aria-label attribute does not exist or is empty

Violation: Ensures the contrast between foreground and background
colors meets WCAG 2 AA contrast ratio thresholds
HTML: <label id="qa-single-household" for="single-household"
class="btn radio-label selected">
Summary: • Element has insufficient color contrast of 3.84 (foreground
color: #cfeffc, background color: #2d8611, font size: 12.0pt, font
weight: bold)Related Nodes:

