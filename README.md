# cs50
Harvard CS50 Web and Python Programming Course

Project name: Project 0

Description: I created a HTML/CSS site that drills down into financial and corporate details of Microsoft.

Credit: I used data from Yahoo Finance and logos from Google search results.

Table of Contents: 
  1) Index: Portfolio "splash page" that lists stocks in a portfolio. The index page drills down to 4 other pages, but only for Microsoft.
  2) Summary page that provides high-level information on Microsoft (e.g., stock price)
  3) Statistics page provides some financial details on Microsoft (e.g., Return on Equity)
  4) Executives page provide information on top Micosoft executive (e.g., CEO)
  5) Analysis page provides analyst estimates and other details

Features: Per Project 0's requirements, I added the following functionality:
  1) The website contains five .html pages.
  2) Each page contains an unordered list of hyperlinks that connect to one other.
  3) The index page lists images of corportate logos.
  4) The index page ("Portfolio Page") uses bootstrap as a stylesheet and formats the company logos using two Bootstrap columns for layout purposes within Bootstrap’s grid model.
  5) The index page also makes use of the alert Bootstrap 4 component when stating the disclaimer, "For education purposes only". Consequently, this page also employs @media "print-only" class to only print "Print for education purposes only" when the page is printed via printer. I realize this is a reprint of the Bootstrap 4 alert, "For education purposes only," but I'm doing this to fulfill the requirement of Project 0--not for asthetics. 
  6) The index page also references style.css. Style.css employs several properties. For example, the ".mytable" class defines properties for border, border-collapse, font-family, font-size, while the "#Summary_title" ID sets properties such as font color and font-family.  
  7) Style.css also invokes @media to expanding/contracting screensize (min_width: 500px and max_width: 499px) by adjusting the font-size property. The index page also declares meta name ="viewport" and content="width=device-width, initial-scale=1.0".
  8) Finally, I used SCSS variable of $color1 and $color2 as a global declaration to adjust colors of "div" "p" text and unordered list, respectively across the Microsoft Executives page. Instead of compiling SCSS to CSS, I used an online interpretter, "https://www.cssportal.com/scss-to-css/" and simply copy/pasted the resulting code into the inheritence.css file. 
