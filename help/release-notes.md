---
title: Release Notes
description: Release Notes and known issues of [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
---

# Release notes of [!DNL Assets Essentials] {#release-notes}

The current release is the first public release of [!DNL Assets Essentials] that was made available on June 21, 2021. [!DNL Assets Essentials] offers lightweight asset management capabilities and its first version supports the following major features and CRUD (create, read, update, and delete) operations:

* Upload and add assets, including nested folders. Preview the assets and versions.
* Full-text search, nuanced search filters, and saved searches for rapid asset discovery.
* Basic asset management operations like update, delete, download, and manage metadata.
* Integration with [[!DNL Adobe Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

Currently, [!DNL Assets Essentials] is available to [[!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer.html) customers. 

To know more about the solution, see the [introduction to [!DNL Assets Essentials]](introduction.md). To start using the features, see [get started](/help/get-started.md).

## Current release {#release-notes-current}

The current release of Assets Essentials is 2021.7.0, released on July 29, 2021, with the following updates:

* You can create and manage customized metadata forms to be used for displaying metadata properties to users in the asset detail screen in [!DNL Metadata Forms] option under [!DNL Settings]. 
* Various bug fixes and improvements, including better performance when uploading a folder structrure with many folders.

## Known issues {#known-issues}

The list of known issues of [!DNL Assets Essentials] offering is revised and updated on an ongoing basis:

* Upload - when dragging and dropping folder/assets into a folder with subfolders in the repository, the upload goes into one of the subfolders automatically. Workaround: click [!DNL Upload assets] button and drag and drop into the dialog. <!-- CQ-4327753 -->
* Upload - in certain situations, newly created folders might show up in a wrong place in the left-hand rail instead inside of the tree view. Workaround: refresh the browser. <!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

If you come across any issues or even enhancement requests, [provide feedback](#provide-feedback) to the team.
