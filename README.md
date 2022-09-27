# Python-Engineer-Assesment
Contains assignment "Python Engineer Assesment" for SteelEye

Brief:

The assignment developed in Python 3
Code follows pep8 standards significantly and includes pydoc, logging
Unit test can be done in google collab.
github link for review = https://github.com/chandrakar-shubham/Python-Engineer-Assesment

Following implementation has been done as per requirement:

1. Downloaded the xml from provided link = 'https://registers.esma.europa.eu/solr/esma_registers_firds_files/select?q=*&fq=publication_date:%5B2021-01-17T00:00:00Z+TO+2021-01-19T23:59:59Z%5D&wt=xml&indent=true&start=0&rows=100'

2. From the xml, please XML is parsed and download link whose file_type is DLTINS

3. Zip is downloaded

4. Extraction the four xml files from the zip done.

5. Convertion of the contents of the xml into a CSV with the following header:

FinInstrmGnlAttrbts.Id
FinInstrmGnlAttrbts.FullNm
FinInstrmGnlAttrbts.ClssfctnTp
FinInstrmGnlAttrbts.CmmdtyDerivInd
FinInstrmGnlAttrbts.NtnlCcy
Issr

has been done. 


6. CSV has been saved after conversion

Following things has not been performed by me:
1. Upload CSV in AWS S3 bucket
2. The above function should be run as an AWS Lambda (Optional)
