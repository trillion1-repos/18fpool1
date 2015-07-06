## Trillion OpenFDA Data Visualization Platform

Trillion Technology Solutions, Inc. [(Trillion))](http://www.ttsiglobal.com) has implemented a prototype – “Trillion OpenFDA Data Visualization Platform” [(ODV Platform)](https://18fpool1.ttsiglobal.com) - in response to GSA 18F Agile BPA that leverages industry leading open source technology stacks and developed using Agile development methodology.

## Methodology Approach
Trillion has embraced Agile since 2006 and successfully implemented several turnkey and mission critical applications in commercial and government sectors. We leveraged this experience to create a compact set of [Agile sprints for developing](https://github.com/trillion1-repos/18fpool1/blob/master/doc/DesignPoolEvidenceForQuestion2.jpg) a solution for the challenge posed by GSA 18F BPA. [Our team](https://github.com/trillion1-repos/18fpool1/blob/master/doc/WorkingSessions.pdf) comprised of members who were self-organizing, cross-functional and participated in flushing out user stories, design and development, unit and integration testing. One of the conference rooms in our office was barricaded off from the rest of the company and was used exclusively by the ODV Platform Agile team for daily Scrums, discussions and collaborative team development.  An open source Agile Lifecycle Management (ALM) tool – [Tiaga](https://github.com/trillion1-repos/18fpool1/blob/master/doc/Pool1DesignTeamBacklogIssues.pdf) – was used for capturing all Agile artifacts.
The development consisted of one single Sprint of one week.  User stories were created based on product owner discussions with the team as well as style guides and wireframes created by the user interface experts on the team, per product owners requirements.  Skeleton user stories were created based on the wireframes and style guide. Daily Scrum meetings provided everyone to come together formally to discuss work done the previous day, to plan for that day, and to bring up impediments if any. The last day of each sprint included sprint retrospective and review followed by sprint planning for the next sprint. A product backlog was created by the product owner from which user stories were chosen for the sprint which went into the sprint backlog.
End-of-the-sprint deployment was done on the Amazon instance.  Product owner and another stakeholder provided feedback on the application, including the visualization and usability aspect of the application.  The usability tester, Visual designer, content provider and user interface developer worked closely to review the feedback.  Defects and tasks were created to incorporate these changes on the last day of the sprint which was considered the hardening sprint, due to the short one week sprint used for Pool 1 prototype.  

## Design and Development Approach
The ODV Platform was developed using a human centered design.  The goal was to create a simple intuitive web based graphical user interface for users to view drug, device and food recall data provided by the government for consumption by the general public.  The prototype was implemented using a technology stack that is pluggable and requires minimal changes to substitute technology libraries.  A style guide was created that outlined the fonts and colors that the product owner wanted in the end product.  It also outlined the general features of the user interface that the product owner required per their user feedback and requirements.  Based on the product owner requirements, our UI designer/expert and Content designer got together and created a set of wireframes that outlined how the screens should look like and how the navigation on the screens is expected to work.  The style guide and wireframes were handed over to the development team where we created a "Responsive Design" to work across different devices.

## ODV Features and Usage
ODV Platform allows users an interactive user interface that provides a drill down method to accessing recall information provided by the government. Hierarchical information access works as follows:
 *	At the top level from the home page which takes them to an interactive graphic page which shows graphs – pie, doughnut and bar – based on the recall data.  Recall information is available for each category – Drugs, Devices and Food
* The user can view a graph for each category – Drugs, Devices and Food.  This results in the graph changing per the data for that category
*	The user can also update these graphs by selecting the data fields for each of the recalls – Classification, Status and Voluntary Mandated
*	The users can click on the graphs for viewing detailed records of the data associated with the section of the graph that was clicked
*	The detailed list has smart search per each column shown.  Typing in part or full phrases filters down the records list to match the search pattern.
*	The detailed list also allows users to pick and choose the columns/fields that they wish to view in the detailed records.

##Production URL
https://18fpool1.ttsiglobal.com

## Installation
See our [Installation Guide](INSTALL.md)
