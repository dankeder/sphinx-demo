
Confluence comparision
======================

Pros
----

.. glossary::

    wiki markup
        less fighting with clever rich text editor and more work done.
        More structure and less a random-set-of-pages.

    aligned with code/reality
        more likely to be in sync with code it is documenting. Same branching
        model. More versions of the same doc, eg. one per branch.

    less management
        easy to add more project to readthedocs.org. No need to setup/upgrade/backup.
        No user management, no groups or authorization (handled by git).

    lower cost
        readthedocs.org is free. Private instance of RTD is less resource
        hungly and still zero license cost.

    generated content
        easier to generate docs with git/commit/push than SOAP/RPC-XML api.

Cons
----

.. glossary::

    one repo == one site
        one git repo typically generates one documentation site.
        References to symbols on other site (via intersphinx) are symbolic.
        Search is for one site only (AFAIK).

    longer turnaround
        save/commit/push is longer that simple "save" button. See Edit on Github feature.

    no WYSIWYG
        editing plain text might not be for everyone (Sales, HR, ..).

    no custom formating
        No support for explicit font type/size/color. Placement on the screen, etc.
        Individuals cannot imprint their "personality" to doc. Is this a Pros point ?

    no integration with Atlasian products
        particulary JIRA

    no Stars, Watchers, Followers, Likes
        Seriously, is this bad ?

