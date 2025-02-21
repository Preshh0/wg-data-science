# Practitioner Guide: Introduction - Things to Think about When Interpreting Metrics

* Related Metrics: [All](https://chaoss.community/kb-metrics-and-metrics-models/)
* Audience: Practitioner Guides are designed to be used by practitioners who may not be experts in data analysis and who want to better understand how to interpret the data about an open source project to develop insights that can help them improve the project health of an open source project. These guides will be especially useful for Open Source Program Offices (OSPOs), project leads, community managers, maintainers, and anyone who wants to better understand project health and take action on what they learn from their metrics.

This Introduction Guide is designed to get you thinking about what you might want to measure and how to measure it along with some general tips and cautions. It is meant to complement the Practitioner Guide series, which is where you will find the details about how to draw insights about specific topics, like Responsiveness, Contributor Sustainability, Organizational Participation, and more.

There is no one size fits all approach to using metrics to measure project health. Every open source project is a little different, and metrics should always be interpreted with the needs of that project taken into account. Small projects will have different needs than large projects. An open source operating system project will have very different characteristics than a project that produces a small package or library. Different communities will have different ways of working to produce their open source software projects. Projects have different methods of publishing releases. Projects and the people who contribute to them will have different needs and goals.  

One of the best places to start isn’t actually with the metrics, but by spending some time understanding the overall goals for the project. If the project is primarily driven by one organization or owned by an organization, you should also consider the goals for that organization. By thinking strategically about the overall goals, you’ll be in a better place to decide what you need to measure to determine whether the project is achieving its goals. Open source projects generate a tsunami of data that can be overwhelming, but by focusing on the goals, you can develop a [metrics strategy](https://community.linuxfoundation.org/events/details/lfhq-todo-group-ospology-presents-ways-to-define-a-metrics-strategy-in-your-ospo/) that helps you focus on the metrics that matter most for a particular project.

All of this and more will have an impact on the interpretation of any open source metrics. The real experts are the people who are involved in the day to day work on a project. In addition to focusing on the goals, you might also need to spend some time looking at trends related to who participates in the community and how they participate to get an overall feel for the project and who you might want to reach out to for more details. You need to involve key people from the project / community that you are measuring, since they can help you interpret the metrics and any trends identified in ways that make the most sense for that particular project as described in more detail in the "Step 2: Diagnosis" section. If you haven’t already read [Beyond the Repository](https://cacm.acm.org/magazines/2023/10/276630-beyond-the-repository/fulltext) by Amanda Casari, Julia Ferraioli, and Juniper Lovato, I recommend pausing and reading this 6-page article now.

Within the CHAOSS project, we have [software (Augur and GrimoireLab)](https://chaoss.community/software/) that can be used to gather data and identify trends in a neutral way that can be easily audited and tracked over time. However, these Practitioner Guides don’t assume that you are using any particular piece of software, since you may have other metrics tools that work for your particular situation. Regardless of how you are gathering metrics, these guides help you interpret those metrics to draw meaningful and actionable insights to help improve project health.

# Step 1: Identify Trends

Metrics for open source projects can be noisy, with many data points generated by the many activities within a project. One way to cut through this noise is to focus on the trends over time. Rather than looking at what happened yesterday or last week, it can help to start by aggregating your data by month and looking at whether some aspect of your community is improving, staying steady, or declining over the past 3 to 6 months. You can drill down later into the data for a specific day or week to help understand what you see. By looking at the big-picture trends, you can avoid over-correcting or worrying too much about day to day fluctuations.

# Step 2: Diagnosis 

The first action of diagnosing problems or identifying opportunities for improvement is to talk to the people intimately involved in the project. Show them the data and ask what might be causing the issues. Project leaders and community members might not know what is causing the problems, so each guide should have some tips for exploring areas and potential ideas for where to look and how to diagnose specific issues or find opportunities to improve.

When deciding if something is a problem or concern that needs to be addressed, the first question is whether the issue might be a temporary fluctuation instead of a real problem. What else is happening in your community, project, and ecosystem? Was there a big conference, major release, vacation season, or other things that impacted people's time to make contributions? It can help to overlay these types of milestones on a graph to understand their impact better, and if it looks like there is an impact, wait a month or two and see if the metric(s) rebound after the temporary disruption. As mentioned earlier, this is why it’s so important to have people involved in the project daily, helping to interpret what you are seeing in the metrics. 

An excellent example of a temporary fluctuation is when there are downward trends in July / August and December / January if you have a lot of contributors in places where these are vacation or holiday seasons. A downward trend shows that people are taking some time off to rest and recharge, which is likely a positive sign for the long-term sustainability of your project, instead of a problem.

If you’ve decided that the problem will likely be ongoing and not temporary, then it’s time to start thinking about what might be causing the issue. This will likely be metric-specific and will be covered in more detail in the Practitioner Guides for specific topics.

# Step 3: Gather Additional Data if Needed

At this point, if you know what you need to improve and how to improve it, you can skip this step for now. You can always return to it if you make changes but don’t see any improvements over the next few months.

In other cases, you should look into an area in more detail before deciding what improvement actions to make. The Practitioner Guides for specific topics will include additional metrics that can be used to gather additional data to diagnose specific problems.

# Step 4: Make Improvements

It is important for this step to have buy-in from the community and project leadership before you start taking action toward making improvements. Not having support from the project could lead to changes being ineffective, disruptive, or even damaging for the project and the people contributing to it.

Open source projects, communities, and ecosystems are complex; changes you make in one area might impact other parts of the project. Many people working on open source projects are likely to be busy with little time for additional work, so it’s important not to overload people to the point of burnout. For these reasons, it is usually best to focus on no more than 2 or 3 improvement actions to make at one time. 

Like with the other steps, the Practitioner Guides for specific topics will include more details on how to make improvements for that topic.

# Step 5: Monitor Results 

An important step toward knowing whether your actions to improve a topic have been effective is to continue measuring and then monitor those results. At a minimum, you’ll probably want to monitor it for 2 or 3 months (more for complex changes) before deciding whether your actions are starting to be effective. Remember that if anything happens that might cause temporary fluctuations, you’ll want to increase that timeframe. 

You should also continue to monitor it over the long-term to see if your improvements continue to have an impact. A frequent pattern is that improvements tend to continue while people are focused on them but then can backslide if people fall into old patterns and stop making improvements. You might find yourself cycling through these steps to renew people’s interest and continue making improvements. 

# Cautions and Considerations

* When interpreting metrics and making improvements in your open source project, you should always think first about the people involved in your project and how these changes might impact them (positively and negatively).
* Always have the people working on the project involved in gathering and interpreting the metrics and in any potential improvement actions you might make.
* Every project is a little different, so it’s essential to interpret the metrics in light of a project’s individual needs and ways of operating.
* Avoid using metrics to compare projects against each other when possible, but if you need to compare projects, make sure that you are only comparing projects with similar characteristics. Just a few of the many examples include, Javascript projects will have very different characteristics and patterns than C / C++ projects; foundation-owned projects will be different from projects driven out of corporations; and a project the size of Kubernetes will be nothing like a project producing a small library or package.
* Be careful never to set yourself up for people to weaponize your metrics, and be very careful with metrics that can be used to compare people against each other in ways that might result in the punishment of individuals.
* Remember that automation and bot activity can influence the interpretation of many metrics, so it’s essential to understand how automation and bots might influence your results.

# Additional Reading

* [Practitioner Guide series](https://chaoss.community/about-chaoss-practitioner-guides/) with guides to help you improve responsiveness, contributor sustainability, organizational participation, and more.
* For more cautions, considerations, and best practices, please read [Beyond the Repository](https://cacm.acm.org/magazines/2023/10/276630-beyond-the-repository/fulltext) by Amanda Casari, Julia Ferraioli, and Juniper Lovato.
* Video of a panel related to developing a [metrics strategy for your OSPO](https://community.linuxfoundation.org/events/details/lfhq-todo-group-ospology-presents-ways-to-define-a-metrics-strategy-in-your-ospo/) and a blog post about [building an open source strategy](https://blogs.vmware.com/opensource/2020/03/03/open-source-strategy/) and using metrics to determine success. 
* [CHAOSS Software](https://chaoss.community/software/)

# Feedback

We would love to have feedback to learn more about how people are using the CHAOSS Practitioner Guides and how we can improve them over time. Please complete this [short survey](https://forms.gle/w3B1gBH8kp3rPbhr8) to provide your feedback.

# Contributors

The following people contributed to this guide:

* Dawn Foster
* Chan Voong
* Luis Cañas Díaz
