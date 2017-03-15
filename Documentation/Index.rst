.. Tip - just do it:
      don't use TABs (= \t, tabulators)
      replace each TAB by *three blanks* (enable RegExp for Search and Replace in your IDE)
      set TAB width and indentation to THREE in your IDE
      set 'Use blanks instead of TABs' in your IDE


.. With the following include we import some definition. We do this in each and every file.
   so we can change the definition at a single place. Use the relative path to the Includes.txt file,
   which may look as well like ../../../Includes.txt for a deeply nested source file.

.. include:: Includes.txt


.. Usually we define 'php' as default highlight language in Includes.txt.
   With the following 'highlight' directive we switch to reStructuredText as default highlight language.

.. highlight:: rst


.. The following, first section (= headline) is the 'Document Title'.


======================
My Public Info Project
======================


.. The following is 'field list' which is rendered as a horizontal table.
   Think of it as key-value pairs.


:Writing here:     Peter Niederlag
:Rendered:         |today|
:Buildinfo:        `buildinfo <_buildinfo>`_
:Similar projects: `Other starter projects`__

__ https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-001/TeachingDocs/StarterManuals/

.. _Martin: martin.bless@mbless.de
.. _Peter: peter.niederlag@typo3.org

.. attention::

   This is work in progress and just in intial phase


---------------------------------------------


.. _hello:

**Hello,**

Peter_ here.

What's it about?

#. This is my TYPO3 scratchpad where I publish thoughts and snippets related to TYPO3 CMS

#. ToBeContinued



TYPO3 - Inspire people to share!

Thx to Martin_ for the engagement on documentation for the TYPO3 project


.. These are anonymous hyperlinks. Each link in the text, which is formed by TWO trailing
   underscores, will consume the next of the following links.

__ https://docs.typo3.org/typo3cms/RenderTYPO3DocumentationGuide/ProjectsOnGithub/Index.html
__ https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-000/reStructuredText/Index.html
__ https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-000/



.. toctree::
   :hidden:

   HelloWorld/Index
   Hyperlinks/Index
   reStructuredText/Index
