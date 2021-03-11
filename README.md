# draggable_div_js
Modified W3School's code for draggable divs to work for elements with margins
(the original code causes any draggable element with a margin to fly away)

See [here](https://danbatiste.github.io/draggable_div_js/example.html) for a demonstration.

Source for their original code: [https://www.w3schools.com/howto/howto_js_draggable.asp](https://www.w3schools.com/howto/howto_js_draggable.asp)


**Note:** The script must be loaded only after the draggable elements exist. I recommended deferring it to the footer.
Deferring scripts also reduces FCP and FID which are two important speed metrics that [Google uses to rank pages (2019)](https://support.google.com/webmasters/answer/9205520?hl=en).
