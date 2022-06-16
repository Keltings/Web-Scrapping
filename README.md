## Web-Scrapping
A computer software technique of extracting information from websites in an automated fashion 
The focus is on the transformation of unstructured data or HTML format on the web into structured data/ database/spreadsheet
It can e done in various ways eg; google docs, python, PHP or java

We will use python for extracting information from the web since it is easy to use with its rich ecosystem 

### Goals
Importance of web scraping
Steps involved in the web scraping process
Basic terminologies eg parse, object and tree associated with BeautifulSoup
Operations: searching, modifying and navigating the tree to yied the required result


#### Use cases
You might want to launch some promo to compare market price of certain product for online sales; to build data products and services using large industry websites; to know the upcoming movies for a week; to complete the assignment given to you by a teacher; to learn newtechnologies in the market; to fulfill your daily activities eg shopping; or to interact with the internet to find reviews and to predict or interpret results from the existing data. 
###### You can perform all these activities in the easiest and fastest way thanks to python's web scrapping concept due to its rich ecosystem


### Web Scraping Process - Basic Preparation
Two basic things to consider before setting up the web scraping process.
    - Understand the target data on the internet
    - Finalize the list of websites that provides you with the desired data
Once the two are solved, you need to design the web scraping process
 - 1. A web request is sent to the targeted website to collect the required data.
 - 2. The information is retrieved from the targeted website in HTML or XML format from web
 - 3.The retrieved information is parsed to the several parsers based on the data format.Parsing is a technique to read data and extract information from the available document
 - 4. The parsed data is stored in the desired format. You can follow the same process to scarp another targeted web.
 

### Web Scraping Software vs. Web browser
The software interacts with the website in the same way as your web browser. However, instead of displaying the data served by the website on screen, it saves the required data fromthe web page to a local file or db
Web scraper is used to extract the information from the web in a routine, an automated manner for the target segment

### Web Scraping Considerations
It is important to read and understand the legal informations and terms and conditions mentioned in the website
There can be several categories:
Legal Constrains; Notice; Copyright; Trademark Material; or Patented Information which cannot be used without there permission

### Web Scraping Tool - BeautifulSoup
An easy, intuitive and robust Python library designed for web scraping:
- Efficient tool for dissecting documents and extracting information from web pages
- Powerful sets of built-in methods for navigating, searching, modifying a parse tree
- Possess parser that suppots both html and xml documents
- Converts all incoming documents to Unicode automatically
- Converts all outgoing documents to UTF-8 automatically(to match the global standards)


#### Common Data/ Page Formats on the Web
     - HTML; one of the oldest,easiest and most popular methods to upload information on the web
     - HTML 5; a new HTML standard which gained popularity with mobile devices
     - XML; popular way to upload your information on the web
     - CSS; mainly used for consisntent presentation of data using cascadedstyle sheets
     - Application Profram Interface/APIs; has now become a common practice to extract information from the website which provide structured information
     - PDF; widely use to upload information and reports
     - Javascrip Object Notation/JSON; a lightweight popular format used for information exchange on the web


#### Parser - How it helps Data Scientists in the webs craping process;
A basic tool to interpret or render information from a web document
- It receives input as program instructions, interactive commands and markup tags
- Outputs the web docuents as objects, methods and their attributes
This enables you to extract information in a meaningful way
It is also used to validate the input information before processing it

###### importance of parsing as a webscraping process is that; the extracted file can be understood and stored in the desired format only if parsed successfully. Failure to do that will lead to failure of the entire process

#### Various Parser suppoted by BautifulSoup
    - html.parser--python based, fast and linient.
    - lxml html--not build on python but depends on C.However, it is fast and linient in nature
    - lxml xml--the only xml parser available and also depends on C
    - html5lib--another python-based parser;however, it is slow and able to create valid HTML5


###### Importance of Objects
Web document gets transformed into a complex tree of objects once parsed
a tree being defined as a collection of simple and complex objects
Objects are used to extract the required information from tree strucures by seraching or navigating through the parts of the document
There exists a realtonship between the objects, which enables to extract the information faster and in an efficient way


##### Types of Objects
BeautifulSoup transforms a complex HTML document into a complex tree of Python objects. 
1. Tag; an XML/HTML tag in the document. Tags have a lot of attributes and methods

2. Navigable String; a string or set of characters that corresponds to the text present within a tag

3. BeautifulSoup; represens the entire web document and supports navigating and searching the document tree

4. Comment; represents the comment or information section of the document. a speial type of navigable string
     - 
