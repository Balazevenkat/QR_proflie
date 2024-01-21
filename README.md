#QR generator

 ![Made-With-NodeJS](https://img.shields.io/badge/Made_with-NodeJS-informational?style=for-the-badge&logo=javascript) 
---

Which files in this repository define the process of Node.js performance in `index.js`, pure raw code modified by packages like the Node Package Manager (npm)?

Steps:

1. We need to run the following command in the terminal: `npm i <file name>`.
   Example: `npm i inquirer qr-image`.

2. The first thing we need to do is run `npm init`.
   Note: The above two steps are performed in the terminal. To open the terminal in VS Code, click on "View" above the left side and select it.

3. Once you're done with step 2, you will see the `package.json` file appear.

4. Now, make a small correction in `package.json` by adding `[type:"module"]`.

5. Copy the required code snippet from a Google search using `npm node sub search inquirer`. Import the code into `index.js`. The same approach applies to `qr-image` as well.

6. Make changes to use `message.txt` instead of `URL.txt`.

7. Ensure that the brackets in `var qr_svg = qr.image(url);` are consistent for the URL.

8. Make the last change by searching for the Node file system using Google (`fs.writeFile`). After selecting it, copy the code `writeFile("URL.txt", url, (err) => {...}` and add it to `index.js`.

9. The 9th step is to understand how the URL is stored in a text file. The result appears as an image, which can be scanned with a lens.

From the 3rd step onward, everything is done in `index.js`. Check the process in the terminal:

Steps:

1. Use `cd` to navigate to the path of `index.js`.
2. Run `node index.js`.
3. Type or paste the link that appears when scanning is done.

--- 
<h3 align="center"><b>Developed with :heart: by Balazevenkat</b></h1>
