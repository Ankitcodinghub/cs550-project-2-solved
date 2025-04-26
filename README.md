# cs550-project-2-solved
**TO GET THIS SOLUTION VISIT:** [Cs550 Project 2 Solved](https://www.ankitcodinghub.com/product/cs550-project-description-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131837&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Cs550  Project 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
Your database consists of the following tables:

Your command-line interface should include the following functionalities.

1. The user can view the contents of each table. Show the name of each table and display the tuples of the table(s) that the user selects. (The user can select more than one tables to view.)

3. The user can search the database by specifying one or more input attributes from {AUTHOR, TITLE, YEAR, TYPE} and specify one or more output attributes from both tables. In addition, the user can specify a field on which the search result should be sorted. Your search should consider pattern matching for input strings.

4. Your program should exit only when the user chooses to.

When your program starts, prompt the user for his/her Oracle username and password. Please do not hard-code your own login information in the code. After the program connects to the database successfully, prompt the user for the location of paper.sql script file when you create and insert data into the database from the script file. After the database is ready for search, print a menu like below and prompt the user to choose an option from the menu. If the user enters an option that is not valid, a message stating the option is invalid should be displayed and the menu is displayed again.

1. View table contents

2. Search by PUBLICATIONID

3. Search by one or more attributes

4. Exit

When the user chooses one of the options listed below:

2. prompt the user for PUBLICATIONID

3. prompt the user for input fields, output fields, and a sorted field like below:

Input fields:

AUTHOR:

TITLE:

YEAR: TYPE:

Output fields:

PUBLICATIONID (Yes/No):

AUTHOR (Yes/No):

TITLE (Yes/No):

YEAR (Yes/No):

TYPE (Yes/No):

SUMMARY (Yes/No):

Sorted by:

4. Exit the program

The output should be either in tabular form (with or without lines) or each field is separated by commas. Print out an error message when no (valid) inputs are specified and prompt for inputs again. Print out a message when no results are found and go back to the main menu. After an option is executed, your program should go back to the main menu.

Extra credit: (10 Points)

Create a GUI interface or a web application and give a demo to the GTA. Your interface should be user friendly and be able to achieve the same functionalities specified for command-line interface above.

The deliverable:

Submit your source file(s) and the script of running each option from the menu.

Tips:

The file Student.java includes Java commands for loading the necessary driver and connecting to Oracle database (Make changes to username and password). It will display the following information after it compiles and runs successfully:

jdbc:oracle:thin:@artemis.vsnet.gmu.edu:1521/vse18c.vsnet.gmu.edu Connected.

Database Product Name: Oracle

Database Product Version: Oracle Database 18c Enterprise Edition

Release 18.0.0.0.0 – Production

Version 18.6.0.0.0

Database Driver Name: Oracle JDBC driver

Database Driver Version: 18.3.0.0.0

Resources:

1. Quick start with JDBC https://www.oracle.com/database/technologies/develop-java-apps-using-jdbc.html

2. JDBC Tutorial

https://docs.oracle.com/javase/tutorial/jdbc/basics/index.html

3. Oracle JDBC FAQ

https://www.oracle.com/database/technologies/faq-jdbc.html

4. Execute SQL script using JDBC https://www.tutorialspoint.com/how-to-run-sql-script-using-jdbc https://github.com/mybatis/mybatis-3/releases/tag/mybatis-3.5.7
