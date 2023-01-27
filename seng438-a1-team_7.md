>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group: Group Number      |
|--------------------------|
| Student 1: Carter Drewes |   
| Student 2: Michele Pham  |   
| Student 3: Farica Mago   |   
| Student 4: Samira Khan   |   


**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction

The goal of this lab is to explore and practice two different testing approaches that 
we will see later in industry. Before this lab we knew that exploratory testing was when the
application was explored with some knowledge of the testing requirements, and by humans in a team
choosing what to explore and to what extent. We also knew that manual testing was testing with a
specific set of test cases and functionality to verify. And that with manual testing you will miss
the same bugs each time the system is tested.

# High-level description of the exploratory testing plan

### Sub-team 1:
By using the use-case requirements we will explore the required functionality.
If a bug or an error is found the function will be explored further in hopes of finding 
further issues within broken functionality.

### Sub-team 2:
Another approach to exploratory testing is to test each function in the order they appear on each 
window and manually look for bugs or faults that does not logically make sense. 
Once a suspected bug is found, the function is used again to ensure that the bug still exits.

# Comparison of exploratory and manual functional testing

Most of the bugs we found were discovered during exploratory testing, there were only a small handful
of new bugs found once we move onto manual testing. As well, some more complex bugs we found during 
exploratory testing would have been missed with just manual testing. For example, the wrong withdraw
amount bug would have been missed, and instead the error we would have seen was incorrect verification
of number of bills in the machine. However, this bug is due to the mismatch between amount displayed
when selecting to withdraw, and the actual amount withdrawn.

# Notes and discussion of the peer reviews of defect reports

After all bugs have been reported, each member was given some time to look through all the bugs and review them. 
First, a similar format of each individual bug report must be he same for consistency. 
Then, for some bugs that certain members were unaware of, they could use the repro steps to see 
if they could find the bug again. If any bugs were re-reported, a member would inform the group 
via WhatsApp and other members would verify the duplication before the repeated bug was released. 
Overall, the team worked well together to ensure all work was up to standard.

# How the pair testing was managed and team work/effort was divided 

After partnering up, each pair created their own strategy on how to go through the application. 
Michele and Samira tested the program layer by layer. They examined if there were any errors 
within the first layer before moving onto the next. One partner went through the application 
while the other one checked if the program performed the expected functionality. 
Carter and Farica explored for bugs by using the use-case requirements we will explore the 
required functionality. If a bug or an error is found the function will be explored further in 
hopes of finding further issues within the broken functionality. Similar to the last pair, one 
person ran the application while another checked for its functionality. Both pairs had a designated 
member who added the bug report to DevOps.


# Difficulties encountered, challenges overcome, and lessons learned

A difficulty we first encountered was finding an efficient way of searching for bugs. 
Initially, each pair ran the program in an uncoordinated manner and searched for bugs without 
communicating properly with their team member. This led to a lot of missed bugs and wasted our 
time as we were unsure which parts of the application was tested and which parts weren't. 
Although each pair had a strategy planned out, there was not proper discussion on who would take 
on what role. To solve this problem, each pair divided the tasks and assigned themselves specific 
roles. This allowed the pairs to find bugs more easily and in a more organized fashion.


# Comments/feedback on the lab and lab document itself

This lab allowed the team to get comfortable with each other and understand each other's working 
styles. The lab itself was great practice and allowed students to understand the steps of bug 
identification and reporting as well as different testing methods. The group felt that the lab 
document was overcrowded with information and was hard to understand and identify clear 
instructions on what was expected to be done in for lab. In general, for the first lab, 
it went very well within the group, but for future labs, we hope lab documents are easier to 
read and understand.
