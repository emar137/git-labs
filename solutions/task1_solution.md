mkdir task1
echo "#doctor" >> RENAME.md
git add  RENAME.md
git commit -m "intial version"  RENAME.md
git branch -M main
git remote  add origin  //http/....
git push -u origin main 
git branch test
git switch test
touch file1.txt
git add file1.txt
git commit -m "file.txt" file.txt
git push origin test 
git branch dev
git switch dev
touch file2.txt
git add file2.txt
git commit -m "file2.txt" file2.txt
git push origin dev
git switch master
git merge dev
git merge test
git push origin 
git branch -d test 
git branch -d dev
