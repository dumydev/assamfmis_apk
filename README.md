Update the file id into Direct downlodable url everytime when new apk uploaded.

-------------// EXAMPLE //--------------

STEP 1: 
Direct downlodable url formate:
https://drive.google.com/uc?export=download&id=1AbCDefGhIjKlMnOp

STEP 2: 
Sharable URL formate:
https://drive.google.com/file/d/1AbCDefGhIjKlMnOp/view?usp=sharing

-----------------// How to release new version //-------------------
1-Upload apk file to google drive > get shareble link (Public)
2-Copy the file id from the shareble link and update it to github 'version.json' file in file id value
3- Go to > version.json and update:
a)- fileId
b)- versionName & versionCode
c)- updatedAt

Now refreash the page link to see new update , using this link : https://dumydev.github.io/assamfmis_apk/



