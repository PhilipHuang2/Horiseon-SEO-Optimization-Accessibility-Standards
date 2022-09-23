# Horiseon Accessibility Standard Update

# Description

In this project, I am updating the Horiseon home page to modern SEO and accessibility standards.  I am doing this because updating the home page will help Horiseon as a business and help users in accessing and navigating the site.

Improvements to the structure of the home page will make the page easier to read for internet crawlers boosting its ranking in search engines ratings which allows more customers to find Horiseon.  In addition, the improvements will help screen readers and make the site accessible through shortcuts which helps both those who have difficulty with their eyes such as the blind or the elderly and proper headers allows people with motor disabilities to bypass scrolling.

The home page is built on HTML and styled with CSS, and the changes that I made were titled all the images with alternative texts so that screen readers can understand the website, renamed and ordered the headers to a more logical and intuitive structure, restructured the main HTML to a logical order, and introduced semantic HTML elements that better describe the Document for future developers and search engine crawlers.  In addition, I cleaned up duplicate CSS code to minimize reading and improve clarity.

Through this project, I have learn the meaning and proper usage of semantic elements, and headers.  I have also learned how to restructure a document to become more logical and easier to parse.  Also CSS has also been a hard point for me, so reading the Stylesheet and comparing it to the HTML document has improved my CSS knowledge about selectors and the different combinations and syntax there of. 

I hope that this documents will be easier to read through my work and the CSS has become easier to manage.

## Example

Below is segment of the CSS from the home page.  This code is styling 3 articles about the benefits of working with Horiseon.  Each article uses a different class can contains different styles for each sub element.  However this is a waste as each class is styled exactly the same.
``` CSS
.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-lead h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-lead img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-brand img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
```

Instead, I have chosen to merge all three benefits classes into one class benefit-article.  
``` CSS
.benefit-article {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-article h2 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-article img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

```

This change improves the code in two ways.  First of all, we have reduced the code by two thirds which makes the code concise and more readable.  In addition, this change eases future development as changes or additions to the benefits section can be standardized under one class.



# Installation
Just clone the repository on your machine and drag and drop the index.html file to your browser and you can see Horiseon's home page.

# License

## MIT License

Copyright (c) 2022 Philip Huang

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.