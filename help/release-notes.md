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

* You can create and manage customized metadata forms to be used for displaying metadata properties to users in the asset detail screen in [!UICONTROL Metadata Forms] option under [!DNL Settings]. See [metadata forms](,metadata.md#metadata-forms).
* Various bug fixes and product improvements, including better performance when uploading a nested folder with many subfolders.

## Known issues {#known-issues}

The list of known issues of [!DNL Assets Essentials] offering is revised and updated on an ongoing basis:

* To upload a folder or assets, when you drag the items into a folder with subfolders in the repository, the upload goes into one of the subfolders automatically. The workaround is to click [!DNL Upload assets] option and drag into the dialog. <!-- CQ-4327753 -->
* After uploading folder, new folders may sometimes display incorrectly in the left rail instead of displaying in the tree view. The workaround is to refresh the browser. <!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

If you come across any issues or even enhancement requests, [provide feedback](#provide-feedback) to the team.
