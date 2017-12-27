NLPH development meeting #1 - 21.12.17
######################################

* Shay explained the agenda and main targets of the discussion, mainly:

  * Examine existing tagging tools and understanding how (and if) they should be adapted, and which tagging projects can already commence with existing tools.
  * Bootstrap the Common Voice: Hebrew project.

* Reut and Yoav explained the needed focus on creating larger tagged corpora to enable better models.

Tagging Tool
============

* Should enable tagging of substrings of any length.
* Have the possibility to automatically tag the text, while annotators need only to accept or reject tags.
* Manage projects, where a certain corpus and tag sets is associated with the projects, and you can require a certain amount of annotators per text.

Good candidates
---------------

* `LightTag <nlph.lighttag.io>`_ [?] {not open source> - A tool for managing annotation projects. Written by Tal Perry, who has generously offered free licenses to the NLPH project.`Tutorial video here <https://www.youtube.com/watch?v=eTlrTC_n_yg>`_.

* `Recogito <http://recogito.pelagios.org/>`_ [Scala, JavaScript, HTML] {`Apache License 2.0`_} - A tool for linked data annotation.

* `CATMA <http://catma.de/>`_ [HTML, Java] {unclear} - A web-based tool for research and collaboration over text data.

  * See the system itself here: http://portal.catma.de/catma/
  * And the code here: https://github.com/mpetris/catma
  
* `Arethusa: Annotation Environment <https://www.perseids.org/tools/arethusa/app/#/>`_ [JavaScript] {`MIT`_} - A backend-independent client-side annotation framework. `Repository here <https://github.com/alpheios-project/arethusa>`_.


Tagging tool-related action points 
----------------------------------

* Experienced consumers - at least Reut, Sinai and Yoav - should take a look at the possible candidates and:

  * Consider which tagging projects, if any, can already commence with the existing tools.
  * Write down what missing in each one.
  * Specifically, for Recogito, Sinai will contact Reiner (the project developer) and advise with him regarding the possibility of said extensions.
  * Come up with a definition for the ideal/dream tool required for our desired tagging projects.
  
* Programmers with experience should take a look at Recogito and estimate how challenging and time-consuming should adding the missing features be. **Erez has volunteered**.

* Find a good dataset for a first tagging projects, and decide on the type of tagging.


Datasets
========

* Shay & Inbar will advise with relevant HaSadna people, and others, regarding the licensing of Knesset protocols.
* We aim to keep on expanding the least of datasets and potential sources for datasets.


Common Voice: Hebrew
====================

* Eli Leszczynski will start working on a Hebrew version of the Mozilla Common Voice web app.
* Shay will open a GitHub repository and a dedicated AWS account under NLPH credentials and provide Eli with access. [the repo `is here <https://github.com/NLPH/voice-web>`_]
* Inbar & Shay will approach Amazon regarding sponsorship of AWS costs (server, but more so the storage).
* Shay will update on his communication with the Mozilla people, and hopefully can connect them with Eli for any development-related help, and also get their advice on methodology. 
