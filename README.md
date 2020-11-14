README document
General project documentation is to be compiled as a single markdown file named README.md. This file should contain,

A link (URL) to your published portfolio website
A link to your GitHub repo
Description of your portfolio website, including,
Purpose
Functionality / features
Sitemap
Screenshots
Target audience
Tech stack (e.g. html, css, deployment platform, etc)

# MICHAEL DART - T1A2 - PORTFOLIO ASSIGNMENT
<br>
<br>

### Target Audience
Seeking the attention of industry professionals who are looking for a junior web developer with rich life experience who is eager to learn and develop and in due time progress past an entry-level of employment

## ABOUT THE WEBSITE

### Purpose
A comprehensive insight into me and who I am as a person, showcasing my work and study history, what got me into coding and my coding journey so far with some projects I have embarked on.
<br>
<br>

### Functionality and Features
As a portfolio website, I have kept the functionality as simple as possible with only 4 pages.<br>
A uniformed layout is noticeable across the website, the simplified layout includes:
- Header
- Navigation Bar
- Body
- Footer
<br>
<br>

#### THE HEADER
The header features a title sitting infront of an image which is used to increase the websites identity. A fade-in animation is a set to these elements for "wow" effect when the audience enters/refreshes the page, additional coding allows the styling is accessible across multiple browsers. The image is finished off with curved edges for a calm feel.

Example code HTML Code:
``` html
    <div class="header">
        <header>
            <img src="images/kitesurfing.jpg" alt="Kite-Surfing-Pic">
            <div class="title">Michael Dart - an evolving Developer</div>
        </header>
    </div>
```

Example code CSS Code:
``` css 
.header {
    position: relative;
}

.header img {
    border-radius: 5px 5px 70px 70px;
    max-width: 100%;
    animation: fadeIn ease 3.5s;
    -webkit-animation: fadeIn ease 3.5s;
    -moz-animation: fadeIn ease 3.5s;
    -o-animation: fadeIn ease 3.5s;
    -ms-animation: fadeIn ease 3.5s;
}

.title {
    position: absolute;
    display: inline-block;
    top: 8px;
    left: 10px;
    color: rgb(172, 204, 240);
    font-size: 2.3vh;
    font-family: 'Fredoka One', cursive;
    background-color: rgb(77, 77, 77);
    border-radius: 10px;
    padding: 4px 10px 4px 10px;
    animation: fadeIn ease 3s;
    -webkit-animation: fadeIn ease 3.5s;
    -moz-animation: fadeIn ease 3.5s;
    -o-animation: fadeIn ease 3.5s;
    -ms-animation: fadeIn ease 3.5s; 
```
<br>
<br>

#### THE NAVIGATION BAR
A single line bar with 4 titles that shrinks in smaller screen sizes. This navigation bar is easy to see across all devices allowing the audience to connect seemlessly to any page on the website. For easy reference, the active (or current) page is highlighted in a different colour, bold and uppercase text.
<br>
<br>

Example code HTML Code:
``` html
    <div class="navbar">
        <nav>
            <ul>
                <li><a class="active" href="#">Home</a></li>
                <li><a href="aboutme.html">About Me</a></li>
                <li><a href="blogs.html">Blogs</a></li>
                <li><a href="contactme.html">Contact Me</a></li>
            </ul>
        </nav>
    </div>
```

Example code CSS Code:
``` css
.navbar {
    border-radius: 15px;
    margin-top: 10px;
    margin-bottom: 5px;
    background-color: rgb(24, 131, 99);
    width: 100%;
    overflow: auto;
}

ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

.navbar li {
    font-size: 2.10vh;
    font-weight: 400;
    font-family: 'Varela Round', sans-serif;
}

.navbar li a {
    float: left;
    color: white;
    text-decoration: none;
    text-align: center;
    width: 25%;
}

li a:hover {
    background-color: rgb(9, 243, 165);
}

.active {
    background-color: rgb(9, 243, 165);
    font-weight: 700;
}
```

#### The footer
The footer is shown across all pages and shows the copyright information.
<br>
<br>

## SITEMAP
![Sitemap](docs/Sitemap.jpeg)

## SCREENSHOTS




## TECH STACK
Below is a list of tools I used to develop my site:
- Balsamiq (for Wireframes)
- HTML and CSS (in VS Code)
- Images - Created or captured by me and externally sourced (credits are referenced in the footer of the pages where these images exist)
- GitHub (for remote repository)
- Netlify (for deploying)
- Microsoft Powerpoint (for Slidedeck presentation)
- Lucidchart (for Sitemap)

## REMOTE CONNECTIONS

### Netlify 
You can access my website via [My Netlify]{https://app.netlify.com/teams/mdart86/overview} &&& UPDATE THE LINK&&&
<br>
<br>

### Git Hub
To see my remote respository - please go to [My GitHub Repository]{https://github.com/mdart86/Michael-Dart_T1A2}
<br>
<br>




