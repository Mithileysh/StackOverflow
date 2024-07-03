# StackOverflow

DATASET

Data from StackOverflow, a popular and efficient Q&A website,
was used for our study. This is considered one of the most prominent forums in software
development and is used in software engineering studies. The popularity of this website is
proven by the fact that as of March 2021, there are 14 million registered users, and this
website has received more than 21 million queries and 31 million answers. Moreover, the
data is easily accessible through Stack Exchange Data Explorer, which is an open-source tool
that is used to run random SQL queries as opposed to public data from the Exchange
network.

In the initial stage, the questions, answers tags, and other metadata
were extracted from the StackOverflow dump. This data is filtered to find the questions
related to energy: “Energy Efficiency (EE)” and “Energy Consumption (EC)”. The tags from
these questions extract the questions from the StackOverflow. The data explorer used is
StackExchange, and data collection is done using SQL queries related to tag and date. The
tags used for collecting data include power management, power-saving, CPU usage, energy,
EE, EC, CPU architecture, cuda, and battery. The duration of the study was from 01-01-2014
to 31-03-2022. Appendix I shows the partial sample of data collected with the help of Stack
Exchange Data Explorer. The sample consisted of 9484 questions and 10770 answers. The
data is semi-structured with unstructured questions and answers with standard fields such as
ID, CreationDate, Score, ViewCount, Title, and Tags for filtering questions. Most generated
content is untagged, as tags cannot be openly used for an answer or comment type. In case of
misuse of tags or inappropriate tagging, the posts’ content might not be represented by tags
