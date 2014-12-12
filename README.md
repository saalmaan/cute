##History:
At this day an age we have very sophisticated Frontend User interface tools, these tools give us (UI developers) magical powers to develop highly complex tools and scaleable apps/systems. Typically during production grade UI development we use these automated scripts and programs to check code quality, find inconsistent UI, unmaintainable and poorly performing code, compressing the code etc.

Historically UX designers have been preparing detailed specs and after project implementation these documents are archived. During the life cycles of a big project user interface can starts to deviate from its original proposed spec. Like UI developers UX designers can be forgiving (less strict) sometimes and bad inconsistent design makes its way into the project. On large scale projects this can become a big issue and overtime project UX can get out of hand.

Most organisations don't really have the enough resources to keep an eye on old projects, under resources teams are then under pressure to work on new projects leaving old projects in the hands of UI Developers :(

Surely this has to change and there should be a solution?
 
##Proposal:
I would like to put forward a proposal to solve above problem that would elevate most of the problems we face with UX testing.

----------------------- _Introducing_ -----------------------
         *CUTE (Continuous Automated UX Testing)*
-------------------------------------------------------------

We will develop set of tools that will run automatically every time a developer commits code to the main repository. These tools will test the code against UX specs (format to be defined). Also these tools should be made available to UX team to further investigate any page(s) of the website for problems. Here is a quick summary of the Tools/Library we should build as minimum.

1. Check which colours are being used in the CSS/HTML against colours defined in UX specs
2. Check all button and links on the page are touch friendly  (height/width >= 44px) etc
3. Form validations
4. Responsive layout validation
5. Margins and padding validation
6. Font family and font size check
7. Broken links checker

> These tools are and will not be an alternative to functional tests rather a way to validate/enforce UX principles during UI development.

###First steps:
As a first step I have already stated to write individual scripts that will act as building blocks for this library. 

But here are few things we should do during this process

* Make these tools Compatible with Grunt, Gulp and other build process managers
* Expose an API
* Open Source the tools
* Test todomvc UX
* Integrate test/build results with GA
* Add bootstrap UX profile

###Future:
In future we should create a generic ux auditing customer facing website for people to test their sties against our tools.

##More Tools:
Also I would like you guys to think about following tools, how we can use and build them to help us get deeper insight into our customers

###User research Tools:
1. ToH (Tower of Hanoi) UX design sorting Tool
2. Flip Test
3. Blur Test
4. Black & White Test
5. Interest Graph based on first 5 clicks of page content (via GA)
6. Who am I? Test
7. Memory Test


Please feel free to post your comments & suggestions.
