# SciCommons

**March 17th - Note for GSoC applicants.**

Please note that you cannot be doing another job or internship or even courses during the 12 week GSoC period without prior discussion and approval, and it has to be mentioned clearly in your proposal. You are expected to be devoting full time and attention for 350 hours during the week, not on weekends, and daily updates as well as availability for meetings will be expected. GSoC pays quite well for this internship. Please understand that if this is violated,  you are in serious risk of failing the program.

For GSoC applicants: the proposal should outline the technologies you are familiar with in order to create the front-end, back-end, communication between the two as well as communication between them and the openReview API. The project aims to create a browser-based portal where papers can be viewed, commented on and rated, and these comments and ratings are stored in the back-end and associated with each user, who can get a reputation from this activity. Imagine a StackOverflow or Reddit for scientific articles. The GSoC proposal should discuss in as much detail as possible the technical aspects and feasibility of the planned work based on the intern’s experience and knowledge.

**Project Title: A social-web tool to facilitate rating and commenting on research reports**
 
It is generally agreed that the 10 billion USD research/science publishing industry represents a bad way to expend scarce research funds. Funded by university budgets and grants to researchers, and based on the volunteerism of the research community, this market diverts substantial sums from the research activity itself, while putting up barriers to access to the research literature. Current open-access mandates merely transfer the costs from reader to authors and/or their funding/employing organizations. Research journals provide objective peer-review and an article rating and filtering mechanism. We propose to to leverage modern internet-based social technology to create an open reviewing and quality-ranking web portal that, if adopted, will drastically improve research discourse, functioning and accessibility.
 
The project involves the design of the portal and development of a front-end as well as the back-end database and logic, that will interact with the OpenReview API. Familiarity with web-technology as well as Python will be ideal. The goal is to develop a proof of concept portal that facilitates manuscript submission and an automated, free, community-based open access, peer review and quality-rating system. The system will eventually be tested with the Aperture Neuro open access publishing platform of the Organization for Human Brain Mapping (OHBM), in consultation with that community.

https://openreview-py.readthedocs.io/en/latest/
https://docs.openreview.net/getting-started/using-the-api
https://docs.openreview.net/reference/api-v1

The idea is to create a portal where documents can be viewed, commented on and rated (pseudonymously) and for the comments and rating to be stored in a back-end database, while the articles themselves are stored on OpenReview and accessed via the API.
 
Planned effort: 350 hours 
Skill level: Intermediate/Advanced
Pre-requisite skills: Comfortable with Python. Experience with web technology – React/equivalent Javascript library, front-end programming, back-end programming with databases.
Tech keywords: Science publishing, social web, science portals.
Mentor: JB Poline (mentor), Suresh Krishna (co-mentor)
No planned longer absences.

Answers to FAQ
--------------
1. The goal for now is to start small-scale as a proof of concept, so we are not trying to capture all of the scientific literature, either via a cron job, or via users posting articles to start a discussion. Instead the idea for now, but this can be discussed/changed, is to start with article authors submitting their articles to openReview via the portal using the openReview API. This then makes their articles available on the portal. Other users can then comment and review on the article, similar to what happens in OpenReview. The idea is to give detailed comments. And comments on comments. Everything can be rated. 
The main difference from openReview is that commenters/users get a reputation via their activity, and users can filter articles who have a certain reputation among users with a certain reputation, so that you can for example see what high-reputation people think of the article. Journals can now form as communities of commenters/reviewers - a community can manage the rating/reviewing of submitted articles and in their own page, declare an article as published by them. In this scheme, multiple communities/journals can publish the same article, so the authors have the right to allocate formal publication to one of these journals, so that their article can be indexed by services following the current system.

This is different from Semantic Scholar, Pubmed etc, because they do not have any of the above rating features - they are just databases of titles and abstracts like Pubmed, and a searching tool.

We already have potential tie-ins with some communities, which will mean that communities (journals) and authors from that community (interetsed in publishing in that journal) will likely use the platform in the near future once it is built.

2. And yes, all of this is independent of OpenReview. 

3. Such a system does not exist now because a reputation-based platform has not been developed till now. Pure commenting systems were Pubmed Commons (died due to nobody using it, like comments sections that every journal has), PubPeer (used only for negative criticism), OpenReview (used by some conferences). Reputation allows one to filter spammy reviews. Having real-name known to system to be part of a community (journal) also allows one to do the same thing. Having real-name be invisible to community allows for fearless reviewing. Ability to earn a reputation gives one incentive to participate. And now that Twitter is not so fashionable, perhaps there is an incentive to move some of that conversation to a different portal, and have it be conducted in longer-form.
