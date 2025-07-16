### test-cases

The folder test-cases contains test cases for AGEPRO versions 4.24 and 4.25.

The test cases for version 4.24 verify the change in the implementation

of StockSummaryFlag from version 4.20. The test cases for version 4.25

verify the new implementation of AuxiliaryOutputFlag from the deprecated

StockSummaryFlag in version 4.24.

[View Stock Summary PDF](../diagrams/StockSummaryFlag-pdf.pdf)

<br>

For version 4.24, the test cases are named test#.INP.

To run a test case on the command line, use "agepro_MLS_rebuild.exe test#.INP".

These cases verify the changes in the implementation of StockSummaryFlag

from version 4.20 to version 4.24.

These included options to output some (value=2 or 3) or none (value=0)

of the auxiliary output files as well as to automatically output the stock summary distributions.

<br>

For version 4.25, the test cases are named Example#-AOFlag=#.INP.

To run a test case on the command line, use "agepro.exe Example#-AOFlag=#.INP".

These cases verify the changes from StockSummaryFlag to AuxiliaryOutputFlag

for outputting the stock summary distributions and for outputting the auxiliary output files.

In Version 4.25, the implementation of the AuxiliaryOutputFlag matches the behavior of

StockSummaryFlag in version 4.20 for both possible values of the logical flag (0 and 1).
