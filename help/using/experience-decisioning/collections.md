---
title: Collections
description: Learn how to work with collections
feature: Offers
topic: Integrations
role: User
level: Intermediate
hide: yes
hidefromtoc: yes
badge: label="Beta" 
---
# Collections {#collections}

>[!BEGINSHADEBOX]

What you'll find in this documentation guide:

* [Get started with Experience Decisioning](gs-experience-decisioning.md)
* Manage your decision items
    * [Configure the items catalog](catalogs.md)
    * [Create decision items](items.md)
    * **[Manage items collections](collections.md)**
* Configure items' selection
    * [Create decision rules](rules.md)
    * [Create ranking methods](ranking.md)
* [Create selection strategies](selection-strategies.md)
* [Create decision policies](create-decision.md)

>[!ENDSHADEBOX]

Collections allow you to categorize and group your decision items according to your preferences. These categories are created by crafting rules that leverage the attributes of decision items.

For instance, let's say you have added a "Category" custom attribute to your decision items' catalog schema. This allows you to create a collection that includes all decision items with the "Yoga" value in the "Category" attribute.

The list of collections is accessible from the **[!UICONTROL Items]** menu.   

To create a collection, follow these steps:

1. Navigate to **[!UICONTROL Items]** > **[!UICONTROL Collections]** and click **[!UICONTROL Create collection]**.
1. Provide a name and a description for the collection.
1. Add one or multiple rules to determine the items to be included in the collection. To do this:

    1. Choose an item attribute to use as criterion. The attributes list includes all standard and custom attributes defined in the catalog schema. [Learn more on the items' catalog](catalogs.md)
    1. Select the desired operator and input the value to filter on.
    1. Repeat these steps to add as many rules as necessary. When multiple rules are added, you can choose between the **And** and **Or** operators to combine them. To do this, click the operator badge to switch between the two choices.

    ![](assets/collection-create.png)

1. Once the collection rules have been defined, click **[!UICONTROL Create]**. The collection now displays in the list.