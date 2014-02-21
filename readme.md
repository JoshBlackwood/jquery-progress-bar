##jQuery Progress Bar

A simple jQuery progress bar plugin for Bootstrap forms. Please give it a try with the demo.html page.

* Progress bar only advances when a required (can be HTML5 ``required`` attribute or a CSS class of ``.required``) field gains a value
* User-declarable progress messages. When calling the script, set breakpoints and messages in JSON format 
* Progress bar is collapsible
* Fully Section 508 compliant, with appropriate ``aria`` attributes and percentage readout for screen readers

To add or change default progress messages or positioning:

    $('#test_form').showProgress({ message: { '10': 'You\'re off to a great start!', '25': 'You\'re doing great so far!', '50': 'You\'re halfway there!', '75': 'Look at that, you\'re nearly done already!', '100': 'All done! Just click &lt;strong&gt;Submit&lt;/strong&gt; to continue!' }, position: 'bottom' });

Definitely still a work in progress. Please don't hesitate to submit any bugs! There's a lot of little details left to iron out