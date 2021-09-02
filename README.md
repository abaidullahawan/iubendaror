# iubendaror
Senior Backend / Ruby on Rails Developer (Remote) - iubenda

How to setup and run the application/automated tests?
	First you have to setup your system in a way that it supports ruby. 
For run our application, you have to put “code.rb” file in any directory. And then you have to move into the following directory and run command like this “ruby code.rb”
For the test cases, I am just passing the template and desired clause or section. If you want to change the example you can call the function with template, clause and section add at the end. 

Design Decisions:
	In this application, there are different methods use for replacement of tags like Clauses and Sections. In main flow of the application, we call “parse_template” method and assign clauses, sections and templates to this method. This method parse clauses and for parsing of sections this method further call another method name “ find_clause_text” which return section text to us. And we replace clause and section text in original template.

How much time you took and what you would have done given more time.?	
	It take 2 hours to complete this application and if I would have more time then I will make it more dynamic and also made its responsive UI for better look.
