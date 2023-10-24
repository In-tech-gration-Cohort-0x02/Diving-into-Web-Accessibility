# CONTRIBUTING

for contribution to our project

## Steps

* **REMEMBER: always do a git pull first before start coding**

### HTML

* Make sure you are in your
`<section></section>`  
* for sub slides you can add new `<section></section>` but only under your section
* inside a folder *assets* place images which you are going to use, and use path for image like ``<img src="assets/*name-of-your-aria-attribute*.jpg">``

### CSS

for styling  

* make sure to use only ```class``` and  ```id```  
* avoid tag name like ```main``` or ```section``` or ```h1``` or ```p``` this can mix your styles with other styling or you can also use inline styling in your elements  
* while using ```class``` or ```id``` try to use descriptive name like name with your  ***aria*** attribute  is highly recommended  
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
***Note** you are free to use external css file or any other approach you like*  

### uploading your changes to github  

Note since we are all working in one single file `index.html`  
when you add it to staging area it should be  

```
 git status  
 git add index.html   
 git commit -m <your message>  
 git push  
```

 Hope this helps  
 HAppy coding  
