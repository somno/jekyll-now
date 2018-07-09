---
layout: post
title: Hello World
---

Introducing Somno. An agile, 21st century, digital Anaesthetic record that's built for the people that use them


<h2>What?</h2>
2 years ago I pitched the idea of an open source electronic anaesthetic chart at a <a href="http://nhshackday.com/">NHS Hack Day</a> in London. I'd brought along an old anaesthetic monitor my hospital was about to send to the auctioneers and managed to get a team together. I was pretty stunned by how much we got done that weekend and thought there was some real potential with the idea and since then have dabbled with the code base, mostly just rewriting how we graphed observations and bending C3.js to sort of create a timeline for medications. Progress was slow due to work and a steady stream of post graduate medical exams but now, thanks to a grant from the Apperta Foundation's Access to Innovation Fund, this project is really starting to come to life.

![_config.yml]({{ site.baseurl }}/images/theatrepano.jpg)

<h2>The Problem</h2>
I'm an Anaesthetist. Two thirds of hospital patients will see one us during their hospital stay and we're second only to Intensive Care as the most data rich specialties but there's a problem. Even in some of the most digitally mature hospitals in the country that data is thrown away when it's written down on paper. Worse still there is a huge amount of double handling of information where patient data is transcribed from one system to the front of a paper chart and that may then be transcribed a third time if the patient in question is entered into one of the many fantastic projects being conducted by the Anaesthetic community at the moment such as the National Emergency Laparotomy Audit(NELA) or any the of trainee led national audits.

The volume of information we get from our monitors is almost impossible to record accurately and contemporaneously while paying full attention to the patient, particularly at key times such as the end of a procedure or during an emergency where attention can be divided by multiple competing tasks. While there are existing systems many suffer from the same problems that afflict the majority of medical software in day to day use. Expensive, designed for billing rather then to help the clinician, clunky infrastructure, poor user experience and closed.

<h2>The Plan</h2>
<h4>User centric design</h4>
Clinical software that is merely functional is not acceptable. The software we use in day to day practice must complement our natural workflow and aid us in our day to day work instead of slowing us down like much of what is already out there. That is why day 1 of this project involved getting together and mapping out the steps in a patients journey through theatres, what the interactions and problems are and where Somno might fit in. We'll also be conducting interviews with other anaesthetists to make sure it suits everyone, not just those who are already true believers in technological solutions and so that it works whether the case is 10 minutes long or 10 hours

![_config.yml]({{ site.baseurl }}/images/brainstorm.jpg)

<h4>Open API's</h4>
Somno is built on top of <a href="https://opal.openhealthcare.org.uk/">Opal</a> a Django framework for healthcare applications. One of it's neat features is every database model automatically has a corresponding API. Digitising paper and then walling it off isn't innovation, it's a barrier to it and an application that has easy to use API's will provide a base for the next phase of technological innovation without allowing vendor lock in. Imagine your electronic record was continually updating your logbook, could fill in NELA for you or allowed you to complete an audit with a couple of lines of code? That doesn't happen when you lock away your data.

<h4>Interoperability</h4>
Siloed information is annoying, it makes work harder and it's dangerous because eventually people stop looking at it if they can get away with it. Thankfully there are real strides being made with FHiR and openEHR to create common standards that allow clinical systems to talk to each other in a way most people who've written a little code can understand. While there's a lot to do with a limited budget we'll be looking to leverage the currently available resources as much as possible to allow Somno to ingest relevant information such as patient medications and allergies to speed up and enhance the anaesthetic pre-assessment.

<h4>Anaesthetics on the Blockchain</h4>
I'm Joking

<h2>How?</h2>
<p>First off this project has been enabled by a grant from the <a href="https://apperta.org/">Apperta Foundation</a> and I'm extremely grateful to have been one of the successful applicants to the Innovation Fund</p>
<p>David Millar and Fred Kingham of <a href="https://www.openhealthcare.org.uk/">Open Healthcare</a> will be doing alot of the redevelopment and have experience of delivering great healthcare software in the chaotic reality that is the NHS</p>
<p><a href="http://artifactual.co.uk/">Mike Thompson</a> will be conducting user research and doing some initial design work. He was a member of the original hackday team!</p>
<p>Kristian Glass was another member of the hackday team and I'm incredible pleased to have him back to help. He'll be working on redoing how we ingest data with the slightly battered monitor I've bought for the project</p>
<p>In accordance with the conditions of the fund the money had to be administered by a community interest company and I'm really grateful to <a href="https://www.openhealthhub.org/">Open Health Hub</a> for doing so</p>

<h2>What Next?</h2>
We get to work!

The grant is fairly small in the grand scheme of things but should get us from what effectively was the output of a hackday to something that we can pilot in a hospital toward the end of the year (if you would be interested in hosting this I'd love to hear from you!). You'll be able to follow updates on github and i'll try and do a few more blog posts to document the process and out thoughts.

I'd also love to hear from anyone that's interested in the project. Anything you might like to see put in, anything you feel we're doing wrong or if you just want to see how it's looking.


<b>Dr Jakob Mathiszig-Lee</b>
<a href="https://twitter.com/willtube4food">
      <i class="fa fa-twitter"></i> Twitter
</a>
