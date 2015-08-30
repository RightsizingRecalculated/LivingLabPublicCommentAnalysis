STEP 3 NOTES

This folder contains the cleaned-up conversion of the original PDF to spreadsheet format.  It also contains the working copy which illustrates the clean-up process. (Note that this is technically referred to as ‘data normalization’.)

CLEANED_living-lab-community-feedback-1-201508261015_FINAL.ods
CLEANED_living-lab-community-feedback-1-201508261015_WORKING.ods

I did this using LibreOffice, so the spreadsheet files are in ods format. As a courtesy, I am also providing the files in excel (.xlsx) format.

Procedures:

(1) Each table was examined to determine on what page of the pdf the data begins, and on what page it ends, then manually copied and pasted at the end of Table 1. The conversion program split the pdf into separate tables at irregular page breaks. Notes were made in the working cope at the bottom of every table after Table 1 to indicate the page or pages from which that table originated.

(2) Each table’s data was carefully examined by hand to make certain that no comments were omitted or duplicated programatically. No data appeared to be lost or omitted by the conversion program.  

In one case, a public comment appeared to be duplicated at the bottom of Table 12 and the Top of Table 13. On closer inspection however, that duplication also occurs in the city’s pdf at the bottom of page 120 and the top of page 121. I did not remove that duplicate public comment from the analysis since it is in the city’s original dataset.

(3) Tables 14 and 17, which correspond to pages and 168 of the original pdf, were badly garbled by the conversion program.

In the case of Table 14, the problem appeared to be that conversion program did not parse the columns of the pdf consistently. It was possible to export the table as a comma separated value (.csv) file, fix it by searching and replacing two commas (“,,”) with a single “,” and then reimport the table as Table 14a. The resulting rows were then hand-checked against page 

In the case of Table 17, the conversion program hopelessly garbled the pdf. Each row of Table 17a had to be manually copied and pasted from page 168 of the pdf. During that process, I noted that city staff had apparently entered a duplicate comment on both rows 11 and 13 on that page. Since this artifact was present in the pdf, both entries were left in the dataset.

(4) Tables 2-20 were deleted and a new copy of the file was saved as 

CLEANED_living-lab-community-feedback-1-201508261015_FINAL.ods

There are 1609 discrete public comments in the cleaned up dataset. (1611 rows minus 2 header rows).

Note that while it remains conceivable that some unnoticed artifacts might still be present, I believe this dataset to be an accurate reflection of the original pdf.


