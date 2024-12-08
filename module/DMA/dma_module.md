---
permalink: /dma-module/
layout: module
---

<br>
<br>

# Database Migration Assessment

The DMA module offers a preliminary estimate of the effort needed to migrate on Oracle database to PostgreSQL.

Upon receiving an SQL Developer export in an `.zip` archive format, the module parses and analyzes the contained SQL files. This entire process is executed within the browser, without relying on any external resources.

# SQL Developer Export Instructions

1. Launch SQL Developer and ensure your database has been introspected
2. Navigate to **_Tools > Database Export_** to open the Export Wizard
3. In the **_Source/Destination_** tab:
   * Choose your database connection
   * Disable the **_Export Data_** option
   * Select **_Save As Separate Directory_** and enable **_Compressed_**
   * Specify the desired output path in the **_File_** field (e.g., `HR.zip`)
   * Click **_Next_**
4. In the **_Types to Export_** tab, click **_Next_**
5. In the **_Specify Objects_** tab:
   * Click **_More..._**
   * Choose the desired Schema (e.g., `HR`)
   * Click **_Lookup_** and wait for all database objects to load
   * Click **_>>_** to export all database objects
   * Click **_Next_**
6. In the **_Export Summary_** tab, click **_Finish_**
