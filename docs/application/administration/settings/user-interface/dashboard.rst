Dashboard Settings
******************

The dashboard settings allows us to adjust what users will see after they log in, i.e. on the application initial page called the dashboard. 

Dashboard Style
===============

We can select the **Dashboard Style** whether the user should see a standard **welcome** screen which just greets the user in the application, or a **role-based** dashboard which contains widgets based on current user's role (see :ref:`user-roles`):

* **Researcher**

  * **Recent Projects Widget** contains a list of recent projects of the user for a quick navigation.

  * **Create Project Widget** lets the user quickly start a new project.

* **Data Steward**

  * **Create KM / Project Template Widgets** let the user to quickly start a new knowledge model editor or project template.

  * **Outdated KM / Document Templates Widgets** allow to quickly see outdated packages and document templates in case the DSW Registry connection is configured.

  * **Import KM / Document Template Widgets** allow to proceed easily to import of a knowledge model or a document template in case the DSW Registry connection is configured.

* **Administrator**

  * **Outdated KM / Document Templates Widgets** allow to quickly see outdated packages and document templates in case the DSW Registry connection is configured.

  * **Usage Widget** summarises the usage just as is also possible to see in the :doc:`../info/usage`.

  * **Configure Organization Widget** quickly navigates to :doc:`../system/organization` if it is not yet done.

  * **Configure Look and Feel Widget** quickly navigates to :doc:`../user-interface/look-and-feel` to adjust style of the DSW instance.

  * **Connect DSW Registry Widget** quickly navigates to :doc:`../content/dsw-registry` to configure the connection (if not yet been done).

  * **Add OpenID Widget** quickly navigates to :doc:`../system/authentication` to configure the identity provider services (if not yet been done).


Welcome Info and Warning
========================

Another option to adjust the dashboard is to add **Welcome Info** or **Welcome Warning** which is then visible above the main dashboard content (both **welcome** and **role-based**). The different between info and warning is just in the style; in both cases, we can use Markdown syntax. We should use **Welcome Info** for some generic information for users, e.g. some custom welcome message and links. On the other hand **Welcome Warning** is suitable for important notification, for example, that there is some work in progress being done or outage is planned.
