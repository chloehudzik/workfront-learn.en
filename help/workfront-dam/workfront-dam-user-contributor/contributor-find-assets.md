---
title: Find and Organize Assets in [!UICONTROL Workfront DAM]
description: Learn how to search for assets, search within folders, streamline search results, use metadata and keywords as search filters, and more in [!UICONTROL Workfront DAM].
activity: use
feature: Digital Content and Documents
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
kt: 8993
exl-id: 28b60118-a471-48bf-ae9b-3a2aed6a6130
doc-type: video
---
# Contributor: find assets

In this video, you will learn how to:

* Search for assets
* Search within folders
* Streamline search results
* Use metadata and keywords as search filters
* View folder details
* View and update asset metadata and keywords

>[!VIDEO](https://video.tv.adobe.com/v/335253/?quality=12)

## Basic search criteria

A basic search looks at filenames, metadata fields, keywords, and asset content (depending on the asset type). It does not include folder name.

Most search results are exact matches. An exception to this “exact match” rule is when the [!UICONTROL Workfront DAM] searches the filename field. [!UICONTROL Workfront DAM] returns partial filename matches, rather than just exact filename matches.

## User operators while searching

Although the basic searching features will often find the assets you need, you may need to use additional search parameters from time to time.

### Partial matches

To find a partial match, add an asterisk to the search term. The asterisk may be used only at the end of a word.

### AND operator

To find results containing multiple search terms, enter AND between the words. The words can be found in any order. When searching across all fields, both words may not be present in the same field. For example, Paris AND tower will find assets that have both of those words in any of the fields.

### OR operator

Use the OR operator to find assets that contain any of the search terms. For example, Paris OR Arc will find assets that have either of the words, but not necessarily both.

### Phrase

To find an exact phrase, use double quotes around the words. All words will be found together and in order. For example, “Eiffel Tower” will find those words in that exact order.

### Negative operator

If you want to exclude a word from the search results, put a minus sign (–) in front of the word. Make sure there isn’t a space between the minus sign and the word. For example, to exclude assets that have the word “tower” in the metadata, your search could be set up as Paris -tower.

### Empty field operator

To find assets that have no information in a specific metadata field, enter the field you want to search in this format: ?[xxxxx]. For example, if you want to find assets that don’t have keywords assigned, enter ?[keyword] in the search field.
