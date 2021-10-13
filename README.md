
Social good parter: Samarthya

Samarthya's mission: Gathering citizens and communities to colloborate amongst themselves, discuss and reach out to authorities to improve the quality fo public services delivered to them.

Problem statement we were given: Make use of technology to create a digital tool that can help SMC(School Management Committee) members generate grievances forms/letters. The grievance form inturn has to be forwarded to the concerned government bodies. There should be a way to notify government bodies of actions pending under them as well as sending reminders to SMC members to follow up if the request raised by them is still open.

Solution:

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

Methodology:
![image](https://user-images.githubusercontent.com/84508881/137131581-2ea10745-240c-4705-82fa-d00a91ce69a5.png)


Screenshots-
![image](https://user-images.githubusercontent.com/84508881/137122979-4d0de8b0-90e1-45e9-9fab-1a77f7754dc3.png)
Fig 1. Public Dashboard
![image](https://user-images.githubusercontent.com/84508881/137123041-8a001d0b-863c-4363-91b6-d80a875a649b.png)
Fig 2. Login page
![image](https://user-images.githubusercontent.com/84508881/137124506-2d51a090-f91b-4dbd-96a9-f0c6e5919db5.png)
Fig 3. SMCs Dashboard
![image](https://user-images.githubusercontent.com/84508881/137124533-e8fb0eeb-1008-4281-8115-dc5840469f91.png)
Fig 4. Various graphs using dashly and plotly
![image](https://user-images.githubusercontent.com/84508881/137124592-4c3763f0-7668-4a70-980d-da94f86b7493.png)
Fig 5. Pending requests
![image](https://user-images.githubusercontent.com/84508881/137125625-480dd1f0-90e8-4324-bf54-2fd5956df42d.png)
Fig 6. Twitter messages regarding school issues
![image](https://user-images.githubusercontent.com/84508881/137124638-b0e270a8-5985-474d-b7e2-bdc1ef3fd64b.png)
Fig 7. Greivance Forms
![image](https://user-images.githubusercontent.com/84508881/137124697-17ef0503-d6f2-4957-922d-b43690e4091d.png)
Fig 8. Grievances for which SMCs applied that are still opened
![image](https://user-images.githubusercontent.com/84508881/137124731-0a1a73cb-081d-44a3-8c54-879cd86d5c8f.png)
Fig 9. SMCs members can edit their profile

Novelty of the project:

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

Live link - http://127.0.0.1:8000/dashboard/landing
