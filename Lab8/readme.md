# Executive Summary #

To finish off this course, you will learn about data and databases, including a peek into SQL coding for database management, and you will read about the ethics and laws of data and how regulation has been trying to catch up with the data boom of the 21st century. Hopefully, this unit will leave you with an impression of your responsibilities as a software engineer, to not abuse these marvelous tools, but to use them for good, to help people and not to steal their data.

***

# Data, Information and Knowledge #

### Relational Data ###

  * Data 

    * Data is bits of information with no context, like numbers in a vacuum or colors referring to no object.

    * Information is data with context, when context is applied to data. So numbers of moviegoers on a weekend or available colors at an art store.

    * Knowledge is the result of analysis and comprehension of information, like me, reading the textbook, synthesizing it in my head, and then writing down its ideas in my own words. I have knowledge on thai topic now

  * Database

    * When designing a database for a company with customers and orders, I would assign the order number as the primary key to relate the customers and orders.
    * This primary key of order numbers would connect the information about each order to the information about each customer, being that it represents each individual order from each customer.
    * A foreign key in the orders table could be the key to the different kinds of orders that are possible and it would relate to the primary key to connect that information about the customer.
    * The order table will have a date field to allow filtering by each day. This prevents confusion, because customers will likely order similar products every day. It also allows the primary key to reset every day for the order numbers with no interference.

### Big Data ###

  * The Four “V”s

    * Volume is the quantity of data available for use. Typically, the more data available for analysis, the better.
    * Variety is the diversity of data available. No matter the quantity, data is not very useful if it is only of one kind. Diverse data points provide more accuracy and insight.
    * Veracity is the level of trust data carries with it. The source of data is crucial to its veracity; unsourced data is worthless, and sketchy data sources make for tenuous conclusions.
    * Velocity is how quickly data can be synthesized and converted into useful information and billable products. In this day and age of instant-access and streaming, the window of time for the velocity data is instantaneous.

  * Various technologies have driven the increase of the need for big data, each building on each other. Streaming has driven the need for user data like demographics, so advertisers can effectively advertise their products to the right audiences. Search engines like Google have driven the need for all sorts of obscure datasets like time windows of browser usage, and probability of news scrolling and retention rate for layouts of search bars. All these data points provide Google with information on how to further optimize the internet searching experience for their users, giving them an edge over smaller browsers. Those data on retention become even more in-demand in video services like Youtube and TikTok, where audience retention is the key to making money. The longer the companies have eyeballs, the more ads they show, and the more money they make, so retention data is immensely useful, and ends of shaping what kind of videos are created in the first place

# Structured Query Language #

  * The Relational Database Management System (RDBMS) is the underlying architecture that orders databases controlled by SQL. AS evident in that statement, SQL is a programming language for interacting and managing the data in a RDBMS. SQL was created to have an easier way to access and manipulate data within a database, to expedite the process for businesses and individuals.

  * In the Northwind database tables, the two tables, “Suppliers” and “Products” are related by the products between them, the “Suppliers” table providing information on where the products in the “Products” table are coming from. The primary key is the SupplierID, which is then fed into the “Products” table to be assigned to different products to create the foreign ProductID key for each product, containing the supplier information. These two tables give a picture of where the products are coming from and the different properties of the suppliers and products and how they relate to each other.

# SQL Injections #

  * A SQL Injection is when a user returns malicious SQL code instead of requesting information, like typing SQL code to retrieve all the passwords in a database in response to a prompt for the user’s name. The hacker can use truth statements like 1=1 to run their code under to ensure it continues to parse through the entire database, because 1 is always equal to 1. Using parameters in your SQL code ensures that each line is checked before running it, to protect from the database confusing the SQL input in the user box for a SQL command for the database.

# Ethical and Legal Implications #


### Code of Ethics ###

  * A code of ethics is created to explicitly state rules to be followed by those whom it applies to. Because humans vary in experiences and ideas of what is normal, a code of ethics puts everyone on the same page and brings consistency and expectations to be met and standards to hold each other to. ACM created a code of ethics for computing because the advance of computing technology happened much faster than any regulation could be made concerning it, so people were downloading music that cost money in the store, and other activities like that. Since laws take time to make, ACM made a code of ethics to apply within its jurisdiction at the very least, to organize everyone working under them to all be on the same page about what was acceptable and not.

  * An Acceptable Use Policy is quite similar to Code of Ethics, in that it is also a list of rules to be followed within a governing entity. It appears to me that the difference between the two is that a code of ethics is a more broad document applying to the standards of digital technology, like the constitution, whereas an acceptable use policy is smaller, pertaining to using a particular service.

    * In the Twitter TOS (Terms of Service) document( https://twitter.com/en/tos ), they note that they have the right to deactivate your account at any time if they feel it is necessary. This is why people sometimes get banned from twitter and cannot do anything about it, because they agree to this condition by making an account in the first place. 

###  Intellectual Property ###

  * WIPO is an integral part of the governing ideas in this time of rapid data transfer. They are an organization under the United Nations responsible for managing IP laws, the policies surrounding intellectual property and what is fair use and what is copyright and so on and so forth. Without them, ideas can be stolen and inventors left in the dust for whoever shouts the loudest. WIPO works to protect those working hard to create their own ideas and products from predatory copycats.

  * In the US, a copyright is acquired by simply creating something. One automatically has the rights to their creation by virtue of creating it. But registering for a copyright with the US Copyright Office gives you a registered copyright, which is needed in the event of a legal battle, so it is certainly better to have a registered copyright on your creations.
    * The SVG image we created earlier is something we created from scratch, and it is our own design, so if it is important to us that it remains ours and that others cannot profit off of it without our permission, registering for a copyright on it would prevent that.

 * If we liked our SVG image so much that we would assign it as the defining logo of a future company we owned, then a trademark would be important. A trademark certifies that my version of the SVG is the true and original one, so people who want to buy goods from me only need to look for my image and they know they have found the correct place. Without a trademark, it may get confusing, with other businesses using my SVG as their logo too.

### Information Collection ###

  * COPPA, FERPA and HIPPA are all different agencies that work to protect the privacy of information of different individuals on the internet. COPPA protects the privacy of children under 13, FERPA concerns students' educational information and when their parents lose access, and HIPPA deals with medical records and protects the privacy of patients.


***
# Conclusion #

What an interesting way to finish this course! I found all the data talk a bit heavy and hard to understand, but I understood its importance and I am happy I learned it. The SQL coding was cool though, seeing how powerful the language is, to be able to execute just a few lines of code to get curated useful sections of databases. And of course, the legal and ethical issues, while not necessarily fun, I thought were a fitting way to end this course, to impress upon us the importance of the responsibilities we have as software engineers. I think this course was a nice introduction to all things digital, and I am excited to continue this journey into the next IT course.
