# SGTS Assistant: Revolutionizing Developer Support at Our Company

## Team Member

- Kevin Ng (CEP)
- Justin Hoe (CEP)
- Xu Yangbo (CEP)
- Yufeng Zhang (DAIP)

## Overview

The SGTS (Singapore Government Tech Suite) has been a comprehensive ecosystem for various developer needs, featuring a wide range of tools and products. However, as the suite grew in complexity, we noticed growing challenges for developers in adopting these tools. Despite the extensive library of online documentation, developers still face challenges in onboarding these products and understanding their proper usage. In response, we have developed a LLM bot equipped with Retrieval-Augmented Generation (RAG) capabilities and agentic automation features. Available directly via Slack, this bot promises to significantly improve how developers and support teams interact with our documentation by providing a consolidated source of knowledge. This allow teams to then easily streamline their operations, and foster better integration across products.

## Problem

Despite available online documentation outlining what each SGTS product does, including how to onboard and use them, developers often find themselves struggling to adopt these products. After interviewing our product managers, technical writers and reviewing the queries raised by users, we identified the following key pain points:

- **Incomplete Awareness**: With numerous SGTS products available, users found it difficult to understand and to weigh all the existing solutions that could be used.
- **Preference for Interactive Q&A**: For finding new information, users generally favor interactive, conversational querying instead of combing through lengthy documentation.
- **Siloed Support**: Questions that spanned multiple products were repeatedly routed to different teams, increasing turnaround times and complicating resolution processes.
- **Excessive Basic Queries**: Product managers and engineers were frequently burdened with relatively basic queries, diverting their attention away from more innovative and strategic tasks.

## Product Features

The SGTS Assistant bot leverages RAG techniques on the entire corpus of SGTS documents. It quickly retrieves the most relevant answers from our extensive library of guides, onboarding materials, and product descriptions. Users can now engage in natural language queries and receive precise, context-aware answers in real time.

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

## How it works

1. Access the bot via Slack by typing `team110` in the search bar and selecting the app.
2. Start conversing the with the bot.
3. It's that easy!

## Next steps

- **Operationalize the refresh process for its RAG data source:**
We plan to automate the update process for the knowledge base to ensure that the bot always has access to the most current documentation and resources — thereby enhancing its accuracy and relevance. In addition, we intend to expand the scope of documents that is fed into the bot, ensuring a broader and more holistic coverage for GovTech and the Singapore Government.

- **Expand integrations into more products:**
We will actively engage with product managers to identify additional products and service requests that can be seamlessly integrated into the bot to further enhance its agentic capabilities. Their insights will be invaluable for feature and integration priorization, ensuring that the assistant remains a comprehensive, one-stop solution that continues to meet the evolving needs of our users.
