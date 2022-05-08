# Summary of the Andorville™ Software Projects

Andorville™ applications, or software cells, are small single-purpose programs that are easy to code and modify. They can be used in stand-alone mode or linked together to form larger "multi-cellular" applications.

The cells are connected and coordinated through the Andorville™ Network. XML based "H7" code is used to control each cell and communicate between cells.

Each cell is linked to a project that contains information and processes related to the cell's function. The Project Network software manages and coordinates a collection of projects that store the data used by a multi-cellular application.

The problem domain of an application can be expanded by adding new software cells and related projects. The multi-cellular architecture limits the system complexity as the application is expanded. These systems are easy to update and highly scalable.

The open source software versions released here are licensed under the Apache License, Version 2.0.

***Network***
The Andorville™ Network uses the Microsoft® Windows® Communication Foundation (WCF) to allow Andorville™ applications to exchange information and interact to perform higher level functions. Information is exchanged using XML based XMessages.

***Project Network***
The Project Network application is used to create a hierarchy of projects to build a data model. The activity of the project host applications is coordinated to perform processing and analysis of the data model.

***Utilities Library***
The Utilities Class Library contains a set of common classes used by Andorville™ applications. It contains classes to manage projects, compress data, and run the XMessage instructions used to communicate between applications.

***Application Template***
The Application Template is a core software cell containing all the communication and  processing code required to connect and operate within an Andorville™ Network. A new software cell can be created easily using the template generated from this software.

***Coordinates***
The Coordinates application is used to convert between different geodetic and projected coordinates. It uses the EPSG Geodetic Parameter Dataset. The software uses the Coordinates Class Library. (Note: An updated is planned for compatibility with the latest EPSG parameter dataset.)

***Import***
The Import application is used to import data from text files into a database.

***Database Tools***
The Database Tools application is used to create, edit and save a database design and create new databases and tables.

***Chart***
The Chart application displays charts from data stored in database tables.

***Shares***
The Shares application is used to analyse share market data. Separate Access databases are used to store share prices, historical financials and calculated data. The software is being developed to test the performance of different share selection methods.

***Document Library***
The Document Library application creates, stores and edits documents in different formats including text, rtf, xml and html.

***Information Library***
The Information Library application stores a collection of related information as nodes in a tree structure. The software allows multiple versions and updates of each information node. (Note: An update is required for coompatibility with the latest Andorville™ system formats.)

***Well Deviation***
The Well Deviation application calculates the deviation of an oil well from deviation log measurements. The software uses the Coordinates application to calculate the projected coordinates of the well location from the geodetic coordinates. The well path is plotted in plan and vertical section views.

***Regression***
The Regression application provides linear and non-linear regression services to applications connected to the Andorville™ Network.

***Monte Carlo***
The Monte Carlo application is used to design, run and analyse Monte Carlo simulations.

***"H7" Code***
"H7" code consists of an information sequence (sequence of data-location pairs) used to control an Andorville™ application. This code is converted to XML format for Network transmission and for file storage. "H7+" code contains instructions for loops, branches and subroutines and is used to code processing sequences.

***Other Projects in Development:***

The "M7" alternative mathematics system is based on "H7+" but with mathematical instructions added. This system uses only whole numbers and processes to construct mathematical models. Non-integer constants like pi and e are represented by the corresponding processes instead of decimal numbers. "M7" demonstrates the advantages of a simplified mathematical system based on the philosophy of Leopold Kronecker.

"S7" is a general purpose multi-dimensional signal processing system. This is a re-write of an existing system. The new version will be compatible with the Andorville™ Network.

"Q7" is a quantum mechanics modelling system. This system is designed to test a multi-dimensional frequency domain interpretation of quantum mechanics. In this interpretation, the energy of a particle, or a group of particles, evolves in the multi-dimensional frequency domain. The energy only appears as a particle, localized in the apparent space domain, at the instant of interaction with the energy of another particle. This interaction is also called an observation. This is analogous to an inverse Fourier transformation from the frequency (or wavenumber) domain to the space domain. Between interactions, the energy continues to evolve in the frequency domain, unobserved.

"ADVL Hardware" provides a general purpose interface between a hardware device and the Andorville™ Network.

"ADVL Connect" provides a connection between Andorville™ Networks on different computers across the Internet.

7 March 2021 
(Edited 8 May 2022)

Copyright © 2021 Robert Cowley