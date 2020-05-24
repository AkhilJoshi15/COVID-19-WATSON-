# COVID-19-WATSON-
CRACK THE COVID-19 IBM
Py Cyphers Team


1.	Solution Brief Overview - 
What is the problem?
In times of crisis, communications systems are often overwhelmed with people trying to find basic information about testing, symptoms, community response, and other resources. When communication lines get clogged, people who need real help can't get through. Chatbots help respond to tens, even hundreds of thousands of messages a day.
How can technology help?
Whether via text, phone, websites, or communication apps, conversing with chatbots and other AI-enabled resources can play a critical role in helping communities quickly understand crucial information and free up customer service resources to focus on higher-level issues.

IBM Watson Assistant helps you build, train, and deploy conversational interactions into any application, device, or channel. Creating a chatbot using Watson Assistant can help address the issues that our users face while trying to gather accurate, relevant information. Whether you're trying to learn the latest news about COVID-19 or learn where there's testing in your area, a chatbot can play a major role in helping communities quickly understand crucial information and free up customer service resources to focus on higher-level issues.

2.	Solution description- The current situation of COVID-19 has put people in a dilemma where they do not know where to find answers about symptoms and testing sites. They don't even have information about status of schools, transportation, and any other public services available. With this Watson Assistant-powered Crisis Communications solution, you can integrate a chatbot into your Call for Code solution in an IBM Cloud-hosted web server, using a Slack integration, or via a Node-RED dashboard.
Using Watson Assistant, this Call for Code starter kit has designed a virtual assistant pre-loaded to understand and respond to common questions about COVID-19, scan COVID-19 news articles using Watson Discovery, and respond to COVID-19 statistics inquiries with data from trusted sources.
It can:
i.	Respond by sharing consistent, accurate COVID-19 information.
ii.	Help citizens quickly and easily access the latest information through their channel of choice – voice, text, or collaborative tool.
iii.	Free valuable resources by automating answers to common COVID-19 questions.
iv.	Dynamically update information with the latest developments and recommendations.

3.	Solution Architecture - Provide architectural overview/wireframe of solution. Additionally you can also provide a solution roadmap. Create a document or image that shows how mature your solution is today and how you would like to improve it in the future. This can include information on the business model, funding needs, and a sustainability plan.
a.	The user visits a website with the COVID-19 chatbot and asks a question.
b.	The Node.js web server calls Watson Assistant hosted in IBM Cloud.
c.	Watson Assistant uses natural language understanding and machine learning to extract entities and intents of the user question.
d.	The COVID-19 FAQ is sourced from trusted CDC data.
e.	Watson Assistant invokes an Open Whisk open source-powered IBM Cloud Function.
f.	IBM Cloud Function calls Watson Discovery running in IBM Cloud.
g.	Watson Discovery scans news articles and responds with relevant articles.
h.	Watson Assistant invokes an Open Whisk open source powered IBM Cloud Function.
i.	IBM Cloud Function calls the COVID-19 API to get statistics.
j.	Watson Assistant replies to the user inquiry.
k.	The Node.js web server displays the chat answer to the user.

4.	IBM Cloud Services/Systems – Watson Assistant, IBM Cloud Function
