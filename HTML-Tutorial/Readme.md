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

    - ```<head></head>``` This element contains the content which developer didn't want to shown to the user. It generally contains metadata, css files, js files, title tag, keywords for the websites and page description. ```<meta>``` tag for the site. In this part we link our ```css``` and ```js```

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

    - Block-level elements vs Inline elements

    - Block-level elements are those which form a visible block on page and appears on new line following the content precedes it. Whereas Inline elements are contained in the block-level elements and just surrounds the small parts of content not the entire paragraphs or grouping of elements. Inline elements won't appear in new line.
    
    - Block-level elements can be contained in another block-level elements. Inline elements can't contain block-level elements however they can be contained in the block-level elements.
    
    - Some block-level elements are headings, paragraphs, lists, navigation menus or footers. For example:-
    ```html
    <div>
        <p>The div element is a container for another elements. It takes the space of the element. It is used for grouping the other elements together.</p>
    </div>
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
    <p>It's an <b>link</b> <a href="https://www.google.co.in">Google</a></p>
    ```
    Output -
    It's an **link** [Google](https://www.google.co.in)

    - Its an anchor tag we used for the links. ```href``` is an atribute which tells where to go after clickin the link. it will open the link on the same tab. to open the link in the new tab we use attribute ```target="_blank"```. Anchor tag also contains ```title="Hi Link to google"``` attribute. What does it do? So when we move our cursor on the link an text will appear above the link desribing what is this link for, that can be done by title attribute.
    ```
    <a href="link" target="_blank" title="Description about the link">Text</a>
    ```

    - By default anchor tag contents are blue and underlined.

- What are attributes?
    - 
    - Attributes contain extra information about the elements. Like in anchor tag it will tells the link to open in a new tab. They are always written inside the opening tags. We will see them in more places in HTML as they are the essential part of the HTML. ```src``` ```alt``` attribute for ```img``` element. 

- Void Elements
    - 
    - Void elements are without closing tag. They are mostly used when we want to embed/insert something in the document like image. ```<img>``` element emebeds an image onto a page.
    ```html
    <img src="link to the image(can be on local or on a internet)" alt="alternative text when image isn't visible due to some reason">
    ```

- Basic Tags in HTML :- 
    - 
    - Let's start with some basic tags in ```HTML``` and see how these tags helps us in making elements which in return helps users to show what we want to show them.
    
    - ```Heading Tag``` - So the first tag we're gonna learn about is an heading tag. As we know we use headings to give information about what to expect or something to explain write in headings. These elements are bold by default.
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

    - ```List``` You all must have use list in your daily life. So these are the same. Two types
        -  Numbered
        ```Ordered List(ol) ```
        -  Bulleted
        ```Unordered list (ul)```

        -  ```<li>List Item</li>``` used for adding items to the above lists like you were write in the list line after line.

    ```html
    <h3>First List</h3> <!--used h3 as it will great fit for its size-->
    <ul>
        <li>List Item 1</li>
        <li>List Item 2</li>
        <li>List Item 3</li>
        <li>List Item 4</li>
    </ul>

    <h3>Second List</h3> 
    <ol>
        <li>List Item 1</li>
        <li>List Item 2</li>
        <li>List Item 3</li>
        <li>List Item 4</li>
    </ol>
    ```
    Output - 
    ```
    First List
        . List Item 1
        . List Item 2
        . List Item 3
        . List Item 4
    Second List
        1. List Item 1
        2. List Item 2
        3. List Item 3
        4. List Item 4
    ```
    Nested list - 
    ```html
    <ol>
        <li>Fruits</li>
        <ul>
            <li>Apple</li>
            <li>Mango</li>
            <li>Grapes</li>
        </ul>
        <li>Vegetable</li>

        <ul>
            <li>Onion</li>
            <li>Cabbage</li>
            <li>Potato</li>
        </ul>
        <li>Fast Food</li>
        <ul>
            <li>Burger</li>
            <li>Noodles</li>
            <li>Manchurian</li>
        </ul>
    </ol>
    ```
    Output :-
    ```
    1. Fruits
        Apple
        Mango
        Grapes
    2. Vegetable
        Onion
        Cabbage
        Potato
    3. Fast Food
        Burger
        Noodles
        Manchurian
    ```

- CREATING HYPERLINKS
    - 
    - What are hyperlinks? Hyperlinks allow us to link one document to other document or resourced , link to specific part of a document, link to another websites or othe resources. e.g :- can be url or path to other files in folder or in a website.
    - ```a``` tag used for creating hyperlinks. ```<a href="url or file path">Text or can use another tags</a>```. 
    - Lets's make some hyperlinks.
    ```html
    <!-- Link to another file on a same folder or project -->
    <a href="./BasicTags.html">Basic Tags</a>
    <!-- Linking a image element to another resource -->
    <p>Block Level Link</p>
    <a href="url or path"><img src="path or url to image" alt="alternate name"/></a>
    ```
    - Paths in the href attribute -
        - 
        - Suppose there is a directories :- 
        ```
        Contacts
            contacts.html
            tel.html
            Address
                address.html
        Project
            pdf.html
            project.html
        ```
        - If file in the same directory loike I want to access the ```contacts.html``` from ```tel.html``` then ```href="contacts.html``` or ```href="./contacts.html``` (./ means in same directory) in ```tel.html``` file. Just the name of the file will link to that file in same directory.

        - If the file in the sub-directories like ```address.html``` then ```href="Address/address.html"``` we have to give path to that file.

        - If the file in moving back in directories like I want to access ```pdf.html``` from ```address.html``` then ```href="../../Project/pdf.html```. What happens here is first ../ will move out form Address directory then next ../ move out from Contacts directory then /Project this access the project directory and then pdf.html will accessed.

    - Document Fragments :- 
    - 
    Document fragments means accessing the specific
    part in the same file or document. Suppose a college website, there are may sections and in the above there is list of all the sectons. Now if you want to go a specific section, you just have to click on that section link and it will take you to that section. You don't have to scroll it will take you there. 
    Let's take example a website 
    ```
    section 1
    section 2
    section 3
    section 4
    section 5
    In below there are introduction to eact section.
    ```

    Now if you want to acces the section 5 directly  you don't have to scroll just click on it, it will take you to that part.
    For this functionality we use ```id``` attribute.
    What is ```id``` attribute? It's an unique attribute specific to the element means this element can be accessed from anywhere on the document using this ```id``` attribute. We can't provide same ```id``` to different element. We access ```id``` attribute using ```#``` symbol.
    ```html
    <!-- contacts.html -->
    <a href="contacts.html#section-1">Section 1</a>
    <a href="contacts.html#section-2">Section 2</a>
    <a href="contacts.html#section-3">Section 3</a>
    <a href="contacts.html#section-4">Section 4</a>
    <a href="contacts.html#section-5">Section 5</a>

    <h4 id="section-1">Section 1</h4>
        <p>Some Contents...</p>

    <h4 id="section-2">Section 2</h4>
        <p>Some Contents...</p>

    <h4 id="section-3">Section 3</h4>
        <p>Some Contents...</p>

    <h4 id="section-4">Section 4</h4>
        <p>Some Contents...</p>

    <h4 id="section-5">Section 5</h4>
        <p>Some Contents...</p>
    ```
    [Try Here](BasicTags.html)

    - Absolute URL vs Relative URL
        - 
        - Absolute URl points to a location defined by its absolute path including protocol and domain name. For example, if an ```index.html``` page is uploaded to a directory called ```projects``` that is inside the root of a web server, and the website domain is ```https://www.example.com```, the page would be available at ```https://www.example.com/projects/index.html``` or ```https://www.example.com/projects/``` as most web server will look for ```index.html``` if it isn't specified in url.
        An absolute url will always points to same location wherever it is used. It is independent of the location at which it used.

        - Relative URl are the location that are realtive to the file from you are linking from like we do with the paths in the directories.
        We don't have to mention the whole url we can just mention the path to sub directories in the project. For example if we want to link a file from ```https://www.example.com/projects/index.html``` to a file inside the same directory, the URL would be just the name of the file - ```example.pdf```. Relative url is dependent on the location they are used.
    
    - links best practice
        - 
        - Name of the links should be relative to the resource for is it used. Don't write Click here only.
        - Links should be descriptive.
        - Use keywords to define link text as it's a good practice for search engines to find your links.

    - Email Links :-
        - 
        - 
        ```html 
        <a href="mailto:your email address">text..</a>
        ```
        - add cc bcc in email links
        ```html
        <a href="mailto:email?cc=email&bcc=email&subject=your%20subject%here&body=your%20body%20contents%20here">
        Send mail with cc, bcc, subject, body
        </a>
        ```
        Values of each field must be url encoded.

    - [Navigation menu](./Navigation)

- [Some more tags](./sometags.html):-
    - 
    - ```<b></b>``` : used for bold the text.
    - ```<u></u>``` : used for underline text.
    - ```<br />``` : used for break between the line.
    - ```<hr>``` used for horizontal line.
    - ```<strong></strong>``` : used to wrap text that we tend to speak stress. e.g This liquid is **highly toxic**. Here highly toxic words spoke with some stress to show its importance. Used when we use screen readers.
    - ```<em></em>``` : emphasize the text. 
    - ```<i></i>``` : italicize the text. 
    - ```<span></span>``` : Doesn't take any space. Wrap araound the element, text you want to style different from the group of elements. If you want specific ```li``` to behave different then we wrap that ```li``` element in ```span``` and use however style we want.
    - ```<sup></sup>``` used for superscript.
    - ```<sub></sub>``` used for subscript.
    - ```<abbr title="full form"></abbr>``` used for abbrevation. Use title attribute for abbrevation full forms.
    - ```<time date-time="format"></time>``` element for marking date and time in machine readable format.
    - ```<address></address>``` used for markup the contacts details. Don't use for the markup the list of address unrelated to content of the page.


- I'm going to explain different tags in the html file as understanding them is better by using them. [Try it here](./DescriptiveTags.html).
    - Desvription Lists :- 
        - 
        - ```<dl></dl>``` used to wrap the descriptions.
        - ```<dt></dt>``` used for description term.
        - ```<dd></dd>``` used for description definition.
        - example:- tags used for writing computer source code.
        ```html
        <dl>
            <dt>code(Descriptive term)</dt>
            <dd>code tag is used for show the programs on the browser.  (Description definition)</dd>

            <dt>pre</dt>
            <dd>pre tag is used when we want to not use the default justify of  the paragraph tag.The content in the pre 
                tag render on the browser as they were wriiten.</dd>
            
            <dt>var</dt>
            <dd>var tag is used for marking up the variables.</dd>
            
            <dt>kbd</dt>
            <dd>For marking up keyboard</dd>
            <dd>used for write keyboard commands. Ctrl+C/cmd</dd>
            
            <dt>samp</dt>
            <dd>For marking the output.</dd>
        </dl>
        ```
    - Quotation :- 
        - 
        - BlockQuotes ```<blockquote></blockquote>```
            - It is used for markinf the block level content if it is quoted from another source, attribute ```cite``` is used for url pointing the source of the attribute. 
        ```html
        <p>Here is Blockquote:</p>
        <blockquote cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote">
            <p>
                The HTML <code>&lt;blockquote&gt;</code> Element indicates that the enclosed text is an extentded quotation.
            </p>
        </blockquote>
        ```
        Output
        ```
        Here is Blockquote:
            The HTML <blockquote> Element indicates that the enclosed text is an extentded quotation.
        ```

        - quotes```<q cite=""></q>``` or Inline quotations
            - It is used for short quotation that doesn't require the paragraph breaks.
        ```html
        <p>The quote element &lt;q&gt; 
        <q cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote"> is intended for the short quotation that doesn't need paragraph breaks</q>.
        ```
        Output
        ```
        The quote element <q>  "is intended for short quotation that doesn't need a paragraph breaks".
        ``` 

        - ```<cite> </cite>``` contains the title of resource being updated e.g. title of the book.


