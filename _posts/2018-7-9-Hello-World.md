---
layout: post
title: Hello World
---

Introducing Somno. An agile, 21st century, digital Anaesthetic record that's built for the people that use them


<h2>What?</h2>
2 years ago I pitched the idea of an open source electronic anaesthetic chart at a <a href="http://nhshackday.com/">NHS Hack Day</a> in London. I'd brought along an old anaesthetic monitor my hospital was about to send to the auctioneers and managed to get a team together. I was pretty stunned by how much we got done that weekend and thought there was some real potential with the idea and since then have dabbled with the code base, mostly just rewriting how we graphed observations and bending C3.js to sort of create a timeline for medications. Progress was slow due to work and a steady stream of post graduate medical exams but now, thanks to a grant from the Apperta Foundation's Access to Innovation Fund, this project is really starting to come to life.

<h2>The Problem</h2>
I'm an Anaesthetist. Two thirds of hospital patients will see one us during their hospital stay and we're second only to Intensive Care as the most data rich specialties but there's a problem. Even in some of the most digitally mature hospitals in the country that data is thrown away when it's written down on paper. Worse still there is a huge amount of double handling of information where patient data is transcribed from one system to the front of a paper chart and that may then be transcribed a third time if the patient in question is entered into one of the many fantastic projects being conducted by the Anaesthetic community at the moment such as the National Emergency Laparotomy Audit or any the of trainee led national audits.

The volume of information we get from our monitors is almost impossible to record accurately and contemporaneously while paying full attention to the patient, particularly at key times such as the end of a procedure or during an emergency where attention can be divided by multiple competing tasks. While there are existing systems many suffer from the same problems that afflict the majority of medical software in day to day use. Expensive, designed for billing rather then to help the clinician, clunky infrastructure, poor user experience and closed.

<h2>The Plan</h2>
<h4>User centric design</h4>
Clinical software that is merely functional is not acceptable. The software we use in day to day practice must complement our natural workflow and aid us in our day to day work instead of slowing us down like much of what is already out there. That is why day 1 of this project involved getting together and mapping out the steps in a patients journey through theatres, what the interactions and problems are and where Somno might fit in. We'll also be conducting interviews with other anaesthetists to make sure it suits everyone, not just those who are already true believers in technological solutions and so that it works whether the case is 10 minutes long or 10 hours

![_config.yml]({{ site.baseurl }}/images/brainstorm.jpg)

<h4>Open API's</h4>
Somno is built on top of <a href="https://opal.openhealthcare.org.uk/">Opal</a> a Django framework for healthcare applications. One of it's neat features is every database model automatically has a corresponding API. Digitising paper and then walling it off isn't innovation, it's a barrier to it and an application that has easy to use API's will provide a base for the next phase of technological innovation without allowing vendor lock in. Imagine your electronic record was continually updating your logbook, could fill in NELA for you or allowed you to complete an audit with a couple of lines of code? That doesn't happen with siloed information.

<h4>Interoperability<h4>

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.
