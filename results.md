# Results of the ACDHchHackathon2020

## Martina Trognitz & Likas Gehrig: [CORIANDER COurse RegIstry stAtistics aNd aDditional matERial - Adding further functionalities to the DH Cource Registry by CLARIN and DARIAH](https://github.com/bellerophons-pegasus/CORIANDER) 

**Ruling:** We award this submission first place in the ACDH hackathon 2020. Congratulations!

The following detailed review was authored by John McCrae and Gerlinde Schneider.

### Summary
The project provides visual access to the course registry of DARIAH and tools for visualizing it, by year, location and providing data visualization on the topics listed among the courses in the registry.
With CORIANDER, its creators provide a web application that allows an exploratory view to data pulled from the DH course registry’s API. Basically, there are two access points. First, an interactive bar chart that displays keywords from the Course Registry together with countries and dates. Second, a chord chart that shows co-occurrence of keywords in the courses. The data taken from the course registry is enriched by additional data taken from Zotero and Wikidata. The application is purely browser based, using HTML, CSS and JavaScript as well as common JavaScript libraries for visualization. Python3 is used for data processing.
In summary, the contribution is very good. It is evident that a lot of effort and thoughts were put into the creation of the application, into the programming itself but also into documentation and the design of the user interface. Everything fits well together. It's nice to see that in addition to creativity, practicability was also a driving factor in the creation process.

### Creativity
The interface is very clean and well-designed and the methods of visualization show a lot of creativity in terms of the ways to analyze the data. The links to Wikidata and Zotero show interesting results and demonstrate the creativity of this submission.
Looking at the data set from the perspective of the keywords is certainly a creative approach. It provides an alternative way to navigate the course registry, but also visualizes connections in the data and statistics that would otherwise not be visible.
The user interface follows a consistent and really nice design.

### Reproducibility & reusability
The interface is very easy to install as it is essentially provided as a static HTML page and installs very easily. The interface has very long and detailed documentation and so should be easy to reuse. 
The application is very easy to deploy and works without any problems.
The strength of this contribution definitely is its comprehensive documentation. Not only the code itself is very accurately documented but also a detailed user documentation is included in the repository that informs about the motivation for the tool and also provides use cases. The documentation also discusses future potentials and points out bugs and shortcomings. Also, the user interface itself offers a short but useful guide to use the tool. Another plus is that the Python scripts used to preprocess the data are also part of the distribution.
The tools are well-designed and similar tools have been used for other datasets. We could easily see this being adaptable to further applications. The submission is set out as a standalone web application. Because of its practicability, it is certainly usable in the way it is. However, we can also well imagine that both the idea as well as parts of the code could be included into the existing Course Registry in the future. The clear structure and good documentation are certainly helpful.

### Elegance
Both the repository as well as the code itself are well arranged and documented. Attention was paid to a modularized design. The JavaScript code is largely well organized, using a functions-based approach, with just a few inconsistencies. The structure of the Python code can be easily understood. The software is very well-designed and repository seems to be laid out in a clear manner. The tools is very nice and is intuitive in its usage. This is overall a very strong submission.

### Possible improvements
The user interface has some minor problems in its handling, which is definitely acceptable for a prototypical implementation.
A next step might be to transfer the functionalities into a dynamic application and to access the data directly over the API.

## Marta Palandri & Raphael Mitsch: [DH Education Knowledge Map - creating knowledge maps via hypertext](https://github.com/rmitsch/dh-knowledge-map)

**Ruling:** We award this submission ex-aequo second place (together with the submission “Notlef”) in the ACDH hackathon 2020. Congratulations!

The following detailed review was authored by Lenka Bajčetić and Renato Rocha Souza.

### Summary
The team took an interesting approach to the task. It recognizes that using a traditional spatial map would be the obvious approach, but one developed already and not available as an option for the task. They therefore decided to go for a knowledge map. In their considerations, they recognize the relevance of the multi-faceted aspect of the information offered in the directory and try to depict the "great amount of possibility, rather than a set amount of knowledge".
The team decided to use Wikipedia's API to create "intricate webs of knowledge spreading from each bit of information given by the DH Course". The visualization was built on the top of Plotly's Dash - a Python framework for building web applications.
The dashboard is divided into four panels, presenting the courses as a table and a scatterplot, and the wikipedia information in the form of a graph as well as a paragraph from Wiki about the selected node from the graph. The provided solution is simple yet powerful; easily reproducible and surely adds an alternative enriched view to the data, allowing concept based navigation and serendipitous connections to related concepts.

### Creativity
The project has truly offered an enrichment, with the idea to connect to external resources. These are, however, sometimes too generic in relation to the course metadata and can lead to chains of spurious relationships (e.g. "Digital Detectives: Detective Literature Under a Digital Macroscope" - Literature - Apocalyptic Literature). But this is not unexpected, as the team tried to automate the linking process and didn't use a domain specific resource, as Wikipedia. But the authors look at these unexpected links as "starting points for the generation of new webs in all different directions", which is a nice point of view. Given the usual time limits of a Hackathon, some possible features were not implemented, and there is a lot of room for improvements. But this open-endedness is an advantage and adds to the possibilities that were offered by the solution presented.

### Reproducibility & reusability
Both the project's data and code are well documented. In the GitHub repository, there are README files and they have adopted the GPL-3.0, which is a lot permissive, but demand - as all copyleft licenses - that any derivative work must be distributed under the same or equivalent license terms, which guarantees that every spin off will be also open source and publicly available. Apparently, there are no impediments to reproducing the data gathering and enriching, but we must note that given the dynamic characteristics of both the DH Registry and Wikipedia, the results may not be totally the same when the process is repeated in the future.
The authors have chosen mainstream tools which are easily found and integrated. Besides the openness of data and tools used, the team has chosen to use a Docker file to ease the setup of the application environment. There are no technical hindrances to reuse the tool or even to expand the generated graphs with other sources, with a bit of ingenuity. Anyone with a minimum knowledge of Docker and access to the free open source data sources would be able to reuse the complete application. 

### Elegance
Taking the aesthetic point of view, the authors have declared that "having been long fascinated by old-fashion hypertext environments, it came natural for us to steer towards an approach that would allow us to see the precious information given as a great amount of possibility, rather than a set amount of knowledge." So the lack of novelties in the graph interface is not a weakness, but rather a choice on the tried and true power of visualizing relationships through graphs.
In the technical point of view, the solution follows the recommended best practices with the use of open source tools, versioned and documented code, and automated setup. There are no technical shortcomings or apparent difficulties for use.

### Suggestions for improvements
The submission provides an interesting visual representation of the data, and is well executed. However, it could benefit from some design improvements. Perhaps it would be better if the panels were more connected and interactive, for example if the table was updated according to the selected node. 
The knowledge map has potential as a convenient and useful visualization, because it connects courses and institutions to techniques and activities as classified in TADIRAH (e.g. if you are interested in a particular DH technique you can easily see at which institutions you can study it).
The technical solution was well crafted and is well documented, allowing for reproducibility and reuse. This can be used as a starting point for further developments which would truly increase the findability and usefulness of the DH Course Registry.

## Philip Allfrey: [Notlef](https://github.com/philipallfrey/notlef)

**Ruling:** We award this submission ex-aequo second place (together with the submission “DH Education Knowledge Map”) in the ACDH hackathon 2020. Congratulations!

The following detailed review was authored by Lenka Bajčetić and Omar Siam.

### Summary
“... produce a curated set of lists, figures, statistics, and charts which provide an insight into the courses in the registry. This is further enhanced by having one set of data on each page able to act as a filter, so that one can gain the same insight into a subset of the data. “
* The submission is an open source component based web application based on the design of and inspired by http://feltron.com/FAR09.html annual report which is a print product.
* The submission consists of 2 pages:
  * courses: dates and languages (has a documented bug when selecting a different language from the list)
  * places: countries, cities and institutions (filter by county)
* The submission produces a very elegant visual.

### Creativity
The submission captures the aesthetics of the chosen printed template and fills it with the data provided by the course registry. Finding a pleasing way of visualizing statistical data and implementing it as reusable components of a web framework is the creative approach of this project.

### Reproducibility & reusability
* The submission can be easily built and launched using the standard tools for angular development. To date the process only requires (a subset of) the instructions provided.
* The angular app is built according to best practices and conventions of these kinds of applications so it is probably easy to get to the details for everyone familiar with any angular app.
* Code comments are sparse but they only serve as reminder for external observations.
* The submission contains a README.md file that further details the structure of the app and gives instructions on how to use the angular tool to create new components which can be used to extend the available pages/topics.
* angular app, easy to create a skeleton for a new chart component
* easy to reuse as part of other angular apps because of the inherent component based design and separation of data generation and fetching and presentation

### Elegance
* beautiful, simplistic design, visually appealing
* nicely integrated usage instructions and final thoughts / colophon

### Suggestions for further improvements
* there are no meaningful tests (only 3 unit tests, one fails, 1 e2e test, fails) -> this suggests that reproducibility will decline fast in the future
* could have more ways to interact with the data
* could add a new layer of information to the data by for example connecting to other data resources
* it is minimalistic and further visualizations could be added
* although it is a very elegant display of the information at hand it would be an improvement if it conveyed more information
* perhaps there is a practical problem that could be made easier to understand by a visualization derived from this
* fixing bugs would be better than admitting them

## Francesca Giovannetti, Ivan Heibi, Bruno Sartini: [ACDH-2020](https://github.com/br0ast/ACDH-2020)

**Ruling:** We award this submission third place in the ACDH hackathon 2020. Congratulations!

The following detailed review was authored by Omar Siam and Marcella Tambuscio.

### Summary
The project goal is to investigate the techniques taught by the different DH courses and the collaborations in terms of academic publications between institutions: the proposed visualization should offer the user the possibility to easily access, for each course of the registry, the relations among researchers working in each institute, university, or center.
A nice prototype with two kinds of visualizations of the enriched data was created with well known web development and network analysis techniques.

### Creativity
The project enhances the data provided by the course registry using two other data sources and visualizes them using bar charts and familiar network visualization techniques. The idea of integrating the provided data with publications and collaborations is indeed interesting.

**Creativity: Possible improvements**

The creative part seems not so much in the kind of visualization used but in the enrichment of the data. In particular, network analysis possibilities have not been exhaustively exploited to offer a more complex, clear and comprehensive visualization, involving for instance the detection of communities. Moreover, pursuing the network approach, it would be interesting to compare different types of collaborations (co-authored publications and citations, to give an example).  

### Reproducibility & reusability
Website code, data, and tools to generate the data are part of a single repository. Just by cloning that repository on some kind of web server the project can be reproduced. So reproducibility is very high. The externally loaded js libraries are not versioned so the page may break due to external updates.
Using well known JavaScript components and development techniques enables other developers to create their own version of  the visualizations demonstrated here.
The python code also uses well known python packages to fetch data and enrich the original data set.

**Reproducibility & reusability: Possible improvements**

Reusability is not very high as the page is not built with any modern component based framework.
The app is a typical jQuery base application:
* it is not modularized: the whole code is in one (about 1000 lines!) long source code file and this may not be easy to read and understand;
* the code has small HTML snippets spread all over the place;
* there are more proven problematic programming techniques used.

Furthermore, the data is not fetched dynamically but is retrieved (and enhanced) using python in a set of Jupyter notebooks. These notebooks are not used for documenting thoughts but mostly are canvases for python scripts. The python code is documented, even though the documentation is sparse and not all the advantages of python notebooks have been used. 

### Elegance
The color scheme is nice as are the round corners of the boxes.

**Elegance: Possible improvements**

The single webpage could be better organised in terms of space, with a larger visualization of the network (that could be more useful) and a smaller one for the techniques histograms. 
The network visualization is hard to read because of nodes and labels overlapping. By using different parameters for the network visualization and removing isolated nodes these problems could probably be avoided. Such parameters can for example be found using a python network visualization library in the jupyter notebooks used for enriching the data.

### Further ideas for improvements
* Network visualization

Despite the idea of merging these data (course registry and publications) using a network visualization is indeed very useful and interesting, the realization of the project has some problems of usability. The network visualization is chaotic since all the labels are overlapping and many of them are not readable: it could be better visualizing only some of them (the ones with higher degree?) and the other ones only hovering them. Moreover, most of the nodes are not even connected, so the network visualization for them is not very useful. 
The search tools could also be improved since it works only with matching the exact beginning of the string, i.e. looking for “London” the user does not receive suggestions.
Nevertheless, when only two nodes (in the largest connected component) are chosen the visualization works well. 
Finally, the overall project could be improved a lot by exploiting basic network analysis techniques: for instance communities could be enlightened coloring the nodes and running a simple Louvain algorithm for communities detection. Also the visualization of subnetworks concerning a given topic or a geographical area could be interesting to realize.

* Code
  * the website uses out of date methods for creating an interactive site
  * there are no tests at all
  * there is no version information on the different js libraries used (to date this works well but a live website may fail in the future due to unexpected incompatibilities after updates)

