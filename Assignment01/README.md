# ASSIGNMENT 01: HEURISTIC EVALUATION
# Creating a Slack-Like Platform to Support Food Activism
Coco Nakano | DH 110 | Fall 2022
## Project Description
I am both a student of the food studies minor and an intern at a nonprofit that works within the realm of food activism. A common request among these communities is the need for a centralized hub for information, events, opportunities, and collaborations to be shared. If you look up "Los Angeles Food Activism" on Google, you'll quickly find the scattered links that only lead to specific organizations and their internal events. Other alternatives that consolidate resources are often in private communities and don't allow the public to join. Therefore, I would like to focus my project on creating a resource-sharing platform to support food activism.

## Competitor Analysis
### Slack workspace for UCLA Food Studies minors
![Screenshot of announcement channel in workspace](https://user-images.githubusercontent.com/56706104/194003627-79b293a0-2e5d-46f9-8cb7-608281f54ad2.png)
(unfortunately this is a private resource, so the URL is unavailable)

**Description**
This Slack workspace is a private workspace hosted by the Food Studies department at UCLA. In order to get access to the Slack, you must be a Food Studies students or an affiliate of the program. This workspace is meant to serve as a hub for students of the minor to hear of job opportunities, events, volunteering events, and other external activities. It includes channels to discuss announcments, research opportunities, social events, food news, recipes, and others (channels start with # and are in the column on the left of the above screenshot).

**Overall Heuristic Evaluation**
Slack is a well-rounded app. The only drawback as a users is that since you likely have more than one workspace, it is not necessarily the case that the application will open up to the one for the Food Studies minor. This means, users are not prompted to look at that workspace unlesss by their own volition or because of the small dot next to the workspace icon to show there are unread messages.

**Heuristic Evaluation**
1. Visibility of System Status

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Good: it highlights the channel you're in|
|Good: in text fields, it gives a light-grey message of where you're messaging (i.e. thread of in channel)|
|Good: Hovering over the button yields very clear inverted colors so users are aware it's a buttom|
|Good: Bolds the channels that include messages users haven't read|
|Good: says reconnecting when waiting for wifi to return|

2. match between system and real world

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Good: Can start threads / reply to specific messages to prevent confusion in channel|
|Good: Can use emojis similar to texting|
|Certain keyboard commands are different when in Slack (e.g. hyperlinking on most of platforms is command+K where as in Slack it's command+shift+U|1|I found the solutions to keyboard commands by googling, but it would help to make it the same as the users keyboard for all other purpuses|

3. user control and freedom

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Good: clear X's on extra windows that users can close without closing the app|
|Good: can open multiple windows within the desktop app so users can see multiple messages at once|
|Good: Can privately message individuals in workspace about opportunities they send in public channels|

4. consistency and standards

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Good: jargon such as channel, thread, and workspace is common|
|Good: clear distinctions between the different channels are their use|

5. error prevention

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Good: if wifi is cut off, messages cannot be sent|
|Good: character limit changes as letters are typed within channel-name when creating a channel
|Allows users to add more than 8 people in a groupchat even though capacity is 8, and type message (it just doesn't sent even though send buttom is still green)|1|grey out send button, do not let users add more members to private group beyond capacity

6. recognition rather than recall

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Good: users' names pop up once a letter is typed when adding members to chat or channel|
|Good: recently used emojis pop up first, including customized emojis|
|Good: location to look at message draft at top of channel list so users can recall|
|Good: Drop down to creat bookmark under each channel|

7. flexibility and efficiency of use

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Good: Notifications are customizable|
|Good: Can schedule slack messages|
|Good: include customizable emojis per workspace|

8. aesthetic and minimalist design

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|The workspace is overwhelming because there is a lot of information on one tiny screen|2|reduce clutter by having less channels|
|Not prompted to look at workspace unless it is already open or you have deliberate action to take there|2|send reminder notifications about unread messages in recently unvisited channels

9. help users recognize. diagnose, and recover from error

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Good: the error when too many members are added to a groupchat includes a button to create a channel instead with unlimited members|
|Good: Prompted to try again when you add spaces, periods, or most punctuation|
|Unclear what punctuations can/can't be added to channel name|1|include list of okay punctuatioons in error|

10. help and documentation

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|There aren't many messages about how to use the workspace from the owner/creator of the workspace so it is difficult to gauge how users should use the workspace and promoting comfortability in doing so|2|have a message / tutorial for new users and show messages in channels from a diversity of students|
|Good: bookmarks are available in each channel so documentation can be saved|

### [Los Angeles Food Policy Council](https://www.goodfoodla.org/)
<img width="1407" alt="Screen Shot 2022-10-05 at 0 49 02" src="https://user-images.githubusercontent.com/56706104/194009293-be77c744-ba50-4b03-a163-f5c4255fdd95.png">

**Description**
The Los Angeles Food Policy Council is a nonprofit whose mission is to ensure food is healthy, sustainable, affordable and fair for all. This is primarily done within their Working Group Network, which is a collection of groups made up of internal members that work towards various goals related to food activism. There are events and opportunities available to people outside of the working group through their newsletter. Their website contains basic information about their organization, as well as the different working groups and how to join them, the issues they specifically tackle, former programs, former engagement opportunities, former publications, and a blog.

**Overall Heuristic Evaluation**
This website includes all of the basic information that one may want to see. It is a relatively simple website. It could be improved in terms of the transparency of the content. More explicit explanations of what it means to get involved and see available opportunities would be useful for users to feel up to date.

**Heuristic Evaluation**
1. Visibility of System Status

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|When selecting the title of items in the menu bar, it is unclear where it goes to the users and in reality it goes to the first item within the menu|2|have title pages for each menu item that users go to when they click on titles; show which menu bar users are under when they select an item within one of the menu items|
|Good: Hovering over the button yields very clear inverted colors so users are aware it's a buttom|

2. match between system and real world

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Good: They have nested menu items similar to how folders on computers work|
|Good: Menu bar delineates different genres of opportunities that users might be interested in (publications, programs, engagement)|
|The delieanation between the different genres above are not clear (sepecifically: events, programs, engagement)|2|consolidate all opportunities under one menu item and delineate within the menu tab; consolidate the different genres|
3. user control and freedom

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|When prompted to donate, a pop up appears. The X to exit the popup is very light and unclear|1|allow users to click outside of the popup on the webpage to exit, as well as making a clear X|
|No information on which menu item you're under|1|have a tracking bar on top that shows where you are nested under|

4. consistency and standards

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Good: They have standard page titles such as "Home", "About Us", etc.|
|Good: Have whole pages dedicated to organization specific terms|

5. error prevention

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Good: Relatively static website so minimal points of errror|
|Good: All links seem to work and go places|

6. recognition rather than recall

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Good: include all social media logos as a footer on all pages so users can click on and go directly to LAFPC's profile|
|Good: When donating, you're given suggestions for values donation that you can click, and options of repeating or one-time donations are in a drop-down|
|Good: there are "Join me" buttons under each working group, which is the main mode of participation as a public member|
|Users do not know they can get recurring notifications via email about LAFPC for updates and information|1|Have mailing list sign-up be the first prompt users get|

7. flexibility and efficiency of use

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Can't sign-in to have an account, meaning there is no ability to customize as well as less of a social contract to frequent the site|1|create sign-in; alternatively, nothing as this is the cost-benefit of being publicly accessibly|

8. aesthetic and minimalist design

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Good: Consistent colors throughout the website that match their logo|
|Could have the mailing list email field be in line with aesthetic of rest of website|1|change style to match|

9. help users recognize. diagnose, and recover from error

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Good: In email field for mailing list, if you input and invalid email and click "subscribe" you will be prompted to input a valid email address|
|Good: If you type in non-numerical values into the money field under donations, it will autocorrect to zero|

10. help and documentation

|Evaluation|Severity Rating|Solution|
|----------|---------------|--------|
|Good: Thorough explanations of their local tersm|
|Unclear what being a member of a working group involved|2|create a small section of information on top of working group breakdown to explain what it means to be a member|


## Index
**Heuristic Evaluation Criteria**
|#|Usability Heuristic|Description|
|-|-------------------|-----------|
|1|visibility of system status|display information that keeps users in the loop about the status of themselves relative to the website|
|2|match between system and real world|connect the systems of organization and convention to what the user would understand|
|3|user control and freedom|create exits and entrances to specific actions|
|4|consistency and standards|use consistent language within your platform and across industry|
|5|error prevention|minimize costly errors and have productive error messages|
|6|recognition rather than recall|give easily accessible options instead of having users remember information|
|7|flexibility and efficiency of use|allow for accelerators, personalizations, and customizations to user experiences|
|8|aesthetic and minimalist design|keep content relevant and simple|
|9|help users recognize. diagnose, and recover from error|use layman terms in error messages and offer alternatives/solutions|
|10|help and documentation|create documentation that is searchable and readable|

[https://www.nngroup.com/articles/ten-usability-heuristics/](https://www.nngroup.com/articles/ten-usability-heuristics)
