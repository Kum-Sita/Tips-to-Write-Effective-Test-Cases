# Tips-to-Write-Effective-Test-Cases

A strong title, an engaging description, a set of assumptions, and anticipated outcomes are all essential components of a successful test case.

Test cases can be written in a variety of positive and negative ways, but it is essential that they cover all business and functional requirements.

Guidelines for creating quality test cases

* Create test cases with the end user in mind.

* Define the scope and goal of the testing. Determine the testable requirements.

* Domain expertise: A thorough understanding of the requirements is crucial. The quality suffers as a result of incomplete information expanding the potential risks.

* Avoid Making Assumptions: Making assumptions about the features and functionality of a software application could lead to a mismatch between the client's requirements and the finished product, which could hurt the client's business. Follow the specification documents exactly instead. Stick to the scope and specification. A SRS (Software Requirement Specification) document is always better.

* To achieve 100% test coverage, test cases must be written for all software requirements mentioned in the specification document. This will enable the requirement traceability matrix to pinpoint the functions and conditions that weren't tested.

* Updating test cases in accordance with recently introduced changes in the requirements is always a good practice. It is best to update the SRS for major and minor changes.

<image src="Traceability Matrix.avif">

* Take test cases into account based on priorities and risks(high/low). Prioritize test cases

* Attachments to Associated Artifacts

* Avoid repetition whenever possible; test automation (relying on automation), which minimizes manual work and improves the product, makes this easier.

* Use a test management tool to keep track of test cases.

* Test cases should be concise and simple to understand. Be granular while writing down the steps for execution

* Keep in mind the 80/20 rule. The idea behind sanity and smoke tests is that 20% of our tests will cover 80% of our application. Even a brief scenario can help us find a sizable portion of our bugs.

* The length should be just right. It should be possible for test suits to finish a significant portion of the system in between 45 and 90 minutes. 

* Use standard naming practices and a professional format.

* Keep descriptions brief. It's essential to keep the description brief, uncomplicated, and instructive. Nobody enjoys reading lengthy stories. For the record. It wasted developer time in addition to QA time!

* A user's persona: Create various user personas that each represent a group of your intended audience and their profession in order to write test cases that will effectively cover each of their individual aspects.

* Monitor all the test cases and take ownership of test cases. 

* Keep dependent test cases in mind and aiming for exploratory testing. 

* Be intent specific- A requirement known as acceptance criteria checks to see if the software is performing as expected by the end user. Acceptance criteria are intended to help the end-user's intent rather than aid in the evaluation of the steps.

* Cross browser testing can help minimize outages

* Non-functional requirements should be noted

<image src="Non-func-req.avif">





# Basic terminologies used while writing a Test Case



* Test Case ID:         Case_01, TC_

* Test Case Description:         Description of the test case

* Type (Positive / Negative):         Positive test case / negative test case

* Scenario:         for which scenario this case is being tested

* Test Data:         what input data has been taken for this test case

* Pre – Condition:         Condition before running this test case,

* Action / Steps for execution for this test case:         Steps for executing this test case

* Expected Result:         Based on the points mentioned above, the expected result can be mentioned here.

* Actual Result:         This will be filled during the actual execution of the test case.

* Comments:         Any kind of observation will be mentioned here








# How to write test cases in Jira?



**Step 1: Create Project**

Go to the Home Screen—> Projects—> Create Project

Project Name:  Choose any project name. 

Template: Choose “Bug Tracking” also called as “Basic Software Development”. Do not keep it default.
<image src="JIRA TC.avif">



**Step 2: Add Preconditions**

Keep it short and explaining. Mention the other details like priority, status, assignee, version, etc.

<image src="step-2-JIRA.avif">



**Step 3: Insert Test Data and Mention Expected Result**

Properly reference the test scenario in order to create an efficient test case. Mention the input data and the anticipated outcome. Describe the situation that results in the error.

<image src="step-3-JIRA.avif">



**Step 4: Add the attachment**

The document must include all errors as well as information about the environments and tool versions that were employed. Additionally, avoid using repeating bugs to prevent confusion in the future.

<image src="step-4-JIRA.avif">



# How to write test cases in Excel?



**Step 1: Build a Test case Repository**

Include the fundamental information, including the Project Name, Prepared By (Tester's Name), Prepared for (Developer's Name), Document Purpose, Application Type, Date, and Version.

**Step 2: Create a Test Case Matrix**

It will include information about the module and how many test cases there are. Additionally, you must add the status, which can be Pass, Fail, or Not Tested.


**Step 3: Make a Detailed Sheet**

This sheet will include the Test Case ID, Description, Precondition, Test Data, and Test Steps. Include both the expected and actual outputs as well.

Including two columns: one for QA feedback and one for developer feedback
