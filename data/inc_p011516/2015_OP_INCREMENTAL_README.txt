Filename: OP_INCREMENTAL_README.txt
Version: 1.0
Date: January 2016

1. Important Note on the Incremental Data Files

The incremental data files include all payment records that are eligible for publication and were added to, modified in, or deleted from the Open Payments data set in the most recent data publication. These records may be from any program year. The new and modified records in this data set are published in full and are also found in the main publication data files. The deleted records files contain only the deleted records’ Record ID numbers.

The files may not include all of the new or modified data submitted to Open Payments, as some submitted data may not be eligible for publication. Consult the Open Payments Data Dictionary and Methodology document for the criteria the Centers for Medicare and Medicaid (CMS) used to determine what data to publish. The document can be found on the Resources page of the Open Payments website (http://www.cms.gov/OpenPayments/About/Resources.html). It also includes information about the data collection and reporting methodology, data fields included in the files, and any notes or special considerations users should be aware of.

2. Important Considerations for using the CSV Files

Microsoft Excel removes leading zeros from data fields in the CSV files. Certain fields in these data sets may have leading zeros. These zeroes will be missing when viewing the information within Microsoft Excel. 

Additionally, the latest versions of Microsoft Excel cannot display data sets with more than 1,048,576 rows. Some of these CSV files may exceed that limit. Displaying the data in its entirety may require the use of spreadsheet programs capable of handling very large numbers of records.

3. Details about the Datasets Included in this INCR_P011516.zip File

This compressed (.zip) file contains six (6) character-separated value (.csv) format files that use commas as delimiters and one (1) README.txt file. Descriptions of each file contained in this compressed (.zip) file are provided below.

File #1 –INC_GEN_P01152016.csv: 
This file contains the General Payments records for all program years that are new or were modified in the most recent data publication. General Payments are defined as payments or other transfers of value made to a covered recipient (physician or teaching hospital) not in connection with a research agreement or research protocol.

File #2 –DEL_GEN_P01152016.csv: 
This file contains the record ID numbers for all General Payments records for all program years that have been deleted from the most recent publication. General Payments are defined as payments or other transfers of value made to a covered recipient (physician or teaching hospital) not in connection with a research agreement or research protocol.

File #3 - INC_RSRCH__P01152016.csv:
This file contains the Research Payments records for all program years that are new or were modified in the most recent data publication. Research Payments are defined as payments or other transfers of value made in connection with a research agreement or research protocol.

File #4 –DEL_RSRCH_P01152016.csv: 
This file contains the record ID numbers for all Research Payments records for all program years that have been deleted from the most recent publication. Research Payments are defined as payments or other transfers of value made in connection with a research agreement or research protocol.

File #5 - INC_OWNRSHP_P01152016.csv:
This file contains the Ownership and Investment Interest Information records for all program years that are new or were modified in the most recent data publication. Ownership and Investment Interest Information is defined as information about the value of ownership or investment interests that a physician or an immediate family member of a physician held in an applicable manufacturer or applicable group purchasing organization.  

File #6 –DEL_OWNRSHP_P01152016.csv: 
This file contains the record ID numbers for all Ownership and Investment Interest Information records for all program years that have been deleted from the most recent publication. Ownership and Investment Interest Information is defined as information about the value of ownership or investment interests that a physician or an immediate family member of a physician held in an applicable manufacturer or applicable group purchasing organization.  

