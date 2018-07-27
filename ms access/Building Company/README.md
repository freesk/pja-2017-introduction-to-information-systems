CONTEXT
The database and its interface have been created to cover needs of a particular building company.

To work with the given database you need a copy of MS Access 2016.
The instructions on how to install MS Access you can find on the official page
of the product.

NEEDS
1. Creating invoices for a certain client for the given period of time
2. Tracking progress of a particular order and related tasks
3. Tracking workload of a particular employee
4. Printing reports about orders and income

The key elements of the navigation through the app are lists.
You are supposed to click on items in those lists and then click on buttons which
are labeled according to the operations they run.
For example https://screencast.com/t/NPLSF1jdNuq.

The app is full of code written in VBA 7.1 thus before any edits to the source it
is highly recommended to get basics of the language on the official
page https://msdn.microsoft.com/en-us/vba/vba-language-reference.
The code is commented well enough but still, it can be quite confusing, therefore,
unless your purpose is a small update, contact the developer.
Code snippets can be accessed by clicking on a specific icon which is at the top
of the navigation bar of MS Access https://screencast.com/t/5K1Ee1UW9j and
selecting a corresponding form https://screencast.com/t/nmio3sOuE9u.

You can find the schema of the database relationship in the root folder of the project.

If you have any issues with this software or you are willing to contribute, please,
feel free to contact the author. The contact email can be found right at the
top of the text file you are reading.

HERE COMES DESCRIPTION OF EACH FORM AND REPORT (where F stands for form and R for report)

INDEX(F)
- navigation: https://screencast.com/t/4CrYyfQtaAl
- functionality: stands for home page
- data: no data

ORDERS (F)
- navigation: https://screencast.com/t/IBz0dWxLwK1E
- functionality: shows all orders and can navigate a user through them
- data: user input, queries, tables

NEW ORDER (F)
- navigation: https://screencast.com/t/OeqJPdn9
- functionality: creates a new order and holds buttons that redirect to new property/customer pages
- data: user input, queries, tables, lists

NEW CUSTOMER (F)
- navigation: https://screencast.com/t/qWnqCOc0
- functionality: creates a new customer record
- data: queries

EMPLOYEES (F)
- navigation: https://screencast.com/t/vssc7ajTcIu
- functionality: lists all employees, create/update/delete
- data: user input, queries, tables, lists

CUSTOMERS (F)
- navigation: https://screencast.com/t/vssc7ajTcIu
- functionality: lists all customers, create/update
- data: user input, queries, tables, lists

PROPERTIES (F)
- navigation: https://screencast.com/t/JmIf0n03m
- functionality: lists all properties, create/update
- data: user input, queries, tables, lists

ALL_PEOPLE_SUBREPORT (R)
- navigation: none
- functionality: prints a list of all people known
- data: queries

NEW_PROPERTY (F)
- navigation: https://screencast.com/t/hUKlii3o
- functionality: creates a new property
- data: user input

CUSTOMER REPORT (R)
- navigation: none
- functionality: creates a list of orders grouped by clients
- data: queries, tables

NEW EMPLOYEE (F)
- navigation: https://screencast.com/t/qWnqCOc0
- functionality: creates a new employee record
- data: queries

IMPORTANT
Do not rename db.accdb to anything else since this file name has been hardcoded
for an absolute path inside the app.

Author        Dmytro Kurbatov
Email         dmitr.kurbatov@gmail.com
Version       1.0.0
License       MIT
