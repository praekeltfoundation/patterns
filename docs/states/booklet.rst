Booklet
=======

A booklet is a pattern that applies for USSD. It allows an end-user
to read small bits of content from page to page. The content can be
dynamically loaded from an external API.

Code
~~~~

The state that implements this pattern is documented at the
`Go JSBox documentation <http://vumi-jssandbox-toolkit.readthedocs.org/en/latest/states.html#BookletState>`_.

Notes
~~~~~

-   There is a maximum window of 30 seconds within which the content
    needs to be displayed, read and be responded to before a timeout
    is reached.
-   There is no limit on how many pages a Booklet can contain,  the
    limits are all determined by the total session length that the
    mobile network operator imposes. In South Africa this is 3 minutes.
-   Characters per page is limited to roughly 160 characters, including
    any navigation elements (next, previous, etc...)
