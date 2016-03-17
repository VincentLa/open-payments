Filename: OP_PH_PRFL_SPLMTL_README.txt
Version: 1.0
Date: January 2016

1. Important Note on the Physician Profile Supplement File

The Physician Profile Supplement File contains information about physicians who were indicated as recipients of payments, other transfers of value, or ownership and investment interest in payment records as well as principal investigators associated with payment records published by Open Payments. 

This file contains only physicians and principal investigators who have at least one payment record published. The criteria used by the Centers for Medicare and Medicaid Services (CMS) to determine what payment records to publish is available in the Open Payments Data Dictionary and Methodology document. This document can be found on the Resources page of the Open Payments website (http://www.cms.gov/OpenPayments/About/Resources.html). The Data Dictionary and Methodology document also includes information about the data collection and reporting methodology, data fields included in the files, and any notes or special considerations that users should be aware of.

2. Important Considerations for using the CSV Files

Microsoft Excel removes leading zeros from data fields in the CSV files. Certain fields in these data sets may have leading zeros. These zeroes will be missing when viewing the information within Microsoft Excel. 

3. Details about the PHPRFL_P011516.zip File

This compressed (.zip) file contains one (1) character-separated value (.csv) format file that uses commas as delimiters and one (1) README.txt file. A description of the CSV file is provided below.

OP_PH_PRFL_SPLMTL_P01152016.csv:
This is a supplementary file that displays all of the physicians and principal investigators indicated as covered recipients of payments for records published by Open Payments. Each record includes the physician’s or principal investigator’s demographic information, specialties, and license state, as well as the Open Payments’ unique identification number (Physician Profile ID) for each physician and principal investigator. The Physician Profile ID is a unique identifier for a physician within the Open Payments system and can be used to search the data files to find payments made to that specific physician or principal investigator.

The physician profile information included in the data sets is submitted by the reporting entity. In contrast, the physician information included in the supplementary file is derived from the National Plan and Provider Enumeration System (NPPES) and supplemented by information in the Provider Enrollment, Chain and Ownership System (PECOS). As a result, the data in these two sources may differ slightly. When searching for physicians using the Open Payments search tool on http://openpayments.cms.data.gov, use the physician profile information as listed in the supplementary file.
