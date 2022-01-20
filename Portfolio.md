# Portfolio Semester 3

This portfolio has been created to prove that during the third semester of my studies, I satisfied the various learning outcomes using the different references given below as proof. Each of the different sections below will explain why I think I achieved a certain score, in agreement with my teacher. Each of the section titles have "LO" in their name which stands for learning outcome. An overview of what my project is about can be read in the [README.md](https://github.com/FHICT-S-Owen/DiscordBotManager#readme) file.

# Table of contents
 - [IPS learning outcomes](#IPS-learning-outcomes)
   - [LO 1 - Web Application](#LO-1---Web-Application)
     - [User-friendliness](#User-friendliness)
     - [Full-stack](#Full-stack)
   - [LO 2 - Software Quality](#LO-2---Software-Quality)
   - [LO 3 - CI/CD](#LO-3---CI/CD)
   - [LO 4 - Professional](#LO-4---Professional)
     - [Feedback](#Feedback)
     - [Research](#Research)
     - [Project management](#Project-management)
 - [GPS learning outcomes](#GPS-learning-outcomes)
   - [LO 1 - Agile method](#LO-1---Agile-method)
   - [LO 2 - Business processes](#LO-2---Business-processes)
   - [LO 3 - Requirements and design](#LO-3---Requirements-and-design)
   - [LO 4 - Cultural differences and ethics](#LO-4---Cultural-differences-and-ethics])
   - [LO 5 - Professional](#LO-5---Professional)
   - [LO 6 - Web application](#LO-6---Web-application)

# IPS learning outcomes
The sub sections show the various proofs for the learning outcomes of my individual project. Further down in this file there is another section with all the proofs for the group project learning outcomes.

## LO 1 - Web Application
You design and build **user-friendly**, **full-stack** web applications. The proof that I've written about in the sub-sections below should suffice for this learning outcome to be proficient. 

### User-friendliness
You apply basic User experience testing and development techniques.

To validate user-friendliness my teacher and I discussed the different ways in which this can be done. We came to the conclusion that testing for user-friendliness can also be achieved on my monorepo itself. I've created a GitHub issue with [repository feedback](https://github.com/FHICT-S-Owen/DiscordBotManager/issues/42) as title. This issue serves as a gathering place for validating the user-friendliness of my repo by commenting.

### Full-stack
You design and build a full stack application using commonly accepted front end (Javascript-based framework) and back end techniques (e.g. Object Relational Mapping) choosing and implementing relevant communication protocols and addressing asynchronous communication issues.

Within this repo is a full stack application that contains a web dashboard with basic authentication using Vue. The back-end consists of multiple microservices written in Java using the Spring framework and a Discord bot that together form the back-end.

## LO 2 - Software Quality
You use software **tooling and methodology** that continuously monitors and improve the software quality during software development.

From the perspective of the customer it would be very important to be able to show that your code performs like described using the user story and that your code runs without having problems. We can achieve this by running code quality analysis tools and by writing various tests for our code. This is exactly what I did in this project. The LoggingService folder contains a microservice that has various tests that can prove that the acceptance criteria have been met if these tests succeed. The composition of the various tests can be viewed in [this](https://github.com/FHICT-S-Owen/DiscordBotManager/tree/Production/LoggingService/src/test/java/com/owendb/loggingservice) folder.

![Screenshot of tests passing](https://github.com/FHICT-S-Owen/S3-IPS-DOCS/blob/main/screenshots/Screenshot_LogginService_Tests.png?raw=true)

The screenshot below shows a summary page of sonarcloud, which I use for code quality analysis itself.

![Screenshot of tests passing](https://github.com/FHICT-S-Owen/S3-IPS-DOCS/blob/main/screenshots/Screenshot_SonarCloud.png?raw=true)

For this learning outcome I have been able to achieve what I wanted and am on the same page as is required for this LO to be proficient.

## LO 3 - CI/CD
You **design and implement** a (semi)automated software release process that matches the needs of the project context.

Because I use a monorepo to contain all of my projects some interesting challenges appeared that I had to try and solve with the small amount of knowledge I had about both CI/CD and Monorepo's. Using the research as a way to document my findings I think that I have definitely achieved more than enough to have this LO be on an advanced level.

## LO 4 - Professional
You act in a **professional manner** during software development and learning. I achieved this by communicating and asking feedback regularly from peers and teachers, performing research with a fellow student and managing the entirety of the project through a public project page that is attached to this repository. The abovementioned 3 things will be elaborated upon in the sections below. I think that I have been able to achieve a lot of things within this LO as well and expect this to be on a proficient level.

### Feedback
After having a feedback moment with my teacher I'd write down all the feedback that the teacher had for me in a summary on the school page called FeedPulse. In this section I'll show you some of these summaries in the form of screenshots that I've taken directly from the FeedPulse page. The smiley is the teachers rating on this summary which is very positive.

![Screenshot of FeedPulse](https://github.com/FHICT-S-Owen/S3-IPS-DOCS/blob/main/screenshots/Screenshot_FeedPulse.png?raw=true)

### Research

The research paper that Siem Lucassen and I wrote together about monorepo deployment can be found in the [Research.md](https://github.com/FHICT-S-Owen/S3-IPS-DOCS/blob/main/Research.md) file. We got feedback from our teacher during the writing process and applied it as much as possible.

### Project management

My teacher also came up with the idea to use GitHub projects to keep my progress as transparent as possible together with the repository being public. Using GitHub projects has given me a lot of insight into keeping a perspective that is friendly towards outsiders. 

![Screenshot of GitHub Projects page](https://github.com/FHICT-S-Owen/S3-IPS-DOCS/blob/main/screenshots/Screenshot_Projects.png?raw=true)

# GPS learning outcomes
In the sub sections below the proofs regarding the group project are explained. 

## LO 1 - Agile method
You can implement the software process for your project according to a given **agile software development method**.
- [Onderzoek over Agile en verschillende Agile methodes](https://github.com/FHICT-S-Owen/S3-GPS-DOCS/blob/main/Researches%20-%20Owen/Agile_methods.md)

## LO 2 - Business processes
You can explain **simple** business processes and **relate** them to the development of your software project.
- [Onderzoek over Business processes](https://github.com/FHICT-S-Owen/S3-GPS-DOCS/blob/main/Researches%20-%20Owen/Business_process.md)

## LO 3 - Requirements and design
You translate (non-functional) requirements to extend existing (architectural) designs and can validate them using **multiple types of test techniques**.
- [Onderzoek over Requirements en design samen met Dirk](https://github.com/DirkLemmen/Researches/blob/master/Requirements%20and%20Design.md)

## LO 4 - Cultural differences and ethics
You **recognize** and **take into account** cultural differences when working with multi-site teams and are aware of ethical aspects in software development.
- [Culture en Ethics research](https://github.com/FHICT-S-Owen/S3-GPS-DOCS/blob/main/Researches%20-%20Owen/culture_and_ethics.md)

## LO 5 - Professional
You act in a **professional manner** during software development and learning. The images below show that I'm able to communicate in a professional manner towards peers, teachers and stakeholders.
<table>
  <tr>
    <td><image src="https://github.com/FHICT-S-Owen/S3-IPS-DOCS/blob/main/screenshots/FeedPulse_Group.png?raw=true"></td>
		<td><image src="https://github.com/FHICT-S-Owen/S3-IPS-DOCS/blob/main/screenshots/FeedPulse_Self.png?raw=true"></td>    
  </tr>
 </table>

 <td><image src="https://github.com/FHICT-S-Owen/S3-IPS-DOCS/blob/main/screenshots/FeedPulse_Peers.png?raw=true"></td>


## LO 6 - Web application
You design and build **user-friendly**, **full-stack** web applications. In order to keep user-friendliness in mind I wrote some basic user experience testing in the section below. I've also linked to the scrum to show the different user stories that I've taken care of.
- [Basic user experience tests](https://github.com/DirkLemmen/Researches/issues?q=is%3Aopen+is%3Aissue)
- [JIRA scrum board](https://fontysict.atlassian.net/jira/software/projects/SCRUM/boards/1)

The pictures below are there to show how much I have contributed to the project in terms of writing actual code.

<table>
  <tr>
    <td><image src="https://github.com/FHICT-S-Owen/S3-IPS-DOCS/blob/main/screenshots/Contributions_MenuMCS.png?raw=true"></td>
    <td><image src="https://github.com/FHICT-S-Owen/S3-IPS-DOCS/blob/main/screenshots/Contributions_RestaurantMCSGateway.png?raw=true"></td>
  </tr>
	<tr>
    <td><image src="https://github.com/FHICT-S-Owen/S3-IPS-DOCS/blob/main/screenshots/Contributions_RestaurantSPA.png?raw=true"></td>
    <td><image src="https://github.com/FHICT-S-Owen/S3-IPS-DOCS/blob/main/screenshots/Contributions_SessionMCS.png?raw=true"></td>
  </tr>
 </table>
