**********
Deep Links
**********

You can easily create a deep-link to refer to a certain question in a Knowledge Model.

----

Get question UUID for a deep-link
=================================

If you want to construct a deep-link of a preview to a specific question that can be deeper in the KM structure. You can do that either by looking up the question in KM Editor or by having an export of KM using a specific template suitable for this task.

In KM Editor, you can copy the UUID to the clipboard by clicking a button with the start of the ID:

.. TODO::

    Add Screenshot UUID of Question in the Knowledge Model Editor

Compose a deep-link
===================

With a question UUID, you can create easily a deep-link:

``<dswUrl>/knowledge-models/<kmId>/preview?questionUuid=<questionUuid>``

For example:

https://demo.ds-wizard.org/knowledge-models/dsw:root:2.3.0/preview?questionUuid=c56f2e8f-bb78-412e-b238-974a14482f28

Notice that the KM version as part of the ID is included in the URL. You can use keyword latest instead:

https://demo.ds-wizard.org/knowledge-models/dsw:root:latest/preview?questionUuid=c56f2e8f-bb78-412e-b238-974a14482f28

In case that question with the UUID does not exist in the KM, it shows the preview without any question being "selected".

If you want the preview to be available publicly (to not-logged-in users, the administrator must set that in Settings). Similarly, if you need to allow people to create projects directly from a preview.
