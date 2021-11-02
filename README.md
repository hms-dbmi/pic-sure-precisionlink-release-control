# PrecisionLink Release Notes

Visit [https://pl-portal.childrens.harvard.edu](https://pl-portal.childrens.harvard.edu) to view the latest release. <p>
<b> Current version of data</b>
|Data type|Details|Date of extract|
|----------|--|--|
|phenotypic|Demographics  <br> Status|2021-09-28
|genomic|Annotated whole genome sequencing for those patients with phenotypic data |2021-07-23

<b> Data Releases </b> <br>
|Release|Date|Data type|Release Notes|
|-|----------|--|--|
|1|2021-07-23|genomic|- Genomic data has been refreshed with data as of July 14, 2021. <br> - Whole exome data has been replaced with whole genome data. New genomic patients include only their demographic data. |
|1|2021-07-23|phenotypic|- Phenotypic data has been refreshed with data as of July 2021.|

<b> Application Releases </b> </br> 
|Release|Date|Release Notes|
|-------|--|--|
|2|2021-11-XX|New features: <br> - Aggregate Variant Explorer feature:  Users will see the “Variant Explorer” button in the results box after running a genomic query. When clicking the “Variant Explorer” button a modal will show a table with the following information at the aggregate level: Chrom, Position, REF, ALT, Variant consequence calculated, Variant_class, Gene_with_variant,  Variant_severity, Variant_frequency_as_text, Variant_frequency_in_ExAC, Patients with this variant in subset, Patients With this variant NOT in subset.  <br> Search: Users can use the search bar to search within the modal, such as Variant_class:  SNV, insertion, deletion <br> Download Variant Data: Users can download the results to a tsv file Entries: Users can select the number of entries per page that are shown  <br> Sort per column: Users can click the caret icon to the right of the column header to sort the column <p>Optimizations: <br> - Updated the authorization logic so that duplicate users and connections cannot be added on the Users page accessible by Admins. </p> <p> Bugs fixed: <br> - Fixed a bug where Admin users could not edit existing users' details.  </p> Technical updates:<br> - Variant metadata loader supports multiple files.  <br> - Merged PSAMA and PIC-SURE setting files. |
|1|2021-07-23|- First PL Release |


