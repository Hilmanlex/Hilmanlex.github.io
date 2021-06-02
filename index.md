
Welcome to our blog detailing how you can implement best practices to effectively work as a distributed software development team!

Table of contents:

- [What is a globally distributed software team?](#what-is-a-globally-distributed-software-team)
  - [Why should I distribute my team?](#why-should-i-distribute-my-team)
  - [Why shouldn't I distribute my team?](#why-shouldnt-i-distribute-my-team)
  - [On the decision making level](#on-the-decision-making-level)
- [Working as a distributed team](#working-as-a-distributed-team)
  - [Tips for distributed scrum](#tips-for-distributed-scrum)
  - [Navigating differences](#navigating-differences)
    - [Time](#time)
    - [Culture](#culture)
- [Tooling](#tooling)
  - [In the past](#in-the-past)
  - [Modern day tools](#modern-day-tools)
    - [Messaging platforms](#messaging-platforms)
    - [Video conference applications](#video-conference-applications)
    - [DevOps lifecycle tools](#devops-lifecycle-tools)
    - [Our tooling recommendation](#our-tooling-recommendation)
- [A final word](#a-final-word)
- [References](#references)

![](/images/stock_image.jpg)
*[Source](https://medium.com/serious-scrum/7-concrete-ways-to-improve-collaboration-in-remote-or-distributed-scrum-teams-7940fbaed52d)*

# What is a globally distributed software team?
Over the past few decades, the practice of Globally Distributed Software Development has become commonplace in the IT indistry. In essence, it means developing software products through collaboration and a combination of different teams or team members across multiple physical locations as opposed to traditional co-located development. Distributing teams over the globe can have many benefits, but also poses various risks and has no guarantee that it will be beneficial in the end[^4]. As such, we will try to dive deeper into the caveats of globally distributed software development. We'll look into why you should and shouldn't distribute development, discover risk factors of such decision in both large and small enterprises and investigate potential solutions through different development and communication methods supported by technical tooling.

## Why should I distribute my team?
Generally, one would consider going to distributed software development when you can no longer grow or sustain your company locally, which can be grouped into several core reasons[^4]:
<ol>
  <li>The <b>business market proximity advantages</b> including knowledge of customers and local conditions.</li>
  <li>Pressure to <b>improve time-to-market</b> by using timezone differences and having round-the-clock development.</li>
  <li>Create a pool of globally available skilled resources to <b>develop software in reduced cost</b>.</li>
  <li><b>Spread the risk</b> in case of natural catastrophes or other country specific drastic events.</li>
</ol>

While these benefits definitely look alluring, one must also consider potential drawbacks and high initial investment costs which are reflected as monetary costs, time delays and management overhead. As such, globally distributed development should be treated as a double-edged sword that can bring great benefits as well as issues. If it is mismanaged and done incorrectly it can not only add large communication and management overhead but can result in a steep increase in expenses with little revenue gain. These dangers and potential solutions how to avoid them will be covered in the following sections.

## Why shouldn't I distribute my team?

If you do not fit in previously listed reasons to distribute your development effort then perhaps you should not do it. But even then, when you do see yourself benefiting from distributed development, one should also consider legal implications. Perhaps the projects you are working on depend on highly sensitive data? Maybe the data is regulated by law and can not leave the country's borders? Or in the near future you will start working with such data? And then to what extent can your current and future projects can benefit from distributed development? Even if your business is dealing with suitable projects for distributed development you should also analyse if you can support the initial overhead when transitioning towards distribution, and for how long. The answers to these questions should provide good insights into whether distribution is something worth considering.

Additionally, there is a matter of customer base and quality control. If your customers are found locally then you need to consider the potential quality change of your product, and if you really can ensure that transition will not affect customer expectations. Also, if you want to avoid the "small fish in a large pond" situation and can not find a suitable vendor when dealing with off-shore vendors, then perhaps you should also avoid moving towards off-shore distributed development, or at least look at nearshore options. Finally, one might also want to consider choosing remote locations with the potential to attract new clients, if possible. 

While all these considerations are equally important, they <b>might not be as relevant to a large-scale enterprise as it is to a small one</b>, and as such applicability of them might be different.

<!---
Because you have no issues with resources
Because customers are local or niche customer base
Because of quality control
Because you're dealing with highely sensitive data and are subject for protective data regulations (i.e. data can not leave country's borders)
Because you you can not afford additioanl/potential cost overhead
Because you can not find suitable vendor and want to avoid "small fish in a large pond" situation when dealing with off-shore vedor.
-->

## On the decision-making level

Since distributed development is a decision that affects the whole company, it is necessary that the decision-makers really understand what they are doing and why. While it is possible for "cost savings" to be the only underlying reason for migration towards distributed development, generally such type of vendor involvement is rare, short-lived and <b>does not foster deep partnership levels which can quickly lead to "blame game"</b>[^1]. As such, executives should look beyond a way to save costs and engage in strategic or transformational partnership models as proposed by Kedia et al[^2]. In that way, both parties will be able to benefit not only from the advantages that distributed development brings but also from the collaborative effort resulting in a successful product. <b>As a result, all C-level executives from both parties should be actively involved</b> in laying out their goals, key performance indicators, the focus of their collaboration, and most importantly transition and transformation plans[^3].

While these partnership models should work in every enterprise, <b>there is some difference when we are considering only small and medium-sized enterprises (SMEs)</b>. SMEs are generally being forced to concentrate their core service activities within their enterprise boundaries and out-sourcing some of their development or operational tasks to low-cost countries. This is done to maintain a competitive advantage against large enterprises. 

As it was demonstrated in an explorative, qualitative research paper [^2], such a position entails different challenges for SMEs. Primarily, the <b>flexibility provided by the vendor</b> to rapidly increase the number of out-sourced developers is highly valued as opposed to cost savings being a driving force in large enterprises. Then there is issue with cultural and domain knowledge differences which are far more apparent in SMEs than in larger enterprise environments. To this end, <b>SMEs should aim at out-sourcing to a nearshore location</b> as that would help to solve (or at least reduce) cultural and domain knowledge problems. While out-sourcing location does make a difference, SMEs can still benefit (perhaps even more so than larger enterprises) from using previously mentioned partnership models since a close relationship with a vendor would only benefit flexibility and responsiveness of development demand. 

# Working as a distributed team

When distributing your team, you often need to **distribute your workflows** as well. Many software teams already use LEAN and Agile working methods for their projects, however, some adjustments and focuses change when moving to a distributed setting. In this section, we will have a look at how distributed agile and scrum should be set up, and how the impact of common issues present in distributed teams can be reduced, such as time and cultural differences. 

## Tips for Distributed Scrum

This section presumes some knowledge of Scrum, if you have not heard or ever used Scrum, we recommend you read the Scrum guide first[^5].

![](/images/scrum.png)
*Scrum framework [Source](https://www.visual-paradigm.com/scrum/why-scrum-difficult-to-master/)*

Despite the huge improvements in technology over the recent decade, there is no more efficient or effective method of conveying information within a development team than face to face conversation[^6]. With this in mind, it is important that where possible your software team is able to meet face to face at least once. This allows the team to integrate and feel a physical connection to the team, rather than segregated remotely. 

When your team does communicate remotely, it is far better to **communicate (semi-)synchronously through mediums like Slack** for quick fire and respond questions; This is better than emails, which have a tendency to build up and not warrant a quick response. This constant communication allows the team to feel focused on the task, as well as connected to the team as if they were next to each other in the office.

In addition, it helps to **use the same tools universally across all teams**, no matter where they are based. This means that everyone can help each other, as well as reducing any mentality difference between the teams.

Finally, when meetings are performed remotely, **using video chat is much better than purely voice or textual chat**, as it allows people to see each other and bring a sense of closeness to the members. 

## Navigating differences

Working in a distributed team often means you need to overcome certain differences between the team. Although there many more differences that can arise, in this section we will discuss tips to overcome the two main differences in globally distributed software engineering, time and culture.

### Time

When teams are located across the globe, time differences are inevitable. As a result, this means that some teams will not overlap much during the working day. This means that communication is key, so that hand overs between the teams can be done efficiently. 

**Follow the sun** is a workflow that is also used by some companies. This method means that teams are located across the globe such that there is always exactly one team working on a product at a given point in the day. The advantage is that product support is always available for the customer, and time to market theoretically can be reduced as progress is made at all times. However, a good hand off technique is required between the teams, otherwise progress will not be made as efficiently, as teams have to catch up each time a "shift" starts.

Follow the sun development, even though it might on paper sound like a good system, in practice it is very difficult to successfully achieve due to the reliance on good hand offs. Generally, the best way at reducing the impact of time difference is to increase the overlap between the teams, such that meetings and communication that needs to be performed between teams has enough time to do so. This can be maximised by outsourcing to countries which timezones' have large overlap with the other teams.

### Culture

Different countries have vastly different cultures, which extends far into the work place. In order to reduce the effect of cultural differences, it helps to have open minded employees, who are willing to learn and are accepting of other cultures. It also helps to educate teams about the potential cultural differences, and by inviting teams to other offices, this helps expose the teams to other cultures.  

# Tooling
When the choice is made to globally distribute software engineering capacities, the difficulties that arise can be mitigated to some extent by using the proper tools. At the time of writing this, <b>tooling has made an enormous leap forward</b> incited by the Covid-19 pandemic. In this section, we will have a look at how modern tooling can be used to assist in <b>communication</b> and <b>coordination</b>.

## In the past
A little over two decades ago, pair programming did not exist as a concept because it was not notable at all. Software engineers would almost exclusively work in close proximity[^7]. This is no longer the reality and it can be argued that improved communication and coordination tools made this possible. Web conference and instant chat messaging tools replaced emails and made synchronous communication over large distances possible. While these became commonplace 15 years ago and still form the basis of current digital communication, they have greatly improved in recent years.

On the other hand, coordination tools specifically designed for software engineers were still at its infancy two decades ago. While version control software is nearly as old as software itself, additional tools to work together efficiently were still lacking. Early research noted this problem and focussed on visualising what others were working on[^8], in attempt to have a more continuous form of coordination instead of relying on formal processes.

## Modern day tools
Luckily for us as software engineers, there is currently an abundance of tools available to support distributed communication and coordination. Below we will describe some categories of these tools and discuss what problems to do and do not solve. Note that a common denominator between these tools is that they are trying to offer a all-in-one solution, so there is some overlap between the categories of problems the tools try to tackle.

### Messaging platforms
Instant messaging tools such as Slack and Mattermost form the basis of easy and fast messaging for many organisations today. Frequent communication at distance can be achieved by these tools[^9], which is important for distributed software engineering to work. There are some caveats however. The same study shows that a small portion of experienced employees make up for a great portion of the messages. Both language proficiency and experience with use are factors of how likely employees are to use these platforms. Therefore, it is recommended to have clear guidelines and instructions of how and when to use them.

### Video conference applications
While messaging platforms offer an easy way of frequent communication, they are vastly different from video meetings in the way people interact with each other. Emotions are expressed through emoticons in the former while the latter offers visual and audible ones. There are many different popular tools such as Zoom, Teams and WebEx that are primarily focussed on video meetings.

However, people that would normally happily walk past someone's office to have a quick chat can be hesitant to set up a video meeting. While this can be due to lack of experience, it is often because this includes messaging eachother beforehand and agreeing on a time before the video meeting actually takes place. Using messaging platforms with in-built video meeting functionalities can increase the chance of unscheduled meetings[^10]. Therefore, we would recommend choosing a messaging platform with in-built video meeting functionalities.

### DevOps lifecycle tools
DevOps lifecycle tools attempt to incorporate many of the tooling needed for the entirety of software development and IT operations in one tool. It is incredible how fast these have improved and have been adapted. While these tools started emerging around 2010, they are now the key to collaboration for many IT-driven companies. They are especially well-suited for distributed software engineering because they offer a centralized, transparent system of a large portion of an organisation's operations. This improves coordination because what others are working on is visible in near real-time.

GitLab is the prime example of this - being a remote-only distributed software company themselves - they use their own tool for best practices for globally distributed software engineering.

### Our tooling recommendation

Neither of these tools currently solves all problems regarding communication and coordination. For example, while DevOps lifecycle tools are great for coordination, they are usually used asynchronous in communication. The opposite holds for messaging platforms and video conference applications. Therefore, we recommend using a combination of these tools to work efficiently during distributed software engineering.

# A final word

In general, it is difficult to successfully distribute your software development team. The first thing you should look at, is whether it is right for your use case. You and your decision makers, need to look into the the varying different costs and account for the many difficulties that can be encountered when offshoring and distributing the teams. If you decide it is right for your company, then a big focus on communication is required. 

There are frameworks such as distributed Scrum that should be utilised to improve workflows when working distributed, and allow all members to feel like a team, and focused on delivering to the customers.

Luckily, in the modern age, there are communication tools to reduce the "distance" between your distributed team, as well as automation methods to reduce issues on the software level. 

We hope that you found our blog interesting and insightful!


# References
[^1]: Kedia, Ben & Lahiri, Somnath. (2007). International outsourcing of services: A partnership model. Journal of International Management. 13. 22-37. 10.1016/j.intman.2006.09.006. 

[^2]: Klimpke, Lars & Kramer, Tommi & Betz, Stefanie & Nordheimer, Khrystyna. (2011). Globally distributed software development in small and medium-sized enterprises in Germany: Reasons, locations, and obstacles. 19th European Conference on Information Systems, ECIS 2011. 

[^3]: Linder, Jane & Cole, Martin & Jacobson, Alvin. (2002). Business transformation through outsourcing. Strategy & Leadership. 30. 23-28. 10.1108/10878570210435342.

[^4]: Shrivastava, Suprika & Date, Hema. (2010). Distributed Agile Software Development: A Review. J Comput Sci Eng. 1.

[^5]: [Scrum Guide](https://scrumguides.org/docs/scrumguide/v2020/2020-Scrum-Guide-US.pdf)

[^6]: [Agile Manifesto](https://agilemanifesto.org/principles.html)

[^7]: Thissen, M., Page, J.M., Bharathi, M.C., & Austin, T.L. (2007). Communication tools for distributed software development teams. SIGMIS CPR '07.

[^8]: Redmiles, David. (2007). Continuous coordination: A new paradigm to support globally distributed software development projects. Wirtschaftsinformatik. 49. S28-S38.

[^9]: Stray, V., Moe, N.B., & Noroozi, M. (2019). Slack Me If You Can! Using Enterprise Social Networking Tools in Virtual Agile Teams. 2019 ACM/IEEE 14th International Conference on Global Software Engineering (ICGSE), 111-121.

[^10]: Stray, V., & Moe, N.B. (2020). Understanding coordination in global software engineering: A mixed-methods study on the use of meetings and Slack. ArXiv, abs/2007.02328.

