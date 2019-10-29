# **How to Host Your Resume On GitHub Pages**

## **Description of Intended Audience**    
This was written for someone who has somewhat used GitHub a few years ago but has no experience using any of the other tools described in the assignment description. This includes Atom, Jekyll, and Markdown.

## **Before We Start**  

We will need a couple of important pieces before we can start making our resume:
- A way to get Atom on our computer which we can download [here](https://atom.io/)  
- Learn how to create Markdown documents at [Markdown Tutorial](https://www.markdowntutorial.com/)
- Try to login to your GitHub account or reset your password if you need to.
- A positive attitude and a willingness to learn something new

## **How Long Each Section Takes To Complete**
| Section        | Time needed (average)         | Learning Curve  |
| :------------- |:-------------:                | -----:          |
| A              | 45 mins                       | Average         | 
| B              | 2-5 mins                      |   Easy          |
| C              | 1 min                         |    Easy         |
| D              | 2-3 mins                      |    Average      |
| E              | 3-4 mins                      |    Average      |
| F              | 1 min                         |    Easy         |



## **Instructions**  

#### A) Converting Your Resume into a Markdown Resume
1.  Open up Atom and create a new file called index.md.
2.  Use index.md to convert your regular resume into a Markdown resume.
3. Follow the Markdown conventions and if you forget what those are then go to [Markdown Tutorial](https://www.markdowntutorial.com/) again.
4. To preview what your markdown resume will look like you can:
    - simply click on the "packages" button at the top left of the Atom window
    - scroll down to Markdown preview
    - click on toggle preview
5. If you are curious about how to add an element to your Markdown resume review the link in step 3
6. Save your converted resume on your desktop.
7. Way to go! Learning Markdown will be very helpful down the line.

#### B) Log Into Your GitHub Account
1. Go to your favourite browser and type "GitHub"
2. Click on the very first link
3. Find the three horizontal lines at the top right of the webpage and click on them.
4. Press the "sign in" button which is located near the bottom of the side menu
5. Type in your username or email address that you used when creating your account
6. Click the green "Sign in" button when finished
7. That was easy, keep going and you will be done in no time!

#### C) Creating A New Repository
1. Find the "New" button in the top right-hand corner which takes you to a new page to create your repository
2. Fill in the Repository name with [your Github id].github.io.
3. Leave the description box blank
4. Check off the Public Box instead of the private box so anyone can see your resume.
5. Click on the checkbox that allows you to "initialize this repository with a README"
6. Leave the "add .gitignore" as none.
7. Leave the "add a license" as none.
8. Press the green "Create repository" button.
9. You should be on your new repository homepage now.
10. You are all set up! We are well on our way now.

#### D) Uploading Your Resume To Your GitHub Pages Account
1. Locate and click the "Upload files" button which is near the upper right part of your webpage
2. Find the converted resume on your desktop where you left it from before
3. Drag the file into the middle of the webpage
4. If you've done this successfully the header Text should change from "Drag files here …" to "Drag additional files here …"
5. Check off the "commit directly to … master branch" option
6. Press the "commit changes" button.
7. Wait patiently as GitHub "processes the request". Do not click anywhere else.
8. Once that process is finished it should take you back to your repository homepage.
9. Good job! You have just finished successfully uploading your resume to Github. 

#### E) Format Your Resume Using A Jekyll Theme
1. From your repository homepage, you will want to scan the top of the webpage.
2. Click on the settings icon which towards the right of the Page
3. Ensure that your Repository name follows the [your Github id].github.io format mentioned earlier.
4. Scroll down until you see a heading that reads "GitHub" pages and stop.
5. click on "choose a theme" button which will take you to a new page
6. Look over all the themes and pick one that you like but be warned, some work better with lists than others.
7. Choose the theme by pressing the "Select theme" button at the top of the page
8. Now you should be able to view your Markdown resume with a Jekyll theme applied to it by repeating step 4 and clicking the link that is beside the message "Your site is ready …"
9. Your resume looks amazing! it will definitely catch the eye of potential employers. 

#### F) Revise Your Jekyll Theme Front Matter
1. Go back to repository homepage by clicking the "View the Project on GitHub" link at the top of your Jekyll generated resume.
2. Find the config.yml file and click on it. It should be located with your README.md and index.md files.
3. Click on the pencil icon near the left of the window
4. Add a new line to this file by moving your cursor to the end of the first line and simply clicking your space bar
5. Type "title: Resume for [first name intial] [last name]" on the second line
6. Press commit changes at the bottom of your window
7. Now if you go to your to your Jekyll themed resume webpage you will see the new title that you just put in.
8. You are all done! Now anyone can see your beautiful resume just by visiting your profile.

## **Resources**
- This is an intro to GitHub Pages: https://help.github.com/en/github/working-with-github-pages
- Here is the GitHub Flavoured Markdown intro: https://github.github.com/gfm/

## **Authors and Acknowledgments**
I want to thank my group members Jordan Portz and Jacob Macks for helping me create this assignment. A thank you to Christina Penner for the assignment and resources. 

## **FAQs**
Q: can I modify my Jekyll themed resume webpage any further?  
A: No, you must select one of the templates specified in the "select themes" section.  
Q: Why has my README file theme changed but my resume file theme hasn't?  
A: Check the spelling of your resume file and ensure it is index.md and make sure your repository name follows the [your Github id].github.io format.  
