# 01 HTML, CSS, and Git: Code Refactor

# Table of Contents
* [Project Description](#projectdescription)
* [How I refactored](##howirefactored)
* [Usage](##Usage)
* [URL](##URL)

## Project Description
One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities and/or socio-economic restrictions have access to their website. Accessible websites are better optimized for search engines, and help companies avoid litigation.

For this week's Challenge, your task is to refactor an existing webpage to make it accessible and to improve SEO. It's important to follow the Scout Rule when working with an existing codebase: Always leave the code a little cleaner than you found it. 

To impress the imaginary client for this Challenge, you should go the extra mile and improve their codebase for long-term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, such as by consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

Remember when working with a client, it is essential to read the acceptance criteria for guidance and clarity on what the client expects, especially when asked to make a judgment call, such as when an icon needs an accessible alt tag and when it is okay to leave it blank. 

To successfully complete this week's Challenge, all acceptance criteria must be fully addressed!

### User Story
```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our site is optimized for search engines
```

### Acceptance Criteria

```
GIVEN a webpage that meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN I find that they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
## How I Refactored

```
I refactored this webpage and made it more accessible by starting with changing the title and adding navigation that direct the user to the appropriate ids in the body. I simplified the CSS that affected the header by changing all of the selectors to elements for the sake of simplicity since they only occur once on the page anyways. I then moved down to the hero and content in the HTML where I added semantic elements such as <section>s and <article>s and DRYed up the classes used in the sections in the CSS. I did the same for the benefits section, but I didnt add any <article>s. I also added alt attributes to all of the images and icons. I reordered the declarations in the CSS document to match the order in the HTML. I also added comments to both files to index the code.
```

## Usage

```
This is a webpage with naviagtion links in the top header.
Here are the screenshots: 
[header and hero](assets/images/horiseon-header-hero.png)
[content and benefits](assets/images/horiseon-content-benefits.png)
[footer](assets/images/horiseon-content-benefits-footer.png)
```
## URL

```
You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a professional README describing the project.
```
- - -
© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
# Horiseon
