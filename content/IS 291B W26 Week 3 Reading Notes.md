---
title: IS 291B W26 Week 3 Reading Notes
draft: "false"
tags:
  - class-notes
  - information-studies
date: 2026-01-21
---
These are my reading notes from taking *Histories of the Database* with Prof. Miriam Posner in the Information Studies Department at UCLA.
# Haigh, Thomas. “‘A Veritable Bucket of Facts’: Origins of the Data Base Management System.” ACM SIGMOD Record 35, No. 2 (2006): 33–49. https://doi.org/10.1145/1147376.1147382.
## Summary
In this article the author traces the history of the terms database and DBMS (database management system). Database originally referred to a complex management systems and DBMS were packages for file processing and storage accesss, query, and retrieval. As the popularity of DBMS packages rose the database was redefined as the "informational content" of a DBMS.
## Notes
- A DBMS is a complex software that consists of potentially multiple databases and many different tables with data. The DBMS includes applications to store, retrieve, modify, and query data in the database. All access to the database is mediated by the DBMS
- database originated around 1960
- In practice the DBMS worked in specific use cases but was not the universal technology that integrated all corporate data and revolutionized management, which is how this technology was often marketed. 
- Management Information System
	- Before the term database, the term MIS was developed to describe a new approach to information within a firm. An MIS would be a centralized body of data containing all of the various kinds of information of a firm which when pooled and computerized could be used for forecasting, reporting, modelling, and analysis
- The term database comes form the military a part of the SAGE command and control network
- ![](Pasted%20image%2020260122054238.png)
#### DBMS
- DBMS evolved out of file management systems and report generation
- File management systems were developed to handle input and output tasks for programs, before the development of these systems, programmers would have to write all of the minute instructions for reading and writing data.
- The database task group created a broad conceptual outline for the DBMS with two key conponents
	- A data definition language for defining database structure
	- A separate data manupulation language for acessing data from COBOL
### Questions

### Quotes
# Annotations  
(1/22/2026, 5:56:13 AM)

[Go to annotation](zotero://open-pdf/library/items/9QXSXUIW?page=33&annotation=GFEP8NVR) “File-processing packages were among the very first distributed as supported products, but only in the late 1960s were they first called “data base management systems,” in large part through the actions of the Data Base Task Group of the Committee on Data Systems Languages (CODASYL). As the DBMS concept spread, the data base itself was effectively redefined as the informational content of a packaged DBMS.” ([Haigh, 2006, p. 33](zotero://select/library/items/7NQRRL9N))

[Go to annotation](zotero://open-pdf/library/items/9QXSXUIW?page=33&annotation=LZ43Z8AX) “Because all access to stored data is mediated through the DBMS, a data base can be restructured or moved to a different computer without disrupting the programs written to use it. The DBMS polices access to the stored data, giving access only to tables and records for which a given user has been authorized.” ([Haigh, 2006, p. 33](zotero://select/library/items/7NQRRL9N))

[Go to annotation](zotero://open-pdf/library/items/9QXSXUIW?page=33&annotation=DD9WUDKV) “Today, corporate computer staff would usually conceive of a data base as the content of a data base management system. (In fact, the two concepts are so closely associated that DBMSs such as Oracle are often simply called data bases, even by IT specialists). Historically, though, the two ideas were distinct.” ([Haigh, 2006, p. 33](zotero://select/library/items/7NQRRL9N))

[Go to annotation](zotero://open-pdf/library/items/9QXSXUIW?page=33&annotation=UDHNTSU7) “On a technical level, however, the DBMS evolved from a more humble class of programs known as “file management systems”, created within the unglamorous world of corporate data processing to simplify the creation of programs for routine administration. The data base management system conflated the managerial concept of the data base with the specific technology of the file management system.” ([Haigh, 2006, p. 33](zotero://select/library/items/7NQRRL9N))

[Go to annotation](zotero://open-pdf/library/items/9QXSXUIW?page=33&annotation=NB5UDYNN) “The story of the DBMS therefore provides an interesting example of the process by which particular technologies with very specific qualities and distinctive strengths and weaknesses are promoted instead as universal solutions.” ([Haigh, 2006, p. 33](zotero://select/library/items/7NQRRL9N))

[Go to annotation](zotero://open-pdf/library/items/9QXSXUIW?page=34&annotation=93VFIV8G) “During the 1970s, when data base management systems were first promoted to corporate managers, they were sold as the technological means by which all of a company’s computerized information could be assimilated into a single integrated pool of data.” ([Haigh, 2006, p. 34](zotero://select/library/items/7NQRRL9N))

[Go to annotation](zotero://open-pdf/library/items/9QXSXUIW?page=34&annotation=THBYEIDJ) “It was men such as Stone who first introduced managers to the idea of information as a generalized, abstract entity, separate from the forms, reports, files and memos in which it had previously been embodied. Stone recognized that a flexible and complete MIS could only be constructed if a firm’s entire mass of paperwork could be computerized and integrated “to produce an interrelated body of useful data, or information.” He suggested that “this body of data, a veritable ‘bucket of facts,’ [was] the source into which information seeking ladles of various sizes and shapes are thrust in different locations” [102, page 17].” ([Haigh, 2006, p. 34](zotero://select/library/items/7NQRRL9N))

[Go to annotation](zotero://open-pdf/library/items/9QXSXUIW?page=36&annotation=JPADTGQE) “Within the more technical literature it appeared as a means of pooling information from different files, so that each piece of data would be stored only once. Its great advantage would be "to permit categories of information to be added, deleted, expanded and otherwise revised, without completely redesigning the file or reprogramming the retrieval routines" [99, page 4].” ([Haigh, 2006, p. 36](zotero://select/library/items/7NQRRL9N))

[Go to annotation](zotero://open-pdf/library/items/9QXSXUIW?page=36&annotation=V3Y25JR4) “File management systems were intended to reduce the cost of producing routine administrative programs, and to make the finished programs easier to change and maintain. Report generation systems made it easier to produce printed reports based on particular criteria. These ideas, unlike the data base concept itself, were indigenous to the world of administrative data processing, where they had slowly evolved. Whereas the data base reflected a focus “blue sky” technology, on-line operation, scientific genius and enormous expense, these file management systems were initially oriented toward clerical tasks, were used and appreciated primarily by programmers and data processing supervisors, lacked features for interactive or on-line use, and did not cost much.” ([Haigh, 2006, p. 36](zotero://select/library/items/7NQRRL9N))

[Go to annotation](zotero://open-pdf/library/items/9QXSXUIW?page=37&annotation=JJRMNXBS) “File management systems evolved from the reuse of subroutines written to handle input and output tasks within application programs. Early computer programs included all the instructions necessary to specify the minute details of reading and writing information from tape or disk, and were forced to check regularly whether a particular record had yet been retrieved [69, 178-204].” ([Haigh, 2006, p. 37](zotero://select/library/items/7NQRRL9N))

[Go to annotation](zotero://open-pdf/library/items/9QXSXUIW?page=39&annotation=K7BLJURU) “The purpose of the DBTG was to define the capabilities of these new systems, and to develop new standards for them. Its creation was prompted by the realization within CODASYL that COBOL, while doing a great deal to standardize data storage on tape systems and to separate record definitions from program logic, was entirely inadequate when faced with the challenge of random access, disk based storage [80].” ([Haigh, 2006, p. 39](zotero://select/library/items/7NQRRL9N))

[Go to annotation](zotero://open-pdf/library/items/9QXSXUIW?page=40&annotation=PJAUF3W2) “The work of the DBTG provided both a broad conceptual outline for the data base management system, and detailed draft specifications for two specific parts of the over-all system (a data definition language for defining the data base structure, and a separate data manipulation language for accessing the data from within COBOL). It also outlined a way of giving individual programs access to selective or simplified versions of the full data base.” ([Haigh, 2006, p. 40](zotero://select/library/items/7NQRRL9N))

[Go to annotation](zotero://open-pdf/library/items/9QXSXUIW?page=44&annotation=NFZNBM8T) “Use of early DBMS systems was highly concentrated. According to internal reports prepared by one software firm, as late as 1981 TOTAL, the market leader, had just 4,171 installations while IBM’s IMS won second place with an estimated 1,500 [82]. The first widely used relational DBMS, Oracle, was launched in 1980 and found an early niche in the rapidly growing market for minicomputer systems.” ([Haigh, 2006, p. 44](zotero://select/library/items/7NQRRL9N))

[Go to annotation](zotero://open-pdf/library/items/9QXSXUIW?page=44&annotation=YCVNQFSG) “The data base management system provides an interesting example of the tensions hidden behind phrases such as “information technology.” The progression of the concepts of data base and data base management system over the 1960s and 1970s demonstrate an unmistakable tension between the rather limited and technically focused achievements of actual information systems and the universal, almost utopian claims that information problems can be defined, and therefore solved, for the general case if only the right tools or technologies can be deployed.” ([Haigh, 2006, p. 44](zotero://select/library/items/7NQRRL9N))

# Grafton, William. “IMS: Past, Present, Future.” Datamation, September 1983. https://archive.computerhistory.org/resources/access/text/2022/02/102796683-05-01-acc.pdf
## Summary
- This is an article written by William P. Grafton that describes the history of the IMS system. This system was develoepd in 1968 in Downey, CA as a collaboration between IBM and Rockwell as they worked on the Apollo Project
## Notes
- there were two precursor systems to IMS: Guam (Generalized Update Access Method) and RATS (Remote Access Terminal System). When System/360 arrived they decided to create a new software package that combined the features of the previous and had the following features
	- capabilities for concurrent message processing
	- external definition of file structures
	- protection of sensitive data
	- improved search, retrival, and storage methods
	- multiple device support
	- Improved database recovery
- Was initially called ICS (Information Control System) but the name was changed to IMS for copyright reasons
- Tensions developed between Rockwell who wanted to go to the moon and IBM who wanted to develop a marketable product
- The author describes a QA process similar to how we think about bugs, project management and status meetings now
- Why hierarchical data model
	- Hearchical storage techniques were chose because they conserved disk space, seemed natural for the application of tracking parts and bill of materials and GUAM was based on a hierarchical model
### Values Associated with IMS
- reliable
- integrity
### Factors in the Success of IMS
- IMS works
- S/360 and OS/360 compatibility
- Project management lead to a technically sound and operationally reliable product
- end user involvement
- vendor support
- the implementation of an integrated database system may require rethinking the concept of the corporation/firm and centralizing the role of the database in organizational structure and bsuness operations
### Questions

### Quotes
(1/21/2026, 10:17:41 PM)
[Go to annotation](zotero://open-pdf/library/items/BU26ZHX9?page=3&annotation=3LD5LQ57) “There was no comprehensive testing program 10 exercise the system methodica lly. identi fy problems. and fix them. IMS simpl y would not run reliably and no one was doing nnything about it. The project team had deve loped an elit ist "priesthood" attitude towurd the appli cation development group. who were trying 10 implement three major on-line systems under IMS . The project telml hogged the computer resources , crushed the system repeated ly. ruined apptic:tlion lests. and destroyed databases. Application programmers who were seek ing help were treated wi th disdain .” ([Grafton, p. 3](zotero://select/library/items/RFEWBQBB))

[Go to annotation](zotero://open-pdf/library/items/BU26ZHX9?page=3&annotation=PMVXFXVS) “The joint development relationship with 10M should be terminated. The mutual interests of the two companies had diverged , IBM wanted to develop a marketable product. Roc kwell wanted 10 go to the moon.” ([Grafton, p. 3](zotero://select/library/items/RFEWBQBB))

[Go to annotation](zotero://open-pdf/library/items/BU26ZHX9?page=3&annotation=A8HPTZF4) “I sct out to test the system command by command . modu le by module. transaction by transaction . function by funccion. Uli lity by utility. Every time I found a problem . I gave it a number. I organiz.ed a problem resolUIion committee chat met almost daily to classify the problems. detennine priorities. and ass ign responsibil ilies for solution. IBM was it member of Ihe committee and was gi ven a copy of every prob lem . We kept in close telephone contact with 111M team members in Ce ntury City.” ([Grafton, p. 3](zotero://select/library/items/RFEWBQBB))

[Go to annotation](zotero://open-pdf/library/items/BU26ZHX9?page=4&annotation=DMDWZR7T) “When Rockwell negotiated the termination of the Joint IMS Development Project with tBM. Rockwell relinquished its ri ghts to the product in rclUrn fo r: 1. an acknow ledg~ meant on the inside front cover of the firs t issue of the manuals. and 2. a waiver of Ii· ce nse fees, and 10 free setSof manua ls for the fi rst three releases of IMS. Those of us on the Rockwell team considered that IBM had struck the greatest barga in since the Dutch bought Ma nhattan fro m the Ind ians.” ([Grafton, p. 4](zotero://select/library/items/RFEWBQBB))

[Go to annotation](zotero://open-pdf/library/items/BU26ZHX9?page=6&annotation=ET8UJQB4) “Managemcnt's perception is that the bill is too high for whal you get. There is a high fro nl-end cost to be eaten. and the benefits arc seen as largely intangible . We cvangc lists o f the database concept mUSI do a better job o f se lling ou r product as a real (inancia l be nc fit if we cxpect to changc thi s. Managers ure also pUI o rfby Ihe long implementution lead time for Ihc classic approach. They would love to have detailed information at their fingert ips . The trouble is tha! they want it. next week. nol in fi ve years .” ([Grafton, p. 6](zotero://select/library/items/RFEWBQBB))

[Go to annotation](zotero://open-pdf/library/items/BU26ZHX9?page=6&annotation=8KYU5G2Q) “The dal abase approach is also tough to se ll politica ll y Clnd organizati onally . Plans for develop ing the inlegrated datab:tse environme nt require ex tensive cross-organizational cooperation and commitmcnl of resources. Typica lly. Ihe database projcci man ~ ager is new . at SlUff leve l, has a strange vocabulary. and sou nds as ifhc wants to change overnight everyth ing that the tnlditionnl li ne organi zations have been doing comfonubly for years . Another problem Siems from the technology itself. The available informat ion modeling mcthodologies and database des ign lools are inadeq uate, inco mplete. ovcrlapping, and labor intensi ve . The data dictiona ry does not suppon the methodology.” ([Grafton, p. 6](zotero://select/library/items/RFEWBQBB))

[Go to annotation](zotero://open-pdf/library/items/BU26ZHX9?page=6&annotation=DHALH46U) “In this concept , the firm is viewcd nOi as a mono lith. but rather as a SCIof dccoupl ed fun ctions th at work together: manufucturi ng. engineering. finan ~ cial, personnel. markeling . etc . The theory is that each of these fun ct ions is a mini -business. and that the informulion rel ationships between them tend 10 be relatively few. slrnigh lforward. predictab le. and co ntrollable when compared wi th re lationships that exist wit hin a functi on.” ([Grafton, p. 6](zotero://select/library/items/RFEWBQBB))

# Driscoll, Kevin. “From Punched Cards to ‘Big Data’: A Social History of Database Populism.” Communication 1, No. 1 (2012): 1–33. https://doi.org/10.7275/R5B8562P.
## Notes
### Summary
## Questions

### Quotes

# Olson, H.A. “Exclusivity, Teleology and Hierarchy: Our Aristotelean Legacy.” Knowledge Organization 29, No. 2 (1999): 65–73. https://www.imrpress.com/journal/KO/26/2/10.5771/0943-7444-1999-2-65/pdf.
## Summary
- In this article Olsen uses Foucaultian Discourse analysis to analyze Parminides fragments, Plato's the Sophist, and Aristotles Prior Analytics, Parts of Animals, and Generation of Animals to identify three underlying presumptions of classical logic. Thes presumptions are the notion of mutually exclusive categories, teleology, and hierarchy. Olsen argues that these ideas are linked to classificatory thought in the western tradition and reveals how classificaiton is a cultural construction that may be incompatible with other cultures or marginalized cultures in the west.
## Notes
- Olsen traces the presumptions underlying classification back to the development of logic in 4th century Greece BCE
- 
#### Methodology
- Uses Foucaultian Discourse Analysis examining texts to identity the discourses that underly classifacatory thought and practice in western culture
- Discourse analysis is a poststructuralist methodology to identify and question the underlying presumptions that animate discourse
- Critique builds on the work of feminist philosopher Andre Nye and empiricist philosopher John Dupre
#### Parmenides
- Parmenides was a philosopher of Elea active during the 5th century BCE and his surviving work is fragemnts where he discusses ontology in a heroic poem
- In the poem he divides between what is and what is not which Olsen argues introduces the idea of mutually exclusive categories and the law of non-contradiction
- there is a contradiction between being and non-being which is a key presumption of classification
- Nye in her feminist critique of logic discusses gender roles and how the law of non-contradiction polices the boundaries of gender distinction and makes these distinctions become claims about a fundamental essentialist essence

#### Plato
- Plato critiques Parmenides monism and his concept of the wholeness of being but still accepted the idea of mutually exclusive 
- Plato affirms that we must accept non-being because this is implied by non-contradiction, this is the dualism of Plato
- “What is interesting is that Plato (well ahead of Jacques Derrida) shows us how to deconstruct his own concept of dualism when he suggests that "what is not in some sense is and in turn again that what is in some sense is not." Ironi cally, he must contradict the law of non-contradiction before he can claim "what is not" exists and set the stage for using the law of non-contradiction in his dialectic.” (Olson, p. 68) Here it seems like we see the seeds of the dialectice where the dualism reveals it's own contradictios 
- Teleology is linear progress toward some goal or end. The telos is the organizing principle. Olsen argues Plato introduces the teleology alonside relying on mutual exclusivity

#### Aristotle

### Questions

### Quotes


# Berman, Uri. *Birth of IMS*. R0367.2017. Computer History Museum, 2007. [https://archive.computerhistory.org/resources/access/text/2016/08/500001032-05-01-acc.pdf](https://archive.computerhistory.org/resources/access/text/2016/08/500001032-05-01-acc.pdf).
## Summary
In this article Berman describes how he developed software for Rockwells space division and migrated from IBM 7010 to IBM System/360. He and his colleagues developed a standard way to state data definitions and migrated to IBM type 2 standards. This resulting package was called IMS/360 and included DL/I
# Notes
## Precursor to IMS
- In 1963 he was assigned by IBM to work at Rockwell's space division in Downey, CA while they were working on the Apollo capsule. They needed a way to keep track of parts for the capsule and created an application to keep a current parts list on a big disk
- Each engineering department needed to be able to query this list and make sure they had the latest engineering drawing for parts. This created a need to control access, manage recovery
- A key innovation for the software that they created was separating the disk access methods and the application programs that access and used the data
- First software was called DATE (Disk applications in a teleprocessing environment
## Development of IMS
- Needed to port the software to System/360 and building the database capabilities as software meant that it could be built once and implemented many times
- What the team did
	- Standardized the way to state data definitions
	- sophisticated disk error recovery
- Resulting package was called IMS/360 was developed by Berman in a team of about 20 programmers. Programmers were from IBM, Rockwell, and Caterpillar Tracker as a joint project
- The technical transformation of the database resulted in an organizational transformation. A database manager was appointed and was the main person people talked to when they needed to build something that used data
- Berman got a $100,000 check and outstanding contribution award for his work
# Questions

# Quotes
[Go to annotation](zotero://open-pdf/library/items/XQ6CG9U6?page=3&annotation=M6RR8KED) “With a big file and many programs requiring access to it, control gets complicated. I thought disk access methods and recovery planning should be separated from the application programs that accessed that data. To that end, I devised some general-purpose software that would support disk operations and separated the applications programmer from the details.” ([Berman, p. 3](zotero://select/library/items/VDNAHUQW))

[Go to annotation](zotero://open-pdf/library/items/XQ6CG9U6?page=3&annotation=IAVZ7QFR) “DATE separated the file and its definitions from the processing programs that used that file. That improved the integrity of the data and simplified the programming of new or changed work. With this concept, the field, record, and file definitions were separate from the application programs that entered data, inquired about status, or selected data to fulfill requests from engineering management.” ([Berman, p. 3](zotero://select/library/items/VDNAHUQW))

[Go to annotation](zotero://open-pdf/library/items/XQ6CG9U6?page=3&annotation=8AA2MNMG) “By building database capabilities in the form of software, one team could build the database software once and all the rest of the application programmers would benefit from it.” ([Berman, p. 3](zotero://select/library/items/VDNAHUQW))

[Go to annotation](zotero://open-pdf/library/items/XQ6CG9U6?page=4&annotation=HF2MHCVG) “Since programmers using the data were no longer responsible for its integrity and organization, Brown created a new box on the organization chart to carry these responsibilities. The person appointed to manage all those files was Dan Gilbert. He was the first to carry the title of Data Base Manager. When a programmer set out to create a new program that depended on corporate data, he no longer talked to his friends, he went to see Dan.” ([Berman, p. 4](zotero://select/library/items/VDNAHUQW))

# “Chapter 3: Making Data Programmable.” In *Archiving Machines: From Punch Cards to Platforms*, by Amelia Acker. The Information Society Series. MIT Press, 2025. [https://direct.mit.edu/books/oa-monograph/6055/Archiving-MachinesFrom-Punch-Cards-to-Platforms](https://direct.mit.edu/books/oa-monograph/6055/Archiving-MachinesFrom-Punch-Cards-to-Platforms).
## Notes
### Summary
## Questions

## Quotes

