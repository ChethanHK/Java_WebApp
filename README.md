# Java_WebApp

Artha educational institute wants to implement a programmed solution tocompute average assignment rating and overall  rating for eachstudentand/or subjectsto measure  effectiveness of learning. For each subject, the overall ratingis determined by ratings on various categories, including tests, quizzes, labworks, projects, etc.  The percentages of the categories should add to 100%. The number of assignments from each category is unspecified andcan change at any time.  Requirements
1.Compute & display student average score per assignment category & overall  rating for assigned subject(s).
2.Compute & Display subject average score per assignment category & overall rating for assigned student(s).
3.Basic features
a.Add/remove assignment category with weights to an existing list. Ensure no duplicates of assignment category. (Refer below for Distribution table)
b.Display all assignment categories with their weights.
c.CRUD operations for student enrollment to subject(s) with Assignment Category (may be initially  assumed for date of submission  & points with default value and gets updated after submission)Note: 
✓Refer below for design & computation tips.
✓Sample data to be preloaded for demonstrationDemo Expectations:Build a solution to illustrate
•Create UI form for creating “Assignment Category” details•Create UI form for Student enrollment for “assignment” (optional)•Create UI form for updating ‘date of submission’ & score against enrolled assignment
•Create Suitable UI for below mentioned requirement(s)oTo acceptstudent idto display average scores per assignment category for each subject.
▪If invalid id entered, display with suitable messageoTo acceptsubject idto display average scores per assignment category for all studentsExpected Deliverables 1.Maven project -solution  code  base, unit  test  scripts, pom.xml & properties file(s)if any.
2.Read Me file (read.txt) Note: Find below recommended naming conventions to consider
1.groupId: <ADID>.<phase>.<project>Example: avitepa.webapp.rating
2.artifactId: <ADID>_<phase>_<Project>Example: AVITEPA_webapp_Rating
