---
title: Upload assets to the repository
description: Upload assets to [!DNL Assets Essentials], view upload statuses, and resolve upload issues.
role: Business Practitioner
---

# Upload assets {#add-assets}

To add new assets to work with, upload a few assets from your local file system. <!-- TBD: Many of the [common file formats are supported](/help/supported-file-formats.md). -->

You can use the following methods to upload one or more assets or a folder containing assets:

* Drag assets or folders on the user interface and follow the on-screen instructions.
* Click **[!UICONTROL Add Assets]** option from the toolbar and add some files to the upload dialog.

<!-- TBD: Update this GIF
![Asset and nested folder upload demo](assets/do-not-localize/upload-assets.gif) -->

You can use any of these methods to upload assets after creating a folder. To create an empty folder, click **[!UICONTROL Create Folder]** from the toolbar. While [!DNL Assets Essentials] offers a powerful, full-text search functionality, you can also use folders to organize your assets better.

Once you have selected the files, you get a confirmation dialog to add more files or to remove already selected files. To add more files to a selection, click **[!UICONTROL Browse]** and the select **[!UICONTROL Browse files]** or **[!UICONTROL Browse folders]**. Add more files or folders from the same or from a different folder.

Once all files are queued, click **[!UICONTROL Upload]**.

![Upload files and folders](assets/upload-browse-files-folders.png)

*Figure: Before you upload the selected assets, you can add or remove assets from the queue.*

## View upload progress and status {#upload-progress}

When you upload many assets or nested folders to [!DNL Assets Essentials], some assets can fail to upload for various reasons such as duplicate asset and network issues.

To track the upload progress, click **[!UICONTROL Upload Progress]** option on the toolbar. A panel displays the upload progress of all assets.

To view a subset of assets based on the upload progress or status, use the filter in the **[!UICONTROL Upload Progress]** sidebar. The various filters are to display all assets, completed uploads, in-progress uploads, queued assets to be uploaded, paused uploads, duplicate assets, and assets that failed to upload.  

![Filter the upload progress based on status of upload](assets/filter-upload-progress.png)

*Figure: Filter the assets that you attempted to upload based on their upload status or upload progress.*

Immediately after the assets are uploaded, Assets Essentials processes the assets to generate thumbnail and process metadata. For many assets, the processing takes some time. If do not see a thumbnail and see a processing message on the placeholder thumbnail, check the folder again after a few minutes.

![Processing upon upload](assets/upload-processing.png)

## Asset renditions {#renditions}

Assets Essentials processes the uploaded assets in near real time and for many supported file types, it generates renditions. Created for images, the renditions are resized versions of the uploaded image. You can download not just the asset but also the renditions to use an appropriate version. You can view all the renditions of an asset when you [preview an asset](/help/navigate-view.md#preview-assets).

![Renditions](assets/renditions-view-download.png)

## Manage failed uploads {#resolve-upload-fails}

If upload of a supported asset fails for some reason, click **[!UICONTROL Retry]** from the [!UICONTROL Upload Progress] pane.

![Retry a failed upload](assets/upload-retry.png)

*Figure: Retry if a supported file fails to upload for some reason.*

If you attempt to upload duplicate assets, the assets are not uploaded until you explicitly confirm the upload. At first, the duplicate assets are marked as failed uploads. To resolve, you can simply create a version, delete and replace the existing assets, or create a duplicate copy by renaming the asset. You can resolve such failures one asset at a time or do it in bulk for all failed duplicates in one go.

![Manage duplicate assets one at a time](assets/uploads-manage-duplicates.png)

*Figure: For duplicate assets that fail to upload by default, resolve the issue one asset at a time.*

![Manage all failed uploads in bulk](assets/upload-progress-manage-failed-uploads.png)

*Figure: For duplicate assets that fail to upload by default, resolve issues for all assets at once.*

>[!TIP]
>
>You can upload assets to the DAM repository directly from within your [!DNL Creative Cloud] desktop applications. See how [[!DNL Assets Essentials] integrates with [!DNL Adobe Asset Link]](/help/integration.md).

## Delete assets or folders {#delete-assets}

Users can delete individual assets or folders that are no longer required. To delete an asset or a folder do one of the following:

* Use the option available on an asset's or a folder's thumbnail.

  ![Options on asset thumbnail to manage an asset](assets/options-on-thumbnail.png)

* Select an asset or a folder and click **[!UICONTROL Delete]** ![delete icon](assets/do-not-localize/delete-icon.png) in the toolbar.
