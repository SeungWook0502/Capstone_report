## Capstone Report Template using R's bookdown package
This is a template for FoDS Capstone Project Report. Follow the instructions below to copy this template to your GitHub repo and clone your project to a local R project to work on the contents:

[GitHub]  
1. Click on `Use this template` button.  
2. Name your new repository (e.g., capstone-report)  
3. Click on `Create reposotory from template`.  
4. Click on `Code` button and copy the URL under Clone
5. Go back to your RStudio

[RStudio]   
6. Now from your RStudio, click `New Project`  
7. Choose the last option `Version Control`  
8. Choose the first option `Git`  
9. Paste the URL you copied at the step 4 in the `Repository URL` field  
10. Click on `New Project` (This should copy all the files on your GitHub repo to your local drive)  
11. From the Files tab, open index.Rmd and change the options (Title, Author, etc.) and save the file.  
12. From the Build tab, click on the small chevron and check bookdown::gitbook (This will compile all the files in the bookdown structure.)  
13. From the Git tab, check all the check marks under Staged and click Commit.  
14. Type in the following commit message, "Initial change to index.Rmd" and click Commit button.  
15. From the Git Commit window, click on Push (with an uparrow icon) (This will upload all the files that are changed.)  
  
[GitHub]   
16. From your GitHub repo page, click on Settings  
17. Click on Pages menu on the left pane (second from the bottom)  
17. From the Branch menu (saying None), choose master branch and then choose /docs for the select folder menu  
19. Now click on the URL in `Your site is published at https://<<URL>> `  

-------
(Below is from the original template)   
This is a minimal example of a book based on R Markdown and **bookdown** (https://github.com/rstudio/bookdown). Please see the page "[Get Started](https://bookdown.org/yihui/bookdown/get-started.html)" at https://bookdown.org/yihui/bookdown/ for how to compile this example into HTML. You may generate a copy of the book in `bookdown::pdf_book` format by calling `bookdown::render_book('index.Rmd', 'bookdown::pdf_book')`. More detailed instructions are available here https://bookdown.org/yihui/bookdown/build-the-book.html.

You can find the preview of this example at https://bookdown.org/yihui/bookdown-demo/.
