![Microsoft](images/banner.png)
# Bentley Systems - 2025 AI Immersion Day
This repository contains resources and instructions for the Hackathon to implement Microsoft 365 Copilot Agents.

©Microsoft Corporation

## Agenda
![schedule](images/schedule.png)

## Main use case
People taking documents and build a simple agent to ask questions. 
At the end of this hackathon, present your learnings, benefits, and applicable use cases in Bentley.

_Duration: 60 minutes_<br>
_Level: 101_

## Reading materials
1. [What is Copilot Studio](https://learn.microsoft.com/en-us/microsoft-copilot-studio/fundamentals-what-is-copilot-studio)
1. [Use SharePoint Content for generative answers](https://learn.microsoft.com/en-us/microsoft-copilot-studio/nlu-generative-answers-sharepoint-onedrive)
1. [Knowledge sources for Copilot Agent](https://learn.microsoft.com/en-us/microsoft-copilot-studio/knowledge-copilot-studio)

## Lab Manual
Please complete each task:

**Task 1**: _(Optional)_ Complete the reading list to understand what is a copilot agent.

**Task 2**: Explore using the Microsoft Copilot Chat
- Launch the Microsoft Edge explorer
- At the top right corner, click on the Copilot icon ([image](images/CopilotChat.png))
- Use Copilot Chat to answer any question you may have. Take note of the question and the answers
- Use the Add Content (paper clip icon) to attach one of the files from the documents folder in this repo ([image](images/AttachFile.png))
- Ask questions about the contents of the file you just uploaded.
- Observations:
   - What are the benfits of using Copilot Chat versus ChatGPT or other public service?
   - Benefits of Copilot Chat for Bentley employees?
   - How much does Copilot Chat cost?

**Task 3**: Deploy an agent using Copilot Studio ([answer key](answerkey-task3.md))
- Create a folder in your enterprise OneDrive and upload a few files
   - You can use [the sample files in the /sample folder](documents/) of this repository if you like
- Go to _[https://copilotstudio.microsoft.com](https://copilotstudio.microsoft.com)_ and log in.
- Create an agent that will:
   - Use the above OneDrive folder that you created, and the files in it, as a knowledge source
   - Do NOT use the AI's general knowledge. Make the OneDrive folder the authoritative source for all answers.
   - Test your agent to see if it is working. If you used the files in the sample folder, your agent should be able to answer these questions (but do not restrict your testing to just these questions):
      - _"What are the requirements for MicroStation?"_
      - _"What are the data file variables for MicroStation?"_
      - _"Give me high level instructions for developing applications using MDL."_
      - _"What does Bentley Systems do?"_
- Note your observations (examples but not limited to the following examples):
   - Does the agent answer questions that are not covered in by the documents in the folder?
   - How did you test/confirm the above?
   - Does it handle translation for you? What languages? Was it automatic?

**Task 4**: Edit your agent to retrieve the current status of Bentley Cloud Services and recent history of incidents. ([answer key](answerkey-task4.md))
- RSS feed for the Bentley Cloud Services is located here: _https://status.bentley.com/history.rss_
- Expand the capability of your Copilot agent to retrieve the current status of services hosted in the Bentley Cloud Service platform, and a history of recent issues.
- Test your Copilot Agent:
   - Ask about service status
   - Ask details about specific incidents of services that recently had incidents
- Optional: Include other Bentley RSS feeds and test:
   - News releases: _https://bentleysystems.gcs-web.com/rss/news-releases.xml_
   - Latest SEC filings: _https://bentleysystems.gcs-web.com/rss/sec-filings.xml_
   - Recent events: _https://bentleysystems.gcs-web.com/rss/events.xml_

## Extra credit use case
Connect Copilot agent to an external connector (e.g. Salesforce).

_Duration: 30 minutes_

_Level: 101_

## Lab Manual
- In the Knowledge section of your agent, add a new knowledge source
- Select the Advanced tab and pick an external agent. For this Hackathon, select the _Salesforce_ connector
- Ask your coach for a Salesforce login




