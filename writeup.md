# "1-10" SGTS Assistant (DT2, Team110)

###### Search "1to10" app on Slack to try!

## Team Members

- Kevin Ng (CEP)
- Justin Hoe (CEP)
- Xu Yangbo (CEP)
- Yufeng Zhang (DAIP)

## Overview

The SGTS (Singapore Government Tech Suite) offers a comprehensive ecosystem of tools for developers. However, growing complexity has made adoption challenging despite extensive documentation. To address this, we've developed an LLM bot with Retrieval-Augmented Generation (RAG) and agentic automation, accessible via Slack. This bot enhances documentation access, streamlining operations and improving product integration.

## Problem

Despite extensive online documentation, developers struggle to adopt SGTS products. After consulting product managers, technical writers, and reviewing user queries, we identified several key pain points:

- **Incomplete Awareness of Solutions**: Users struggle to properly assess and compare SGTS tools due to the sheer quantity of available solutions.
- **Preference for Interactive Q&A**: For new information, developers favor conversational search over sifting through lengthy documentation.
- **Siloed Support**: Cross-product queries spanning multiple teams are repeatedly redirected, increasing resolution times.
- **Excessive Basic Queries**: Engineers and product managers are frequently distracted by routine questions, limiting focus on more innovative and strategic tasks.

## Product Features

The SGTS Assistant bot leverages RAG techniques on the entire corpus of SGTS documents. It quickly retrieves the most relevant answers from our **extensive library of documentations and product descriptions**. Users can now engage in natural language queries and **receive precise, context-aware answers in real time**.

Besides that, the SGTS Assistant offers additional features that other bots do not have. These unique features include:

1. **Cross-Product Reasoning and Suggestions**:
The bot is not only capable of answering isolated queries but also of reasoning across multiple public tools and SGTS products. It can suggest the combination of tools for specific tasks, guide integration steps, and recommend design implementations that leverage both open-source software as well as SGTS tools.

2. **Automation of Service Requests**:
Beyond informational queries, the SGTS Assistant can automate routine service requests directly within the chat. This automation relieves product teams from mundane task management and reduces the need for users to navigate disparate internal systems for basic tasks.

3. **Seamless Integration with Slack**:
Recognizing the effective adoption of Slack in our company’s communication, the SGTS Assistant is fully integrated into our Slack channels. This provides immediate, on-the-go access without the need to switch between different portals or log into separate systems.

## The Value It Brings

- **Time Savings for Developers and Product teams**:
Developers now get instantaneous, precise answers through natural language interaction; and our engineers and product managers can focus on advanced problem-solving and innovation rather than spending time on repetitive product queries.

- **Increased Product Adoption and Visibility**:
The SGTS Assistant not only streamlines support but also actively promotes our suite of tools. By suggesting the best-fit products for various use cases, it drives awareness and encourages wider adoption of the SGTS solutions among developers.

- **Reducing Ops Team Burdens**:
As our SGTS Assistant integrates with various platforms to automate simple service requests, we can reduce the need to submit tickets and shorten waiting times for manual processing. It provides the user with a better developer experience, and also reduces the burdens on operation team.

## How It Helps

See below for some cool examples of what you can ask:

### Suggest SGTS Tools and Guide Onboarding
<p align="center">
<img width="400" alt="image" src="https://github.com/lyonely/one-ten/blob/main/images/demo_RAG.png?raw=true" />
</p>

### Fulfill Service Requests for TechPass
<p align="center">
<img width="400" alt="image" src="https://github.com/lyonely/one-ten/blob/main/images/demo_Techpass.png?raw=true" />
</p>

### Propose Architecture and Solutions
<p align="center">
<img width="400" alt="image" src="https://github.com/lyonely/one-ten/blob/main/images/demo_architecture.png?raw=true" />
</p>

### Check Maintenance Times and Raise Incident Tickets
<p align="left">
<img width="400" alt="image" src="https://github.com/lyonely/one-ten/blob/main/images/demo_jira_1.png?raw=true" />
<img width="400" alt="image" src="https://github.com/lyonely/one-ten/blob/main/images/demo_jira_2.png?raw=true" />
</p>

### Craft Eloquent Jokes in the Context of GovTech Products and Tools!
<p align="center">
<img width="300" alt="image" src="https://github.com/lyonely/one-ten/blob/main/images/demo_joke.png?raw=true" />
</p>

## Next steps

- **Operationalize the refresh process for its RAG data source:**
We plan to automate the update process for the knowledge base to ensure that the bot always has access to the most current documentation and resources — thereby enhancing its accuracy and relevance. In addition, we intend to expand the scope of documents that is fed into the bot, ensuring a broader and more holistic coverage for GovTech and the Singapore Government.

- **Expand integrations into more products:**
We will actively engage with product managers to identify additional products and service requests that can be seamlessly integrated into the bot to further enhance its agentic capabilities. Their insights will be invaluable for feature and integration priorization, ensuring that the assistant remains a comprehensive, one-stop solution that continues to meet the evolving needs of our users.
