---
layout: essay
type: essay
title: "Project Effort Estimation"
# All dates must be YYYY-MM-DD format!
date: 2023-12-14
published: true
labels:
  - Software Engineering
  - Learning
---

<img width="100%" class="rounded py-4" src="../img/project-effort-banner.png">

## The Task

In completing the assigned task, I followed the procedure of providing time estimates for newly added issues in the project, including the identifier of the person making the estimate. It's acknowledged that these estimates are likely to be inaccurate, but their utility lies in aiding project planning and coordination. I meticulously tracked the effort invested in each issue and, upon resolution, added the actual effort expended. For effective tracking, I opted to integrate a timer extension into IntelliJ. The collected effort data, as outlined in the assignment, is intended for a study on error in effort estimation by novice software engineers. Participants were encouraged to use a timer extension to enhance data accuracy, with the incentive of receiving extra credit for providing high-quality data. This process highlights the importance of accurate record-keeping for research purposes within the context of the project.

## Making Effort Estimates

I developed my effort estimates by leveraging both my experience and an assessment of the perceived difficulty of each task. Initially, as I didn’t have a clear idea of how difficult these tasks would be, I frequently under-or-overestimated the difficulties. To enhance accuracy, I created a "difference" column, which calculates the variance between the actual effort (comprising coding and noncoding efforts) and the estimated effort.

To visually represent these differences, I applied conditional formatting to the difference column, utilizing a range of color intensities. Upon reviewing the formatted cells, it's evident that the initial estimates for the first 25 tasks were notably inaccurate, as indicated by harsher colors. However, as the tasks progressed, the colors in the corresponding cells became less intense, reflecting a convergence between the estimated and actual effort.

The evolution in color intensity suggests a learning curve in refining my estimates. While the initial tasks may have been more challenging to predict accurately, the subsequent tasks demonstrate an improvement in precision as I drew upon my growing understanding of the project's requirements and vision. This iterative process allowed me to progressively enhance the accuracy of my effort estimates based on the evolving dynamics of the project.

## Why bother, when it can be inaccurate?
Despite the occasional inaccuracies in the estimations, there are tangible benefits to making effort estimates in advance. In practical contexts, such as professional settings, providing estimates serves as a valuable communication tool. It offers other group members an approximation of the time required to complete a task, enabling them to gain insights into the projected timeline. This information is crucial for coordinating efforts within a project or workflow. It allows others to plan their activities accordingly—whether to await the completion of a dependent task or to proceed with other non-dependent tasks in the interim.

So, even if the estimates are not always spot-on, the act of making them facilitates better project management and resource allocation. It fosters transparency and helps establish realistic expectations, contributing to a more organized and efficient workflow. Despite the inherent challenge of predicting effort accurately, estimations are a valuable tool for effective project planning and coordination.

A noteworthy example of the impact of estimates is evident in the development and integration of the LLM chatbot into the website. While initial estimates were significantly off, leading to continuous challenges in getting it to function properly, the experience prompted a strategic decision. Since we had spent a week on this part of our project, I opted to redirect my effort towards initiating the development of the website, and leave my other team members to work out the chatbot instead. This adaptive approach showcases how estimation, even when imperfect, can guide timely and informed decisions in the project development process.

## What's the benefit?
There is a definite benefit to tracking the actual effort expended on these issues. As previously mentioned, this practice is essential for maintaining a clear understanding of task completion within the project timeline. Knowing precisely when someone has concluded a particular task is instrumental in orchestrating seamless workflow transitions. It enables efficient decision-making regarding whether team members should proceed with other tasks while awaiting the completion of a specific assignment.

By consistently monitoring the actual effort invested in each issue, project managers and team members gain real-time insights into progress. This information not only aids in gauging project timelines but also facilitates proactive adjustments to resource distribution. Additionally, it serves as a valuable dataset for retrospective analysis, contributing to improved future planning by identifying patterns and refining the accuracy of future effort estimates. In essence, tracking actual effort expended enhances project transparency, fosters efficient resource utilization, and lays the groundwork for continuous process improvement in the future.

## Data Collection
I monitored my actual effort by calculating the time spent on an issue, derived from the difference between the reported time from Darkyen's Time Tracker and the time I initiated work on the respective task. However, I acknowledge that the accuracy of this tracking method fluctuated. The variability arises from instances where noncoding times may not be directly correlated with productive non-coding efforts on the task at hand. In some cases, these noncoding intervals might be attributed to external factors, distractions, or engagements unrelated to the intended non-coding efforts for the specific issue. Consequently, while this tracking approach provided a quantitative measure of effort, its precision was influenced by the nuanced nature of noncoding activities and potential diversions from the intended focus.

## View Data
If you want to view the data collected, [see this spreadsheet](https://docs.google.com/spreadsheets/d/e/2PACX-1vSV459Z-bALjHDeTYfD1Rsv1V8Ka8-GkHGRoEKHDCssPwa_Rf6OQA-5LJnhxRDrrI0dgazFsfa80R3V/pubhtml?gid=0&single=true).

This data was collected during the development of the [ITS AskUs Project](https://echung32.github.io/projects/uh-its-askus-chatbot.html).
