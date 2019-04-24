Input files: [InventBiotech_AACR_leads.csv](https://github.com/deoxy-llc/Karthick/blob/master/campaign-data/InventBiotech_AACR_leads.csv) and "summary_..." [files](https://github.com/deoxy-llc/Karthick/tree/master/campaign-data).

The "summary" files concern three projects "1MinColumn", "RIPA", and "TraceProteins", and each with two kinds of data, namely "opens" and "clicks". 

Task: Match opens and clicks from "summary" files for each project with entries in "InventBiotech_AACR_leads.csv". Use "Email" as identifier. See [Output_Example](https://github.com/deoxy-llc/Karthick/blob/master/campaign-data/Output_Example.csv) for an example of desriable output (the values are not real in that file).

For "clicks", sometimes multiple URLs are associated with the same email. In that case, add up the click numbers and report a total. The following is an example:

    EMAIL URL 1MinColumn-Clicks

    ljh216@psu.edu	https://inventbiotech.com/pages/contact-us	5

    ljh216@psu.edu	https://www.youtube.com/watch?v=W8BlE1Kwuec	4

    ljh216@psu.edu	https://inventbiotech.com/collections/fast-protein-extraction-1	3

    ljh216@psu.edu	https://inventbiotech.com/collections/fast-protein-extraction-1/products/minute-total-protein-extraction-kit-for-animal-cultured-cells-and-tissues-us-patent-9-580-462	3

For the above example, report "15" (which is the sum of 5,4,3,3) for value "1MinColumn-Clicks".
