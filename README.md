# bash
1. Enter ```./getpdf.sh```
2. You will get a prompt to enter a URL
3. Enter this URL for test purpose: https://www.npmjs.com/
4. You will be prompted with this message:
```
"No PDFs found at this URL - exiting.."
```
5. Next, enter ```./getpdf.sh ```
6. Then enter this URL for test purpose: https://www.sydneybusinessschool.edu.au/study/brochures/
7. You will be prompted with this message:
  ```
  Downloading ......6 PDF files have been downloaded to the directory pdfs_14_01_2023
  File Name     File Size
  uow200261.pdf |  4.1M
  uow205891.pdf |  188K
  uow260950.pdf |  1.8M
  uow262727.pdf |  100K
  uow268636.pdf |  136K
  uow273537.pdf |  512K
  ```
8. Enter the following ```./getpdf.sh -z```
9. Then enter this  URL for test purpose: https://www.sydneybusinessschool.edu.au/study/brochures/
10. Then you will get the following message:
  ```
Downloading ......6 PDF files have been downloaded to the directory pdfs_14_01_2023
File Name     File Size
uow200261.pdf |  4.1M
uow205891.pdf |  188K
uow260950.pdf |  1.8M
uow262727.pdf |  100K
uow268636.pdf |  136K
uow273537.pdf |  512K
PDFs archived to pdfs_14_01_2023.zip in the pdfs_14_01_2023 directory
  ```
11. ```cd``` into each directory to check the presence of files
12. ```rm -rf <directory name``` to avoid erros and conflicts
13. If permission error arises, do ```chmod 777 getpdf.sh```
