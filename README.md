## The goal
Many students who leave a college show signs of struggling in their first few weeks, long before a final grade appears. This project asks whether a student's early activity in their online courses, combined with basic background information, can help identify who may need support by week four of a course, early enough for an advisor or coach to reach out. It also checks whether the model works equally well for different groups of students, so that early outreach doesn't miss the students who need it most.

This project builds a simple early-warning model using the Open University Learning Analytics Dataset. The goal is to support people and point to students who might benefit from a check-in, and assist advisors to decide who needs the most support. 
## Data 
Open University Learning Analytics Dataset (OULAD), about 32000 students across 7 courses (2013-2014).
Download: https://archive.ics.uci.edu/dataset/349/open+university+learning+analytics+dataset
Citation: Kuzilek, J., Hlosta, M., & Zdrahal, Z. (2017). Open University Learning Analytics dataset. Scientific Data, 4, 170171.
## Status 
In progress
## notes
Each row is a student-course enrollment. Train and test sets are split by student, so no student appears in both.
About 31% of enrollments ended in withdrawal, much higher than at a residential university like JMU (about 3%), so results may not transfer directly.