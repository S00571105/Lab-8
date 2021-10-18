## Joyce Stonebraker/10.21.21

## Executive Summary 
This section described various database models and allowed the opportunity to practice querying a database with SQL. In addition this section discussed key ethical and legal implications of information systems.

## Data, Information and Knowledge and Compare and contrast data, information and knowledge
In comparing and contrasting data, information and knowledge it is important to understand data is the raw facts and maybe qualitative (descriptive) or quantitative (numeric). Whereby information is processed data that has context, relevance and purpose and  information involves the manipulation of raw data to obtain an indication of magnitude, trends, in patterns in the data for purpose. And knowledge is the area of human believes or perceptions about relationships among facts or concepts relevant to that area. In addition there is explicit knowledge that typically refers to knowledge that can be expressed into words or numbers and tacit knowledge includes insights and intuition that is difficult to transfer to another. And the final step to knowledge is wisdom; this is when a person combines their knowledge and experience to produce a deeper meaning to a topic.

### Relational Data
When creating a database for a small company and two tables you identify are: customers and orders, explained below is the primary key, relationship between customer and orders and foreign key.  The Customer table would include customer Id, Customer name,contact name,address, city, postal code and country.  And the second table customer order would include customer ID, customer name, order date, order number,order name, order unit and price.

#### Primary Key:
The primary key would be Customer id that is unique to both the customer and orders for each table in a relational database.

#### Relationship between customers and orders:
The relationship between the customers and orders would be the primary key Customer ID.

#### Foreign key of orders table:
And possible a foreign key in this example would be an Order number.

### Field Data Types
When defining fields in a database table it is important to give each field data a type. The reason this is important is because the data field type defines what functions can be performed and it also gives the field the proper amount of storage space. The field types are: Text: for storing non-numeric data that is brief, generally under 256 characters. The database designer can identify the maximum length of the text,Number: for storing numbers. There are usually a few different number types that can be selected, depending on how large the largest number will be,Boolean: a data type with only two possible values, such as 0 or 1, “true” or “false”, “yes” or “no”,Date/Time: a special form of the number data type that can be interpreted as a number or a time,Currency: a special form of the number data type that formats all values with a currency indicator and two decimal places,Paragraph Text: this data type allows for text longer than 256 characters andObject: this data type allows for the storage of data that cannot be entered via keyboard, such as an image or a music file.

### Big Data
Big data is the collection of data that is huge in volume, and growing exponential in time. It is data with so large size and complexity that none of the traditional data management tools can store it or process it efficiently. So big data is data with a large size. An example of big data would be the New York Stock Exchange.

#### Four "V"s of Big Data
The four V’s of big data are volume, variety, velocity and variability. Volume refers to the size of the data, variety refers to heterogeneous sources and data nature both structured and unstructured, velocity refers to the speed of generation of data and variability refers to the inconsistency which can be shown by data at times, that may interfere with the processing of data effectively.

#### Technology Driving the need for Big Data
Technology driving the need for big data this is evident with the New York Stock Exchnage, Social Media, and Jet engines. Social Media along shows that five hundred plus terabytes of new data get ingested into databases of social media site Facebook every day. 

## Structured Query Language (SQL) 
SQL is a structured query language that is a basic lanquage for accessing and manipulating databases.

### RDBMS and SQL
An explanation of RDMS is it is a relational data base management system and is the basis for SQL and for all modern database systems such as MS SQL Server, IBM DB 32, Oracle, MySQL and Microsoft Access. The data in RDBMS is stored in database objects called tables, this is how it relates to SQL and the purpose of SQL is to get the data you want.

### Relationship, Primary and Foreign Keys
The relationship of primary and foreign keys is the primary key is a key is usually the unique identification number of the records that is in both tables. And a foreign key is a foreign key is a field in one table that connects to the primary key data in the original table.

## SQL Injections
An explanation SQL injection attacks allow attackers to spoof identity, tamper with existing data, cause repudiation issues such as voiding transactions or changing balances, allow the complete disclosure of all data on the system, destroy the data or make it otherwise unavailable, and become administrators of the database server.  Such security threats can be reduced  by utilizing parameterized database queries with bound, typed parameters and careful use of parameterized stored procedures in the database. Additionally, developers, system administrators, and database administrators can take further steps to minimize attacks or the impact of successful attacks by keeping all web applications up to date with latest security patches, utilizing least privileges, do not use shared database accounts between applications, validate supplier input for expected data types and configure proper error reporting and handling.

## Ethical and Legal Implications
Since information systems have had a huge impact on businesses. It was important to develop Ethics and Legal guidelines to be followed by the information systems industry and individuals.

### Code of Ethics
The code of ethics basically is a document that outlines a set of accepatable behaviors for a professional group or social group. A good example of this is the ACM (Association for Computing Machinery) that created a code for computing discipline. The ACM Code of Ethics and Professional Conduct is a good example of code of ethics that was created to establish ethical professional conduct for every member of the ACM.

### Intellectual Property
Intellectual property is defined as a property (idea, invention or process) that derives from work of the mind or intellect. And basically the svg log created is considered an intellectual property. The role of a trademark in defining intellectual property is it is a word, phrase, logo, shape or sound that identifies a source of goods or services, such as the Nike “Swoosh” and my svg logo. In addition it might be important to copyright the svg image created because the copyright law grants copyright protection for seventy years after the author’s death or ninety-five years from the date of creation for a work created for hire.

### Information Collection
In the US the government has strict guidelines on how much information can be collected on its citizens. Certain classes of information have been restricted by laws over time and the advent of digital tools has made these restrictions more important.COPPA, FERPA, and HIPPA restrict the collection of information on the internet. COPPA is the Children’s Online Privacy Act that requires websites that are collecting data on children under age thirteen to make good faith effort to determine the age of those accessing their websites and if child is under thirteen years old it requires parental consent obtained. FERPA is the Family Education Rights Privacy Act is a law that protects the students education records, this law specifies that parents have a right to their child’s educational information until the child reaches either the age of eighteen or begins attending school beyond the high school level and at that point, control of the information is given to the child. HIPPA the Health Insurance Portability Accountability Act is the law the specifically singles out records related to health care as a special class of personally identifiable information. 

## Conclusion
In conclusion this section was very interesting it described various database models and allowed the opportunity to practice querying a database with SQL. In addition this section discussed key ethical and legal implications of information systems.
