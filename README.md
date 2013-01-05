jBar
====

jBar, the lightweight jQuery notification plugin.

Include it in your page with jQuery to initiate jBar:

    <script src="//ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
    <script src="js/jbar.js"></script>
    <script>
    $(function () {
        $.jBar();
    });
    </script>


Options to choose from to quickly configure the jBar with your colours, call to actions, entrance duration and more:

    <script>
    $(function () {
      $.jBar({
            type: 'fixed', // fixed/static
            delay: '1000', // Entrance delay (milliseconds)
            backgroundColor: '#DB5903', // Background Color
            borderColor: '#FFF', // Background Color
            buttonTextColor: '#FFF', // Button Text
            buttonColor: '#333', // Button Color
            buttonColorHover: '#222', // Button Color Hover
            calltoAction: 'jBar Plugin! A simple and lightweight notification banner.', // Call to action text
            buttonText: 'Download it!', // Button Text
            buttonLink: 'http://www.toddmotto.com/jbar-plugin-the-jquery-call-to-action-bar' // Hyperlink from button
      });
    });
    </script>
