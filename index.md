
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
  - [Communication Tooling](#communication-tooling)
  - [Technical Tooling](#technical-tooling)
- [References](#references)

![](/images/stock_image.jpg)
*[Source](https://medium.com/serious-scrum/7-concrete-ways-to-improve-collaboration-in-remote-or-distributed-scrum-teams-7940fbaed52d)*

## What is a globally distributed software team?
In ever-growing IT industry companies for quite some time have embraced the practice of Globally Distributed Software Development. In essence, it means developing software products through collaboration and a combination of different teams or team members across multiple physical locations as opposed to traditional co-located development. Due to the ability to work remotely, distributed team members can live anywhere across the globe which brings both the benefits and potential issues with no guarantee that it will be beneficial in the end[^4]. As such, we will try to dive deeper into the caveats of globally distributed software development, why one should and shouldn't distribute development, look into risk factors of such decision, both in large-and-small to medium-size enterprises, and potential solutions through different development and communication methods supported by technical tooling.

### Why should I distribute my team?
Generally, one would consider going to distributed software development when you can no longer grow or sustain your company locally, which can be grouped into several core reasons[^4]:
<ol>
<li>The business market proximity advantages
including knowledge of customers and local
conditions.</li>
<li>Pressure to improve time-to-market by using timezone differences and having round-the-clock
development.</li>
<li>Create a pool of globally available skilled resources
to develop software in reduced cost.</li>
<li>Distribution also minimizes the risk in case of
natural catastrophes and other events.</li>
</ol>

While these benefits definitely look alluring one must also consider potential drawbacks and high initial investment costs reflected as monetary costs, time delays, and potential management overhead. As such, globally distributed development should be treated as a double-edged sword that can bring great benefits, but if it is mismanaged and done incorrectly it can not only add large communication and management overhead but can result in a steep increase in expenses with little revenue gain or overall benefit to the company. These dangers and potential solutions how to avoid them will be covered in the following sections.

### Why shouldn't I distribute my team?

Naturally, if you do not fit in previously listed reasons to distribute your team then perhaps you should not do it. But even then, when you do see yourself benefiting from distributed development, one should also consider legal implications. Perhaps the projects you are working on depends on highly sensitive data? Maybe the data is regulated by law and can not leave the country's borders? Or in the near future you will start working with such data? And then to what extent your current and future projects can benefit from distributed development? Even if your business is dealing with suitable projects for distributed development you should also analyze if you can support the initial overhead when transitioning towards distributed, and for how long. The answers to these questions should provide good insights into whether distribution is something worth considering.

Then there is a matter of customer base and quality control. If your customers are found locally then you need to consider the potential quality change of your product, and if you really can ensure that transition will not affect customer expectations. Additionally, if you can not find a suitable vendor and want to avoid "small fish in a large pond" situation when dealing with off-shore vendors, then you should also avoid moving towards distributed development or at least consider nearshore options. Finally, one might also want to consider choosing remote locations with the potential to attract new clients, if possible. 

While all these considerations are equally important, they might not be as relevant to a large-scale enterprise as it is to a small one, and as such applicability of them might be different.

<!---
Because you have no issues with resources
Because customers are local or niche customer base
Because of quality control
Because you're dealing with highely sensitive data and are subject for protective data regulations (i.e. data can not leave country's borders)
Because you you can not afford additioanl/potential cost overhead
Because you can not find suitable vendor and want to avoid "small fish in a large pond" situation when dealing with off-shore vedor.
-->

### On the decision-making level

Since distributed development is a decision that affects the whole company, it is necessary that the decision-makers really understand what and why they are doing. While it is possible for "cost savings" to be the only underlying reason for migration towards distributed development, generally, such type of vendor involvement is rare, short-lived and does not foster deep partnership level which can quickly lead to "blame game" and potential failure of projects or degradation of operational performance[^1]. As such, executives should look beyond a way to save costs and engage in strategic or transformational partnership models as proposed by Kedia et al. In that way, both parties will be able to benefit not only from the advantages that distributed development brings but also from the collaborative effort resulting in a successful product. As a result, all C-level executives from both parties should be actively involved in laying out their goals, key performance indicators, the focus of their collaboration, and most importantly transition and transformation plans[^3].

While these partnership models should work in every enterprise, there is some difference when we are considering only small and medium-sized enterprises (SMEs). SMEs are generally being forced to concentrate their core service activities within their enterprise boundaries while out-sourcing some of their development or operational tasks to low-cost countries in order to maintain a competitive advantage against large enterprises. As it was demonstrated in an explorative, qualitative research paper by Klimpke et al.[^2], such a position entails different challenges for SMEs. Primarily, the flexibility provided by the vendor to rapidly increase the number of out-sourced developers is highly valued as opposed to cost savings being a driving force in large enterprises. Then there is an issue with cultural and domain knowledge differences which, according to Klimpke et al., are far more apparent in SMEs than in larger enterprise environments. To this end SMEs should aim at out-sourcing to a nearshore location as that would help to solve (or at least reduce) cultural and domain knowledge issues. While out-sourcing location does make a difference, SMEs can still benefit (perhaps even more so than larger enterprises) from using previously mentioned partnership models since a close relationship with a vendor would only benefit flexibility and responsiveness of development demand. 

## Working as a distributed team

When distributing your team, you often need to "distribute your workflows" as well. Many software teams already use LEAN and Agile working methods for their projects, however, some adjustments and focuses change when moving to a distributed setting. In this section, we will have a look at how distributed agile and scrum should be set up, and how the impact of common issues present in distributed teams can be reduced, such as time and cultural differences. 

### Tips for Distributed Scrum

This section presumes some knowledge of Scrum, if you have not heard or ever used Scrum, we recommend you read the Scrum guide first[^5].

![](/images/scrum.png)
*Scrum framework [Source](https://www.visual-paradigm.com/scrum/why-scrum-difficult-to-master/)*

Despite the huge improvements in technology over the recent decade, there is no more efficient or effective method of conveying information within a development team than face to face conversation[^6]. With this in mind, it is important that where possible your software team is able to meet face to face at least once. This allows the team to integrate, and feel a physical connection to the team, rather than segregated remotely, so the team can focus on providing value to the customers. 

When your team does communicate remotely, it is far better to **communicate asynchronously through mediums like Slack** for quick fire and respond questions; This is better than emails, which have a tendancy to build up and not warrant a quick response. This constant communication allows the team to feel focused on the task, as well as connected to the team as if they were next to eachother in the office.

In addition, it helps to **use the same tools universally across all teams**, no matter where they are based. This means that everyone can help each other, as well as reducing any mentality difference between the teams.

Finally, when meetings are performed remotely, **using video chat is much better than purely voice or textual chat**, as it allows people to see eachother and bring a sense of closeness to the members. 

### Navigating differences

#### Time

#### Culture

## Tooling

### Communication tooling

### Technical tooling


## References
[^1]: Kedia, Ben & Lahiri, Somnath. (2007). International outsourcing of services: A partnership model. Journal of International Management. 13. 22-37. 10.1016/j.intman.2006.09.006. 

[^2]: Klimpke, Lars & Kramer, Tommi & Betz, Stefanie & Nordheimer, Khrystyna. (2011). Globally distributed software development in small and medium-sized enterprises in Germany: Reasons, locations, and obstacles. 19th European Conference on Information Systems, ECIS 2011. 

[^3]: Linder, Jane & Cole, Martin & Jacobson, Alvin. (2002). Business transformation through outsourcing. Strategy & Leadership. 30. 23-28. 10.1108/10878570210435342.

[^4]: Shrivastava, Suprika & Date, Hema. (2010). Distributed Agile Software Development: A Review. J Comput Sci Eng. 1.

[^5]: [Scrum Guide](https://scrumguides.org/docs/scrumguide/v2020/2020-Scrum-Guide-US.pdf)

[^6]: [Agile Manifesto](https://agilemanifesto.org/principles.html)
