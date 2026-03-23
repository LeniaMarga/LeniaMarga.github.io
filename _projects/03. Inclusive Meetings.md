---
title: Inclusive Meetings
subtitle: Automated mapping of competitive and collaborative overlapping talk in video meetings.
timeline: 2021
description: Inclusive meetings, Future of Work, Data Visualization, Quantitative Analysis, Microsoft Research
featured_image: '/images/content/MSR/patterns_demo.png'
---

Video meetings are notorious for difficulties with conversational turn-taking, which has impacts on inclusion and meeting outcomes. To support more inclusive remote meeting, it would be meaningful to detect non-inclusive behaviours - e.g. someone systematically interrupting the meeting - and design relevant features to support turn taking - e.g. personalized notifications for meeting's attendes, overall meeting inclusion metrics etc. To do so, it is meaningful to be able to automatically detect competitive and collaborative overlapping talk in remote video meetings, in a GDPR-compliant, ethical and non-intrusive manner. With this as the starting point of my internship in Microsoft research, I conducted a data visualization experiment based on automated eyes-off analysis of meeting transcripts, which further evolved into a promising approach of categorising overlapping talk and turn-taking behaviour in meetings. 

Drawing on a series of remote meetings (10 series, 34 total meetings, 52 participants) recorded in July-August 2021 by employees of Microsoft Research, I identified and parametrized patterns of cooperative and competitive overlaps of turns. My analysis shows initial success characterizing people's behaviours as either likely to continue or cede turns based on either the amount of overlap that they produce during other's turns or the amount of overlap they experience in their own turns. With further development and validation, this GDPR-compliant method could be used to measure inclusion in remote and hybrid meetings, and develop meeting's behavior profiles.

The relevant paper presents the scalable automatic process to categorize turn-taking patterns in remote meetings based on eyes-off analysis of meeting transcripts. You can find the publication [here](https://dl.acm.org/doi/10.1145/3491101.3519612).


<br><br>
![](/images/content/MSR/patterns01.png)
Above: An example of initial eyes-in visual analysis of patterns for validation purposes.
<br><br>
![](/images/content/MSR/patterns02.png)
Above: The identified pattern overlap categories. We highlighted short overlaps (Mean=0.92s, Median=0.77s) occuring repeatedly within turns and in the beginning of an overtake (change of turn) as the most promising patterns for further investigation.
<br><br>
![](/images/content/MSR/patterns03.png)
Above: Visual identification of patterns in a multiparty meeting (eyes-off transcripts).
<br><br>
![](/images/content/MSR/patterns04.png)
![](/images/content/MSR/patterns05.png)
Above: Automatic Pattern Identification: Behaviours when initiating turns and when initiating overlap during a turn. This type of automated visual analysis can be meaningful to compare different behaviours of meeting participants within a meeting series, and the basis of developing profiles of turn-taking behaviours.
<br><br>


