# HorseScary.com - The best website known to mankind


## Getting Started

1. Click `Use this template` at the top of this page
2. Set the repository name to `<username>.github.io`, replacing `<username>` with your github username
3. Click `Create repository from template`
4. Go to the settings tab at the top
5. Under the `Github Pages` section, check if it says `Your site is published at <username>.github.io`. If not wait a minute then refresh the page, repeating this until the page is published
6. Click the link to the page. The title should be `horse`, the icon should be the `baldperm` emoji, the background should be the transgender flag and clicking the image should take you to <https://neyoa.me/>
7. Whenever you make changes, you can always check if the website's updated by checking the `Github pages` section in settings - If its green it's updated, if its grey it hasn't yet


## Setting the Background colour

1. Go to the `Code` tab on the github repo page
2. Click `style.css` and open it by pressing the edit button (pencil icon) in the top right of the code box
3. Replace whats in the brackets on line 8 with the colour stops you want for the background
```css
background-image: linear-gradient(#5dcdf5, #f7a9b7, #ffffff, #f7a9b7, #5dcdf5);
```
4. Click the green `Commit changes` button at the bottom - the website may take a few minutes to update


## Setting the website title

1. Go to the `Code` tab on the github repo page
2. Click `index.html` and open it by pressing the edit button (pencil icon) in the top right of the code box
3. Replace `horse` in line 7 with the title you want
```html
<title>
    horse
</title>
```
4. Click the green `Commit changes` button at the bottom - the website may take a few minutes to update

## Setting the redirect website

1. Go to the `Code` tab on the github repo page
2. Click `index.html` and open it by pressing the edit button (pencil icon) in the top right of the code box
3. Replace `neyoa.me` with the website you want to redirect to on line 19
```html
    <a href="https://neyoa.me/">
```
4. Click the green `Commit changes` button at the bottom - the website may take a few minutes to update

## Setting the website icon

1. Go to [this link](https://convertico.com/)
2. Use the website to convert the image you want into a `.ico` file
3. Download it and rename to `favicon.ico`
4. Go to the `Code` tab on the github repo page
5. Select `Add file` -> `Upload files`
6. Upload your new `favicon.ico` and commit the changes
