# BankingMicroservice

 apt install maven -y
 mvn --version
 rmdir myproj
 rm -r myproj
 mvn archetype:generate
 cd myproj
 mvn clean
 mvn package
 cd target
 java -cp myproj-1.0-SNAPSHOT.jar  com.project.App
 git --version
 cd ..
 echo "# BankingMicroservice" >> README.md
 git init
 git add README.md
 git config --global user.email hansneilb@gmail.com
 git config --global user.name hansneil
 git commit -m "first commit"
 git remote add origin https://github.com/hansneilbautista/BankingMicroservice.git
 git push -u origin master
 git branch dev1
 git branch dev2
 git branch
 git checkout dev1
 echo "This file is modified by dev1" >> 1.java
 git add .
 git commit -m "1.java file is modified by dev1"
 cat 1.java
 git checkout dev2
 cat 1.java
 echo "This file is modified by dev2" >> 1.java
 git add .
 git commit -m "1.java file is modified by dev2"
 cat 1.java
 git checkout master
 git merge dev1
 cat 1.java
 git merge dev2
 git mergetool
 cat 1.java
 git status
 git add .
 git commit -m "1.java merge conflict is resolved"
 git push origin master
 git branch
 git push origin dev1
 git push origin dev2
