# Tableau-Covid19_Dashboard

Result:
https://public.tableau.com/app/profile/edward.chen5890/viz/Worldwide_Coivd_19_confirmed_case/Dashboard1?publish=yes

![Alt text](<Dashboard 1.png>)


The file is larger than 100MB so I used below link to push the CSV file:
https://guide.ncloud-docs.com/docs/en/sourcecommit-use-lfs

Step 1:
Download Git Large File
https://git-lfs.com/

Step 2:
Open the cmd along with your file location
Enter below code:
git lfs install
Then it will show:
Git LFS initialized.

Step 3:
Enter which file or type of file you want to upload to GitHub
git lfs track "COVID_19_Cases.csv"
Then it will show:
Tracking "COVID_19_Cases.csv"

Step 4:
After showing "Tracking "COVID_19_Cases.csv""
Enter below code:
git add .gitattributes

Step 5:
Choose which Repositories you want to push 
git commit -m"Tableau-Covid19_Dashboard"

Step 6:
git push

Then it will start to upload.
