# Final Project Proposal


Website Advertising Student Employment Opportunities.


## Problem / Question

Applications are ultimately just tools. What problem or question does
your application attempt to resolve or grapple with? How does your
application speak to this problem/question?

The purpose of this project is to make it easier for PennDesign students to find job
and internship opportunities that match the seeker’s experience, interest, and location
without having to sift through e-mails sent out over a period of months.

## The data

Geospatial applications are all about working with data. What datasets
would you plan/like to use? If the data you'll be working with isn't
already stored in a way that you can use, how will you be storing your data?

The website will use a dataset that is based off of the e-mails sent out to students in the
Spring semester of 2016.

## Technologies used

Which technologies covered in class (or discovered on your own!) do you
plan to use? How do you anticipate using each of these technologies?  

------------Review the APIs/online examples of leaflet, turf, jQuery, underscore (or
any library not explicitly covered in class) for functions/uses which
you'd like to explore. Briefly describe how you might use them.

------------ Webmap will allow PennDesign students to search for work opportunities by their concentration in their respective program, level of experience, and locational preferences. The following languages, libraries, and APIs will be used to display the user's preferences on a webmap: CartoDB, HTML, jQuery,
JavaScript, CSS.

            -----HTML: The skeleton of the website will be coded in HTML. It will provide the initial positions of the webpage's content including, but not limited to, the map, sidebar, text, title, button, dropdown menus, and checkboxes.

                          CSS: The styles of the text, map layers, map markers, and other visual components presented on the webmap will be defined by CSS.  

                          CartoDB: The employment information will be gathered from e-mails, manually inputted into an excel file, and imported as a dataset into CartoDB. The dataset will include the following fields:

                          Post_Date
                          Firm_Name
                          Job_Title
                          Description
                          Category
                          Paid
                          Job_Type
                          Contact_Name
                          Contact_email
                          Source1
                          Source2
                          Source3
                          Firm_Website
                          City
                          State
                          Country
                          Contact_Phone
                          Start_Date
                          AppDeadline
                          Experience
                          Salary
                          Hour/Year
                          US_Citizen_Required``

                          The dataset will be geocoded on CartoDB based on the City and State fields and then converted into a JSON file.

------------JavaScript: JavaScript language and a few of its libraries (jQuery, Underscore.js, Leaflet) will be applied to the HTML document in order for users to interact with the webpage's features.


------------jQuery: The dataset in the form of a JSON link will pulled by way of jQuery in order to be displayed on the webpage. jQuery will also be used to register behaviors that take effect when the user interacts with the browser. One example of such an interaction is when a user will filter employment opportunities by concentration from a dropdown menu. Another example would be inputting job data into a database

------------ Underscore.js: I will try to simplify the JavaScript functions written to process users' interactions using the Underscore library.

------------ Leaflet: All related webmap functionalities will use the Leaflet library. It will display the job opportunities throughout the country and sometimes the world.

## Design spec

#### User experience

At a high level, how do you expect people to use your application?
- Who are the users?
------------PennDesign students, PennDesign staff, Employers
- What do they gain from your application' use?
------------PennDesign students will be able to filter out all the jobs that do not fit
- Are there any website/application examples in the wild to which you can compare your final?
------------www.planningjobs.berkeley.com will provide how to set and display up the input job page and ideas of what should be displayed on the homepage                   and list views as opposed to map views.

#### Layouts and visual design

So far, we've built all our applications with a side bar for
representing non-map content and navigation. This is not the only
successful design. Extra content could be displayed in a top bar,
through modals, through side bars on both sides, and any combination of
these as well as a number not mentioned. Try to describe your
application's visual layout. Conceptually (no need for extensive CSS
here), what will this design require?

------------The website will have headers that include the Homepage, Job Seekers, Employers, About Me?? -option feedback, about the site that will essentially be everything that is talked about here, but more eloquently.
------------Homepage:
                Header: Homepage, Job Seekers, Employer, Resume Posts, About Me?
                Right Sidebar:
                      R side specific links to jobs by with the
                            h1 Concentration like h3 GIS, Transportation etc
                            h1 jobs h3 by major GIS, Transportation etc
                            When  
                        Search button: when clicked map will expand toward the left and covering the left sidebar
                Left Sidebar:
                      Dropdown: Locations
                          Options: city, state

                      Dropdown: Degree Related jobs
                      Dropdown: Concentrations
                      *Experience

                      (search bar that kind find the salary?)
                      Search button: when clicked map will expand toward the right and covering the right Sidebar



                Map center: Map View can cover more of the page by expanding out to after  


                Disclaimer that not all job posts do not include salary options etc
                Map center: Map View can cover more of the page by expanding out to  

------------Sidebar might change between the search options and job information when a marker is clicked on


## Anticipated difficulties

Thinking about weaknesses can be useful. What do you anticipate being
most difficult about this project? How will you attempt to cope with
these difficulties? For example, asynchronous behavior (ajax, events)
are hard to use and think about. Global variables are a strategy for
coping with that difficulty by breaking data out of the asynchronous
context.

------------Weaknesses:
                Calling the data based on user parameters and projecting it on the map
                Input field updating database??



## Missing pieces

We've only managed to scratch the surface of the available technologies
by which you could construct an application. What use-cases haven't we covered
that you think would be useful? What technologies not covered seem exciting to
you (you don't necessarily have to fully understand what they're for,
this is a chance for you to get our help interpreting a technology's
purpose/usage).

## Missing pieces
      Learning about the variety components of CartoDB
