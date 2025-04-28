![Microsoft](images/banner.png)
# Bentley Systems - 2025 AI Immersion Day
This repository contains resources and instructions for the Hackathon to deploy and use Microsoft 365 Copilot Agents.

**__Contents of this repository and the instructions may change until the day of the Hackathon. Please check back freqently for the latest.__**

©Microsoft Corporation

## Agenda
![schedule](images/schedule.png)

## Main use case
Simple and Quick use of Copilot Chat to get the juices flowing!  Then - Fellow Hackers (Makers) will assemble an agent who's main purpose is answering customer and employee questions on Bentley Systems products and services based on the publically available content on the Bentley Systems Website.
### General instructions
Implement the tasks outlined in the lab manual. Resources that can help you with the tasks are provided as reading materials. At the end of this hackathon, present your learnings, benefits, and applicable use cases at Bentley. Tasks may prompt you/team for observations. These are designed to help with your final presentation and overall understanding of Copilot Agents.  You will use this repo to copy content and paste it into the Copilot Design Studio during the hackathon to save you time (so you do not have to type it all ;-)).

If you have questions, you can ask your session coach or look at the _"(answer key)"_ for the task.

_Duration: 60 minutes_<br>
_Level: 101_

## Reading materials
1. [What is Copilot Studio](https://learn.microsoft.com/en-us/microsoft-copilot-studio/fundamentals-what-is-copilot-studio)
2. [Add a public website as a knowledge source](https://learn.microsoft.com/en-us/microsoft-copilot-studio/knowledge-add-public-website)
1. [Use SharePoint Content for generative answers](https://learn.microsoft.com/en-us/microsoft-copilot-studio/nlu-generative-answers-sharepoint-onedrive)
1. [Knowledge sources for Copilot Agent](https://learn.microsoft.com/en-us/microsoft-copilot-studio/knowledge-copilot-studio)

## Lab Manual
Please complete each task:

**Task 1**: _(Optional, but suggested)_ Complete the reading list to understand what is a copilot agent.

**Task 2**: Explore using Microsoft Copilot Chat
- Launch Microsoft Edge internet browser
- At the top right corner, click on the Copilot icon ([image](images/CopilotChat.png))
- Use Copilot Chat to answer any question you may have. Take note of the question and the answers
- Use the Add Content (paper clip icon) to attach the pdf file titled _"ProjectWise_Web_and_Drive_User_Manual.pdf"_ from the documents folder in this repo ([image](images/AttachFile.png))
- Ask questions about the contents of the file you just uploaded.
- Observations:
   - What are the benfits of using Copilot Chat versus ChatGPT or other public service?
   - Benefits of Copilot Chat for Bentley employees?
   - How much does Copilot Chat cost?

**Task 3**: MAIN EVENT - Deploy an agent using Copilot Studio ([answer key](AnswerKeys/answerkey-task3.md))
- Go to _[https://copilotstudio.microsoft.com](https://copilotstudio.microsoft.com)_ and log in. [your user account has been assigned a Copilot Studio License and Security role for one of the (5) Environments available.  If you are in Teams Breakout Room #1, you will use the DEV-BENT-CPS1 Environment, if you are in Teams Breakout Room #2, will use DEV-BENT-CPS2, and so on.  This is a full functional environment.
- Create an agent that will:
   - Use the Bentley Product URL's assigned to your Group (please see ([answer key](AnswerKeys/answerkey-task3.md)) for the URL's to use for each group), as a knowledge sources for your agent.
   - You will then configure severl more settings, ([answer key](AnswerKeys/answerkey-task3.md))
   - Do NOT use the AI's general knowledge. Make the URL's provided as the authoritative source for all answers.  Your leader will show you where these settings are found.
   - Once you have completed the set up, settings, and then published your Agent, you can now test it out.
   - Test your agent to see if it is working. Your agent should be able to answer questions about the products you have set it up specifically to address (but do not restrict your testing to just these questions):
      - Please your team section for "Starter Prompts" and Sample Questions, your group leader will explain the difference.
- Note your observations (examples but not limited to the following):
   - Does the agent answer questions that are not covered by the knowledge you supplied?
   - How did you test/confirm the above?
   - Does it handle translation for you? What languages? Was it automatic?

**Task 4**: Handling translation. ([answer key](AnswerKeys/answerkey-task4.md))
- Now let's turn on the "Allow the agent to use its own General Knowledge" feature.  By doing so, the Agent will now have the ability to digest and respond in a large number of languages.  You
   - You can use the question: _"Pouvez-vous me dire quels sont les secteurs desservis par Bentley Systems?)_
   - Observe response
- Instead of the agent always answering in English, have it answer in the language of the user.

**Task 5**: Edit your agent to retrieve the current status of Bentley Cloud Services and recent history of incidents. ([answer key](AnswerKeys/answerkey-task5.md))
- RSS feed for the Bentley Cloud Services is located here: _https://status.bentley.com/history.rss_
- Expand the capability of your Copilot agent to retrieve the current status of services hosted in the Bentley Cloud Service platform, and a history of recent issues.
- Test your Copilot Agent:
   - Ask about service status
   - Ask details about specific incidents of services that recently had incidents
- Optional: Include other Bentley RSS feeds and test:
   - News releases: _https://bentleysystems.gcs-web.com/rss/news-releases.xml_
   - Latest SEC filings: _https://bentleysystems.gcs-web.com/rss/sec-filings.xml_
   - Recent events: _https://bentleysystems.gcs-web.com/rss/events.xml_

**Task 6**: Have you agent carry out a task. ([answer key](AnswerKeys/answerkey-task6.md))
- Add an Action Item to your agent to do the following:
   - When a request is made to the agent to send an email of the answers to an inquiry, in this case, e.g. "Email the Status of Bentley Cloud Services health dashboard", the agent will:
      - Send the email and upon successfully sending the email, respond that the email was sent, together with the message that will be included in the email, as seen below

      ![ResponseToSendEmail](/images/ResponseToSendEmail.png)

- For this Action Item, use the Outlook Send an Email (V2) connector. ([image](/images/Outlook-SendAnEmailV2.png))


**Task 7**: Prepare final report and presentation

Present what you and your team have learned and how would you apply this in your day-to-day job? You can use your observations when carrying out the tasks above as well as the following guideline:
- Key learnings
- What business challenge or specific use case will you apply this learning, and how does it benefit the organization?
- Can you predict any potential improvement metrics?
- What other capabilities, beyond answering questions, would you/organization benefit from Copilot agents?
- Any other thoughts, recommendations, concerns you want to bring up for discusion with the broader team?
