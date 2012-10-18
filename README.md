# deck.js iframes

A little deck.js plugin to defer loading of iframes until their slide is
(almost) active

## Installation

Add the script to your deck's html and call it:

    <script src="[your server]/deck.iframes.js"></script>
    <script>
        $(function() {
            $.deck('iframes');
        });
    </script>
