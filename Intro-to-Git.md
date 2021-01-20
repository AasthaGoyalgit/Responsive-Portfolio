# What we will cover:

Introduction to Git and Basic Git commands: 
1. Create a repository
2. Make your first commit
3. Fork repository
4. Pull Requests
5. Merge Requests

# 1. Your First Repo
i)  Once you have your github account, go to New (or Create Repository) to create your first repository on GitHub. <br> <br>
![](https://lh6.googleusercontent.com/L_E-WIKiXqs_5wmnc5O_mNLcO9zymjxY8YWX0D2NhbbrerSAJ8zjbNeb8fnavLtybNX43urt481vxqO4eXBr4QmbmesQureXQMewkmJF)
<br>
<br>ii) Give a name to your repository for e.g. "my-first-repo" or "hello-world." Choose the visibility of your repository (public, private etc) and then click on 'Create Repository' <br> <br>
<img src="https://lh6.googleusercontent.com/QcyOmjK_5IrsdsUYvteMh8Ej7D-YgelEW1l1_0egnXWJcLld7KqKDtM-Fid2-ZHtpcDRt5qHSX-vCVYy_y_mHDcHprMipKlW8skghrOFxM9Jmx-VG2DR87iiPcGUaFDRvfSVQu2G" style="width: 200px; height: 200px;">

# 2. Make your first commit
Open Visual Studio Code and do the following:
File > Open Folder > Select your folder > Click on add new file icon > Save the new file as index.html <br>

Now open the 'Terminal' window in Visual Studio and write the following instructions: <br>

      $ git init 
      $ git remote add origin https://github.com/<your-username>/<your-repo-name>.git
      $ git branch -M main
      $ git add .
      $ git commit -m “your-commit-message”
      $ git push -u origin main

<em>Congratulations! You just created your first commit in github!</em>
