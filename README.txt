Lab Exercise 2: Configuring Continuous Integration with GitHub Actions

Steps (run in a terminal from the exp2 folder):
1) git init
2) git add .
3) git commit -m "Configured CI using GitHub Actions"
4) git branch -M main
5) git remote add origin https://github.com/<username>/ci-lab.git
6) git push -u origin main

To trigger CI again:
1) Edit app.py to print("CI triggered again")
2) git add app.py
3) git commit -m "Modified app file"
4) git push
