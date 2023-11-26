## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).

	-Service Oriented Architechture (SOA) is stated to be a software development process that takes advantage of already 
available software or services, reusing it for the development of one's own software, it is said that each block of code
that was reused has its own individual function, mostly for transactional data, although it reusable, those "reusables"
are also interoperable making it compatible to multiple programming languages and other supported standards.

2. List and discuss the characteristics of SOA.

	-SOA or Service Oriented Architechture has 9 characteristics, this include:

	-Standardized Service Contract
	-Loose Coupling
	-Abstraction
	-Service Reusability
	-Autonomy
	-Statelessness
	-Discoverability
	-Composability
	-Interoperability

	-"Standardized Service Contract" states that the services provided should comply and provide both their purpose, limit,
	and the scope of their capability, their contracts would also adhere to be operable at a a standardized version that 
	should be available for interpretation to if not all, then most.

	-"Loose Coupling" states that services reliance are minimized both internally and externally making it easy to place
	on different services and for other services to build on top of it.

	-"Abstraction",it mainly hides the complexion to users and provides only the function.

	-"Service Reusability", focuses on making the servise reusable to different devices and standard.

	-"Autonomy", describes each services ability to be independent and self managed, while maintaining their ability to
	contain or encapsulate their logic.

	-"Statelessness" states that the services are more scalable due to it naturally not storing or keeping previous 
	transaction data, with this, services can be flexible having individual control, promotiing isolation.

	-"Discoverability", services contains adequate type of metadata for others to identify and discover, which would 
	also explain their purpose and capability to us users.

	-"Composability", assembling individual blockes of codes or services to create a much more larger complex service 
	that would give a more complex process, making each block exchange data and perform different complex process.

	-"Interoperability", being a norm or standard of SOA, it promotes the use of standardized form so that varying users
	with different equipments could still communicate and be compatible or flexible to mostly everyone.

3. Define Microservices.

	-Simillar to Service Oriented Architechture, Microservices focuses on the same idea as the SOA with the difference
	of it being more distinctly for building individual aplications and not too much for enterprise like SOA, 
	Microservices.
	
4. List and discuss the benefits of using Microservices.
	
	-Independently Deployable
	-Righ tool for the job
	-Precise scaling

	-"Independently Deployable",this creates small indipendent microservices that communicates with each other lessening 
	the size or memory it occupies, making it more compact and efficient for team members to understand and modify.

	-"Right tool for the job" implies that because Microservices are independently deployed, people has the freedom to 
	choose the most compatible "tool" for the task that could make the task a lot easier with less wasted actions.

	-"Precise Scaling", states that because it is individuality or indepentent nature, services can be scaled up or 
	down to its precise amount, making the project more Cost efficient, freeing up memory space and improving performance.

5. List and discuss the similarities and differences of SOA and Microservices.

	-As explained earlier the main difference between SOA and Microservices would be that Service Oriented Architecture mainly
focuses on the enterprise side or what would you call the transation side while Microservices focuses more on individual 
application creation, in the end it all boils down to their limitations and scope, like how SOA has more information, 
ability, and advantage on an enterprise-wide approach to software development the same can be said to Microservices on its 
side for independent application building.

6. Define Web Services.

	-simply put that website applications are not really created with the same programming language, and for example a user wants
two different website application to communicate with each other but their code is completely different from one another a
WEB SERVICE is used, WEB SERVICE is a middle ground or an eqaul plane for website application, this enables web applications
to communicate and exchange data with each other.

7. List and discuss the benefits of using Web Services.

	Web Services includes a number of characteritics but these are the ones that are focused on,

	-Exposing the Existing Function on the network
	-Interoperability
	-Standardized Protocol
	-Low Cost Communication

	- Exposing the Existing Function on the network is one of the main characteristics of almost every Web Services,
	with this characteristic, web services expose functions of websites or web application to the network making it
	visible for everyone though there are security measures so that functionalities cannot be used by everyone only
	permitted websites.

	- Interoperability, as stated with the SOA, promotes independency, because of this different websites with very
	different languages can communicate with each other.

	-Standardized Protocol, with interoperability comes standardization, this simply means that web services, offers
	itself as a translator to different web applications, web services follows a standard protocol that each website
	application can understand.

	-Low Cost Communication, because of the components of Web Services like SOAP and the standard protocol HTTP/HTTPS
	and other beneficial component that is unique to Web Services simplify interactions and provide seamless communication
	between website applications, all of these factors contribute to the overall affordability of webservices.

8. List and discuss the characteristics of Web Services.

	A couple of important characteristics can be observed in Web Services, this includes,

	-XML-Based
	-Loosely Coupled
	-Coarse-Grained
	-Ability to be Synchronous or Asynchronous
	-Supports Remote Procedure Calls (RPCs)
	-Supports Document Exchange
	
	-"XML-Based", Because of the innate neutrality of the XML language, webservices can easily be recognizable throughout
	diverse system, promoting interoperability and compatibility throughout the network.

	-"Loosely Coupled", Simply Means that web services are not embedded within the clients system, when a client requests
	a web service, the service will function independently as to prevent changes when the services updates.

	-"Coarse-Grained", is a structural characteristics within Web services, with this structure, its code would
	contain large blocks of high level functionality in a single operation where efficiency can be obtained.

	-"Ability to be Synchronous or Asynchronous", is a major adavantage that Web Services contain, this means that services
	can operate with varying timing this allowed web services to be versitile and range of its response timing.

	-"Supports Remote Procedure Calls (RPCs)", Means that web services can call functionalities even if it is in a remote
	server, this inturn increase the functionality, scope, and flexibility of the provided service.

	-"Supports Document Exchange", Means that web services does not only facilitate on exchange of functionality through
	code but also in exchange of structured documents, this will be advantageous if the service requested needs to transfer
	information.

9. List and discuss the distinct roles in Web Services Architecture.
	
	There are 3 Major roles in Web Service Architechture, this include

	- provider
	- requestor
	- broker

	each of these roles communicates with each other to achieve the desired output of web services, the Proivder is responsible
	for providing and creating the Web Service itself, the Requestor serves as the client or the customer that orders
	a certain functionality online, the Broker will then find the said functionality and expose it online in the network,
	although the Provider is the first to notice if the functionality that the requestor demands exists.

10. List and discuss the Web Services Components.

	There exists 3 Major World Wide Standards that Web Services use all throughout its development,

	- SOAP (Simple Object Access Protocol)
	- WSDL (Web Services Description Language)
	- UDDI (Universal Description, Discovery and Integration)

	-The three component although have independent functions still needs each other to have a greater purpose, in fact these
	three standards makes up the majority of a Web Service.
	
	SOAP functions as the communicator in Web Services this protocol
	is the one responsible for Exchanging data to different computers regardless of programing languages.
	
	WSDL serves as the interpreter of the gathered information or Service, WSDL provides clients with an understandable 
	interpretation on how to use the gathered service, or another ways of saying it is it provides standardized way for
	clients to easily understand.

	UDDI provides visibility to web services, it allows other business publish their web services and allows others to find
	their published web service, naturally it is also able to find other web service for its own.	
	


