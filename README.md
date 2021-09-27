# GithubApi
Part 1: 
What concerns would you have from a testing perspective?

1.Initial set up of testing infrastructure is important.
2.Updating schema of API testing. Any updates to the program that create additional parameters for the API calls need to be reflected in the schema configuration.
3.Testing Parameter Combinations:  It’s necessary to test all possible parameter request combinations in the API to test for problems pertaining to specific configurations. 
4.Sequencing the API Calls: In many cases, API calls need to appear in a specific order to work correctly. This creates a sequencing challenge for the testing team.
5.Validating Parameters: Testing teams may find validating the parameters sent through API requests challenging as well. The sheer number of parameters and use cases for those parameters can make it a daunting task.

How would you go about tackling the QA for this work?

Set up scalable testing infrastructure and start from building manual tests. Manual testing helps confirm whether something works. Start from very basic smoke level tests. 
Getting the testing infrastructure up and running is often one of the most challenging parts of the process–not because it is particularly difficult, but because it can be a substantial motivation-killer. Once you manage to motivate your team to get through the process, however, it pays off over the long-term.

What sort of tests would be worth describing or worth automating?

Automate:
-Repetitive tasks
-Features users use everyday
-Basic-smoke level tests
-Things that will allow us to exercise lots of different options
-Things that will alert us when something is wrong

What tools would you use?

-Many tools could be used for API testing. Most popular ones are Postman, Insomnia, JMeter, VSCode. For automation of API tests I would use Java Rest Assured library.

To Run Test File:
-Clone repository in your local (or download teh jmx file). Load the jmx file to Jmeter applicaton and run. 
