#### Let's start with ```HTML```

# ```HTML``` - Hyper Text MArkup Language

- What is HTML? 
    - ```HTML``` is an markup language used for marking the web.In simpler words its an combination of elements which can be applied to pieces of texts to give them different meaning in a document (Is it a paragraph? is it a bulleted list? is it a table or is it an link?). ```HTML``` specifies the section like header, footer, column, body of the document.

- HTML element
    -
    ```html 
    <p>Hello I am an paragraph tag</p>
    ```
    - ```<p>``` is an opening tag and ```</p>``` is an closing tag. All ```HTML``` elemnts have opening and closing tags with some exception. ```Hello i am a paragraph tag``` is an content. So basically all the ```HTML``` elements are of this type.

- [HTML Basic Structure](./Document.html) 
    - 
    - ```HTML``` basic structure defines the section of the ```HTML``` document like title , metadata, body of the document. it's define how different ```HTML``` combine to form ```HTML``` page. 
    - 
    ```html
    <!DOCTYPE html>
    <html lang="en-US">
        <head>
            <meta charset="UTF-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <meta name="author" content="Rohit Samal">
            <title>My page</title>
        </head>
        <body>
            <p>The content of the page which shown to users</p>
        </body>
    </html>
    ```
    - ```<!DOCTYPE html>``` Set of rules HTML page had to follow to be considered a good HTML. They tells the browser what to expect like what type of content it will get. Just this! You need to add at the top of the document structure.

    - ```<html></html>``` The root element which wraps the entire content on the page.

    - ```lang="en-US``` This is an language attribute which sets the language of the contents of the website.

    - ```<head></head>``` This element contains the content which developer didn't want to shown to the user. It generally contains metadata, css files, js files, title tag, keywords for the websites and page description. ```<meta>``` tag for the site.

    -```<meta charset="UTF-8">``` This meta elements represent the metadata. ```charset="UTF-8"``` attributes sets the character set for your document to UTF-8 which contains the most character from human written languages. ```name``` tells the name of the metadata like author, keywords and is associated with the ```content``` attribute which contains the value of that metadata. 

    - ```<title></title>``` This element contains the title page of the website which is the title appear on the tab of the page.

    - ```<body></body>``` This is the elemwnt which contains the content shown to the user. This includes  text, paragraph, images, videos, navbars, tabs etc.

    - Go to the code and run in your browser. [Link](./Document.html)

