<!-- 
 * Licensed to The Apereo Foundation under one or more contributor license
 * agreements. See the NOTICE file distributed with this work for
 * additional information regarding copyright ownership.
 *
 * The Apereo Foundation licenses this file to you under the Apache License,
 * Version 2.0 (the "License"); you may not use this file except in
 * compliance with the License. You may obtain a copy of the License at:
 *
 * http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 *
 * See the License for the specific language governing permissions and
 * limitations under the License.
 * 
 -->
# Team members
- Mootaz Medhat Ezzat Abdelwahab (20206074)
- Yousef Essam Aboelyazed Esmail (20206163)
- Abdulrahman Ashraf Elmahdy     (20186012)
- Amro Adel Farid                (20206145)

# Comprehensive University Timetabling System (UniTime)
UniTime is a comprehensive educational scheduling system that supports developing course and exam timetables, managing changes to these timetables, sharing rooms with other events, and scheduling students to individual classes. It is a distributed system that allows multiple university and departmental schedule managers to coordinate efforts to build and modify a schedule that meets their diverse organizational needs while allowing for minimization of student course conflicts. It can be used alone to create and maintain a school's schedule of classes and/or exams, or interfaced with an existing student information system.
### System Domain:
- Scheduling.
- Education.
### Main Features: 
- Event Management.
- Course Management.
- Student Scheduling.
- Course Timetabling.
- Examination Timetabling.
### System Type and Licenses:
- The system was originally developed as a collaborative effort by faculty, students, and staff at universities in North America and Europe. 
- The software is distributed free under an open source license in hopes that other colleges and universities can benefit their students.
- The UniTime project has become a sponsored project of the Apereo Foundation in March 2015.
### Supported Operating Systems: 
- Linux.
- Mac.
- Windows.
# System Comprehension
### Knowledge Kind
- software-specific knowledge:
  - Exception Handling.
  - Implementation Details.
  - Functional Requirements.
- During the process of system comprehension, we found that we need to have more general knowledge about the system (i.e., what the system does, system main features,   system domain, system type and licenses).
### Comprehension Goal
- Collecting more information about the source code itself to help in refactoring and bugs trouble-shooting.
### Comprehension Scope
- partial understanding of source code.
### Comprehension Approach
- The system comprehension process can work in three Approaches:
  - Top-Down:
    In this approach, the programmer first identifies the goals of the program, followed by possible implementations of those goals such that the implementations match     against the code.
  - Bottom-Up:
    In this approach, the programmer first identifies program plans from source code, makes annotations, and moves up to the top, goal layer.
  - Opportunistic (that we used in system comprehension process):
    In this approach, we have been able to combine the above two approaches to take best advantage of whatever opportunity is available to make best progress in terms     of knowledge gain at any given time.
- We started with top-down to gain an overview of the functions of the program. Then selectively applied bottom-up strategies when nearing “code level” to verify       
  hypotheses resulting from top-down reading.
# Tutorials
- [Installation Instructions][install]
- [Building UniTime][build]
- [Setting up UniTime in Eclipse][eclipse]
- [Customization][customization]
- [Localization][localization]
# Links
- [Unitime.org][unitime]
- [Pereo Foundation][pereo]
- [University Timetabling Code][timetablingcode]


[install]: https://help.unitime.org/installation
[build]: https://help.unitime.org/building-unitime
[eclipse]: https://help.unitime.org/eclipse
[customization]: https://help.unitime.org/customizations
[localization]: https://help.unitime.org/localization
[unitime]: https://www.unitime.org/
[pereo]: https://www.apereo.org/
[timetablingcode]: https://sourceforge.net/p/unitime/code/ci/master/tree/JavaSource/org/unitime/timetable/
