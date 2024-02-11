# Steps in Amazon Web Services (PDF Files Migration)

Connect to the AWS Cloud Shell
Download the PDF files
    - wget https://tcb-public-events.s3.amazonaws.com/icp/mission3.zip
    - unzip mission3.zip

Sync PDF Files with your AWS S3 used for COVID-19 Testing Status System. Replace the bucket name with yours.

    - cd mission3/en/pdf_files
    - aws s3 sync . s3://luxxy-covid-testing-system-pdf-en-xxxx

Test the application. Upon migrating the data and files, you should be able to see the entries  under “View Guest Results” page.

## Congratulations! You have migrated an "on-premises" application & database to a MultiCloud Architecture!!!
