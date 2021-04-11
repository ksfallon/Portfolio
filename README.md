# Portfolio Homework Week 2

This week we made our first website which is our **Portfolio**!

[Here is the link to my portfolio!](https://ksfallon.github.io/Portfolio/)

## Assignment
Our portfolio pages needs to have multiple elements.
1. We need to have an interactive header that includes a navigation bar that links you to other sections of the website as well as a resume and uses the hover function to highlight the link text.

2. Within the main body of the text are 3 sections: 'About Me", "Work" and "Contact Me". In each of these sections the section title is on the left side of the page, tthe body of these sections are on the right.

*  *About Me* includes a current picture of ourselves and some information about us.
* *Work* has 5 containers that have pictures, titles, brief description and links to our work. When you hover over the images the image is highlighted and the top image is larger than the other images. The top image is also on its own row while the rest are two to a row, creating a column of 3 rows. 
* *Contact Me* provides links for ways in which someone could contact us. The hover funtion is also used over these links.
* The website needs to be responsive to screen changes so media queries are required for smaller screens such as ipads and cell phones.

## My Portfolio
Here is a screen shot of my portfolio on a laptop screen

![Portfolio](assets\images\portfolio.png)

1. Body 
In CSS I set the body to display: flex and the flex-direction:column to allow for easy movement as the screen changes sizes. For the media query max-width: 667 and (min-width: 768px) and (max-width: 1025px) I kept the display:flex and made the width 100%


2. Header Section

In the header section I used display: flex , justify-content: space between, and align-items: center to organise the title and the navigation bar. and for the media queries i just kept display flex and added width 100%.

To create the hover I decided to change the navigation font color and the background color

![Navigation hover](assets\images\navhover.png)

3. Work Section 

For the titles of each section I used display: flex and justify-content: flex-start to have them all on the left side of the page. In the media query for (min-width: 768px) I changed the border from right only to a complete border and justfiy-content: left. 

to create the hover effect i decided to enlarge the images using hover transform to make the images larger and hover background color and font color to change the headers and text within the box.

![Work](assets\images\workhover.png)

for both media queries I changed how the images were stacked. They went from 3 rows in a single column to 5 rows (1 picture per row) in a single colum.
to have two images on a row the display was inline-flex with a width of 49% for the 4 bottom images. In the media queries it became a width of 100% instead. The .alignright did not originally have a flex directino so it was given flex-direction: column as well.

4. Contact Me

The last section is my contact section which contains links to my github and linked accounts. I also have blank links for twitter and instagram. I did one last hover feature here to change the font color and the background color.

![contact](assets\images\contacthover.png)