# ASSEMBLY-AI-HACKS

<br>

- Watch Project Demo - [youtube](https://youtu.be/0GZ_3DighyE)
<br>

- Web Page - [https://twilightbot.azurewebsites.net/](https://twilightbot.azurewebsites.net/)
<br>
 
- Android - [Bot-Apk](https://drive.google.com/file/d/1UDit-wS1xf8yZNlONfpBIV3rC_DmarMZ/view)
## Inspiration
Artificial Intelligence (AI) reshapes companies and how innovation management is organized. Consistent with rapid technological development and the replacement of human organization, AI may indeed compel management to rethink a company's entire innovation process.

The Health BotServiceis ideal for developers in IT departments of healthcare organizations such as providers,
pharmaceutical companies, tele-medecine providers,and health insurers. Using theservice, healthcare
organizations can build a "health bot instance"and integrateit with their systems that patients, nurses, doctors,
and other representatives interact with. Building an instanceallows you to:
<br>
- Improve processes
- Improveservices
- Improve outcomes
- Reduces cost
<br>
The Health BotServicecontains a built-in medical database, including triage protocols. You can also extend
a health bot instanceto includeyour own scenarios and integrate with other ITsystems and data sources.
<br>

![image](https://user-images.githubusercontent.com/101945531/206912338-47b7780b-9293-4c0e-bbc7-33cdbd164e29.png)


## What it does
Bot asks users questions like their age, gender, and location, any symptoms they’re experiencing, and whether they may have encountered diagnosed with Asthma, Cold, Headache, Breathing issue.Schedfule appointment and insurance claim, escalate to live agent.
- Triage/symptom checker, powered by built-in medical protocols: Theend user describes a
symptom to the health bot instanceand the bot helps the user to understand itand suggests how to
react; for example, "I havea headache."
- General information about conditions, symptoms, causes, complications, and more: Loaded
with medical content, the health bot instancecan provideinformation about medical conditions,
symptoms,causes,and complications; for example, "information about diabetes," "whatarethecauses of
malaria," "tell meabout thecomplications of arthritis."
- Find doctor type: The health bot instancecan recommend theappropriatetype of doctor to treatan
illness; for example, "What type of doctor treats diabetes?"
- Finding providers: Your health bot instancecan allow customers to search for doctors by specialty, innetwork status,and other specifications.
- Scheduling appointments: Your health bot instancecan be designed to allow your customers to
scheduleappointments easily and securely

- Insurers have built health bot instances that givetheir customers an easy way to look up the status of a claim and ask questions about benefits and services.
- Providers have built health bot instances that triage patient issues with a symptom checker, help patients find appropriate care,and look up nearby doctors.
<br>

**Deliver intelligent, conversational healthcare experiences at scale:-**
<br>
- Integrates medical content from trusted sources including information on conditions, symptoms, specialists, medications and procedures.
- Delivers credible triage and symptom checking
- Understands healthcare intents by leveraging built-in language models tuned to medical terminology
- Handles interruptions, topic changes, human error and complex medical questions



## How we built it

<br>
The Personal care Chatbot was created using Azure Health Bot , a provider of AI-driven solutions for medical diagnosis. By combining ChatBot’s technology and Infermedica's template flow we created a simple tool that helps self-evaluate the risk of infection and support people seeking medical advice.

- Azure Health Bot- empowers healthcare organizations to build and deploy an AI-powered, compliant, conversational healthcare experience at scale. The service combines built-in medical intelligence with natural language capabilities, extensibility tools and compliance constructs, allowing healthcare organizations such as Providers, Payers, Pharma, HMOs, Telehealth to give people access to trusted and relevant healthcare services and information.

- Azure Webapp service-Start fast and finish faster with source code integration from GitHub, live debugging and one-click publish directly from Microsoft Visual Studio.

- Internet hosting service for software development and version control using Git. It provides the distributed version control of Git plus access control, bug tracking, software feature requests, task management, continuous integration.

**Conversation:-**
When using the Handoff feature,additional conversation states areintroduced into your bot runtime.
- Bot state: Theend user is speaking with the bot.This is thetypical conversation state.
- Waiting state: Theend user has triggered a handoff scenario and is waiting to beconnected with an agent.
- Agent state: Theend user has been connected to an agentand they are having a conversation.
 End userexperience
Connecting to agent: If thereare onlineagents, theend user and agent go through a connection sequence
beforethelivechat begins.
1. Theend user says something that triggers the handoff connection sequence
2. Theend user is advised that they will soon beconnected to an agent
3. Theend user is added to the queueand theagents receivea push notification
4. Theagent uses a "Connect" command to talk to theend user that has been in the queuethelongest.
5. A connection is established between theagentand end user
6. Theend user receives a notification they aretalking with an agent
7. Thelivechat continues until theagentends theinteraction
<br>

![image](https://user-images.githubusercontent.com/101945531/206912422-18138dc1-44e8-4f5c-814d-0ec1272f1d0e.png)


**Configuration:-**
The Health BotService provides endless flexibility of useto Microsoft partners:
- Uniquescenarios can beauthored by partners for their health bot instances to extend the baseline scenarios and support their own flows.
- The health bot instance's behavior can beconfigured to match the partner's usecases, processes,and scenarios.
- The health bot instancecan easily beconnected to partners' information systems---for example, systems that manageEMR, health information,and customer information.
- The health bot instancecan beeasily integrated into other systems such as web sites,chat channels,and digital personal assistants.
<br>

![image](https://user-images.githubusercontent.com/101945531/206912465-e4adef22-0e2c-4da1-b4c3-41657f06326c.png)


## Health Bot Analytics Reports

Analytics reports areavailablefor you to measurethe behavior of your botand continuously adaptand revisit
your conversation flows in a responseto your end-users.
Reports areinteractive;you can select within thereports to cross-filter or focus to areas of interestyou can also
choosethetime of interest in thetop bar.

![image](https://user-images.githubusercontent.com/101945531/206427959-38d40528-cd83-4cc4-9187-19d5503a376f.png)

<br>

![image](https://user-images.githubusercontent.com/101945531/206428036-b252b2f1-f960-46ee-b329-939d6709aed9.png)

<br>

![image](https://user-images.githubusercontent.com/101945531/206428152-97cf76e7-1971-488a-adba-9c3f841e09e9.png)

- Availablereports include:
- Daily and monthly unique users
- Built-in session and custom scenarios distribution
- Triagecomplaint distribution and triage outcome distribution
- Messages distribution
- Custom scenario outcome distribution
- Theratio of unrecognized utterances

## Embed your Health Bot instancein your application using WebChat

You can connectyour Health Bot to interact with your web application’s users through a web chat control
1. Sign-in to the Health Bot Management Portal
2. In theleft menu blade,click Channels under Integration.
3. Select the View action of theWeb Chat channel
4. Follow thesteps demonstrated in the GitHub repository to embed the Health Bot in the web application as an
iFrame or as a web pageelement (div embedding).

**Scan and Test:-**

![image](https://user-images.githubusercontent.com/101945531/206912485-e6674907-bbc1-4a55-a59c-fe681aeeb664.png)


## Challenges we ran into
main challenge is integration part , but azure document helped us and finally we made our project live.
Each health bot instanceis easily managed and monitored by Microsoft partners via the Health BotService's
management portal and management API.The management portal provides theability to definethe health bot
instance's behavior in fine detail and to monitor usage with built-in reports. Management APIallows the partner
to embed the health bot instanceand to securely exchange data and information.

## What we learned
Learnt about  azure health bot service

## What's next for TWILIGHT CLOUD CODERZ BOT
Need to check AWS cloud service feature and integrating more features
