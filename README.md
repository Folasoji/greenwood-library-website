# greenwood-library-website
Enhancement of greenwood library website to meet users need and provide up-to date information and support
GIT CAPSTONE PROJECT: GREENWOOD COMMUNITY LIBRARY WEBSITE
SETUP:
1.	I signed onto my GitHub account and created a new repository named “greenwood-library-website, with the description “Enhancement of greenwood library website to meet users need and provide up-to date information and support”. I added a README file by ticking the box.
2.	I cloned the remote repository on my local machine, by opening my terminal. I checked my present working directory by using the command “pwd”, then I cd (change directory from my PC to desktop) using cd desktop, before cloning. To clone I clicked on code tab of the created repository (greenwood-library-website) in my GitHub account and copied the http url. I then use the git clone and the copied url; “git clone https://github.com/Folasoji/greenwood-library-website.git”. See the out put for the command initiated;
PC@DESKTOP-RVR7JSV MINGW64 ~
$ pwd
/c/Users/PC
PC@DESKTOP-RVR7JSV MINGW64 ~
$ cd desktop
PC@DESKTOP-RVR7JSV MINGW64 ~/desktop
$ git clone https://github.com/Folasoji/greenwood-library-website.git
Cloning into 'greenwood-library-website'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
3.	Using visual studio code text editor, I opened the cloned repository and four (4) html files namely; home.html, about_us.html, events.html and contact_us.html. I added contents into each file and saved them. The information I added in the files are in the working area of my system. The contents of the files are untracked with (U). I used the command “git add .” to stage the files. I opted for git add . instead of git add file names since the files are four to save me time. Afterwards, I used “git commit -m “comments” to version the contents of the file. With git commit, I saved the information in the files to my local git repository. I used git status command to check if there are items yet to be moved to my local repository. After the git add, the files change from U to A and after git commit the A disappears. Then, I used the command “git push -u origin main” to push the contents of the files to my remote repository (my GitHub). At this stage all the files are available to my team members for review and collaborative work. See feedback to the steps mentioned above;
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about_us.html
        contact_us.html
        events.html
        home.html
nothing added to commit but untracked files present (use "git add" to track) 
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$ git add .
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$ git commit -m "updating home.html file, contact_us.html file, events.html file and about_us.html file for upgrading greenwood-library-website to meet global standard"
[main 6bfb2f7] updating home.html file, contact_us.html file, events.html file and about_us.html file for upgrading greenwood-library-website to meet global standard
 4 files changed, 237 insertions(+)
 create mode 100644 about_us.html
 create mode 100644 contact_us.html
 create mode 100644 events.html
 create mode 100644 home.html
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$ git push -u origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 2.43 KiB | 311.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), done.
To https://github.com/Folasoji/greenwood-library-website.git
   66bc334..6bfb2f7  main -> main
branch 'main' set up to track 'origin/main'.
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$ git log
commit 6bfb2f7af61d49ac4ee300e05d659fd7bf2c9e1f (HEAD -> main, origin/main, origin/HEAD)
Author: Folasoji <folasoji10@gmail.com>
Date:   Wed Apr 10 23:05:09 2024 +0000
    updating home.html file, contact_us.html file, events.html file and about_us.html file for upgrading greenwood-library-website to meet global standard
commit 66bc334d88315ff53c9a94341353e0dc1926b873
Author: Oluwole Folaranmi <161720500+Folasoji@users.noreply.github.com>
Date:   Wed Apr 10 22:15:37 2024 +0000
    Initial commit
Morgan’s work: Adding Book Reviews;
1.	I created a branch named add-book-reviews for Morgan to make input on the project. I used the git command “git branch add-book-reviews”. I switched to the created branch using the command “git checkout  add-book-reviews”
2.	 I created an empty file called book_reviews.html using the command “touch book_reviews.html”. I added contents into the file by simply opening the file in vscode and pasted the html files. I did not use echo on the terminal because the contents are much.
3.	Morgan has added a section to the website under development with a file called book_reviews.html. in order to move the file from his local system to the stage area, I used the git add command, and used git commit -m “Add book reviews section” to move the file to his local git repository. Afterwards, I used git push so that his work can be viewed for reviews, corrections if need be. See output below;

PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$ git branch add-book-reviews
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$ git checkout add-book-reviews
Switched to branch 'add-book-reviews'
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (add-book-reviews)
$ git status
On branch add-book-reviews
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        book_reviews.html
nothing added to commit but untracked files present (use "git add" to track)
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (add-book-reviews)
$ git add book_reviews.html
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (add-book-reviews)
$ git commit -m "Add book reviews section."
[add-book-reviews 28b73df] Add book reviews section.
 1 file changed, 90 insertions(+)
 create mode 100644 book_reviews.html
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (add-book-reviews)
$ git push -u origin add-book-reviews
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.31 KiB | 669.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'add-book-reviews' on GitHub by visiting:
remote:      https://github.com/Folasoji/greenwood-library-website/pull/new/add-book-reviews
remote:
To https://github.com/Folasoji/greenwood-library-website.git
 * [new branch]      add-book-reviews -> add-book-reviews
branch 'add-book-reviews' set up to track 'origin/add-book-reviews'.
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (add-book-reviews)
4.	I initiated a pull request for the morgan’s work done. This was done in order have an updated file of both main branch and the branch add-book-reviews.  First, I switched back to the main branch using the command “git checkout main”, before initiating the pull request. I used the pull command “git pull origin add-book-reviews”, then I merged Morgan’s work done to the main branch using the git command “ git merge add-book-reviews”. See feedback gotten for all these;

$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$ git pull origin add-book-reviews
From https://github.com/Folasoji/greenwood-library-website
 * branch            add-book-reviews -> FETCH_HEAD
Updating 6bfb2f7..28b73df
Fast-forward
 book_reviews.html | 90 +++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 90 insertions(+)
 create mode 100644 book_reviews.html
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$ git merge add-book-reviews
Already up to date.
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$ git branch
  add-book-reviews
* main.
5.	With above feedback gotten, I went to my Github account, and refresh the url. I clicked on compare and pull request, I clicked create pull request and commented okay and submitted. Then I clicked merge pull request, and clicked confirm merge.
Jamie’s work: updating Events Page
1.	I created a branch for Jamie’s work and switched to it with the git command “git checkout -b update-events”. I already have an existing file called events.html. I opened it and edited the html file, thereafter, I saved changes. On my terminal, I used git status to check whether there are any changes.
2.	I used git add events.html to stage changes made on the files, I used git commit -m "update done on events name, date, venue, time and website name". I used git push to send updated files to the remote repository in the GitHub. See feedback to all these commands below;

PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$ git checkout -b update-events
Switched to a new branch 'update-events'
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (update-events)
$ git status
On branch update-events
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   events.html
no changes added to commit (use "git add" and/or "git commit -a")
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (update-events)
$ git commit -m "update done on events name, date, venue, time and website name"
[update-events f1328f3] update done on events name, date, venue, time and website name
 1 file changed, 6 insertions(+), 6 deletions(-)
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (update-events)
$ git push -u origin update-events
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 441 bytes | 220.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'update-events' on GitHub by visiting:
remote:      https://github.com/Folasoji/greenwood-library-website/pull/new/update-events
remote:
To https://github.com/Folasoji/greenwood-library-website.git
 * [new branch]      update-events -> update-events
branch 'update-events' set up to track 'origin/update-events'.
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (update-events)
3.	To initiate a pull request, I first switch back to the main branch using the git command “git checkout main, then I initiated pull request with git command “git pull origin update-events”.. see my output for the above commands;

PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (update-events)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$ git pull origin update-events
From https://github.com/Folasoji/greenwood-library-website
 * branch            update-events -> FETCH_HEAD
Updating 28b73df..f1328f3
Fast-forward
 events.html | 12 ++++++------
 1 file changed, 6 insertions(+), 6 deletions(-)
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main).
4.	I crossed over to my GitHub account, refreshed it to see the updated repository. I clicked on the update-events branch and clicked on compare and pull request button. For the title is amended it to “website name updated, events name, venue, title and time were all updated.” And commented that “events updates were nicely done”. Then I clicked on create pull request. I clicked merge pull request and then confirm merged button.
5.	By this, all updates have been successfully merged to the main branch.;

PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$ git pull origin main
remote: Enumerating objects: 2, done.
remote: Counting objects: 100% (2/2), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (2/2), 1.80 KiB | 30.00 KiB/s, done.
From https://github.com/Folasoji/greenwood-library-website
 * branch            main       -> FETCH_HEAD
   6bfb2f7..8e45b16  main       -> origin/main
Updating f1328f3..8e45b16
Fast-forward

PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$ git push -u origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date
PC@DESKTOP-RVR7JSV MINGW64 ~/Desktop/greenwood-library-website (main)
$
In conclusion, I have familiarized myself with how git works and how I can use GitHub to collaborate with team member to achieve set target. I learnt the basic git commands and used branching and merging effectively.
