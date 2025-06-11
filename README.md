# cmsc203-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [CMSC203 Assignment 4 Solved](https://mantutor.com/product/cmsc203-solved-9/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113909&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC203 Assignment 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
A property management company manages individual properties they will build to rent, and charges them a management fee as the percentages of the monthly rental amount. The properties cannot overlap each other, and each property must be within the limits of the management company’s plot. Write an application that lets the user create a management company and add the properties managed by the company to its list. Assume the maximum number of properties handled by the company is 5.

• Aggregation

• Passing object to method

• Array Structure

• Objects as elements of the Array

• Processing array elements

• Copy Constructor

• Junit testing

Data Element class – Property.java

The class Property will contain:

1. Instance variables for property name, city, rental amount, owner, and plot. Refer to JavaDoc for the data types of each instance variable.

2. toString method to represent a Property object.

3. Constructors and getter and setter methods. Refer to Javadoc of the Property class.

Data Element class – Plot.java

The class Plot will contain:

1. Instance variables to represent the x and y coordinates of the upper left corner of the location, and depth and width to represent the vertical and horizontal extents of the plot.

2. A toString method to represent a Plot object

3. Constructors, Refer to Javadoc for Plot class.

4. A method named overlaps that takes a Plot instance and determines if it is overlapped by the current plot.

5. A method named encompasses that takes a Plot instance and determines if the current plot contains it. Note that the determination should be inclusive, in other words, if an edge lies on the edge of the current plot, this is acceptable.

Data Structure – An Array of Property objects to hold the properties that the management company handles. This array will be declared as an attribute of the ManagementCompany class.

Data Manager class – ManagementCompany.java

It will contain instance variables of name, tax Id, management fee, MAX_PROPERTY (a constant set to 5) and an array named properties of Property objects of size MAX_PROPERTY, as well as two constants MGMT_WIDTH

and MGMT_DEPTH, both set to 10; an attribute plot of type Plot that defines the plot of the ManagementCompany Class. Refer to Javadoc for more details.

The class ManagementCompany will contain the following methods in addition to get and set methods: 1. Constructors (refer to Javadoc for more details)

2. Method addProperty (3 versions):

2.1.1. Pass in a parameter of type Property object (calls Property copy constructor). It will add the copy of the Property object to the properties array.

2.2. Method addProperty version 2:

2.2.1. Pass in four parameters of types:

• String propertyName,

• String city,

• double rent,

• String ownerName.

2.2.2. Calls Property 4-arg constructor.

2.3. Method addProperty version 3:

2.3.1. Pass in eight parameters of types:

• String propertyName,

• String city,

• double rent,

• String ownerName,

• int x,

• int y,

• int width

• int depth.

2.3.2. Calls Property 8-arg constructor.

2.4. addProperty methods will return the index of the array where the property is added. If there is a problem adding the property, this method will return -1 if the array is full, -2 if the property is null, -3 if the plot for the property is not encompassed by the management company plot, or -4 if the plot for the property overlaps any other property’s plot.

3. Method totalRent– Returns the total rent of the properties in the properties array.

4. Method maxRentPropertyIndex- returns the index of the property within the properties array that has the highest rent amount. This method will be private.

5. Method maxRentProp- Returns the highest rent amount of the property within the properties array. For simplicity assume that each “Property” object’s rent amount is different. This method should call the maxRentPropertyIndex method.

6. Method toString- returns information of ALL the properties within this management company by accessing the “Properties” array. The format is as following example:

List of the properties for Alliance, taxID: 1235

______________________________________________________

Property Name : Belmar

Located in Silver Spring

Belonging to:John Smith

Rent Amount: 1200.0

Property Name : Camden Lakeway

Located in Rockville

Belonging to:Ann Taylor

Rent Amount: 2450.0

Property Name : Hamptons

Located in Rockville

Belonging to:Rick Steves

Rent Amount: 1250.0

______________________________________________________

total management Fee: 294.0

Driver class – (provided)

The provided PropertyMgmDriverNoGui.java is a class that allows you to test the methods of ManagementCompany.java

GUI Driver class – (provided)

A Graphical User Interface (GUI) is provided. Be sure that the GUI will compile and run with your methods. The GUI will not compile if your methods in ManagementCompany.java are not exactly in the format specified.

Do not modify the GUI.

JUnit Test

Run the JUnit test file (provided). Ensure that the JUnit tests all succeed.

Do not modify the JUnit tests.

Implement your tests in ManagementCompanyTestSTUDENT. These tests should be similar to the

Junit tests.

Write a Data Element Class named Property that has fields to hold the property name, the city where the property is located, the rent amount, the owner’s name, and the Plot to be occupied by the property, along with getters and setters to access and set these fields. Write a parameterized constructor (i.e., takes values for the fields as parameters) and a copy constructor (takes a Property object as the parameter). Follow the Javadoc file provided.

A driver class is provided that creates rental properties to test the property manager. A Graphical User Interface is provided using JavaFX which duplicates this driver’s functionality. You are not required to read in any data, but the GUI will allow you to enter the property management company and each property by hand. A directory of images is provided. Be sure to place the “images” directory (provided) inside the “src” directory in Eclipse. The images do not need to display in order for the GUI to continue running.

Upload the initial files from Blackboard and your final java files to GitHub in your repo from Lab 1, in a directory named CMSC203_Assignment4.

Operation

When driver-driven application starts, a driver class (provided) creates a management company, creates rental properties, adds them to the property manager, and prints information about the properties using the property manager’s methods.

When the GUI-driven application starts (provided), a window is created as in the following screen shots which allows the user to enter applicable data and display the resulting property. The driver and the GUI will both use the same classes and methods for their operation.

The JUnit test class also tests the same classes as the driver and the GUI.

Expected output from running PropertyMgmDriverNoGui.java

Expected output from running with GUI:

PropertyMgmGui.java at startup

Add Management Co Info (Note Mgmt Co Plot)

Add property information – the Plot outline

Add property information – successful addition

Add property information – unsuccessful: overlaps

Add property information – unsuccessful: Mgmt Co Plot does not encompass Property Plot Note: red rectangle’s width extends to right of window.

Add property information – unsuccessful: too many properties

Result of “Max Rent” button Result of “Total Rent” button

Result of “List of Properties” button

• Turn in a UML class diagram in a Word document.

• Submit pseudo-code for the primary methods specified in ManagementCompany.java, Property.java, and Plot.java in a Word document. Do not just list what gets read in a printed out, but explain the algorithm being used.

• Learning Experience: highlight your lessons learned and learning experience from working on this project. o What have you learned? o What did you struggle with? o What will you do differently on your next project? o Include what parts of the project you were successful at, and what parts (if any) you were not successful at.

• GitHub: In your repository (see Lab 1), upload your Word file and java file. You will want to upload these files as contents of a directory so that future uploads can be kept separate. Take and submit a screen shot of the GitHub repository. Notes:

• Proper naming conventions: All constants, except 0 and 1, should be named. Constant names should be all upper-case, variable names should begin in lower case, but subsequent words should be in title case. Variable and method names should be descriptive of the role of the variable or method. Single letter names should be avoided.

Indentation: It must be consistent throughout the program and must reflect the control structure

Submission Detail

Submit the following files:

• Word document with a name FirstInitialLastName_Assignment3.docx should include:

o UML Class Diagram

o Pseudocode for each of the methods specified in ManagementCompany.java, Property.java, and Plot.java.

o Screen snapshots of the GUI with several properties o Screen snapshot of GitHub submission o Lessons Learned o Check List

o doc (a directory) containing your javadoc files o src (a directory) contains your (.java) files o File1.java (example)

<img draggable="false" role="img" class="emoji" alt="▪" src="https://s.w.org/images/core/emoji/15.1.0/svg/25aa.svg"> File2.java (example)

<img draggable="false" role="img" class="emoji" alt="▪" src="https://s.w.org/images/core/emoji/15.1.0/svg/25aa.svg"> File_Test.java (example)

• A zip file will only contain the .java files and will be named:

FirstInitialLastName_Assignment4_Moss.zip. This .zip will not have any folders in it – only .java files.

Grading Rubric

See attachment: CMSC203 Assignment 4 Rubric_Summer20.xlsx

Assignment 4 Check List

# Y/N Comments

1. Assignment files:

• FirstInitialLastName_ Assignment#_Moss.zip &lt;Yes or No&gt;

• FirstInitialLastName_Assignment#.docx/.pdf &lt;Yes or No&gt;

• Source java files &lt;Yes or No&gt;

2. Program compiles &lt;Yes or No&gt;

3. Program runs with desired outputs related to a Test Plan &lt;Yes or No&gt;

4. Documentation file:

• Comprehensive Test Plan &lt;Yes or No&gt;

• Screenshots for each Test case listed in the Test Plan &lt;Yes or No&gt;

• Screenshots of your GitHub account with submitted Assignment# (if required) &lt;Yes or No or N/A&gt;

• UML Diagram &lt;Yes or No &gt;

• Algorithms/Pseudocode &lt;Yes or No &gt;

• Flowchart (if required) &lt;Yes or No or N/A&gt;

• Lessons Learned &lt;Yes or No&gt;

• Checklist is completed and included in the Documentation &lt;Yes or No&gt;
