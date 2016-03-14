# SSDir
This project implements an online photo and contact information directory intended for small and medium sized churches. The information in the directory is similar to traditional church printed photo directories, e.g. photographs of members and families, and contact information. This directory is specifically <i>not</i> intended to provide a socal media site for the church. Small and medium sized churches do not typically have enough active online members to create a critical mass of social media content to make such a system viable. It was also clear from early discussion of requirements that church members did not want "yet another" social media site to which they would need to subscribe (see the History section below). So this project was developed to first and foremost replace the printed photo directory such as those commonly produced by various commercial photo processing companies. In addition, the online nature of the project leads naturally to a number of improvements over the printed directories such as always being up-to-date, interactive search, Google mapping, etc.

Some of the features of this directory system include:
<ul>
<li>Import and synchronization with PowerChurch church management system for membership and contact data.</li>
<li>Fully implemented security system with individual user IDs and passwords for each member, encrypted (SSL) communications, encrypted passwords, and encrypted storage of membership data. Users can request reset of forotten passwords without administrator intervention.
<li>A privacy model that allows members to hide (keep private) individual fields and photos.</li>
<li>A "self serve" concept for updating photos and contact information.</li>
<li>Members can upload their own photos, no need for professional photographers or formal potraits.</li>
<li>Search by last name, first name, and any another other contact information (e.g. street).</li>
<li>Photos are associated with individuals and families.</li>
<li>A unique "find-a-face" feature for quickly finding a familier face.</li>
<li>Individual details pages and family pages.
<li>E-mail based notification system.</li>
<li>Maintains list of church groups (e.g. committees, choir, classes) with multiple management styles.</li>
<li>One-click email to any group.</li>
<li>Google mapping of member address, and interactive mapping of church members by neighborhood or distance.</li>
<li>Administractive features for group management, PowerChurch sync, etc. Administrators can upload photos on behalf of any user and update user preferences.</li>
<li>Private groups ("My Circles") with private notes associated with each member.</li>
<li>Welcome page with list of new members, upcoming birthdays, etc.</li>
<li>Automatic 'welcome' email with user ID and passwords sent to new members.</li>
<li>"Canary" system to detect hacking or inappropriate use of directory contact information.</li>
<li>A "limited access" mode for initial startup period.</li>
<li>Neighborhood names automatically obtained from Google maps.</li>
<li>Defaults that protect child and youth contact information. Parents can choose what, if any, information on children/youth is visible to other members. Parents can maintain control of youth profiles, or choose to let the youth manage their own. Information on children is always managed by the parents.</li>
<li>Terms and Conditions acknowledgement for new users.</li>
<li>Online help (FAQ) system.</li>
<li>Activity log (administrator access only) to track usage.</li>
<li>Easy deployment into Amazon Web Services (AWS).</li>
<li>Based on modern, well known web programming technolgoies including HTML-5, Tomcat web server, and Servlets.</li>
</ul>

![alt tag](https://github.com/mark222/SSDir/raw/master/readme-images/ssdir-logon.jpg "Directory Logon Page")

# History of SSDir
Initial development of this project was done by Mark McMillan for [Soapstone United Methodist Church](http://www.soapstoneumc.org) in Raleigh NC starting in October of 2014. The system was opened to church members in July of 2015 and has been in continuous use since then. In 2014 the church's photo directory was several years old and the lack of up-to-date contact information was a barrier to communicaitons within the church community. It was agreed that the membership did not want to engage a commercial photogapher to "upsell" portraits in exchange for a free or low-cost printed directory. It was sugged that an online solution would better serve the members and general needs of the church for accurate contact information.

This directory was created after an extensive search was conducted by the church Technology Committee. A set of requirements was created with input from church staff, leadership, and members. Those requirements were matched against the then-available direcotry systems (both commercial and free/open source). For various reasons, none of the solutions available at that time could satisfiy the "must-have" requirements. Many of the directory systems were morphing into social media sites, something our membership specifically did not want (not only was it felt there would not be enough content contributed by the members for it to be truely useful, members did not want "yet another" site with blogs, followers, subscribers, friends, posts, chats, etc.). Some of the solutions had no ability to synchornize with the church management system (PowerChurch) and dual data entry/maintence was not an option. Other solutions did not have any current development or clear path for future support.

It was always intended that this project become open source for two reasons, (1) to freely share the significant amount of work that was done with other churches, and (2) in the hope that other developers would contribute new features and bug fixes to spread out the support effort and insure a continuation of the project without dependence on the original developer. Some effort was made into making the system independent of the particular church it was developed for so that it could easily be deployed for any church. 
