---
layout: default
title: Pervasive Systems in the IoT era
short: PERSIST-IoT
group: Workshops and Tutorials

dates:
    - info: Abstract registration
      date: April 1, 2019
    - info: Submission deadline
      date: April 8, 2019
    - info: Acceptance notification
      date: May 5, 2019
    - info: Camera ready deadline
      date: May 12, 2019
    - info: Workshop day
      date: July 2, 2019
committees:
    - role: General Chairs
      people:
       - name:        Valeria Loscrì 
         affiliation: "INRIA Lille-Nord Europe, France"
       - name:        Giuseppe Ruggeri 
         affiliation: "University Mediterranea of Reggio Calabria, Italy"
       - name:        Anna Maria Vegni  
         affiliation: "Roma Tre University, Italy"
    - role: TPC Chairs
      people:
       - name:        Syed Hassan Ahmed  
         affiliation: "Georgia Southern University, USA"
       - name:        Carlos Tavares Calafate 
         affiliation: "Universitat Politècnica de València, Spain"
       - name:        Ivan W.H. Ho  
         affiliation: "The Hong Kong Polytechnic University, Hong Kong"
       - name:        De-Nian Yang 
         affiliation: "Institute of Information Science Academia Sinica, Taiwan"
    - role: Steering Committee
      people:
       - name: Abderrahim Benslimane 
         affiliation: University of Avignon, France
       - name: Kwang-Cheng Chen 
         affiliation: University of South Florida, USA
       - name: Pietro Manzoni 
         affiliation: AUniversitat Politècnica de València, Spain
    - role: TPC Members
      people:
       - name: Anna Maria Mandalari 
         affiliation: Imperial College London, UK    
       - name: Antoine Gallais
         affiliation: Inria Lille - Nord Europe, University of Strasbourg, France
       - name: Antoine O. Berthet
         affiliation: CentraleSupélec, Université Paris-Saclay, France      
       - name: Antonella Molinaro 
         affiliation: University of Reggio Calabria, Italy
       - name: Antonino Orsino 
         affiliation: Ericsson, Helsinki Area, Finland
       - name: Antonio Iera
         affiliation: University of Reggio Calabria, Italy
       - name: Chaker Kerrache
         affiliation: University of Ghardaia, Algeria
       - name: Chih-Hang Wang
         affiliation: Academia Sinica, Taiwan (R.O.C.)
       - name: Claudia Campolo 
         affiliation: Universityof Reggio Calabria, Italy         
       - name: Enrico Natalizio 
         affiliation: LORIA, Université de Lorraine, France
       - name: Jian-Jhih Kuo  
         affiliation: National Chung Cheng University, Taiwan (R.O.C.)
       - name: Juan Carlos Cano
         affiliation: Universitat Politècnica de València, Spain              
       - name: Luca Bedogni 
         affiliation: Univesity of Bologna, Italy
       - name: Marco Di Felice 
         affiliation: University of Bologna, Italy
       - name: Marica Amadeo  
         affiliation: University of Reggio Calabria, Italy
       - name: Massimo Condoluci
         affiliation: Ericsson AB, Kista, Sweden
       - name: Nathalie Mitton
         affiliation: Inria Lille-Nord Europe / FUN, France
       - name: Nicola Zema
         affiliation: LRI (Laboratoire de Recherche en Informatique), Université Paris-Sud
       - name: Oscar Alvear
         affiliation: University of Cuenca, Ecuador
       - name: Sema Oktug
         affiliation: Istanbul Technical University, Turkey

---

## ACM MobiHoc Workshop on Pervasive Systems in the IoT Era (PERSIST-IoT)

### [>> Workshop website, call for papers, submission instructions <<](http://www.grc.upv.es/persist-iot2019/)
{: style="text-align: center; margin-bottom: 1em;" }




{% include program-online.html type="ws-mobile-health" %}

### Call For Papers

Leveraging on the global interconnection of billions of tiny smart objects, the Internet of Things (IoT) paradigm is fostering the idea of Pervasive Smart Systems (PSSs), where all the data gathered by different “things” can be analyzed and used to improve the livability, the safety and the security of the environment, and to make IoT user lives easier. However, despite the research advancements in recent years, many open issues still prevent the full realization of such vision.

To meet the requirements of PSSs, telecommunication systems should deliver significantly high data rates, traffic capacity, connection density, energy efficiency, as well as small latencies. Being massively distributed into the environment, smart things may generate, collect, exchange and process big data, provide distributed services, offer computational resources, and cooperate to perform some tasks locally, as well as to delegate their execution to more powerful nodes in the cloud or at the network edge. In addition to the traditional pull-based data delivery, push-based and publish/subscribe traffic patterns must be supported. To accommodate newly emerging services, the network infrastructure should be agile, cost effective and possibly softwarized. Finally, meeting security and privacy requirements will play a fundamental role in the PSSs; indeed, without effective mechanisms, attacks and malfunctions in the IoT will outweigh any of their benefits. 

The PERSIST-IoT workshop aims to solicit a collection of innovative papers reporting the most recent advancements in the fields of smart network architecture protocols and practical implementations enabling IoT for smart systems applications. Topics of interests include, but are not limited to the following:

Topics of interests could be:
- Models of network component interactions for IoT systems;
- Distributed sensing and control in pervasive systems;
- Mobile-aware cloud computing models, infrastructures, and approaches for pervasive systems;
- Mobile edge computing for smart environments;
- Crowdsourcing in smart environments;
- Novel communication protocols for M2M/MTC communication;
- Novel networking paradigms (e.g., ICN, SDN) for IoT;
- Energy efficient solutions for IoT;
- Reliability, security, privacy and trust in pervasive systems;
- Business models to promote user collaboration and resource sharing in pervasive systems;
- Interaction of human-IoT for pervasive systems
- Social networking in IoT architecture and middleware;
- Social IoT models, e.g., co-location, co-work, ownership, and etc.
- Cyber-physical-social security for pervasive systems
- Social-based routing protocols and architectures for pervasive systems
- Testbeds, applications, business, standards, and social issues



{% include dates2.html dates=page.dates %}

<div class="row">
  <div class="col-sm-6 col-sm-offset-3">
    <a href="mailto:{% for person in page.committees[0].people %}{% if person.email and person.email != "" %}{% unless forloop.first %},{% endunless %}{{ person.email }}{% endif %}{% endfor %}?subject=[{{ page.short }}]" class="btn btn-primary btn-block" role="button">Contact Workshop Chairs</a>
  </div>
</div>


### Committees

{% include committees.html committees=page.committees %}
