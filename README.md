# <img src="https://raw.githubusercontent.com/SCIENCE-RESEARCH-ACTIVITY-SUPPORT-SRASS/.github/main/profile/asset/logo.png" width="80" height="50" style="border-radius: 10%"/> Science Research Activity Support System (SRASS)​ - Capstone Project

## Welcome to our Graduation Capstone Project

> During the process of composing this dissertation, we have been the fortunate recipients of abundant support and guidance.
>
> First and foremost, we express our deep gratitude to our dedicated supervisor, Mr. Kieu Trong Khanh. Mr. Khanh's invaluable role in introducing us to this project idea and connecting us with the resources of FPT University, Ho Chi Minh Campus's Library and Research Department has been instrumental. His insightful feedback challenged us to refine our ideas and elevate our work, and for this, we are immensely thankful for his unwavering support and encouragement throughout this journey.
>
>Additionally, we extend our appreciation to Dr. Dang Ngoc Minh Duc and Mr. Dinh Truong Lam for their vital assistance with the necessary business requirements. Their generous time spent reviewing and providing feedback and innovative ideas to improve our system has been invaluable to our project's success.
>
>We also wish to express our heartfelt thanks to the diligent reviewers whose insightful criticism enabled us to identify and address our project's weaknesses, ultimately leading to the presentation of optimal solutions. We are equally grateful to FPT University for providing us with this outstanding opportunity.
>
>Lastly, we acknowledge and appreciate our own dedication and collaboration in completing this project. We thank ourselves for being a steadfast presence as we worked together to create the Science Research Activity Support System.

## Table of Contents
- [Description](#description)
- [Live Demo](#live-demo)
- [Technology](#technology)
- [Requirements](#requirements)
- [Useful Resources](#useful-resources)
- [Contributors](#contributors)
- [References](#references)
- [License & Copyright](#license--copyright)

## Description
The Science Research Activity Support System (SRASS) was designed to meet the specific requirements of the FPT University, Ho Chi Minh Campus's Library and Research Department. Its primary purpose is to simplify the process of managing scientific conferences, with the initial deployment taking place at the HCM Campus. The basic idea behind this project is to establish a system to support conference management activities and coordinate activities of conference attendees: PC chairs, authors, and reviewers, from the initial phase when the individual accountable for managing a conference receives the approved conference plan up to the end of the conference.

For over two decades, FPT Education has been on a transformative journey, guided by a steadfast vision known as iGSM (Industry-Relevant - Global - Smart Education - Mega). This vision is firmly grounded in the aspiration to become an internationally recognized mega-education system that aligns with societal demands and harnesses state-of-the-art educational technologies. With a history marked by growth and innovation, FPT Education has established itself as a pioneer in the field of education.
At the heart of FPT Education, FPT University plays a pivotal role by organizing numerous annual academic initiatives to promote research and innovation. However, as scientific conferences evolve to enhance research and innovation, FPT University encounters challenges in optimizing the management process. Currently, this process encompasses the following sequential activities:
1.	Input Conference Plan 
2.	Configure Conference Preferences 
3.	Initiate a Call for Research Papers 
4.	Appoint Paper Reviewers 
5.	Finalize Paper Decisions 
6.	Communicate Decision Results 
7.	Request for Camera Readies 
8.	Request Presentation Materials 
9.	Produce Reports

This is a sophisticated process. Furthermore, this process largely depends on the experience of the person responsible for managing these conferences to run smoothly. This would impose a restriction on the effectiveness of the standard procedures.


## Live Demo
 👨‍💻 [Live Demo Here](https://www.youtube.com/watch?v=Cvmue92NwxE)
  
## Technology
**1. Frontend**
  - React JS
  - Material UI
  - Redux Tool Kit
  - RTK Query

**2. Backend**
  - C# (.NET Core 7.0)

**3. Database**
  - Microsoft SQL Server - a relational model database server produced by Microsoft

**4. Other Technologies**
- Firebase Storage
- Web socket
- Payment service - PayPal
- Azure App Service
- Azure SQL Database
- Vercel 

**5. Tool**
  - Visual Studio Code
  - Visual Studio 
  - Figma
  - Swagger API Documentation
  - StarUML, DrawIO, Lucidchart for Diagram
  - Microsoft SQL Server Management Studio 18 | DataGrip
  - Microsoft Office, Google Docs/Sheets
  - GitHub (Source Codes), GitKraken (Source Codes), Google Drive (Documents)

## Requirements
**1. Unauthenticated user:**
An unauthenticated user is a person who has not logged in the SRASS. An unauthenticated user has limited permission to some functions, only:
+ Sign up
+ Login


**2. Authenticated user:**
An authenticated user is a person who has logged in to the SRASS. An authenticated user has permission with the following functions:
+ Get conference list
+ Get action reminder message
+ Logout

**3. Admin:**
An admin is an authenticated user who has the authority to initialize a conference based on the conference plan. An admin has permission with the following functions:
+ Initialize conference
+ Create a conference's website content
+ Export a conference website's content
+ Export conference reports

**4. PC chair:**
A PC chair is an authenticated user who has the authority to monitor and manage the conference from the initial phase up to the end of the conference. A PC chair has permission with the following functions:
+ Acquire conference summary
+ Modify a conference's track list
+ Create a track plan
+ Update a track's activity timeline
+ Adjust conference general settings (is the PC chair is a chair)
+ Adjust track settings
+ Get list of conference users
+ Define a track's subject area list
+ Call for papers
+ Submit a conference paper
+ Aggregate list of conference submissions
+ Make statistical information about conference submissions
+ View a submission summary
+ Desk check a submission
+ Invite a reviewer
+ View the reviewer invitation list
+ Get list of recommended reviewers for a submission
+ Assign reviewers to submission evaluation
+ View aggregation reviews of a submission
+ Decide on paper
+ Set up email templates
+ Notify result to authors
+ Request for camera ready submission
+ View order
+ Aggregate list of conference manuscripts
+ Make statistical information about conference manuscripts
+ Request for presentation submission
+ Track essential activities and tasks
+ Export conference reports

**5. Author:**
An author is an authenticated user who wants or has submitted papers to a conference. An author has permission with the following functions:
+ Submit a conference paper
+ Declare submission conflicts of interest
+ Submit supplementary materials
+ Get the list of author submissions
+ View a submission summary
+ Upload revision
+ Upload camera-ready
+ Register an author's qualified papers
+ View order
+ Get an author's list of registered papers
+ Upload presentation


**6. Reviewer:**
A reviewer is an authenticated user who joins a conference as a reviewer to evaluate assigned submissions. A reviewer has permission with the following functions: 
+ Specifying reviewing information
+ Get list submission assigned to reviewer
+ Enter review
+ Declare reviewer conflicts of interest

**7. Research lecturer:**
A research lecturer is an authenticated user who has registered the email of the domain "fe.edu.vn". A research lecturer has
permission with the following functions:
+ Input research profile information
+ View the research profile

**8. System handler:**
A system handler is a system actor that performs some system's special tasks. These tasks include:
+ Update automatically conference progress over time
+ Detect submission conflicts of interest
+ Detect reviewer conflicts of interest
+ Detect potential review issues of conferences

## Useful Resources
#| #| Name | Description
-| -| ---- | -----------
1| -| Main Project Folder | Main source code
-| 1.1| [Front-end](https://github.com/Hien-BT01/capstone-client) | Front-end source code (Private)
-| 1.2| [Back-end](https://github.com/ThuongHoang456189/Sras.PublicCoreflow) | Back-end source code (Private)
2| -| Database | Database Information
-| 2.1| [Database Entity Relationship Diagram](/DatabaseScript) | Database ERD
3| -| [Document Folder](/Report) | Final Document
4| -| [Test Report](/SU23SE08_Test_Report.xlsx) | Test Report
5| -| [Slide](/Presentation%20Slide) | Final Presentation Slide
6| -| [Diagram Image](/Diagram) | Diagram Image
7| -| [ScreenFlow](/ScreenFlow) | Diagram Image

## Contributors
**1. Supervisor:**
- Lecturer - Mentor: **Kieu Trong Khanh**
- Enterprise: **FPT University, Ho Chi Minh Campus's Research Department**

**2. Members:**
- [Hoang THi Hoai Thuong](https://github.com/ThuongHoang456189) - SE140087 - **Team Leader | Back-end Developer | Database Designer | Business Analyst**
- [Mai Hoang Duong](https://github.com/HoangDuong1106) - 	SE140196 - **Back-end Lead | Back-end Developer | Database Designer**
- [Bui The Hien](https://github.com/Hien-BT01) - SE150763 - **Front-end Lead | Front-end Developer | Tester**
- [Nguyen Dang Truong Anh](https://github.com/peterndta) - SE150640 - **UI Designer | Front-end Developer | Tester**

## References


## License & Copyright
***All ideas, content, images, and related documents are owned by the SRASS Team and FPT University, Ho Chi Minh Campus's Research Department.***

***This presentation is protected by Vietnam and International Copyright laws. Reproduction, distribution, display and use of the presentation without written permission of the owner is prohibited.***

&copy; 2023 SRASS-Team
