# Metadata

## What is Metadata?

### Overview

Metadata is information that describes your data - essentially “data about data”. Just as a book has a table of contents to help you understand its structure, metadata provides context about your data’s content, origin, purpose, etc., making it easier for you to find and manage information in your knowledge base.

This guide aims to help you understand metadata and effectively manage your knowledge base.

### Core Concepts

-  **Field:** The label of a metadata field (e.g., “author”, “language”).

-  **Value:** The information stored in a metadata field (e.g., “Jack”, “English”).

<p align="center">
  <img src="https://assets-docs.dify.ai/2025/03/b6a197aa21ab92db93869fcbfa156b62.png" width="300" alt="Field name and value">
</p>

-  **Value Count:** The number of values contained in a metadata field，including duplicates. (e.g., “3”).

<p align="center">
  <img src="https://assets-docs.dify.ai/2025/03/330f26e90438cf50167c4cb6ce30e458.png" width="300" alt="Metadata field">
</p>

-  **Value Type:** The type of value a field can contain.
    - Dify supports three value types:
        - String: For text-based information
        - Number: For numerical data
        - Time: For dates/timestamps

<p align="center">
  <img src="https://assets-docs.dify.ai/2025/03/f6adc7418869334805361535c8cd6874.png" width="300" alt="Value type">
</p>

## How to Manage My Metadata?

### Manage Metadata Fields in the Knowledge Base

You can create, modify, and delete metadata fields in the knowledge base.

> Any changes you make to metadata fields here affect your knowledge base globally.

#### Get Started with the Metadata Panel

**Access the Metadata Panel**

To access the Metadata Panel, go to **Knowledge Base** page and click **Metadata**.

![Entrance of Metadata Panel](https://assets-docs.dify.ai/2025/03/bd43305d49cc1511683b4a098c8f6e5a.png)

![New metadata](https://assets-docs.dify.ai/2025/03/6000c85b5d2e29a2a5af5e0a047a7a59.png)

**Built-in vs Custom Metadata**

<table border="0" cellspacing="0" cellpadding="10" style="width: 100%; border-collapse: collapse;">
    <tr>
        <th style="width: 15%; text-align: center; background-color: #f5f5f5;">Feature</th>
        <th style="width: 42.5%; text-align: center; background-color: #f5f5f5;">Built-in Metadata</th>
        <th style="width: 42.5%; text-align: center; background-color: #f5f5f5;">Custom Metadata</th>
    </tr>
    <tr>
        <td style="text-align: center;">Location</td>
        <td>Lower section of the Metadata panel</td>
        <td>Upper section of the Metadata panel</td>
    </tr>
    <tr>
        <td style="text-align: center;">Activation</td>
        <td>Disabled by default; requires manual activation</td>
        <td>Add as needed</td>
    </tr>
    <tr>
        <td style="text-align: center;">Generation</td>
        <td>System automatically extracts and generates field values</td>
        <td>User-defined and manually added</td>
    </tr>
    <tr>
        <td style="text-align: center;">Editing</td>
        <td>Fields and values cannot be modified once generated</td>
        <td>Fields and values can be edited or deleted</td>
    </tr>
    <tr>
        <td style="text-align: center;">Scope</td>
        <td>Applies to all existing and new documents when enabled</td>
        <td>Stored in metadata list; requires manual assignment to documents</td>
    </tr>
    <tr>
        <td style="text-align: center;">Fields</td>
        <td>
            System-defined fields include:<br>
            • document_name (string)<br>
            • uploader (string)<br>
            • upload_date (time)<br>
            • last_update_date (time)<br>
            • source (string)
        </td>
        <td>No default fields; all fields must be manually created</td>
    </tr>
    <tr>
        <td style="text-align: center;">Value Types</td>
        <td>
            • String: For text values<br>
            • Number: For numerical values<br>
            • Time: For dates and timestamps
        </td>
        <td>
            • String: For text values<br>
            • Number: For numerical values<br>
            • Time: For dates and timestamps
        </td>
    </tr>
</table>

#### Create New Metadata Fields

To create a new metadata field:

1. Click **+Add Metadata** to open the **New Metadata** dialog.

![New metadata](https://assets-docs.dify.ai/2025/03/5086db42c40be64e54926b645c38c9a0.png)

2. Choose the value type.

3. Name the field.

> Naming rules: Use lowercase letters, numbers, and underscores only.

<p align="center">
  <img src="https://assets-docs.dify.ai/2025/03/f6adc7418869334805361535c8cd6874.png" width="300" alt="Value type">
</p>

4. Click **Save** to apply changes.

![Save field](https://assets-docs.dify.ai/2025/03/f44114cc58d4ba11ba60adb2d04c9b4c.png)

#### Edit Metadata Fields

To edit a metadata field:

1. Click the edit icon next to a field to open the **Rename** dialog.

![Rename field](https://assets-docs.dify.ai/2025/03/94327185cbe366bf99221abf2f5ef55a.png)

2. Enter the new name in the **Name** field.

> Note: You can only modify the field name, not the value type.

<p align="center">
  <img src="https://assets-docs.dify.ai/2025/03/2f814f725df9aeb1a0048e51d736d969.png" width="350" alt="Rename field">
</p>

3. Click **Save** to apply changes.

> Note: Field changes update across all related documents in your knowledge base.

![Renamed field](https://assets-docs.dify.ai/2025/03/022e42c170b40c35622b9b156c8cc159.png)

#### Delete Metadata Fields

To delete a metadata field, click the delete icon next to a field to delete it.

> Note: Deleting a field deletes it and all its values from all documents in your knowledge base.

![Delete field](https://assets-docs.dify.ai/2025/03/022e42c170b40c35622b9b156c8cc159.png)

### Edit Metadata 

#### Bulk Edit Metadata in the Metadata Editor

You can edit metadata in bulk in the knowledge base.

**Access the Metadata Editor**

To access the Metadata Editor:

1. In the knowledge base, select documents using the checkboxes on the left.

![Entrance of Edit Metadata](https://assets-docs.dify.ai/2025/03/18b0c435604db6173acba41662474446.png)

2. Click **Metadata** in the bottom action bar to open the Metadata Editor.

![Edit metadata](https://assets-docs.dify.ai/2025/03/719f3c31498f23747fed7d7349fd64ba.png)

**Bulk Add Metadata**

To add metadata in bulk:

1. Click **+Add Metadata** in the editor to:

<p align="center"><img src="https://assets-docs.dify.ai/2025/03/d4e4f87447c3e445d5b7507df1126c7b.png" width="400" alt="Add metadata"></p>

- Add existing fields from the dropdown or from the search box.

    <p align="center"><img src="https://assets-docs.dify.ai/2025/03/ea9aab2c4071bf2ec75409b05725ac1f.png" width="400" alt="Existing field"></p>

- Create new fields via **+New Metadata**.
    
    > New fields are automatically added to the knowledge base.

    <p align="center"><img src="https://assets-docs.dify.ai/2025/03/e32211f56421f61b788943ba40c6959e.png" width="400" alt="New metadata field"></p>

- Access the Metadata Panel to manage metadata fields via **Manage**.

    <p align="center"><img src="https://assets-docs.dify.ai/2025/03/82561edeb747b100c5295483c6238ffa.png" width="400" alt="Manage field"></p>

2. *(Optional)* Enter values for new fields.

<p align="center"><img src="https://assets-docs.dify.ai/2025/03/aabfe789f607a1db9062beb493213376.png" width="400" alt="Value for field"></p>

> The date picker is for time-type fields.

<p align="center"><img src="https://assets-docs.dify.ai/2025/03/65df828e605ebfb4947fccce189520a3.png" width="440" alt="Date picker"></p>

3. Click **Save** to apply changes.

**Bulk Update Metadata**

To update metadata in bulk:

1. In the editor:

- **Add Values:** Type directly in the field boxes.

- **Reset Values:** Click the blue dot that appears on hover.

    <p align="center"><img src="https://assets-docs.dify.ai/2025/03/01c0cde5a6eafa48e1c6e5438fc2fa6b.png" width="400" alt="Reset values"></p>

- **Delete Values:** Clear the field or delete the **Multiple Value** card.

    <p align="center"><img src="https://assets-docs.dify.ai/2025/03/5c4323095644d2658881b783246914f1.png" width="400" alt="Multiple values"></p>

- **Delete fields:** Click the delete icon (fields appear struck through and grayed out).

    > Note: This only deletes the field from this document, not from your knowledge base.

    <p align="center"><img src="https://assets-docs.dify.ai/2025/03/1b0318b898f951e307e3dc8cdc2f48d3.png" width="400" alt="Delete fields"></p>

2. Click **Save** to apply changes.

**Set Update Scope**

Use **Apply to All Documents** to control changes:

  - **Unchecked (Default)**: Updates only documents that already have the field.

  - **Checked**: Adds or updates fields across all selected documents.

<p align="center"><img src="https://assets-docs.dify.ai/2025/03/4550c68960802c24271492b63a39ad05.png" width="400" alt="Apply all changes"></p>

#### Edit Metadata on the Document Details Page

You can edit a single document’s metadata on its details page.

**Access Metadata Edit Mode**

To edit a single document’s metadata:

On the document details page, click **Start labeling** to begin editing.

![Details page](https://assets-docs.dify.ai/2025/03/066cb8eaa89f6ec17aacd8b09f06771c.png)

![Start labeling](https://assets-docs.dify.ai/2025/03/4806c56e324589e1711c407f6a1443de.png)

**Add Metadata**

To add a single document’s metadata fields and values:

1. Click **+Add Metadata** to:
![Add metadata](https://assets-docs.dify.ai/2025/03/f9ba9b10bbcf6eaca787eed4fcde44da.png)

    - Create new fields via **+New Metadata**.

    > New fields are automatically added to the knowledge base.
    
    ![New fields](https://assets-docs.dify.ai/2025/03/739e7e51436259fca45d16065509fabb.png)
    
    - Add existing fields from the dropdown or from the search box.

    ![Existing fields](https://assets-docs.dify.ai/2025/03/5b1876e8bc2c880b3b774c97eba371ab.png)

    - Access the Metadata Panel via **Manage**.

    ![Manage metadata](https://assets-docs.dify.ai/2025/03/8dc74a1d2cdd87294e58dbc3d6dd161b.png)

2. *(Optional)* Enter values for new fields.

![Values for fields](https://assets-docs.dify.ai/2025/03/488107cbea73fd4583e043234fe2fd2e.png)

3. Click **Save** to apply changes.

**Edit Metadata**

To update a single document’s metadata fields and values:

1. Click **Edit** in the top right to begin editing.

![Edit mode](https://assets-docs.dify.ai/2025/03/bb33a0f9c6980300c0f979f8dc0d274d.png)

2. Edit metadata:

    - **Update Values:** Type directly in value fields or delete it.

    > Note: You can only modify the value, not the value name.
    
    - **Delete Fields:** Click the delete icon.

    > Note: This only deletes the field from this document, not from your knowledge base.

![Edit metadata](https://assets-docs.dify.ai/2025/03/4c0c4d83d3ad240568f316abfccc9c2c.png)

3. Click **Save** to apply changes.

## How to Filter Documents with Metadata?

See **Metadata Filtering** in *[Integrate Knowledge Base within Application](https://docs.dify.ai/guides/knowledge-base/integrate-knowledge-within-application)*.

## API Documentation

See *[Maintaining Dataset via API](https://docs.dify.ai/guides/knowledge-base/knowledge-and-documents-maintenance/maintain-dataset-via-api)*.

## FAQ

- **What can I do with metadata?**

    - Find information faster with smart filtering.

    - Control access to sensitive content.

    - Organize data more effectively.

    - Automate workflows based on metadata rules.

- **Fields vs Values: What is the difference?**

<table style="width: 100%; border-collapse: collapse; background-color: #f8f9ff;">
    <thead>
        <tr>
            <th style="width: 25%; padding: 12px; border: 1px solid #e5e7eb; background-color: #f9fafb;">Concept</th>
            <th style="width: 25%; padding: 12px; border: 1px solid #e5e7eb; background-color: #f9fafb;">Definition</th>
            <th style="width: 25%; padding: 12px; border: 1px solid #e5e7eb; background-color: #f9fafb;">Characteristics</th>
            <th style="width: 50%; padding: 12px; border: 1px solid #e5e7eb; background-color: #f9fafb;">Examples</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: top;">Metadata Fields in the Metadata Panel</td>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: top;">System-defined attributes that describe document properties</td>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: top;">Global fields accessible across all documents in the knowledge base</td>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: top;">Author, Type, Date, etc.</td>
        </tr>
        <tr>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: top;">Metadata Value on a document’s detail page</td>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: top;">Custom metadata tagged according to individual document requirements</td>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: top;">Unique metadata values assigned based on document content and context</td>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: top;">The “Author” field in Document A is set to “Mary” value, while in Document B it is set to “John” value.</td>
        </tr>
    </tbody>
</table>

- **How do different delete options work?**

<table style="width: 100%; border-collapse: collapse; background-color: #fff;">
    <thead>
        <tr style="background-color: #f9fafb;">
            <th style="padding: 12px; border: 1px solid #e5e7eb; width: 15%;">Action</th>
            <th style="padding: 12px; border: 1px solid #e5e7eb; width: 25%;">Steps</th>
            <th style="padding: 12px; border: 1px solid #e5e7eb; width: 20%;">Impact</th>
            <th style="padding: 12px; border: 1px solid #e5e7eb; width: 20%;">Outcome</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: middle;">Delete field in the Metadata Panel</td>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: middle;">In the Metadata Panel, click delete icon next to field</td>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: middle;">Global - affects all documents</td>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: middle;">Field and all values permanently deleted from the knowledge base</td>
        </tr>
        <tr>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: middle;">Delete field in the Metadata Editor</td>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: middle;">In the Metadata Editor, click delete icon next to field</td>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: middle;">Selected documents only</td>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: middle;">Field deleted from selected documents; remains in the knowledge base</td>
        </tr>
        <tr>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: middle;">Delete field on the document detail page</td>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: middle;">In the Edit Mode, click delete icon next to field</td>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: middle;">Current document only</td>
            <td style="padding: 12px; border: 1px solid #e5e7eb; vertical-align: middle;">Field deleted from current document; remains in the knowledge base</td>
        </tr>
    </tbody>
</table>
