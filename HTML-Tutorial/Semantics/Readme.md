#### Let's talk about semantic elements. In simple words words semantic means the reason behind the word, what it views, that why this word is used according to the situation. 

- Semantic elements are those which shows the meaningful markup of the document i.e why this element is used here. Semantic elements tells us that they are the best fit according to the current markup. 

- Till now you must have been using the div elements for the grouping of different elements. But the div element in itself doesn't tells us the meaning of that markup that it is header, footer, section or navigation bar etc. Like what is the meaning of that markup.

- To give meaning to the markup we use semantic elements like 
    - ```<main></main>```
        - The main content of the page will go inside the main element. It is used once per page and directly inside the body element.
    - ```<header></header>```
        - The header element contain the top part of the document like navigations, introductions etc. If its child of the body element then its gloal header or if it's a child of article or section then it is header related to that particular element.
    - ```<nav></nav>``` 
        - This element contains the navigation of the page not another secondary link which have no relaton to page navigation.
    - ```<section></section>```
        - The section element used for dividing the different section inside the main element or any other element. It describes the particular section related to particular content.
    - ```<footer></footer>```
        - This element contains the footer of the page. In most of the pages at the last of the page, information like contact, social media platforms, author information were given which comes under the footer element.
    -   ```<article></aticle>```
        - The content which can make sense on its own without the reference of the content on the document written inside the article element.(example : a blog post, an note, any disclaimer). 
    - ```<aside></aside>```
        - Contains information indirectly related to the main content (author biography, related links). In the most of the site you have been observe that is there are some links which are at the side of the documents, are not directly related to the main content but indirectly gives the information about the main content. They are mostly designed in a fashion like section of many links which are going up and down or from right to left in the documents.

    ```html
    <body>
        <header><!--global header-->
        </header>
        <nav>Navigation links comes here.</nav>
        <main>
            <section>
                <header><!--local header-->

                </header>
                <setion></section>
            </section>
        </main>
        <footer>
                contacts, social media platform, address, like info.
        </footer>
    </body>
    ```
    - I have made a page describing the use of semanting elements. [Try it here](./semantics.html)