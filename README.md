Human Resource Module
========
This project is part of the program called Google Summer of Code organized by Google.

1. Problem Statement - OpenMRS (OpenMedicalRecordSystem) is an open source EMR (Electronic Medical Record system) platform. As a open source developer I care about OpenMRS’ human resource management and needed to build an OpenMRS module that handles this. 

2. The Solution is to build a module that can be installed on the web platform. The module building is focused on building the front-end, the back-end and database design and creation. The front-end of OpenMRS is made really simple and is not at all jazzy. It mostly is plain HTML pages with very less CSS. As a Google Summer of Code student I was assigned two mentors who helped me a lot to understand and implement the database schemas and populate them with test data.

3. My choice to work with OpenMRS was made because it uses Spring and Hibernate framework which is best MVC framework I have known. It was a great learning experience for me because at the time I hadn’t formally learnt any of these technologies and this was one my first exposures to Full-Stack Development


4.  The code I am proud of is where I had to get all the standard ISCO codes for Job Titles and make a nested tree like structure to choose from on the UI. We can see the JSTL code implemented in a very Java way, thats because I had originally written the program in Java and translated the logic to JSTL. The code basically builds a nested list which then is transformed to look like a tree using a library.

https://github.com/openmrs/openmrs-module-hr/blob/master/omod/src/main/webapp/admin/jobTitle.jsp

5. My Resume can be found here - 
https://drive.google.com/file/d/0ByJUKf3MpJ6lTHM5ODdoRU1XS2s/view

6. OpenMRS has limited support for other modules in their public demo (http://demo.openmrs.org )  servers. To try the module out, one has to download the standalone application under the compatibility specified and run the jar to open the web page to try. One can add the HR Module from the Manage Modules link in the Admin section. 

The code for the module can be found here -
https://github.com/openmrs/openmrs-module-hr/

The module was worked on in later years by another student but we can still find the old version of the module which only I worked on packaged, available as an .omod file which is what gets installed on the server  - 
https://modules.openmrs.org/#/show/hr/ 

Project Page - 
https://wiki.openmrs.org/display/projects/Human+Resources+Module

Video Demo link and Documentation - 
https://wiki.openmrs.org/display/projects/Human+Resource+Module+Documentation





