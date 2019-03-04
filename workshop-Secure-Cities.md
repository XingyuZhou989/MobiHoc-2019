---
layout: default
title: Secure-Cities
short: Secure-Cities
group: Workshops and Tutorials

dates:
    - info: Submission deadline
      date: April 1, 2019
    - info: Acceptance notification
      date: May 5, 2019
    - info: Camera ready deadline
      date: May 12, 2019
    - info: Workshop day
      date: July 2, 2019
committees:
    - role: TPC Chairs
      people:
       - name:        Syed Hassan Ahmed 
         affiliation: Georgia Southern University, USA
         email:       sh.ahmed@ieee.org  
       - name:        Danda B. Rawat
         affiliation: Howard University, Washington D.C., USA
         email:       db.rawat@ieee.org
       - name:        Jaime Lloret
         affiliation: UPV, Valencia, Spain
         email:       jlloret@dcom.upv.es 
       - name:        Min Song
         affiliation: Stevens Institute of Technology, USA
         email:       Min.Song@stevens.edu           
    - role: Technical Program Committee
      people:
       - name:        Di Zhang
         affiliation: Waseda University, Japan
       - name:        Suzan Bayhan
         affiliation: University of Helsinki, Finland
       - name:        Ali Kashif Bashir
         affiliation: University of the Faroe Islands, Denmark
       - name:        Zhiwei Yan
         affiliation: CNNIC, China
       - name:        Marica Amadeo
         affiliation: University "Mediterranea" of Reggio Calabria, Italy
       - name:        Wael Guibene
         affiliation: Intel Labs, San Jose, California, USA
       - name:        Muhammad Faran Majeed
         affiliation: Asian Institute of Technology, Thailand
       - name:        Cormac J. Sreenan
         affiliation: University College Cork, Ireland
       - name:        Rasheed Hussain
         affiliation: University of Amsterdam, Netherland
       - name:        Imran Khan 
         affiliation: Schneider Electric, France
       - name:        Zeeshan Pervez
         affiliation: University of West Scotland, United Kingdom
       - name:        Kishwer Abdul Khaliq
         affiliation: University of Bremen, Germany
       - name:        Fatima Hussain
         affiliation: Ryerson University, Canada
       - name:        Adnan Shahid
         affiliation: Taif University, Kingdom of Saudi Arabia
       - name:        Syed Ali Hassan
         affiliation: SEECS, NUST Pakistan
---

## 2nd ACM MobiHoc Workshop on Networking and Cybersecurity for Smart Cities (Securing Smart Cities)

### [>> Submission Website <<]()
{: style="text-align: center; margin-bottom: 1em;" }


{% include program-online.html type="ws-mobile-health" %}

### Call For Papers

Call for Papers: 
Cities have been incorporating new technologies for several years, but lately the rate of technology adoption has increased and cities around the world are becoming smarter. Furthermore, plethora of networking technologies and connectable devices made it more convenient to build smart eco systems and connected commodities that can help us predict the Smart Cities to become reality very soon. The key applications could be ranging from Smart Campuses for education, connected Hospitals for better treatment and medical information sharing among doctors & patients, Smart Watering & Gardening systems at the city level to reserve natural resources, smart fishing, Smart & connected transportation systems, and many more to name. To be precise, Internet of Things (IoT) can bring noticeable efforts to connect various entities yet those efforts are prone to cyber-attacks. Likewise, every new technology and innovation brings new challenges and problems. In this workshop, we are focusing on cyber security-related problems that currently affect or will affect cities in general around the world, whether considered smart or not. These problems would impact the city government, residents, and the businesses and other organizations that conduct business there. Keeping in mind the new technologies and life in a smarter city, let’s consider what could happen if one or more technology-reliant services don’t work. What would be commuting look like with non-functioning traffic control systems, no street lights, and no public transportation? How would citizens respond to an inadequate supply of electricity or water, dark streets, and no cameras? What if garbage collection is interrupted in summertime and stinks up the streets? We believe, it would be unpleasant and cause a lot of chaos in any city.

We expect this workshop to be one of the key steps towards collecting researchers and developers to get under one roof and pave through the policy making and providing interesting insights of the following topics but not limited to: 

-	Cyber Security Testing Challenges
-	Poor or Nonexistent Security Issues
-	Encryption Issues 
-	Computer Emergency Response Maneuvers 
-	Protection against Large and Complex Cyber Attack
-	Patch Deployment Issues 
-	Insecure Legacy Systems 
-	Simple Bugs with Huge Impact 
-	Public Sector Issues 
-	Cyber Attack Emergency Plans 
-	Susceptibility to Denial of Service 
-	Privacy issues in Intelligent Transportation
-	Cyber Forensics & Challenges 
-	Big Data Analysis for Cyber Security in Smart Cities

{% include dates2.html dates=page.dates %}

<div class="row">
  <div class="col-sm-6 col-sm-offset-3">
    <a href="mailto:{% for person in page.committees[0].people %}{% if person.email and person.email != "" %}{% unless forloop.first %},{% endunless %}{{ person.email }}{% endif %}{% endfor %}?subject=[{{ page.short }}]" class="btn btn-primary btn-block" role="button">Contact Workshop Chairs</a>
  </div>
</div>


### Committees

{% include committees.html committees=page.committees %}
