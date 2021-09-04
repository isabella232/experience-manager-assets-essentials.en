---
title: Supported file formats
description: Supported file formats for the various use cases of [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
---
# Files formats support in [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] supports a wide range of file formats and each functionality has varied support for different file types.

* ![image file type icon](assets/do-not-localize/image-icon.png) Images: GIF, JPG, PNG, and TIFF
* ![document file type icon](assets/do-not-localize/document-icon.png) Documents: DOCX, PDF, PPTX, and XLSX
* ![video file type icon](assets/do-not-localize/video-icon.png) Videos: MP4

The various file types have different degrees of support for the use cases and features as described below. Use the legend to understand the support level.

| Support Level     | Description             |
|-------------------|-------------------------|
| &#10003;          | Supported               |
| &#10003; &Dagger; | Supported conditionally |
| &minus;           | Not applicable          |

## Add, upload, and view assets {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Asset type        | [Browse](/help/navigate-view.md)   | Copy     | [Upload](/help/add-delete.md)   | Create   | [Delete](/help/add-delete.md#delete-assets)   | Details           | Image zoom | [Recently Viewed](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| Raster images     | &#10003; | &#10003; | &#10003; | &minus;  | &#10003; | &#10003;          | &#10003;   | &#10003;        |
| Folders           | &#10003; | &#10003; | &#10003; | &#10003; | &#10003; | &#10003;          | &minus;    | &minus;         |
| MP4 videos        | &#10003; | &#10003; | &#10003; | &minus;  | &#10003; | &#10003; &Dagger; | &minus;    | &#10003;        |
| PDF               | &#10003; | &#10003; | &#10003; | &minus;  | &#10003; | &#10003;          | &minus;    | &#10003;        |
| PSD, AI, and INDD | &#10003; | &#10003; | &#10003; | &minus;  | &#10003; | &#10003; &Dagger; | &minus;    | &#10003;        |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## Search, use, and edit assets {#support-to-search-use-edit}

| Asset type    | [Download](/help/manage-organize.md#download) | Drag and drop | [Image editor](/help/edit-images.md) | [Search](/help/search.md)   | [Smart Tags](/help/metadata.md#tags) | [Rename](/help/manage-organize.md)   | [Versions](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Raster images | &#10003; | &#10003;      | &#10003;     | &#10003; | &#10003;   | &#10003; | &#10003; |
| Folders       | &#10003; | &#10003;      | &minus;      | &#10003; | &minus;    | &#10003; | &minus;  |
| Videos        | &#10003; | &#10003;      | &minus;      | &#10003; | &#10003;   | &#10003; | &minus;  |
| CC Libraries  | &minus;  | &minus;       | &minus;      | &minus;  | &minus;    | &#10003; | &minus;  |
| PDF           | &#10003; | &#10003;      | &minus;      | &#10003; | &#10003;   | &#10003; | &minus;  |
| PSD           | &#10003; | &#10003;      | &minus;      | &#10003; | &#10003;   | &#10003; | &minus;  |
| AI            | &#10003; | &#10003;      | &minus;      | &#10003; | &#10003;   | &#10003; | &minus;  |
| INDD          | &#10003; | &#10003;      | &minus;      | &#10003; | &#10003;   | &#10003; | &minus;  |

## Review assets and collaborate {#support-to-review-collaborate}

| Asset type    | Annotate | Comment  | Create tasks and review |
|---------------|----------|----------|-------------------------|
| Raster images | &#10003; | &#10003; | &#10003;                |
| Folders       | &minus;  | &minus;  | &minus;                 |
| Videos        | &minus;  | &#10003; | &#10003;                |
| CC Libraries  | &minus;  | &minus;  | &minus;                 |
| PDF           | &minus;  | &#10003; | &#10003;                |
| PSD           | &minus;  | &#10003; | &#10003;                |
| AI            | &minus;  | &#10003; | &#10003;                |
| INDD          | &minus;  | &#10003; | &#10003;                |

## Other asset management tasks {#support-to-manage-assets}

| Asset type    | [Metadata](/help/metadata.md)          | [Renditions](/help/add-delete.md#renditions) | [Trash](/help/add-delete.md#delete-assets)    | Copy     | Move     |
|---------------|-------------------|------------|----------|----------|----------|
| Raster images | &#10003; | &#10003;   | &#10003; | &#10003; | &#10003; |
| Folders       | &#10003; | &minus;    | &#10003; | &#10003; | &#10003; |
| Videos        | &#10003; | &minus;    | &#10003; | &#10003; | &#10003; |
| CC Libraries  | &#10003; | &minus;    | &minus;  | &minus;  | &minus;  |
| PDF           | &#10003; | &minus;    | &#10003; | &#10003; | &#10003; |
| PSD           | &#10003; | &minus;    | &#10003; | &#10003; | &#10003; |
| AI            | &#10003; | &minus;    | &#10003; | &#10003; | &#10003; |
| INDD          | &#10003; | &minus;    | &#10003; | &#10003; | &#10003; |

Users of [!DNL Adobe Asset Link] can check-in the raster images into the [!DNL Assets Essentials] repository from the supported [!DNL Adobe Creative Cloud] desktop applications.

<!-- TBD: Saving the template table separately for later use.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->
