# GSoC CPAchecker Poject - Final Work Submission

<img src="https://camo.githubusercontent.com/ed508e9c66d718f76333215a139af24f8bb8fa8d/68747470733a2f2f6d75736573636f72652e6f72672f73697465732f6d75736573636f72652e6f72672f66696c65732f4361707475726525323064253237652543432538316372616e253230323031362d30332d303125323030392e34382e31315f302e706e67" align="center"/>

## Introduction and Background: 
 
- Organisation Name: Software and Computational Systems Lab 
- Project Idea: [CPAchecker - Upgrade of AngularJS, Refactoring User Interface and automated tests for verification report](https://summerofcode.withgoogle.com/projects/#4562331867021312).
- Mentor: Philipp Wender
- Name: Lokesh Nandanwar
- Country of Residence: India
- University: National Institute of Technology Durgapur
- Major: Information Technology
- Year of Study: Final Year
- Github: [github.com/lokeshkvn](github.com/lokeshkvn)
- Website: [lokeshnandanwar.wordpress.com](lokeshnandanwar.wordpress.com)

### Project Information:

CPAchecker is an award-winning open-source framework for the verification of software. It is written in Java and based on a highly modular architecture that allows to develop and combine a wide range of different analyses. CPAchecker is used for verification of the Linux kernel and has helped to find more than 50 bugs in the kernel. 
CPAchecker produces as result a report about its verification work. This report is a web application based on AngularJS and D3. The basic goal of this project is to upgrade AngularJS and to write tests for the functionality of this report using an appropriate framework for automated tests. 

## Project Goals Delivered:

The major goal of this project idea is to upgrade AngularJS and to write tests for the functionality of this report using an appropriate framework for automated tests. The details of all the goals which are delivered for this project is as below: 
 
 
- **Milestone 1**=> Upgrade of AngularJS to latest build: Upgraded the version of angularJS v1.6.5 to v1.7.0 (Major stable release on 30 June 2018). 
 
- **Milestone 2**=> Upgrading versions of all the 3​rd​ party libraries used: The versions of third party libraries used in the web application is now very old (Specified later), so some of the functionality of the app may not work properly. So I have upgraded it to its latest version.
 
- **Milestone 3**=> User Interface upgraded to follow modern architecture and Additional features to web interface of application: 
  - Bootstrapping and css to required elements and Refactoring of page layout as per latest standards. 
  - Collapsing vertical navigation on the left-hand side of the page which contains a table-like representation of the error-path data. 
  - Tooltips to the buttons and elements on the page to help user know the functionalities of the web applications better.  
  - Sortable & Responsive Table for logs, statistics and configuration tab. 
  - Make divider between left and right half movable with the mouse. 
  - Add a "full screen mode" button. 
 
● Automation Testing of Application using Jasmine and Protractor framework: Writing of automation tests functions for the web application in Jasmine framework and run the automation test. There will be two types of testing:

- **Milestone 4** => Unit Testing of Application using Jasmine/Karma framework.

- **Milestone 5** => End to End Testing of application using Protractor Framework.


## Code Contribution

- Project Repository: https://gitlab.com/sosy-lab/software/cpachecker

- Commits: https://github.com/sosy-lab/cpachecker/commits?author=nandanwar@4712c6d2-40bb-43ae-aa4b-fec3f1bdfe4c

- Deployment: [Link]()

## Future Improvements

Unit testing part of some functions of D3.js and Dargre-D3 graph from Milestone-4 is not completed due to the following reason, we can implement that in future:
- Code archtecture for testing needed is BDD/TDD.
- There are several nested functions.
- Dynamic data for generating graph.
If we overcome the above drwabacks we can unit test the reamining functions.

## Final Words

GSoC was a wonderful experience for me. I now feel a bit more comfortable with the large codebase to work on. I learned a lot of useful stuff like Docker, GitLab Continous Integration, SVN for version control, and much more stuff. I also learn that automated testing help us a lot to monitor and prevent bugs in our code before it can be merged in upstream repository. I loved working on a really cool open-source project like CPAchecker this summer and am very thankful to Google for providing me this opportunity.
I will try my best to regularly contribute CPAchecker in a free time. Thanks to Philipp Wender and various others in SoSy Lab team for such a wonderful experience and the knowledge.









