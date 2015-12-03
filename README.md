play-java-idea-template
=======================

The Play 2.4.x wizard in IntelliJ Idea 15 is currently broken. Importing a project from a Play 2.4.4 Activator created 
project also has some issues that aren't too difficult to fix, but are fairly annoying. This IntelliJ Idea template was 
made as a boilerplate to expedite the creation of a Play 2.4.4 project (with Bootstrap 3!).

How to Use
----------
1. **Clone**: git clone http://github.com/scrapcode/play-java-idea-template.git
2. **Import into IntelliJ Idea**: Import the project into IntelliJ Idea as an SBT Project
3. **Save as a Template**: Tools -> Save Project as a Template...
4. **Create Project**: File -> New Project -> user-defined
5. **Resolve Dependencies**: Open `project/plugins.sbt` and click `import project` in the notification header.

Contributing
------------
This template has been through very little testing. If you try to use it and have issues **please** file a big report, 
or submit a pull request!