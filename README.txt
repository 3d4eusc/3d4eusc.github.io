# 3D4E Website Update Instructions

Hi New Eboard, I'm Enqi. Here is how you maintain this website.
If you have questions, please reach out to enqiwang0805@gmail.com or habbytherabbit on discord
## 1. Download the Website

1. Log in to the 3D4E Google Account, then use that to login to our GitHub account with access to the repository. 
This step should be simple, you first sign in to Github with 3d4e's google account. 2FA should be our gmail, so you can see the verification code.
2. Open the 3D4E website repository on GitHub. Should be just 3d4e.github.io
3. Click the green **Code** button.
4. Select **Open with GitHub Desktop**. If you haven't download Github Desktop, please do so.
5. Choose where to save the project on your computer.
6. Click **Clone**.

Do not download the repository as a ZIP unless necessary. GitHub Desktop makes it easier to save and upload changes.

## 2. Open the Website in Visual Studio Code

1. Open GitHub Desktop.
2. Select the 3D4E website repository.
3. Click **Open in Visual Studio Code**.
4. Use the file explorer on the left side of Visual Studio Code to find the file you need to update.

Most regular updates should only require editing:

* `people.html`
* `people.css`
* The Projects page or Projects section
* Images inside the `images` folder

Avoid changing `styles.css`, the navigation bar, footer, or homepage layout unless you know what you are doing.

## 3. Update the People Page

Open `people.html`.

Copy an existing card, paste it inside the correct year’s `people-grid`, and replace the information.


### Adding Officer Photos

1. Place each photo inside: images/people/


2. Use a simple filename without spaces: FirstNameLastName.png


3. Make sure the filename in the HTML matches the real filename exactly, including capitalization and the `.png`, `.jpg`, or `.jpeg` extension.
If a broken-image icon appears, the filename or folder path is incorrect.

## 4. Update Projects

Open the file containing the Projects page or Projects section.
Copy an existing project card so that the current design and formatting remain consistent. Replace only the project’s:

* Name
* Description
* Team members
* Image
* Link, if applicable

Save project images in the existing project image folder. Use clear filenames without spaces.
Do not create new CSS classes unless the existing project classes cannot support the content.

## 5. Preview the Changes

Save the files in Visual Studio Code.
Open the relevant HTML file in a browser, you can also use Go Live Extension on VS Code, and check:
* All images load correctly.
* Names and positions are accurate.
* Text does not overflow the cards.
* Five officer cards appear per row on a large screen.
* The page works on a smaller browser window.
* Navigation links still work.
* The previous EBoard is still present.
* No unrelated page formatting has changed.

## 6. Upload the Changes

Return to GitHub Desktop. The changed files should appear automatically.
1. Review every changed file.
2. Confirm that no unrelated files were accidentally modified.
3. Enter a short summary, such as: Update 2027–2028 EBoard

4. Click **Commit to main**.
5. Click **Push origin**.

If the repository uses branches or pull requests, create a new branch instead and submit a pull request for review.

## 7. Check the Published Website
After pushing the changes, wait a few minutes and open the live 3D4E website.

Refresh the page and confirm that:

* The new content appears.
* Photos display correctly.
* The layout works on desktop and mobile.
* There are no broken links or missing images.

If the update does not appear immediately, wait a few minutes and perform a hard refresh with `Ctrl + Shift + R` on Windows or `Command + Shift + R` on Mac.
