---
layout: default
title: TOP-Cars
short: TOP-Cars
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
       - name:        Carla Fabiana Chiasserini 
         affiliation: Politecnico di Torino
         email:       carla.chiasserini@polito.it
       - name:        Sinem Coleri Ergen 
         affiliation: Koc University
         email:       sergen@ku.edu.tr
       - name:        Falko Dressler 
         affiliation: Paderborn University
         email:       dressler@ccs-labs.org
    - role: Web Chair
      people:
       - name:        Francesco Malandrino 
         affiliation: IEIIT-CNR, Italy
    - role: Technical Program Committee
      people:
       - name:        Onur Altintas 
         affiliation: Toyota InfoTechnology Center, USA
       - name:        Donald Grimm
         affiliation: General Motors, USA
       - name:        Mate Boban 
         affiliation: Huawei European Research Center, Germany
       - name:        Francesca Cuomo 
         affiliation: University of Rome La Sapienza, Italy
       - name:        David Eckhoff 
         affiliation: TUMCREATE Singapore
       - name:        Eylem Ekici 
         affiliation: Ohio State University, USA
       - name:        Marco Fiore 
         affiliation: CNR-IEIIT, Italy
       - name:        Jérôme Härri 
         affiliation: EURECOM, France
       - name:        Tim Leinmuller 
         affiliation: DENSO AUTOMOTIVE Deutschland GmbH, Germany
       - name:        Francesco Malandrino 
         affiliation: CNR-IEIIT, Italy
       - name:        Renato Lo Cigno 
         affiliation: University of Trento, Italy
       - name:        Josep Mangues 
         affiliation: CTTC, Spain
       - name:        Miguel Sepulcre 
         affiliation: Universidad Miguel Hernandez de Elche, Spain
       - name:        Seyhan Ucar 
         affiliation: Toyota InfoTechnology Center, USA
       - name:        Alexey Vinel 
         affiliation: Halmstad University, Sweden
---

## 1st ACM MobiHoc Workshop on Technologies, mOdels, and Protocols for Cooperative Connected Cars (TOP-Cars)

### [>> Workshop website, call for papers, submission instructions <<](http://topcars19.polito.it/)
{: style="text-align: center; margin-bottom: 1em;" }


{% include program-online.html type="ws-TOPCARS" %}

### Call For Papers

Providing highly reliable services to connected cars through ICT technologies is one of the most urgent challenges in the field of today’s communication networks. Relevant use cases include safety of car drivers, passengers, and vulnerable users, reduction in pollution and daily commuting time through vehicle traffic management (e.g., in case of road works), support of autonomous driving. In all these scenarios, three tasks are of critical importance. First, the collection of large amounts of data coming from multiple sources like sensors aboard vehicles and smart cities cameras. Second, the transfer of such data from the vehicles to the road and network infrastructure, as well as their exchange between the vehicles, and between the vehicles and the vulnerable users. Third, the storage and processing of the collected information for the deployment of cooperative automotive services and applications, exploiting the caching and computing capabilities of both the vehicles and the network infrastructure.

The TOP-Cars workshop will aim at capturing the research and technology trends that enable the realization of such tasks by soliciting contributions along three main directions. Firstly, solutions that leverage the availability of handheld devices (e.g., smartphones) as well as of sensors and radio interfaces aboard cars, which can act as data sources and prime contact point to deliver warning messages or convenience information to drivers and vulnerable users. Secondly, data analysis techniques and cooperative decision-making mechanisms that provide accurate data checking and generate output useful to the involved users. And, finally, emerging networking paradigms that go beyond the traditional infrastructure-based model, leveraging C2X communication paradigms as well as edge and distributed computing. 

The workshop seeks original work presented in the form of research papers describing new research approaches and results. Highly disruptive work-in-progress and position papers are welcome, provided they focus on particularly innovative solutions or applications for connected care. We also invite authors to submit papers presenting extensive experiences with implementation, deployment, and operation.

Topics of interest for the workshop include, but are not limited to:
-	C2X communications and spectrum sharing
-	mmWave and VLC for vehicular communications
-	Applications and services for connected cars (safety, entertainment, …)
-	Interaction between cars and smart cities infrastructure 
-	Edge computing and distributed computing for vehicular networks
-	Cooperative perception in vehicular networks
-	Cooperative services (e.g., maneuvering and electronic horizon building)
-	Security/trust/privacy in vehicular networks
-	Data analytics and machine learning for vehicular networks
-	Modeling, optimization, and performance evaluation of vehicular networks
-	Results from experimental systems 
-	Simulation of autonomous connected cars and mobility traces.




{% include dates2.html dates=page.dates %}

<div class="row">
  <div class="col-sm-6 col-sm-offset-3">
    <a href="mailto:{% for person in page.committees[0].people %}{% if person.email and person.email != "" %}{% unless forloop.first %},{% endunless %}{{ person.email }}{% endif %}{% endfor %}?subject=[{{ page.short }}]" class="btn btn-primary btn-block" role="button">Contact Workshop Chairs</a>
  </div>
</div>


### Committees

{% include committees.html committees=page.committees %}
