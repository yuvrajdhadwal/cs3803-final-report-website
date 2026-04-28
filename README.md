# cs3803-final-report-website

INTRODUCTION 

MARTA is Metro Atlanta’s biggest public transit option. Since 1972 it has been servicing the city of Atlanta later moving into deeper suburbs as urban sprawl increased. 2006 saw the introduction of the breeze card system. A centralized way for riders to acquire funds for their busses and train rides, with vending machines able to take in cash and cards in exchange for the breeze of cards. This allowed riders from all community's access to essential transit options.  

Along with the emersion of the system came a web application called breezecard.com. This website provides online services for the bare bone needs of riders and institutions. Suddenly riders could add funds to their card without having to travel to a rail station and deal with often faulty vending machines. The folly of the system was the lack of maintenance. Since the website worked and did its job, there was a low priority in its update.   

This seemed to last almost two decades. Early 2026 we stumbled upon the breeze card website. Its appearance has not changed since 2016. Changes in container placement, information visibility and functionality accessibility needed to be addressed. Users of the breeze card website ranged from all ages and backgrounds, allowing accessibility for users that may not be able to easily access or use the vending machines.  We believe we were able to address these core issues along with others that came up during our usability testing.  

 

METHADOLOGY 

To test the usability of existing Breeze Card website, we conducted usability testing with five participants who had prior experience using MARTA’s transit system. Participants were recruited to reflect a range of familiarity with the website to capture first impression and reengagement experiences. Tests were conducted both in-person and virtually, with all interactions recorded via Microsoft Teams to allow for reviewing and analysis. 

Prior to testing, participants completed a pre-test questionnaire to establish a baseline context. This questionnaire captured how frequently each participant uses MARTA, their typical ticketing method, whether they had previously visited the Breeze Card website, and whether the current payment system had every discouraged them from using MARTA. These responses helped contextualize individual performance and discover any prior familiarity that might influence task completion.  

After pre-task questionnaires, each participant was asked to complete eight tasks representative of common user experiences on the Breeze Card website. These tasks ranged from checking an existing card balance and expiration date, to find a route map, adding funds to a card, bulk ordering cards for a group, purchasing a replacement card, and discover program-specific information such as the University Pass Program and the MARTA Partnership Program. Finally, locate instructions for using a vending machine to reload a card balance. Throughout testing, two primary metrics were tracked: the time taken to complete each task and the number of errors encountered during each task.  	Participants were asked post-task questionnaires after their completion of all tasks. They responded to nine questions. This gathered qualitative impressions of the overall experience, asking them to reflect on which tasks felt the most challenging, most intuitive, or most time consuming. Post-questionnaires also ask for their view of the website’s layout, standout features, potentially unnecessary features, and likelihood of future use.  

 

 

FINDINGS AND ANALYSIS 

FINDINGS 

The usability test with five participants showed several critical issues with the Breeze Card website. The most significant problem was the bulk ordering feature, which required users to log in to a separate account without any clear indication beforehand. Four out of five participants encountered this difficulty during their bulk ordering task. Two participants reported that this task was the most frustrating task. One of the participants shared that “Needing to have another account for this functionality is not reasonable.” 

A second critical issue was the difficulty to locate specific information on the website. Tasks such as finding the University Pass Program details and the Perimeter Center Partnership sign up required participants to navigate through multiple layers of menus and pages as the buttons for this information were too small to intuitively spot them. One of the participants said, “The hardest task was the partnership because at first, I didn’t see it, so I searched it up, and it brought me to another website that would need to be forwarded to another website. In the Breeze card website, it doesn’t let you download the file.” Even after navigating to the detailed information page, the instructions were not very clear. Task 7’s completion time ranged from 10 seconds to 164 seconds, meaning that success depended heavily on chance navigation rather than clear information architecture. 

The process of adding funds and purchasing a new card also revealed to be more complicated than expected. Task 3, adding $10 to a card had the highest average completion time of all tasks at around 152 seconds, and two participants required over 240 seconds. Two participants reported that this task was the most frustrating task. One of the participants reported to the hardest task, “Task 3 because the login feature failed and was unable to reload my card. Additionally, there was no specific indicator for reloading a card. The purchase card was the only indicator and that alone was very vague.” Even with task 5, purchasing a replacement card, while quick on average, one participant had an error.  

All of the participants commented on the website’s outdated visual design and interface. The dense blocks of text, small text, and navigation menus that did not account for modern web conventions, making it difficult to glance at pages quickly or locate buttons. One of the participants shared that “layout is old and hard to figure out where things are.” Some of the usability difficulties discussed previously were due to the UI issue. 

These findings point to four main usability issues: a broken bulk ordering flow that requires secondary login, poor information architecture to navigate, a complex card purchasing and reloading process, and an outdated UI that discourages user’s navigating skill. We aimed to directly address these issues in our new design.  

 

 

 

 

ANALYSIS 

One of the major issues with the breeze card website was bulk ordering. As seen in both Figure (BLANK) and Figure (BLANK), 33% of the most frustration was in task 4 as well as 57% of the errors. Having an entirely different login to bulk order was as one of the users put “not reasonable”. To fix this issue, we merged the 2 accounts, connecting the breeze card to the user, and when they were to sign in, they can see all the information about the card such as Balance, Remaining Trips, Remaining passes, and Expiration Date. Because in the initial website design, the purchasing of group orders was separate from buying for individuals, which led to a lot of confusion on the users' side, we decided to make it easier by merging the individual purchasing and the group purchasing. 

As seen in the findings previously, an issue that we needed to address was the difficulty of finding specific information such as the University Pass Program details, and the Perimeter Center Partnership to sign up. A user was unable to find the partnership on the website, so they were forced to look it up online, which brought them to a different website from the breeze card website. One of the participants marked the task of trying to find information about the Programs as the hardest because once going into the purchase page it was not clear on how to leave it and go back to the home. To fix this problem, we decided to add a dedicated information section, and a tab that extends with all the information that a user would need. In Figure (Blank), you can see how the Information tab is extended with clear details on each tab, fixing the issue with the user unable to find it and trying to look up the information on another website.  

The outdated UI was a major eye sore to the users, which exacerbated the other technical issues the user had to deal with. All the participants commented on how the website had not been properly updated in a while, with small text, major amounts of unused space, as well as misleading buttons. We made a full overhaul to the website, with easier to follow flows and updated UI. As seen in Figure (BLANK), we have a new header with all the relevant information one would need, as well as larger text which uses the full screen instead of half the page being left blank.  

2 out of our 5 participants marked Task 3 as the hardest, as well as it having the largest average Time to completion compared to the other tasks. Only 2 of our participants were able to add 10 $ to their card in sub 100 second time, while 2 other participants had a time of nearly 3 minutes. This being one of the easier tasks was unacceptable because this would be a regular task that one needs to do to ride the bus. As a fix, we added the section in the header so that the user has a clear and easy button to click on to add money to their card. In addition to being able to add money in this section, they would also be able to buy passes and group orders, which fixes our other issue on separate logins. 

 

 

 

RECOMMENDATIONS 

All our recommendations branch off one main critique. The website, while being updated recently, still has the aesthetic of a 2005 website. The User Interface is clunky; the User Experience is unintuitive, and the backend is slow or simply unresponsive. The entire website requires a major overhaul, four aspects of which, we will recommend. 

Let’s start with the home page first.  

breezecard.com Home Page 

We added a border on this image to fully illustrate how much whitespace there is. This layout is clearly not designed for modern day monitors. The top bar is nonfunctional, if you look closely there is a home button, it doesn’t work. Instead, to go back to this page from any other page, the user must click on the Breeze Card Logo, which is transparent and hard to see as a result. Beyond these two obvious flaws, the home page is overwhelming with information. There is no ordered of buttons on the left in terms of popularity; (we highly suspect that the number of people reading the Terms and Conditions cannot be higher than the number of people looking to purchase a Breeze Card). We overhauled this home page to focus on showing users what they want. Most users, from our usability testing, mentioned that their main use-case for breezecard.com was to purchase funds or view their balance. Thus, we made these the center-piece of the website. All other information, can be easily accessible from the information tab. However, since most visits never go to those pages, there is no need to clutter the home page with endless options. Our design is pictured below. 

The image depicts a website page for Breeze, a service that allows users to purchase and manage public transportation cards for MARTA and other regional transit agencies. 

Moving on, to one of the main functionalities of breezecard.com: purchasing cards and refueling cards. 

The image shows a webpage interface for entering Breeze Card information, including a field for the card's serial number.

AI-generated content may be incorrect. 

Again, this page struggles from the display issues. The bigger problem here is that once a user is logged in, all the options are listed. There is no ordering or estimated total shown and it can get confusing to figure out what a user is purchasing. This is why we ensured that we categorized all purchases by type. The image is a screenshot of a user interface for a mobile app, likely for a public transportation service, showing options to add balance, review payments, and select various trip options.

AI-generated content may be incorrect. 

We have also made it easy, instead of selecting options such as 1 ticket, 2 tickets, 5 tickets, etc. Users can now have the freedom to select as many tickets, passes, or cash they’d like and prices are listed on the side and total estimated cost is listed below. Purchasing funds is now also a multi-step process. With a review section, a clear payment screen, and a receipt screen. This makes is abundantly clear to the user when they are shopping and when they are purchasing. The current system takes multiple days until purchases are registered to users, in a full website overhaul, we would also decrease the latency of this down to a few minutes. The infrastructure of this already exists in other mass transit systems and also with the refueling funds at the MARTA Station itself, there is no reason for a massive delay for online purchases. 

Another main use-case for breezecard.com would be an online way to check a user’s balance. Currently on the MARTA page, you need to log-in and then a single number with the amount of funds the user has is listed. This number is not very helpful unless broken down into trips and day passes. The image shows a Breeze Card purchase page with sections for user login, card information, and a note about postal service delays.

AI-generated content may be incorrect.	Thus we suggest to do that in our website overhaul shown below. 

The image displays a Manta account dashboard with a purchase confirmation, account balance, and various trip and pass details, including serial number, remaining trips, day passes, and an expiration date.

AI-generated content may be incorrect. 

So, we have discussed all the major pages on breezecard.com. To recap, that would be the home page, the balance page, and the purchase page. However, a non-insignificant poriton of users also mention using this website to scroll through all its information about MARTA services. In the home page, we suggested pigeonholing all this information elsewhere since most users do not need this information. We believe that good UI/UX design requires giving the user exactly what they are looking for and nothing more. This is why we chose to take all the information off the home page, since most users do not have a desire for that. The same logic applies for our information page. Rather than giving a laundry list of every single page and policy on MARTA, we choose to employ drop down menus and intuitive categorization of topics. This way, while it may take more clicks to get to a specific page (Example: Home Page à Information Page à Pass Programs à University Pass Programs vs. Home Page à University Pass Programs), each page only has a few options. This decreases the cognitive load for the user since they do not need to do a search through a list of maybe 35 pages and can instead scan maybe 3 or 4 topics and then select the correct categorization intuitively. This will save time for the average user who is unfamiliar with the breezecard.com website, which most users will be as it is not a regularly used site.  

The image depicts a map of the MARTA rail system, showing various stations and lines, including the Red Line, Gold Line, Green Line, and others, along with a section highlighting the purchase and balance information for users.

AI-generated content may be incorrect. 

Here is a comparison side-by-side of before menu vs. our new categorization menu. With this new menu it is easier to find exactly what you are looking for. 

While this is a short summary of our suggestions for the MARTA breezecard.com website, a full prototype of our suggested changes can be found at the following link: https://www.figma.com/proto/FlZZhznnzGohMO4kzQZyVs/Hi-Fi-Prototype?node-id=0-1&t=pntFjRv2vkmXKK1s-1 

 

CONCLUSION 

The redesign of the breeze card website provided an opportunity to rethink how users interact with transit platforms, and highlighted the importance of simplicity, accessibility, and consistency in UI design. Throughout the process, our team focused on improving usability by streamlining access through a single log in, decluttering the interface, and creating a cohesive color scheme which enhances readability and navigability.  These changes, supported via our usability testing, displayed that users value efficiency, and clarity, especially in something as essential as transport.  

We learnt that users tend to want consistency within their applications. Using UI styles that were popularized 20 years ago and faded 10 years after that, confuse users of today when many of their most used websites function the same.  We learnt that even minor decisions such as button placement and color scheming buttons on intended outcomes had huge effects. Design became less of ensuring the components exist, and more of ensuring users can more easily and intuitively access them. Content simply being somewhere on the website is not nearly enough.  

Any handing off this project needs to be done so with the assurance that these core design principals are retained.  Further enhancements to the project, such as the inclusion of more information pages and more key features involving the new breeze card, need to integrate well with the already existing product. By ensuring that users can navigated tot their desired location in no more than 3 button presses and an easy way to navigate back to the home screen from almost every other screen, we can ensure that the content that exists today will be accessible for all users no matter how diverse the tasks they want to perform on the website. 
