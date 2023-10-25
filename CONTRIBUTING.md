# CONTRIBUTING

for contribution to our project

***Tip** you can preview this markdown file by using* `CTRL + SHIFT + V`

## Instructions

* **REMEMBER: always do a git pull first before start coding**
* Resources of this project can be found in pdf file pinned in our group

### To see your site live

* you can use `live server` in `index.html` file or click `GoLive` button on status bar

### HTML

* Make sure you are in your
`<section></section>`  
* for sub slides you can add new `<section></section>` but only under your section
* inside a folder *assets* place images which you are going to use, and use path for image like ``<img src="assets/*name-of-your-aria-attribute*.jpg">``

### CSS

for styling  

* make sure to use only ```class``` and  ```id```  
* avoid tag name like ```main``` or ```section``` or ```h1``` or ```p``` this can mix your styles with other styling or you can also use inline styling in your elements  
* while using ```class``` or ```id``` try to use descriptive name like name with your  ***aria*** attribute are highly recommended  
* also document your styles in ```<style></style>``` tag like ⬇️  

```CSS
/* aria-errormessage styles */ 
.error-message{
/*styles here*/
background: blue;
}
/* aria-errormessage styles end here*/

```  

* you can also use your `aria` attribute to style your html  
* also you can format your file by right clicking on any file ==> `Format Document`  
***Note** you are free to use external css file or any other approach you like*  

### Adding Images

* if you decided to use images you can add them in ***assets*** 📂
* give them a name related to your *aria*
* path can be something like this `assets/aria-something.jpeg` (do check *aria-label* section for some inspiration)

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

* after git push  check you changes online [here](https://voronaav23.github.io/Cohort-2-Group-Presentation/). 🎉

 Hope this helps  
 Happy coding  
