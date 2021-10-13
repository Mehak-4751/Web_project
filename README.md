# team-91
Social good parter: Samarthya

Samarthya's mission: Gathering citizens and communities to colloborate amongst themselves, discuss and reach out to authorities to improve the quality fo public services delivered to them.

Problem statement we were given: Make use of technology to create a digital tool that can help SMC(School Management Committee) members generate grievances forms/letters. The grievance form inturn has to be forwarded to the concerned government bodies. There should be a way to notify government bodies of actions pending under them as well as sending reminders to SMC members to follow up if the request raised by them is still open.

Our solution:

The application has two different views. One for the public to view and other for the SMCs. We will be authenticating SMCs via their user ids and passwords.
The public view of the application has different types of stats/graphs displayed on the page to see as the ones mentioned below:
a) A PieChart on No. of grievances issued on the portal VS No. of grievance issues solved
b) A ColumnChart on solved VS unsolved grievances data on different types of issues a school might face
c) Analytics on number of unsolved grievances for different type of grievance domains

The SMC view of the application has two basic functionalities. i) Dashboard ii) Submitting the grievance form

The dashboard of an SMC would contain various charts/graphs displayed on the page.
For submitting the grievances, the SMC could do that in one of the following ways:

i) Uploading an image that contains grievance details
ii) Calling authorities via voice calls and letting them know the issues
iii) Filling in the form(on the portal)

The innovation we had brought into the project:

a) When the SMC uploads the input(the grievance details) via an image to the portal, NLP(Natural Language Processing) is used to autodetect the government body that a grievance might need to forward to. Even if the image has data in Hindi language, that would work too

b) Calling feature for the SMC to speak up via the portal and also sending notifs to the SMCs if their grievance has been which we have done through the Twilio API

c) Automatic tweets on Twitter platform via the Twitter API about the issue, and tagging in concerned authorities in the posts, if the grievance hasn't been solved over a long period of time

Tech stack used:
1) Django for the entire web application
2) HTML, CSS, JS, BootStrap, SCSS for the frontend
3) Django ofcourse for the backend
4) Dash, Plotly and Google Charts for cool graphs/stats
5) NLP and OPENCV for image processing
6) Twilio API for sending notifs and voice calls
7) Twitter API for auto tweets
