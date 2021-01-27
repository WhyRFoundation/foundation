---
layout: post
permalink: /2021/hackathon/
robots: noindex
---

<img src="/foundation/images/fulls/2021/hackathon_pwc/text_matching.jpg" class="fit image">


## Winners

### 1st place

- Team: Górnicy Carla Friedricha Team
- Solution: [github.com/pfilo8/WhyR-Hackathon-2021](https://github.com/pfilo8/WhyR-Hackathon-2021)
- Team Members: 
    * [Łukasz Łaszczuk](https://www.linkedin.com/in/%C5%82ukasz-%C5%82aszczuk-141361187/)
    * [Robert Benke](https://www.linkedin.com/in/robert-benke-396b56175/) 
    * [Patryk Wielopolski](https://www.linkedin.com/in/patryk-wielopolski/)

### 2nd place

- Team: Eskisehir R Users Group
- Solution: [github.com/ugurdar/PwCPoland](https://github.com/ugurdar/PwCPoland)
- Team Members: 
    * [Ugur DAR](https://www.linkedin.com/in/ugurdar/)
    * [Mustafa CAVUS](https://www.linkedin.com/in/mustafacavusphd/)

### 3rd place

- [Katarzyna Sornat](https://www.linkedin.com/in/katarzynasornat)
- Solution: [github.com/katarzynasornat/text_matching_hackathon](https://github.com/katarzynasornat/text_matching_hackathon)

### Why Hackathon?

Hackathons are events where enthusiasts of a specific topic gather in one place to work together on challenges that arose for a particular community.<br>

Hackathons tend to be timepressure events, where solutions need to be created quicky and  active cooperation between participants is necessary. To set the pace of the event, participants are divided into teams which compete to prepare the most valuable solution and win a prize. <br>

For a participant such an undertaking is a great chance to: <br>

<ul>
<li>develop the ability to work in group</li>
<li>learn from more experienced practitioners</li>
<li>take part in lectures related to data analysis</li>
<li>have a remarkable networking experience</li>
<li>participate in healthy and fair competition</li>
<li>test his/her skills in comparison with the others</li>
<li>win prizes</li>
<li>learn new presentation techniques</li>
<li><b>brainstorm new business use cases</b></li>
</ul>

### Partner

<img src="/foundation/images/fulls/2021/hackathon_pwc/PwC_fl_c.png" class="fit image">

We are passionate professionals from Financial Crime Unit in PwC Poland with hands-on experience in financial regulations area.

Our comprehensive know-how gained on over 100 successfully delivered projects allows us to support our clients from Target Operating Model design to Operational Delivery. 

In PwC Financial Crime Unit, we provide innovative approaches supported by a set of solutions based on AI (Artificial Intelligence) and RPA (Robotic Process Automation) to ensure best in class, efficient services. 

We are glad to support Why R and be a part of your community! 

### The challenge

> Academic papers are not cited by every researcher in proper format, for academic search engines it is problematic to find citations per each paper. As papers are cited in different formats, also with some typos, matching citations with the title of the papers is a complicated task. 

The challenge was about matching name of academic papers in different format. In the zip file, you could find four datasets: tableA.csv, tableB.csv, train.csv, valid.csv

Please find the dataset [here](https://github.com/WhyRFoundation/foundation/blob/master/2021/data_hackathon.zip)

- tableA.csv : It contains title, authors, venue, year columns. It gives information, what are the names of the academic papers, who are the authors, on which journals they were published. 
- tableB.csv : It contains title, authors, venue, year columns. It gives information, what are the names of the academic papers, who are the authors, on which journals they were published.
- train.csv : It contains, ltable_id, rtable_id, label columns. ltable_id is showing IDs of academic papers from tableA.csv. rtable_id is showing IDs of academic papers from tableB.csv. label coloumn is the information, if those articles are matched or not. 
- valid.csv : It contains, ltable_id, rtable_id, label columns. ltable_id is showing IDs of academic papers from tableA.csv. rtable_id is showing IDs of academic papers from tableB.csv. You are expected to put your predictions to label coloumn. 

In tableA.csv and tableB.csv you had same academic papers but their title, author names are in different formats. This brings the challenge. The main goal was to develop a model which will succesfully match those names. Using train.csv file, participants got information about which of those academic papers are matched. 

After training the models using train.csv files, the validation.csv file was used to provide binary predictions (0 - 1). The pairs could be found on that file. 


### Competition Rules

Since the event was a competition with symbolic prices, we graded solutions. Solutions were scored based on accuracy & F1 of the predictions and based on the creativity of the solution.

### Mentors and Judges

To provide solutions of the highest quality we had invited data science experts that were available during the event for mentoring. At the time of closing presentations mentors had become judges of solutions and did score them based on the competition rules.

<img src="/foundation/images/fulls/2021/hackathon_pwc/marcin_and_olgun.jpg" class="fit image">

- Olgun Aydin, Technical Lead, Data Science Team at PwC FCU
- Marcin Kosinski, Leader of Why R Foundation

### Webinar

The hackathon was opened by a webinar!

**Analyzing anomalies in the business processes using R and D3.js**

<img src="/foundation/images/fulls/2021/hackathon_pwc/text_matching_speakers.jpg" class="fit image">

Agenda of the webinar

- What do we do in R&D Unit at the Financial Crime Unit(FCU) ?
- Anomalies in the business processes using 
- Finding anomalies using Self Organizing Maps (SOM) in R
    * Quick intro about anomaly detection concept
    * How to detect anomalies using SOM ?
    * SOM in R
- Application: 
    * Applying SOM to find anomalies using R
       * Example: Financial process
    * Finding anomalies and bottlenecks using D3.js
       * Example: Recruitment process
       
<iframe width="750" height="480" src="https://www.youtube.com/embed/cBINdqdk6NE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



### Registration

The Text Matching Hackathon was a free event. However, the registration was required.


### Event details

- Place: Remote Global Challenge
- Date: 2021-01-26 - 2021-01-27
- Start     -  7:00pm UTC /  8:00pm CET 2021-01-26
- End       -  8:00pm UTC /  9:00pm CET 2021-01-27
- Decisions - 10:00pm UTC / 11:00pm CET 2021-01-27

- For? For everyone interested in text mining!
- Tech? No tech skills are needed to participate in the event!

### Organizer

Why R? Foundation - [whyr.pl](http://whyr.pl).

<img src="/foundation/images/profile.jpg">
