Paged Result Set
================

The paged result set allows an end-user to page through a set of results
that is larger than the communication channel is able to display fully.


Code
~~~~

The state that implements this pattern is called the PaginatedChoiceState_
and is documented at the `Go JSBox documentation`_.

Implementations
~~~~~~~~~~~~~~~

-   `RTS Zambia`_ uses a paged result set to allow an end user to page
    through a list of districts.
-   Switchboard_ uses a paged result set to allow a community health worker
    to select a cadre from a long list of cadres.
-   mAgriculture_ used a paged result set to allow a farmer to select
    crops from a long list of known crops.

Notes
~~~~~

-   the PaginatedChoiceState_ is a variation of the ChoiceState_ but
    adds the ability to page through a larger set.


.. _`Go JSBox documentation`: http://vumi-jssandbox-toolkit.readthedocs.org/
.. _PaginatedChoiceState: http://vumi-jssandbox-toolkit.readthedocs.org/en/latest/states.html#PaginatedChoiceState
.. _ChoiceState: http://vumi-jssandbox-toolkit.readthedocs.org/en/latest/states.html#ChoiceState
.. _`RTS Zambia`: https://github.com/praekelt/go-rts-zambia/blob/develop/js_sandbox/lib/go-rts-zambia.js#L576-L592
.. _Switchboard: https://github.com/praekelt/switchboard-go/blob/master/lib/switchboard-ussd.js#L691-L706
.. _mAgriculture: https://github.com/praekelt/magriculture/blob/develop/go-js/lib/magri-ussd.js#L549-L564
