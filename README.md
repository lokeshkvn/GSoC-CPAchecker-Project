# GSoC CPAchecker Poject - Final Work Submission

<p align="center">
<img src="https://raw.githubusercontent.com/lokeshkvn/GSoC-CPAchecker-Project/master/gsoc-title-new2.jpg" width="500px" height="270px"> 
</p>

## Introduction and Background: 
 
- Organisation Name: [Software and Computational Systems Lab, LMU Munich, Germany](https://www.sosy-lab.org/) 
- Project Idea: [CPAchecker - Upgrade of AngularJS, Refactoring User Interface and automated tests for verification report](https://summerofcode.withgoogle.com/projects/#4562331867021312).
- Project Proposal: [Link](https://docs.google.com/document/d/160ILV_sB2MWPtB0YNyJex_Vm5w7HQN8lvrWY1ub9SDE/edit?usp=sharing) 
- Mentor: Philipp Wender
- Name: Lokesh Nandanwar
- Country of Residence: India
- University: National Institute of Technology Durgapur
- Major: Information Technology
- Year of Study: B.Tech, Final Year
- Github: [github.com/lokeshkvn](https://github.com/lokeshkvn)
- Website: [lokeshnandanwar.wordpress.com](https://lokeshnandanwar.wordpress.com)


<p align="center">
<img src="https://raw.githubusercontent.com/lokeshkvn/GSoC-CPAchecker-Project/master/unnamed.png"> 
</p>


### Project Information:

CPAchecker is an award-winning open-source framework for the verification of software. It is written in Java and based on a highly modular architecture that allows to develop and combine a wide range of different analyses. CPAchecker is used for verification of the Linux kernel and has helped to find more than 50 bugs in the kernel. 
CPAchecker produces as result a report about its verification work. This report is a web application based on AngularJS and D3. The basic goal of this project is to upgrade AngularJS and to write tests for the functionality of this report using an appropriate framework for automated tests. 


## Summary of Achievements:

- AngularJS and other libraraies upgraded to latest build.
- User Interface upgraded to follow modern architecture and latest standards.
- Addition of 61 unit test cases and 47 specs for end-to-end tests.
- Automation of [Unit testing](https://gitlab.com/sosy-lab/software/cpachecker/-/jobs/88612239) and [End-to-end testing](https://gitlab.com/sosy-lab/software/cpachecker/-/jobs/88612240) using Gitlab CI to reduce the defects and errors that were made during the development phases.
- Test coverage with generation of [reports](https://gitlab.com/sosy-lab/software/cpachecker/-/jobs/88612239/artifacts/browse/src/org/sosy_lab/cpachecker/core/counterexample/) and [screenshots](https://gitlab.com/sosy-lab/software/cpachecker/-/jobs/88612240/artifacts/browse/src/org/sosy_lab/cpachecker/core/counterexample/).
- [Coding guidelines](https://gitlab.com/sosy-lab/software/cpachecker/blob/trunk/doc/ReportTemplateStyleGuide.md) and [Testing](https://gitlab.com/sosy-lab/software/cpachecker/blob/trunk/doc/JavascriptTesting.md) Documentation.
-  Increased maintainability.

## Project Goals Delivered and Milestones:

The major goal of this project idea is to upgrade AngularJS and to write tests for the functionality of this report using an appropriate framework for automated tests. The details of all the goals which are delivered for this project is as below: 
 
 
- **Milestone 1**: Upgrade of AngularJS to latest build: Upgraded the version of angularJS v1.6.5 to v1.7.0 (Major stable release on 30 June 2018). 
 
- **Milestone 2**: Upgraded versions of all the 3rd party libraries used: The versions of third party libraries used in the web application is now very old (Specified later), so some of the functionality of the app may not work properly. So I have upgraded it to its latest version.
 
- **Milestone 3**: User Interface upgraded to follow modern architecture and Additional features to web interface of application: 
  - Bootstrapping and css to required elements and Refactoring of page layout as per latest standards. 
  - Collapsing vertical navigation on the left-hand side of the page which contains a table-like representation of the error-path data. 
  - Tooltips to the buttons and elements on the page to help user know the functionalities of the web applications better.  
  - Sortable & Responsive Table for logs, statistics and configuration tab. 
  - Divider between left and right half movable with the mouse. 
  - Added a "full screen mode" button. 
 
● Automated Testing of Application using Jasmine and Protractor framework: Writing of automation tests functions for the web application in Jasmine framework and run the automation test. There will be two types of testing:

- **Milestone 4**: Unit Testing of Application using Jasmine/Karma framework.

- **Milestone 5**: End to End Testing of application using Protractor Framework.

## Code Contribution:

- Project Repository: [https://gitlab.com/sosy-lab/software/cpachecker]()

- Commits: [https://github.com/sosy-lab/cpachecker/commits?author=nandanwar@4712c6d2-40bb-43ae-aa4b-fec3f1bdfe4c]()

- Final Product: [You can have a look at my working branch `angularjs-dev` which got merged to master/trunk of the CPAchecker Application](https://gitlab.com/sosy-lab/software/cpachecker/tree/angularjs-dev)

- Deployed Example report: [Link](https://cpachecker.sosy-lab.org/counterexample-report/ErrorPath.0.html)


## Timeline:

### Week 1 (May 14 - May 19, 2018)

- Setting-up and deployment of the application.
- Creating branch for development and test commit.
- Upgrade of jQuery library and removal of deprecated functions.
- Addition of Style Guide for HTML/CSS/Javascript for Report Template as per Google's Style guide.
- Upgrade of D3.js and Dagre-D3 libraries.
- Replacement of deprecated methods/functions.
- Formatted  HTML/CSS/Javascript files of Report Template as per Google's Style and coding guidelines.

### Week 2 (May 20 - May 25, 2018)

- Exploration of Documentation of Bootstrap v4.1.1
- Upgraded the Bootstrap library to v4.1.1
- Added popper.js and fontawesome.css libraries as a support for Bootstrap v4.1.1 ( Because of breaking changes).
- Removed and Replaced deprecated elements and fixed bugs caused by upgradation of Bootstrap library.
- Upgraded Google Prettify code library to latest version dated 29-4-2018.
- Added new theme for Source code and Error code and done some refactoring for best UX.

### Week 3 (May 26 - June 1, 2018)

- Upgrade of Angularjs to v1.7.0
- Refactored HTML elements with the latest bootstrap.
- Updated elements of the HTML (buttons, labels, dropdown,etc).

### Week 4 (June 2 - June 8, 2018)
	
- fixed Modal dialogue hide() property. 
- Added User interface for a Modal dialogue box.
- Updated navigation bar and toolbar. 
- Refactored header of the report template.
- Updated background color of code sections.

### Week 5 (June 11, 2018 - June 17, 2018)

- Collapsing Vertical navigation on the left-hand side of the page which contains a table-like representation of the error-path data.
- minor fix of google-code-prettify library
- Addition of toggle button to show/hide error path section

### Week 6 (June 18, 2018 - June 24, 2018)
	
- Tooltips to the all the buttons and some required elements on the page using popper.js 
- Added new tooltip UI for the ARG and CFA graph nodes and edges
- Added rounded edges for rectangles in ARG graph
- Added fullscreen mode feature

### Week 7 (June 25, 2018 - July 1, 2018)

- addition of Datatables library
- Table view for logs, statistics and configuration tabs.
- Added indentation to the statistics table for hierarchical view and new column for additional value in statistics table
- Error Fixed : google prettify code loading from external server cdn.rawgit.com
- Error Fixed : local variable which is not in use and Formatted code

### Week 8 (July 2, 2018 - July 9, 2018)

- Setting up of environment, addition of dependencies and Sample test case for Unit testing using Jasmine/Karma/PhantomJS
- Added third party dependencies using bower and loaded report.js for unit testing
- Added jasmine-jquery plugin for DOM testing
- Mock testReport.js and testReport.html as Mock files for Unit testing
- Primary unit tests cases for all controllers and init function

### Week 9 (July 10, 2018 - July 16, 2018)

- Automated generation of testReport.html with search and replace in report.html file
- Added CI for unit testing of report in gitlab-ci.yml
- Fixed slider error in error path section and external file section.

### Week 10 (July 17, 2018 - July 23, 2018)

- Completed Unit testing of the Javascrpit report.
- Completion of Milestone 4.
- Installed protractor and selenium driver for e2e testing.
- Added E2E testing setup and base test case.
- Fixed Bug in statistics table

### Week 11 (July 24, 2018 - August 31, 2018)

- Added e2e testing for all the controllers. 
- Added Tests for e2e testing  error path section and external file sections.
- Added testing for graphs and content inside tabs.
- Fixed truncated error code and source code bug.

### Week 12 (August 1, 2018 - August 9, 2018)

- Created docker image for java and nodejs.
- Added stage for creating counterexample report from CPAcheker for e2e testing in CI
- Completion of Milestone 5 (e2e testing).
- Added e2e tests in GitLab CI.
- Added report generator for e2e testing using external plugin
- Added Unit testing report generator using karma-html-reporter
- Added documentation for Javascript Report Testing.


## Future Improvements:

Unit testing part of some functions of D3.js and Dargre-D3 graph from Milestone-4 is not completed due to the following reason, we can implement that in future:
- Code archtecture for testing needed is BDD/TDD.
- There are several nested functions.
- Dynamic data for generating graph.

If we overcome the above drawbacks we can unit test the remaining functions.

## Final Words:

GSoC was a wonderful experience for me. I now feel a bit more comfortable with the large codebase to work on. I learned a lot of useful stuff like Docker, GitLab Continous Integration, SVN for version control, and much more stuff. I also got to know that automated testing help us a lot to monitor and prevent bugs in our code before it can be merged in upstream repository. I loved working on a really cool open-source project like CPAchecker this summer and am very thankful to Google for providing me this opportunity.
I will try my best to regularly contribute CPAchecker in a free time. I would encourage everyone reading this to give the CPAchecker a try and contribute if possible. Thanks to **Philipp Wender** and various others in SoSy Lab team for such a wonderful experience and the knowledge.
