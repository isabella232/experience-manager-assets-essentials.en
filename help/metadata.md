---
title: Manage metadata
description: Manage metadata of assets in [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
---

# Metadata in [!DNL Assets Essentials] {#metadata}

Metadata means data or description about the data. For example, your images as an asset can contain information about the camera it was clicked with or any copyright information. This information is metadata of the image. Metadata is critical for efficient asset management. Metadata is the collection of all the data available for an asset but it may not necessarily be contained in that asset.

Metadata helps you further categorize assets and is helpful as the amount of digital information grows. It is possible to manage a few hundred files based on just the filenames, thumbnails, and memory. However, this approach is not scalable. It falls short when the number of people involved and the number of managed assets increase.

With the addition of metadata, the value of a digital asset grows, because the asset becomes,

* More accessible - systems and users can find it easily.
* Easier to manage - you can find assets with the same set of properties easier and apply changes to them.
* Complete - asset carries more information and context with more metadata.

For these reasons, Assets provides you with the right means of creating, managing, and exchanging metadata for your digital assets.

## View the metadata {#view-metadata}

To view the metadata of an asset, browse to the asset or search the asset, select the asset, and click **[!UICONTROL Details]** in the toolbar.

![View metadata of an asset](assets/metadata-view1.png)

*Figure: To view an asset and its metadata, click **[!UICONTROL Details]** from toolbar or double-click on the asset.*

The basic metadata such as title, description, and upload date is available in the [!UICONTROL Basic] tab. The [!UICONTROL Advanced] tab contains more advanced metadata such as camera model, lens details, and geotags. The [!UICONTROL Tags] tab contains auto-applied tags based on the contents of the image.

## Update metadata {#update-metadata}

You can update a few metadata fields manually. The fields includes [!UICONTROL Title], [!UICONTROL Description], [!UICONTROL Author], and [!UICONTROL Keywords].

## Tags {#tags}

[!DNL Assets Essentials] uses artificial intelligence provided by [Adobe Sensei](https://www.adobe.com/sensei.html) to automatically apply relevant tags to all your uploaded assets. These tags, aptly named Smart Tags, increase the content velocity of your projects by helping you find relevant assets quickly. The smart tags are an example of metadata that is not contained in the image. 

The smart tags are applied in near real time and are generated based on the contents of the image. When you upload an asset, the user interface displays [!UICONTROL Processing] on the asset thumbnail for some time. Once the processing is complete, you can [view the metadata](#view-metadata) and the smart tags.

![View Smart Tags of an asset](assets/metadata-view-tags.png)

*Figure: To view the Smart Tags of an asset, click **[!UICONTROL Details]** from toolbar or double-click on the asset.*

Smart tags also contain a confidence score as a percentage. It indicates the confidence associated with the applied tag. You can moderate the automatically applied smart tags.

## Add or update tags {#manually-tag}

You may add more tags to your assets, in addition to the Smart Tags that are added automatically using the [!DNL Adobe Sensei] smart service. Open an asset for preview, click [!UICONTROL Tags], and type the desired keywords in the [!UICONTROL Keywords] field. To add the tag, press Return. [!DNL Assets Essentials] indexes the keyword in near real time and your team can soon search the updated assets using the new keywords.

You can also remove tags from the [!UICONTROL Smart Tags] section that are automatically added by [!DNL Assets Essentials] to all the uploaded assets.

<!-- TBD: Queries for PM and engg.

Can we edit the existing metadata in any form?

How to moderate smart tags?

Allow or deny list for smart tags?

What about Tags displayed just above Smart Tags in the UI?

Is there a detailed metadata tab. Where do the other details of an asset go?

How can one search based strictly on the metadata. Similar to AEM Assets GQL queries.
-->

<!-- TBD: Link to related articles if any.

>[!MORELIKETHIS]
>
>* [Search assets](search.md).
-->
