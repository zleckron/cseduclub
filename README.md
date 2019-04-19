# *SQUARE WHO? Let's Build a Portfolio Site with HTML/SCSS*
#### Hosted by the [Computer Science Education Club](https://my3.my.umbc.edu/groups/cs-ed) and [UMBC](https://www.umbc.edu/)
##### Date: April 19, 2019
##### Time: 12pm to 2pm
##### Location: ITE 239
##### What to Bring: Your Personal Laptop
#
#
---
# WORKSHOP AGENDA
#
## __Hour 1__
### Part 1a: Setting Up  
1. [Download Node.js](https://nodejs.org/en/download/).
2. [Download Git](https://git-scm.com/downloads).
3. [Download Atom IDE](https://flight-manual.atom.io/getting-started/sections/installing-atom/).
4. [Create a GitHub account](https://github.com/) and make sure you are logged in.
5. Now navigate to the [workshop's Git repository](https://github.com/zleckron/cseduclub) where the starter files exist.
6. _Fork_ the repository to your account by pressing the "Fork" button in the upper right-hand corner.
7. *__IMPORTANT:__* Rename the newly forked repository to `username.github.io`, where `username` is your username on GitHub. No exceptions.
    Here's a link to do that: https://help.github.com/en/articles/renaming-a-repository
8. Copy to clipboard the url to your renamed Git repo i.e. `https://github.com/username/username.github.io`
9. Now from an easily accessible place on your computer (i.e. "My Documents"), create a new folder and name it "Websites" (you can name it whatever you want but we'll use "Websites" for consistency).
*__Protip:__ avoid having spaces in your folder names; instead use a dash or underscore.*
10. Open up a terminal. On MacOS, open the pre-installed app called Terminal. On Windows, open the pre-installed app Command Prompt.
11. In the terminal, execute each command below, line by line. Replace `username` with your GitHub username. Do not type the `$` character. Zoee will show you how to navigate your files with the `cd` command.
#
```sh
$ cd into/your/Websites/folder
$ git clone https://github.com/username/username.github.io
$ cd username.github.io
$ npm install
$ npm rebuild node-sass
$ npm start
```
12. Open the Atom IDE that you downloaded in step 2. From your Atom IDE, open `username.github.io` (File > Open > navitage to `username.github.io` in your Websites folder and select it).
13. [Add the atom-live-server package] by visiting this link (https://atom.io/packages/atom-live-server) and clicking the green "Install" button.
14. In Atom, enter `ctrl-alt-l` with your keyboard (`ctrl-option-l` on MacOS).
15. go to `localhost:3000` in a browser of your choice (if one doesn't open up for you after step 13) and marvel at what is being rendered from your starter code. __DON'T WORRY -__ you will get a chance to customize the site later on in the workshop. But first ...
#
### Part 1b: Brief Overview of HTML & SCSS
1. Open the Google Slides with the links for Part 1b: https://docs.google.com/presentation/d/124nU7ZKkGKpjYBQ6iwncdnb-aAI8JUVX2V-SuWC8cfA/edit?usp=sharing
1. Open HelloWorld.html in your Atom IDE and also in a browser of your choice (by double-clicking it in your finder).
2. In the browser, try using the Inspect feature. To open this on Chrome, go to the webpage in the browser and right-click, then select Inspect from the menu that appears.
3. When editing, save your HTML code in the Atom IDE and refresh the page in the browser.
4. You can view the HTML code from the Elements pane of the Inspect panel, and you can view errors from the Console pane. You should see 2 errors. See if you can figure out how to fix them!
5. Experiment with replacing words and adding elements (we suggest paragraphs, headings, or images).
6. When you are satisfied with the changes you have made to HelloWorld.html, you can go ahead and close it in the browser and close the HelloWorld.html tab in the Atom IDE.
7. Open up index.html in the Atom IDE to follow along with Zoee for the live coding and customization.
#
#
## __Hour 2__
### Part 2: Customize with [Bulma](http://bulma.io)
1. Now return to your Atom IDE and follow along with the instructor in this __*live coding*__ session. The goal here is to get you familiar with Bulma's file structure as well as Bulma's syntax for using its various components.

Once you are more or less happy with how your site looks in `localhost:3000`, it is now time to "push" these new changes up to your newly created GitHub account.
2. Open up a __second__ terminal and run the following commands.
#
```sh
$ cd into/your/Websites/folder
$ git status
$ git add --all
$ git commit -m "Initial commit"
$ git push -u origin master
```
3. … and you're done! Fire up a browser and go to `https://username.github.io`. Do a little dance to celebrate your very first website!
#
_Refer to [GitHub Pages](https://pages.github.com/) if you want to change the url to a custom domain name of yours, among other things._
_And don't forget to check out all the other cool links for your benefit. They can be found in the workshop slides that will be emailed to you. **You're Welcome :)**_
