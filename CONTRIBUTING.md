# CONTRIBUTING to ARIA LABELS & A11y

for contribution to our project

***Tip** you can preview this markdown file by using* `CTRL + SHIFT + V`

## Instructions

* **REMEMBER: always do a git pull first before start coding**
* Resources of this project can be found in pdf file pinned in our group

### To see your site live

* you can use `live server` in `index.html` file or click `GoLive` button on status bar

### HTML  

Source: `index.html`

* Make sure you are in your
`<section></section>`  
* for sub slides you can add new `<section></section>` but only under your section

### Images

Source: ***assets*** 📂

* if you decided to use images you can add them in ***assets*** 📂
* give them a name related to your *aria*
* inside a folder *assets* place images which you are going to use, and use path for image like `<img src="assets/*name-of-your-aria-attribute*.jpg">` (do check *aria-label* section for some inspiration)

### CSS

for styling  
Source: ```css/style.css```

* We decided to work with external style.css which can be found in  css folder so every contributor can write  own css styles inside
***Note** Make sure you include your style in the file like this

```css
/*---------------------- Start of [Contributor's name] CSS -------------------------*/ *

   >>>>>>  Your styles here

 /*------------------- End of [Contributor's name] CSS --------------------------*/ 
```

* make sure to use only ```class``` and  ```id```  
* avoid tag name like ```main``` or ```section``` or ```h1``` or ```p``` this can mix your styles with other styling or you can also use inline styling in your elements  
* while using ```class``` or ```id``` try to use descriptive name like name with your  ***aria*** attribute are highly recommended  
<!-- * also document your styles in like ⬇️  

```CSS
/* aria-errormessage styles */ 
.error-message{
/*styles here*/
background: blue;
}
/* aria-errormessage styles end here*/

```   -->

* you can also use your `aria` attribute to style your html  
* also you can format your file by right clicking on any file ==> `Format Document`  
***Note** you are free to use external css file or any other approach you like*  

### Files and Folder we are working with

* index.html
* css/style.css
* assets 📂
* CONTRIBUTING.md
* README.md

### Uploading your changes to github  

**Note** since we are all working in one single file `index.html`  
when you decide your changes should be online  
make sure to add `index.html` and other related files/images

```bash
 git status  
 git add index.html (images) 
 git status  
 git commit -m <your message>  
 git status 
 git push  
 
```

* after git push  check you changes online [here](https://in-tech-gration-cohort-0x02.github.io/Diving-into-Web-Accessibility/). 🎉

 Hope this helps  
 Happy coding  
