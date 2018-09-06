# LECTURE_09_06


# Demo of adding Navigation with Bootstrap to your project

* Use <https://github.com/ucsb-cs56-pconrad/sparkjava-mustache-example-02> as an example.


# How we will grade the work on the projects

* Each student needs to earn 1000 points to get their "full grade" for the project component of their final grade.
* Points are awarded by TAs or the instructor, NOT by the mentors.  MENTORS DO NOT GRADE.
* HOWEVER: the mentors do "peer code review", and "coaching" and "estimating" to help organize the information that is presented to TAs and instructors for grading.

# How you can earn the 1000 points

* By completing issues (tasks, stories, pull requests) that are:
   * listed on the repo for your project
   
   
# Those story links:

| Mentor | Project | Issues List |  m18-project |
|-|-|-|-|
|  Derek | [Ride2School](https://github.com/ucsb-cs56-webapps/ucsb-cs56-ride2school) | [Issues](https://github.com/ucsb-cs56-webapps/ucsb-cs56-ride2school/issues)| [Project](https://github.com/ucsb-cs56-webapps/ucsb-cs56-ride2school/projects/1)|
| 	Nuan	|[Go!](https://github.com/ucsb-cs56-webapps/ucsb-cs56-go)| [Issues](https://github.com/ucsb-cs56-webapps/ucsb-cs56-go/issues)| [Project](https://github.com/ucsb-cs56-webapps/ucsb-cs56-go/projects/1)|
| Wilson | [ScrapsToSnacks](https://github.com/ucsb-cs56-webapps/ucsb-cs56-scrapstosnacks	) | [Issues](https://github.com/ucsb-cs56-webapps/ucsb-cs56-scrapstosnacks/issues)| [Project](https://github.com/ucsb-cs56-webapps/ucsb-cs56-scrapstosnacks/projects/1)|
| Fuheng | [GauchoCourses](https://github.com/ucsb-cs56-webapps/ucsb-cs56-gauchocourses) | [Issues](https://github.com/ucsb-cs56-webapps/ucsb-cs56-gauchocourses/issues)|[Project](https://github.com/ucsb-cs56-webapps/ucsb-cs56-gauchocourses/projects/1)|
| Yunkai | [Go Gaucho](https://github.com/ucsb-cs56-webapps/ucsb-cs56-gogaucho) | [Issues](https://github.com/ucsb-cs56-webapps/ucsb-cs56-gogaucho/issues)|[Project](https://github.com/ucsb-cs56-webapps/ucsb-cs56-gogaucho/projects/1)|
| Chandler | [GauchoGains](https://github.com/ucsb-cs56-webapps/ucsb-cs56-gauchogains) | [Issues](https://github.com/ucsb-cs56-webapps/ucsb-cs56-gauchogains/issues)|[Project](https://github.com/ucsb-cs56-webapps/ucsb-cs56-gauchogains/projects/2)|
| Zihao | [GauchoAlarm](https://github.com/ucsb-cs56-webapps/ucsb-cs56-gauchoalarm) | [Issues](https://github.com/ucsb-cs56-webapps/ucsb-cs56-gauchoalarm/issues) |[Project](https://github.com/ucsb-cs56-webapps/ucsb-cs56-gauchoalarm/projects/1) |
| Omer | [DogWalker](https://github.com/ucsb-cs56-webapps/ucsb-cs56-dogwalker) | [Issues](https://github.com/ucsb-cs56-webapps/ucsb-cs56-dogwalker/issues)|[Project](https://github.com/ucsb-cs56-webapps/ucsb-cs56-dogwalker/projects/1)|
| Conrad | [WebApp-Catalog](https://github.com/ucsb-cs56-webapps/ucsb-cs56-webapp-catalog) | [Issues](https://github.com/ucsb-cs56-webapps/ucsb-cs56-webapp-catalog/issues) | [Project](https://github.com/ucsb-cs56-webapps/ucsb-cs56-webapp-catalog/projects/2) | 


# What is a Kanban board?

* Simply put: it is a visual/physical representation of work in progress. 
* The work *Kanban* comes from the Japanese language; the concept originated in work done in Japan on improving efficiency of work processes.
* The idea is to:
   * Know how much work you have at each stage in the pipeline from "TO-DO" to "WORK-IN-PROGRESS" to "DONE"
   * Use the visual representation to see how work is flowing (or not)
   * Do what you can to keep work flowing through the system
   * Minimize "WORK-IN-PROGRESS"; this is the central idea of so-called "Lean Business" (Lean Software, Lean Manufacturing, etc.)
   
# What kinds of "issues" will we put on the Kanban board?

* Anything that helps us move forward with the projects:
   * Adding features
   * Improving the UI/UX
   * Fixing bugs
   * Planning
   * "Skunk-works" projects
   * Adding testing

Note:
  * that in some "pure" forms of Agile, not all of those things would be considered "issues".  
  * Also note: "pure Agile" is contrary to the spirit of Agile.  
  * Agile values helping people getting stuff done over slavish devotion to processes or tools.
  

# Skunk Works? What's that?

Suppose you know you need a thing in your project, such as:

* User authentication
* Database access
* Testing of webapps with selenium
* Access to the Google Maps API
* Reading data from a CSV or JSON file (e.g. about Dogs, Recipies, Courses, etc.) into an ArrayList or HashMap of plain old Java Objects.

You can probably come up with many more ideas of "useful components" that:
* might now immediately deliver value for a user of your web app, but 
* you can plausibly make a case that they are useful things to learn how to do

These are examples of what you might develop in a "skunk works" project.

To develop a Skunk Works project:

* Put an issue into the issues list that describes it
* Ask your mentor to review it, and approve it (they may have suggestions for modificaitons before they say yes)
* Ask them to put a point estimate on it (100, 200 or 400 points)
* Then, create a public repo with this naming convention, under the organization <https://github.com/ucsb-cs56-m18>.  If the project is `dogwalker` and the issue number you are working on is `9`, use:
    * https://github.com/ucsb-cs56-m18/ucsb-cs56-dogwalker-sw9
    
Then BEFORE you start working, FORK that repo to one of your personal repos, and do your work THERE.  This allow you then later do a pull request, so there is something that your mentors, TAs and instructors can REVIEW.

# IDEAS of what to work on

* Setting up a basic navigation bar with placeholders for the features of your mininum viable product webapp
* Setting up a skunk works based on the rest-mlab demo for storing some basic object that relates to your project
* Setting up a form to enter data for your webapp 
* Working on sessions and authentication, either in a skunkworks, or in your main app.
TODO: Add more ideas here...
