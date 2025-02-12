<h1 align="center">
  Web Scraping with Beautiful Soup [High Five]
  <br>
</h1>

<b>Web scraping</b> is the process of automatically extracting information from a website using a software program. It involves making HTTP requests to a website's server, downloading the HTML of the web page, and then parsing that HTML to extract the data you're interested in. The data can then be stored in a file, a database or a spreadsheet for further analysis and use.Web scraping can be used for a wide variety of purposes, such as data mining, data analysis, price comparison, sentiment analysis, and more. The web scraping process can be done manually or using web scraping tools and libraries such as Beautiful Soup, Scrapy, Selenium, and many more.<b>It is important to note that web scraping can be subject to legal restrictions and terms of use of the websites.</b>


<b>Beautiful Soup</b> is a package provided by Python with the purpose of parsing XML and HTML files. Beautiful Soup is commonly used to perform web scraping since most websites and web pages used HTML. It provides simple methods and Pythonic idioms for navigating, searching, and modifying the parse tree, and it sits on top of popular Python parsers like lxml and html5lib, allowing users to try out different parsing strategies or trade speed for flexibility. 

In this project, we are required to perform web scraping using Beautiful Soup for any website which have any relation with Malaysia. Since we were briefed to specifically choose the website that related to Malaysia, we had chosen to use [this](https://eduspiral.com/about-us-eduspiral-consultant-services/advise-best-course-study-top-private-universities-malaysia/top-guides-choosing-the-best-course/best-courses-study-in-malaysia/top-10-degree-courses-in-malaysia-with-highest-starting-salaries/choosing-a-degree-malaysia-top-most-popular-courses/top-ten-best-degree-diploma-foundtion-pre-university-courses-to-study-in-malaysia-after-spm-uec-olevels-stpm-alevels-cpu-sam-ausmat-mufy/) website to execute the web scraping.

The output of this web scraping will be a list of dictionaries, where each dictionary represents one item from the first ordered list (ol) element on the web page. The dictionaries will contain the following key-value pairs:

    'Category': the text of the first <strong> element found within the list item
    'Course Name': the text of the list item
    'Link': the value of the 'href' attribute of the first <a> element found within the list item.

"The 'Category' field represents the general field of study, while the 'Course Name' is a subcategory within that field, and the 'Link' directs the user to a webpage that provides more detailed information about the course."

<h3 align=center>

![image](https://user-images.githubusercontent.com/99240177/214037671-3a6d291e-358c-4f66-b2bc-204d65dae20e.png)

Group members:
</h3>

<table align=center>
  <tr>
    <th>Name</th>
    <th>Matric Number</th>
  </tr>
    <tr>
    <td>AHMAD MUHAIMIN BIN AHMAD HAMBALI</td>
    <td>A20EC0006</td>
  </tr>
    <tr>
    <td>NAYLI NABIHAH BINTI JASNI</td>
    <td>A20EC0105</td>
  </tr>
     <tr>
    <td>SAKINAH AL’IZZAH BINTI MOHD ASRI</td>
    <td>A20EC0142</td>
  </tr>
     <tr>
    <td>LEE JIA XIAN</td>
    <td>A20EC0200</td>
  </tr>
  </table>
