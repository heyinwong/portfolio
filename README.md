This is my repo for my portfolio website. Credit to Joey who made the framework -> [PRISM](https://github.com/xyjoey).

My portfolio website is here: [Portfolio](https://heyinwong.github.io/). Essentially I replaced the code related to research and paper and modified it to better fit the theme of a cv website that is easy to change based on markdown file.

Deployment guide:
1.  **Build Project**

   Install correct version of Node.js.
     **Download**：from [https://nodejs.org/en/download](https://nodejs.org/en/download) . We then open terminal and run the following code, which we will then obtain a foler of `out`. It contains all the static file for the portfolio website.


    npm install
    npm run build

2.  **create GitHub repo**

    *   create a **Public** repo。
    *   **key**：repo name must be`YourUserName.github.io` 

3.  **upload file**

    *   upload everything from 'out' to this repo

4.  **add .nojekyll file**

    *   on repo managment, do  "Add file" -> "Create new file"。
    *   file name should be `.nojekyll`
    *   leave it empty and do  "Commit changes"。

5.  **configure Pages**

    *   go to **Settings** 。
    *   find **Pages**。
    *   under **Build and deployment** . make sure it is "Deploy from a branch"。
    *   select your brunch (usually it is `main`），then do **Save**。

6.  **you make it!**
