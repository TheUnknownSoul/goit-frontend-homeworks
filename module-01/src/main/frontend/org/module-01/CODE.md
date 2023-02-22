# Part 1

# Task 1

```html
<h1>The main theme of the web page in the h1 header.</h1>
```

# Task 2

```html
<!-- The commentary answers the question "Why is this part of the code written".-->
```

# Task 3

```html
<img src="/photo.jpg" alt="Image example" width="200" height="150">
```

# Task 4

```html

<ul>
    <li> HTML</li>
    <li> CSS</li>
    <li> JavaScript</li>
</ul>
```

# Task 5

```html

<div class="buttons">

    <button type="button" class="button">inline</button>
    <button type="button" class="button">block</button>
    <button type="button" class="button">inline-block</button>

</div>
<div class="buttons">

    <button type="button" class="button">HTML</button>
    <button type="button" class="button">CSS</button>
    <button type="button" class="button">JavaScript</button>

</div>
```

# Task 6

```html

<div class="box">
    <a href="#" class="link-inline"><span>Text</span></a>
    without line break
</div>
<div class="box">
    <a href="#" class="link-block"><p>Text</p></a>
    line break
</div>

```

# Task 7

```html

<div class="card">
    <h4 class="card-title">The order in which files are loaded by the browser</h4>
    <ol reversed class="card-items">
        <li class="card-item">HTML file</li>
        <li class="card-item">Link to files inside head</li>
        <li class="card-item">Link to files inside body</li>
    </ol>
</div>

```

# Task 8

```html

<ul class="cards">
    <li class="card">
        <h4 class="card-title">Card title 1</h4>
        <div class="wrp-img">
            <img
                    class="card-image"
                    src="https://ac.goit.global/img/photo1.jpg"
                    alt="image description"
            />
        </div>
        <p class="card-description">Description of the topic 1</p>
    </li>
    <li class="card">
        <h4 class="card-title">Card title 2</h4>
        <div class="wrp-img">
            <img
                    class="card-image"
                    src="https://ac.goit.global/img/photo2.jpg"
                    alt="image description"
            />
        </div>
        <p class="card-description">Description of the topic 2</p>
    </li>
    <li class="card">
        <h4 class="card-title">Card title 3</h4>
        <div class="wrp-img">
            <img
                    class="card-image"
                    src="https://ac.goit.global/img/photo3.jpg"
                    alt="image description"
            />
        </div>
        <p class="card-description">Description of the topic 3</p>
    </li>
</ul>

```

# Task 9

```html
<a href="https://goit.global" target="_blank" rel="noreferrer & noopener & nofollow"> GoIT </a>

```

# Task 10

```html
<a href="resume.pdf" download="">Resume</a>
<!-- Link to phone number  -->
<a href="tel:+14251234563">+1 (425) 123-45-63</a>
<!-- Link to e-mail address -->
<a href="mailto:example@gmail.com">example@gmail.com</a>

```

# Task 11

```html

<header id="top">
    <!-- content from logo, nav, search  -->
</header>
<main>
    <aside>
        <ul>
            <li><a href="#top">Top of the page</a></li>
            <li><a href="#page-theme">Main theme</a></li>
            <li><a href="#bottom">Footer of the page</a></li>
        </ul>
    </aside>
    <article id="page-theme">
        <!-- main page theme -->
    </article>
</main>
<footer id="bottom">
    <!-- content from logo, nav, contacts, copyright  -->
</footer>

```

# Task 12

```html

<header id="top">
    <!-- content from logo, nav, search  -->
</header>
<main>
    <aside>
        <ul>
            <li><a href="#top">Top of the page</a></li>
            <li><a href="#page-theme">Main theme</a></li>
            <li><a href="#bottom">Footer of the page</a></li>
        </ul>
    </aside>
    <article id="page-theme">
        <!-- main page theme -->
    </article>
</main>
<footer id="bottom">
    <!-- content from logo, nav, contacts, copyright  -->
</footer>

```

# Task 13

```html

<figure>
    <img src="https://ac.goit.global/img/photo1.jpg" alt="photo description"/>
    <figcaption>Only
        one img element and any number of text or other elements can be used inside
        link. You cannot use interactive elements inside link tag.
    </figcaption>
</figure>
```

# Task 14

```html
<a class="link"
   target="_blank"
   href="https://goit.global"
>
    <img src="https://ac.goit.global/img/photo1.jpg"
         alt="note in laptop"
    />
</a>
<a class="link"
   target="_blank"
   href="https://goit.global"
>
    <img src="https://ac.goit.global/img/photo2.jpg"
         alt="note on paper"
    />
</a>
```

# Task 15

```html
<!--  TODO
* create project with the following structure:
images/logo.svg
css/style.css
about.html
index.html
-->
```

# Task 16

```html
<img src="https://ac.goit.global/img/html-css.png" alt="logo"/>

```

# Part 2

# Task 1

```html

<dl>
    <dt>Tag span.</dt>
    <dd> A universal container for text content.</dd>
    <dt>Tag pre.</dt>
    <dd> Preservation of spaces and hyphens.</dd>
    <dt>Tag sup and sub.</dt>
    <dd>Displays characters in superscript and subscript.</dd>
    <dt>Tag strong.</dt>
    <dd> Highlighting an important word or a whole phrase within the text.</dd>
    <dt> Tag b.</dt>
    <dd> Visual highlighting of text with a thicker font.</dd>
    <dt> Tag em.</dt>
    <dd> Semantically and visually (italic) emphasizes the text.</dd>
    <dt> Tag i.</dt>
    <dd> Visually (italic) emphasizes the text.</dd>
    <dt> Tag address.</dt>
    <dd> Wraps tags with content about an address or recipient.</dd>
</dl>

```

# Task 2

```html

<p>
    Epoch of Unix time started at
    <time datetime="1970-01-01T00:00">північ станом на 01 січня 1970 року</time>
</p>

```

# Task 3

```html

<span>&#174;</span>
```

# Task 4

```html

<audio controls preload="none">
    <source src="https://goit.ua/autocheck/bensound-summer.mp3" type="audio/mp3">
</audio>
```

# Task 5

```html

<table>
    <caption>
        What is the difference between block, inline and inline-block
    </caption>
    <thead>
    <tr>
        <th>/</th>
        <th>block</th>
        <th>inline</th>
        <th>inline-block</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <th>height determined</th>
        <td colspan="3">by height of content</td>

    </tr>
    <tr>
        <th>width determined</th>
        <td>by width of parent element</td>
        <td colspan="2">by width of content</td>
    </tr>
    <tr>
        <th>Is it possible to set height and width</th>
        <td>yes</td>
        <td>no</td>
        <td>yes</td>
    </tr>
    <tr>
        <th>How line wrapping works</th>
        <td>always on a new line</td>
        <td colspan="2">only when filling the width of the parent element</td>
    </tr>
    </tbody>
</table>


```