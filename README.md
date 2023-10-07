 introduction: Our intelligent Traffic Expert Solution for road traffic control System offers the ability to acquire real-time traffic information, .Traffic Expert enables operators to perform real-time data analysis on the information gathered. Traffic management measures are aimed at improving the safety and flow of traffic utilizing traffic capacity more effectively.Purpose
Smart Traffic Management is mainly improvised for looking after the Set off data of a region to manage the Traffic along that area and implement various useful technologies which are been required by various persons like vehicle owners, pedestrians, police officers etc….Mainly the purpose of Smart traffic management system is to give the details which can be used and they can be implemented in their daily life. The problems which have been occurred at their presence can be solved by this Smart Traffic.scope
Smart Traffic is a Video Analytics Module and provides Traffic Incident Detection, and real time Traffic Flow Metrics & statistical analysis. Smart Traffic Monitoring can integrate with third pDefinitions, Acronyms, and Abbreviations:arty traffic management and smart roadway systems and hosts a feature rich product scope itself. The system can be used for incident detection or for statistical metrics of a roadway. HTML (Hyper Text Markup Language): It is used to create static web pages.
 JSP (Java Server Pages): It is used to create dynamic web content.
 J2EE (Java 2 Enterprise Edition): It is a programming platform, belonging tothe Java platform, which is used for developing and running distributed java
Applications.
 DB2 (IBM Database 2): It is a database management system that provides a
 Flexible and efficient database platform to raise a strong "on demand" business 
 HTTP (Hyper Text Transfer Protocol): It is a transaction oriented client/ server Protocol between a web browser and a web server.
 Database: Collection of information in a structured form.
 Login ID: A user identification number to enter the system.
 Password: A word that enables one to gain admission into the system.
 XML (Extensible Markup Language): It is a markup language that wasdesigned to transport and store data.
 Ajax (Asynchronous Java Script and XML): It is a technique used in java script to create dynamic web pages.
 ORACLE: It is software used in to insert Tables.
Technologies to be used:JAVA: Application architecture.
 DB2: Database.
 Ajax: Asynchronous Java Script and XML.
 XML: Extension Markup Language.
 WASCE: (Web Sphere Application Server Community Edition) Web Server.
 J2EE: (Servlet, JSP, JAXP, Java Beans) Application architecture.TSM (Admin): Tivoli storage Manager Admin.
 Soda: For developing use case reports.
 Local Language Translator: For local language developing
 ORACLE For inserting Tables.
Overall Description:System EnvironmentThe Smart Traffic management System has three active actors one cooperating system. Mainly pedestrians who uses the dataset provide by the admin and give the complaints important suggestions which are under taken by the traffic police and admins.where as the vehicle owners too generate the same idea of the pedestrians .Traffic police maintains the information which are provided by the users(pedestrains,vehicle owners)and make into implementation.These are all settled by the admin of STM.Software Interface:
 Client 
: Web Browser, Windows series
 Web Server
: WASCE, Windows series
 Data Base Server : DB2,Windows series
 Development End : J2EE, Java, Oracle, XML, DB2, OSCommunication Interface:
 Client on Internet will be using HTTP/HTTPS protocol.
 Firewall security is required for securing the server.
 TCP/IP protocol is basic need for client side.User Characteristics:
 Every user should be comfortable of working with computer and net browsing.
 Every user has to register with the STM.
 Every user should have their own login and password.
 Every users can issue the complaints.
 Every user must have basic knowledge of English too.Constraints:
 GUI is only in English.
 This system is working for single server.
 Limited to HTTP/HTTPS.
 User should have basic knowledge of computer.Architecture Design:In Model 2 architecture, a controller handles the user request instead of another JSP.The controller is implemented as a Servlet. The following steps are executed when the user submits the request.
 The Controller Servlet handles the user’s request. (This means the hyperlink in the JSP should point to the controller servlet).
 The Controller Servlet then instantiates appropriate JavaBeans based on the request parameters (and optionally also based on session attributes).
 The Controller Servlet then by itself or through a controller helper communicates with the middle tier or directly to the database to fetch the required data.The Controller sets the resultant JavaBeans (either same or a new one) in one of the following contexts – request, session or application.
 The controller then dispatches the request to the next view based on the request URL.
The View uses the resultant JavaBeans from Step 4 to display data. Note that there is no presentation logic in the JSP. The sole function of the JSP in Model
Architecture is to display the data from the JavaBeans set in the request, session or application scopes.
