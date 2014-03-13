# SENG3150 Project 1 - Problem Based Learning Reports.

To support the development of the FlightPub website, each team member should 
choose one research topic from the following list, research it and write a report.
Research topic should be different for members of the same team.

### Topic 1: “Apache Maven”.
Describe what is Maven, main features of Maven, how Maven can assist in project
management and the differences between Maven and Ant. Must include a demo of the
software in the final presentation.

### Topic 2: “Compare Struts 2 and Restful architecture”
Describe what the Restful architecture is and compare the differences between the
two frameworks. Justify your choice of the architecture for the project.

### Topic 3: "Jetty and Tomcat."
Jetty and Tomcat are often cast as direct competitors, you should compare the
technical differences of these two servelt containers.

### Topic 4: "GIT vs SVN."
Provide a technical comparison between these two popular source-code repository
packages. Describe which package is suited to which type of project, taking into
account the size of the team and amount of concurrent development tasks.

### Topic 5: "JIRA vs Bitbucket"
Explain what each of these software is and benefit it provides a team of 
developers. Describe how a common workflow can work in these two softwares that
cover development, code review, testing and documentation. Compare them in terms 
of benefits and drawbacks to the project.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - -

##### LaTeX Compilation Notes
Use BibTex for compiling the bibliography, Texmaker | Laxtexian should work it 
out.

######eg. On Windows:
Configure TexMaker - QuickBuild Settings:

`pdflatex -synctex=1 -interaction=nonstopmode %.tex|bibtex %|pdflatex -synctex=1 -interaction=nonstopmode %.tex|pdflatex -synctex=1 -interaction=nonstopmode %.tex|"C:/Program Files/Adobe/Reader 11.0/Reader/AcroRd32.exe" %.pdf`
