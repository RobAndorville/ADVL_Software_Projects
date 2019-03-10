# Summary of the Andorville™ Software Projects
Andorville™ applications are small single-purpose programs that are easy to code and modify. They can be connected and coordinated through the Application Network. "H7" code is used to control each application and communicate between applications. This code stores the machine intelligence of a multi-project application.

***Message Service***
The Message Service uses the Microsoft® Windows® Communication Foundation (WCF) for Andorville™ applications to exchange information and interact to perform higher level functions.

***Application Network***
The Application Network Software is used to create a hierarchy of projects to build a data model. The activity of the project host applications is coordinated to perform processing and analysis on the data model.

***Utilities Library***
The Utilties Class Library contains a set of common classes used by Andorville™ applications. It contains classes to manage projects, compress data, and run XMessage instructions used to communicate between applications.

***Application Template***
The Application Template is a simple example application containing all the software features required for an Andorville™ application.

***Coordinates***
The Coordinates application is used to convert between different geodetic and projected coordinates. It uses the EPSG Geodetic Parameter Dataset. The software uses the Coordinates Class Library.

***Import***
The Import application is used to import data from a text file into a database.

***Database Tools***
The Database Tools application is used to create, edit and save a database design and create new databases and tables.

***Chart***
The Chart application displays charts from data stored in database tables.

***Shares***
The Shares application is used to analyse share market data. Separate Access databases are used to store share prices, historical financials and calculated data. The software is being developed to test the performance of different share selection methods.

***Information Library***
The Information Library application stores a collection of related information as nodes in a tree structure. The software allows multiple versions and updates of each information node.

***Well Deviation***
The Well Deviation application calculates the deviation of an oil well from deviation log measurements. The software uses the Coordinates application to calculate the projected coordinates of the well location from the geodetic coordinates. The well path is plotted in plan and vertical section views.

***"H7" Code***
"H7" code consists of a sequence of information/destination pairs that are used to control an Andorville™ application. This code is converted to XML format for file storage.
