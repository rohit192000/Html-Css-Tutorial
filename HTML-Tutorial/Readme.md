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

- How to run HTML file:-
    -
    - To run the html file simply save file with ```.html``` extension. Then open that file by going to that folder in which you save the file and click on that file, it will open in the browser.

- Types of elements
    - 
    - Before heading to the tags lets talk about types of elements. In HTML there are two types of elements called Block-Level elements and Inline elements.

    - Block-level elements are those which form a visible block on page and appears on new line following the content precedes it. Whereas Inline elements are contained in the block-level elements and just surrounds the small parts of content not the entire paragraphs or grouping of elements. Inline elements won't appear in new line.
    
    - Block-level elements can be contained in another block-level elements. Inline elements can't contain block-level elements however they can be contained in the block-level elements.
    
    - Some block-level elements are headings, paragraphs, lists, navigation menus or footers. For example:-
    ```html
    <p>This is a paragraph. It will take the whole block. In simpler words, it will take whole space from left side of window screen to the right side of window screen even though the content is not that greater in length.</p>
    <p>Also the contents 
        in this 

         element tag will automaticaly 
    Justify.
    </p>
    ```
    Output :- 
    ```
    This is a paragraph. It will take the whole block. In simpler words, it will take whole space from left side of window screen to the right side of window screen even though the content is not that greater in length.

    Also the contents in this element tag will automatically Justify.
    ```

    - Some inline elements are links, emphasis, bold, italic, strong etc. For example :-
    ```html
    <p>It's an <b>link</b> <a href="www.google.com">Google</a></p>
    ```
    Output -
    It's an **link** [Google](www.google.com)
    - Its an anchor tag we used for the links. ```href``` is an atribute which tells where to go after clickin the link.

- Basic Tags in HTML :- 
    - 
    - Let's start with some basic tags in ```HTML``` and see how these tags helps us in making elements which in return helps users to show what we want to show them.
    
    - ```Heading Tag``` - So the first tag we're gonna learn about is an heading tag. As we know we use headings to give information about what to expect or something to explain write in headings.
    The tag used here is ```<h1></h1>```.
        - There are total of 6 types of heading ranging from ```h1 to h6```.
        ```html
        <h1>Heading 1</h1> <!-- This is the heading we used at the page starting and is bigger in size-->
        <h2>Heading 2</h2> <!-- This is like an subheading to heading h1 and smaller in size than h1-->
        <h3>Heading 3</h3> <!-- This is an subheading to the subheading h2 and smaller than h2 and like this it goes on to h6-->
        <h4>Heading 4</h4>
        <h5>Heading 5</h5>
        <h6>Heading 6</h6>
        ```
        - Always use these heading in order like ```h1>h2>h3>h4>h5>h6``` also their sizes are the lesser than their previous heading tag like ```h1>h2>h3>h4>h5>h6```. [See Here](./BasicTags.html)
