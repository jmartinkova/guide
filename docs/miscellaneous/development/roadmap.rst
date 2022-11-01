*******
Roadmap
*******

Need to know some info about the latest released version?

----

.. NOTE::

     The backlog is being highly affected by provided feedback, community needs, and discussion with our key users. You can visit our `Ideas <https://ideas.ds-wizard.org/>`__ or `JIRA <https://ds-wizard.atlassian.net/jira/software/c/projects/DSW/issues/?filter=allopenissues>`__ or check out `DSW Advisory Board <https://ds-wizard.org/about.html>`__.

Planned versions
================

3.18
----

* Release (expected): 29 November 2022
* `Jira issues 3.18.0 <https://ds-wizard.atlassian.net/browse/DSW-1560?jql=project%20%3D%20DSW%20AND%20fixVersion%20%3D%203.18.0%20ORDER%20BY%20priority%20DESC>`__
* Key changes:
    * Add book references to KM
    * Filter file extensions when importing KM or template
    * Compute indications for newly created project
    * Add optional importer window size to importer metadata

Released versions
=================

3.17
----

* Release: 1 November 2022
* `Jira issues 3.17.0 <https://ds-wizard.atlassian.net/browse/DSW-1463?jql=project%20%3D%20DSW%20AND%20fixVersion%20%3D%203.16.0%20ORDER%20BY%20priority%20DESC>`__
* Key changes:
    * Consistency checks before publishing KM (`idea <https://ideas.ds-wizard.org/posts/77/check-some-consistency-before-publishing-new-km>`__)
    * Filter projects by KM (`idea <https://ideas.ds-wizard.org/posts/87/filter-projects-by-km>`__)
    * Support for ZIP/TAR archives and Excel exports
    * Use of gettext for client localizations
    * Support for OpenID logout functionality

3.16
----

* Release: 4 October 2022
* `Jira issues 3.16.0 <https://ds-wizard.atlassian.net/browse/DSW-1434?jql=project%20%3D%20DSW%20AND%20fixVersion%20%3D%203.15.0%20ORDER%20BY%20priority%20DESC>`__
* Key changes:
    * Import for replies from other questionnaires
    * Collapsible and movable items in list questions
    * Main menu grouping
    * Speed optimizations and refactoring
* Hotfixes:
    * 3.16.1 (fix deleting user, fix synchronizing feedback issue)
    * 3.16.2 (remove unnecessary caching to reduce RAM usage)
    * 3.16.3 (fix wrong date deserialization from the database)

3.15
----

* Release: 5 September 2022
* `Jira issues 3.15.0 <https://ds-wizard.atlassian.net/browse/DSW-1434?jql=project%20%3D%20DSW%20AND%20fixVersion%20%3D%203.15.0%20ORDER%20BY%20priority%20DESC>`__
* Key changes:
    * Project loading optimization
    * Python components refactoring
    * Several other fixes and refactoring
* Hotfixes:
    * 3.15.2 (document-worker, mailer), 7 September 2022
    * 3.15.1 (wizard-client), 7 September 2022

3.14
----

* Release: 2 August 2022
* `Jira issues 3.14.0 <https://ds-wizard.atlassian.net/browse/DSW-1406?jql=project%20%3D%20DSW%20AND%20fixVersion%20%3D%203.14.0%20ORDER%20BY%20priority%20DESC>`__
Key changes:
Migrate to Bootstrap 5
Improve authentication for downloads
Python components refactoring
Hotfixes:
3.14.1 (wizard-server), 4 August 2022
3.14.1 (document-worker), 4 August 2022
3.13
Release: 28 June 2022
Jira issues 3.13.0
Key changes:
Prevent user leave unsaved changes
Improved exceptions monitoring
3.12
Release: 31 May 2022
Jira issues 3.12.0
Key changes:
New types of value questions
KM events optimizations
Several bugfixes and UI/UX improvements
Hotfixes:
3.12.1 (wizard-server), 5 June 2022
3.12.1 (document-worker), 13 June 2022
3.11
Release: 3 May 2022
Jira issues 3.11.0
Key changes:
Apply all action for KM migrations
Improved efficiency of document worker
Auto-upgrade default document templates in project
Several bugfixes and UI improvements
3.10
Release: 5 April 2022
Jira issues 3.10.0
Key changes:
Mailer
Integration widget
Opening Markdown links in new tab/window
Several bugfixes and UI improvements
Hotfixes:
3.10.1 (wizard-client), 6 April 2022
3.10.2 (wizard-client), 17 April 2022
3.10.1 (wizard-server), 17 April 2022
3.9
Release: 1 March 2022
Jira issues 3.9.0
Key changes:
Basic password requirements
KM Editor: list of questions used with integration
Improved project migration
Usage statistics for administrators
Several bugfixes and UI improvements
Hotfixes:
3.9.1 (wizard-server), 8 March 2022, Jira issues 3.9.1
3.8
Release: 1 February 2022
Jira issues 3.8.0
Key changes:
Online collaboration in KM Editor
Hotfixes:
3.8.1 (wizard-client), 1 February 2022, Jira issues 3.8.1
3.8.1 (registry-server), 2 February 2022, Jira issues 3.8.1
3.8.2 (wizard-server), 14 February 2022, Jira issues 3.8.2
3.7
Release: 4 January 2022
Jira issues 3.7.0
Key changes:
Projects tagging and filtering
3.6
Release: 7 December 2021
Jira issues 3.6.0
Key changes:
Enhancing integration question options (item template)
Hotfixes:
3.6.1 (document-worker), 9 December 2021, Jira issues 3.6.1
3.5
Release: 2 November 2021
Jira issues 3.5.0
Key changes:
Additional metadata for KM entities
Improved document submissions
Admin operations
3.4
Release: 5 October 2021
Jira issues 3.4.0
Key changes:
Comments in projects
New Jinja filters for document context handling
3.3
Release: 8 September 2021
Jira issues 3.3.0
Key changes:
Improved default document template
Improved template development experience
Enhanced Search API
Several fixes
3.2
Release: 3 August 2021
Jira issues 3.2.0
Key changes:
Custom metrics (in KM)
Custom phases (in KM)
Several optimizations
Hotfixes:
3.2.1 (registry-server), 6 August 2021, Jira issues 3.2.1
3.2.2 (wizard-server), 20 August 2021, Jira issues 3.2.2
3.1
Release: 25 June 2021
Jira issues 3.1.0
Key changes:
Project templates
Minor UI improvements
3.0
Release: 1 June 2021
Jira issues 3.0.0
Key changes:
Migration from MongoDB and RabbitMQ to PostgreSQL and S3
Deep links feature
2.14
Release: 4 May 2021
Jira issues 2.14.0
Key changes:
Submitting forms using Enter key
Shortcuts for KM Editor and Forking KM
Clarified public link for project in UI
2.13
End of development: 31 March 2021
Release: 7 April 2021
Jira issues 2.13.0
Key changes:
Auto-reconnect in questionnaires (websockets)
Fix text inputs in questionnaires when using Grammarly in browser
Added actions directly to list views of knowledge models and templates
2.12
End of development: 2 March 2021
Release: 12 March 2021
Jira issues 2.12.0
Key changes:
Questionnaire versioning (Version History)
2.11
End of development: February 2021
Release: February 2021
Jira issues 2.11.0
Key changes:
Add multiple choice question
Show tags in the questionnaire
2.10
End of development: January 2021
Release: January 2021
Jira issues 2.10.0
Key changes:
Possibility to add specific users to the questionnaire as collaborators
2.9
End of development: 30 November 2020
Release: 9 December 2020
Jira issues 2.9.0
Key changes:
Refactored error messages
Several bugfixes
2.8
End of development: 27 October 2020
Release: 3 November 2020
Jira issues 2.8.0
Key changes:
Pagination & sorting in table views
Introduced DSW Template Development Kit
Minor UX improvements
Hotfixes:
2.8.1 (wizard-server), 24 November 2020, Jira issues 2.8.1
2.7
End of development: 29 September 2020
Release: 5 October 2020
Jira issues 2.7.0
Key changes:
Improved caching for speed optimization
Reworked questionnaire detail
2.6
End of development: 5 September 2020
Release: 9 September 2020
Jira issues 2.6.0
Key changes:
Added questionnaire live collaboration
Introduced Projects to relate questionnaire, TODOs, documents, and settings
Several UI/UX improvements
Improved design of email templates
2.5
End of development: 24 June 2020
Release: 8 July 2020
Jira issues 2.5.0
Key changes:
Added templates management
Several UI/UX improvements
Introduced backend workers for scheduled/async tasks
Added option to disable questionnaire summary report
2.4
End of development: 27 May 2020
Release: 3 June 2020
Jira issues 2.4.0
Key changes:
Added RDF support step in document worker
Improved default naming of new documents
Minor UI/UX improvements
Several bugfixes
2.3
End of development: 29 April 2020
Release: 6 May 2020
Jira issues 2.3.0
Key changes:
Enhanced backend logging for ELK
Added document submission
Improved integration with Registry for simpler Sign Up
Added user avatars
Several bugfixes and optimizations
2.2
End of development: 25 March 2020
Release: 1 April 2020
Jira issues 2.2.0
Key changes:
Added support for OpenID
Added affiliations in user profiles
Introduced settings to change configurations directly in DSW interface
Added API documentation using Swagger
UI/UX improvements
Several bugfixes and optimizations
2.1
End of development: 25 February 2020
Release: 3 March 2020
Jira issues 2.1.0
Key changes:
Introduced document worker for better scalability
Migrated backend to new framework
Added dropdown actions to list views
Several bugfixes
2.0
End of development: 14 January 2020
Release: 14 January 2020
Jira issues 2.0.0
Key changes:
Added move functionality for knowledge models
Added possibility to assign template to KMs
Added questionnaire cloning
Added expand/collapse all in KM Editor
Internal refactoring and structure enhancements
Several bugfixes
1.10
End of development: 27 August 2019
Release: 3 September 2019
Jira issues 1.10.0
Hotfixes:
1.10.1 (wizard-client), 18 September 2019, Jira issues 1.10.1
1.9
End of development: 23 June 2019
Release: 30 June 2019
Jira issues 1.9.0
Hotfixes:
1.9.1 (wizard-server), 7 August 2019, Jira issues 1.9.1
1.9.2 (wizard-server), 13 August 2019, Jira issues 1.9.2
1.8
End of development: 11 June 2019
Release: 13 June 2019
Jira issues 1.8.0
Hotfixes:
1.8.1 (wizard-client), 13 June 2019, Jira issues 1.8.1
1.7
End of development: 15 May 2019
Release: 16 May 2019
Jira issues 1.7.0
1.6
End of development: 30 April 2019
Release: 7 May 2019
Jira issues 1.6.0
1.5
End of development: 2 April 2019
Release: 9 April 2019
Jira issues 1.5.0
1.4
End of development: 3 March 2019
Release: 10 March 2019
Jira issues 1.4.0
1.3
End of development: 3 February 2019
Release: 10 February 2019
Jira issues 1.3.0
1.2
End of development: 6 January 2019
Release: 13 January 2019
Jira issues 1.2.0
Hotfixes:
1.2.1 (wizard-server), 14 January 2019, Jira issue 1.2.1
1.1
End of development: 9 December 2018
Release: 16 December 2018
Jira issues 1.1.0
1.0
End of development: 24 October 2018
Release: 30 October 2018