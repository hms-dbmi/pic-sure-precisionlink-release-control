# PrecisionLink Release Notes

Visit [https://pl-portal.childrens.harvard.edu](https://pl-portal.childrens.harvard.edu) to view the latest release. <p>
<b> Current version of data</b>
|Data type|Details|Date of extract|
|----------|--|--|
|phenotypic|Allergies <br> Biospecimens <br> Clinic site <br> Demographics  <br> Diagnosis  <br> Insurance Payors <br> Laboratory Results  <br> Medications <br> Procedures <br> Protocols <br> Service <br> Vital Signs |2021-01-21
|genomic|Genotype Array, WES, WGS |2021-01-21

<b> Data Releases </b> <br>
|Release|Date|Data type|Release Notes|
|-|----------|--|--|
|2|2021-06-25|phenotypic|- Phenotypic data has been refreshed with data as of January 21, 2021. This refresh included all BCH data. |
|1|2021-06-25|genomic|- Genomic Data: WES, WGS, and Genotype Array, as well as CDRC WES and WGS.  |

<b> Application Releases </b> </br> 
|Release|Date|Release Notes|
|-------|--|--|
|2|2021-11-18|<p> New features: <br> - Aggregate Variant Explorer feature:  Users will see the “Variant Explorer” button in the results box after running a genomic query. When clicking the “Variant Explorer” button a modal will show a table with the following information at the aggregate level: Chrom, Position, REF, ALT, Variant consequence calculated, Variant_class, Gene_with_variant,  Variant_severity, Variant_frequency_as_text, Variant_frequency_in_ExAC, Patients with this variant in subset, Patients With this variant NOT in subset.  <br> Search: Users can use the search bar to search within the modal, such as Variant_class:  SNV, insertion, deletion <br> Download Variant Data: Users can download the results to a tsv file <br> Entries: Users can select the number of entries per page that are shown  <br> Sort per column: Users can click the caret icon to the right of the column header to sort the column </p> <p> Optimizations: <br> - Updated the authorization logic so that duplicate users and connections cannot be added on the Users page accessible by Admins.  <br> - Updated the PrecisionLink training videos and user guide.  </p> <p> Bugs fixed: <br> - Fixed a bug where Admin users could not edit existing users' details. </p> Technical updates:<br> - Variant metadata loader supports multiple files.  <br> - Merged PSAMA and PIC-SURE setting files. </p>|
|1|2021-06-25|<p> New features: <br> - Results box has been updated to include carets to expand and show additional information. <br>  - Users must be on the BCH Pulse Secure VPN to access Precision Link, it will not be available using the HMS VPN. If the user attempts to access Precision Link while not on the BCH Pulse Secure VPN they will now see a webpage with instructions. <br> - The Biobank landing page has been updated to include the new BCH Precision Link logo, updated stats, and a link to the GIC landing page. </p>  <p> Optimizations: <br> - Precision Link logo has been updated to the new BCH Precision Link logo. The name of the app in the web browser tab has been changed to "PrecisionLink PIC-SURE" for the website name.  <br> - The header and footer are now consistent across all pages of the application.  <br> - Query ID button is available after the user filters their search results. <br> - The information modal includes a list of the categories of data available in Precision Link. The modal also includes a table of the genomic batch names so that the user can query them directly in the application. <br> - The "Admin" tab is now named "Users". <br> - Underscores have been removed from search terms. </p>  <p> Technical updates: <br> - Unified the header, footer, and router. <br> - Removed tildes from the procedure concept paths. <br> - The Bio Specimen concept path was expanded to have separate values for Quantity, Temp Stored, and Container Type. <br> - Created a synthetic concept path for biobank consented for searching purposes. <br> - Updated the Auth0-Lock based buttons to work with the latest Auth0-Lock, no longer rely on webtask.io. </p>|


