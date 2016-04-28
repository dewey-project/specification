# specification

The Dewey specification defines how colleges should present data about departments, 
courses, professors, etc. 

The general system works like so: 

The Dewey Project hosts an api that provides information on schools and where their 
data resides. Applications can then make calls to this api to search for schools 
and more detailed information such as departments, courses, professors, etc. 

The specification defines the minimum requirements for a schools data api. This way 
no matter what school an application is looking at through the discovery tool they 
can be assured that they retrieve data. 

The Dewey Project provides an implementation of the specification so that schools can 
store and run the data api with their own resources. The Dewey Project also provides 
hosting for schools that want us to handle setting up the api, but the school can 
still manipulate the data. 

1. Specification 
2. Discovery API (Schools) (Single Instance)
3. Data API (Departments, Courses, Professors) (Multiple Instances) 
4. Web UI
5. Desktop UI (Electron)

