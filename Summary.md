# Summary of the Andorville™ Software Projects
Andorville™ applications are small single-purpose programs that are easy to code and modify. They can be connected and coordinated through the Application Network. "H7" code is used to control each application and communicate between applications. This code stores the machine intelligence of a multi-project application.

***Network***
The Andorville™ Network (previously called the Message Service) uses the Microsoft® Windows® Communication Foundation (WCF) to allow Andorville™ applications to exchange information and interact to perform higher level functions. (Update in progress.)

***Project Network***
The Project Network Software (previously called the Application Network) is used to create a hierarchy of projects to build a data model. The activity of the project host applications is coordinated to perform processing and analysis of the data model. (Update in progress.)

***Utilities Library***
The Utilities Class Library contains a set of common classes used by Andorville™ applications. It contains classes to manage projects, compress data, and run XMessage instructions used to communicate between applications.

***Application Template***
The Application Template is a simple example application containing all the software features required for an Andorville™ application.

***Coordinates***
The Coordinates application is used to convert between different geodetic and projected coordinates. It uses the EPSG Geodetic Parameter Dataset. The software uses the Coordinates Class Library.

***Import***
The Import application is used to import data from text files into a database.

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

***Regression***
The Regression application provides linear and non-linear regression services to applications connected to the Andorville™ Network. (Update in progress.)

***"H7" Code***
"H7" code consists of a sequence of information/destination pairs that are used to control an Andorville™ application. This code is converted to XML format for file storage. "H7+" code contains instructions for loops, branches and subroutines and is used to store processing sequences.

***Other Projects in Development:***

The "M7" alternative mathematics system is based in "H7+" but with mathematical instructions added. This system uses only whole numbers and processes to construct mathematical models. Non-integer constants like pi and e are represented by the corresponding processes not decimal numbers. "M7" demonstrates the advantages of a mathematical system based on the philosophy of Leopold Kronecker.

"S7" is a general purpose multi-dimensional signal processing system. This is a re-write of an existing system. The new version will be compatible with the Andorville™ Network.

The "Q7" system is a demonstration of a suggested "3D Wavenumber - Time" (3DKT) interpretation of quantum mechanics. Multi-dimensional Fourier transforms share some of the peculiar behaviours observed in quantum mechanics experiments.

Key points of the 3DKT interpretation:
Quantum mechanics occurs in the 3D Wavenumber - Time domain.
Elementary particles, photons etc. are the space domain manifestation of sets of 3D waveforms.
Space is an illusion, representing the differences in phase between waveforms in the wavenumber domain.
Elementary particles, photons etc. are only manifested in the apparent space domain at the moment of interaction.
Between interactions, 3D waveforms evolve in the wavenumber domain. This produces the perceived quantum mechanics weirdness in the apparent space domain.

These ideas are hard to comprehend without a background in multi-dimensional filter theory. The Q7 software project will aim to demonstrate quantum mechanics processes in the 3DKT domain.

19 September 2019

Copyright © Robert Cowley 2019