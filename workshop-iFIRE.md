---
layout: default
title: iFIRE
short: iFIRE
group: Workshops and Tutorials

dates:
    - info: Abstract registration
      date: April 1, 2019
    - info: Submission deadline
      date: April 7, 2019
    - info: Acceptance notification
      date: May 5, 2019
    - info: Camera ready deadline
      date: May 12, 2019
    - info: Workshop day
      date: July 2, 2019
committees:
    - role: Workshop CO-Chairs
      people:
       - name:        Vincenzo Sciancalepore
         affiliation: "NEC Laboratories Europe GmbH, Germany"
         email:       vincenzo.sciancalepore@neclab.eu
       - name:        Marco di Renzo
         affiliation: "CNRS / Paris-Saclay University, France"
         email:       Marco.DIRENZO@l2s.centralesupelec.fr
       - name:        Syed Zaidi
         affiliation: "University of Leeds, UK"
         email:       S.A.Zaidi@leeds.ac.uk
       - name:        Toktam Mahmoodi
         affiliation: "King's College London, UK"
         email:       toktam.mahmoodi@kcl.ac.uk
    - role: TPC Chairs
      people:
       - name:        Maurizio Magarini
         affiliation: "Politecnico di Milano, Italy"
       - name:        Muhammad Mahtab Alam
         affiliation: "Tallin University of Technology, Estonia"
       - name:        Xavier Costa-Perez
         affiliation: "NEC Laboratories Europe GmbH, Germany"
       - name:        Kamesh Namuduri
         affiliation: "University of North Texas, USA"
---

## ACM MobiHoc workshop on innovative aerial communication solutions for FIrst REsponders network in emergency scenarios (iFIRE)

### [>> Workshop website, call for papers, submission instructions <<](http://ifire.neclab.eu)
{: style="text-align: center; margin-bottom: 1em;" }


{% include program-online.html type="ws-iFire" %}

### Call For Papers

The ACM International Workshop on innovative aerial communication solutions for FIrst REsponders network in emergency scenarios (iFIRE '19) will be held on July 2, 2019 in Catania, Italy along with the ACM MobiHoc 2019. It will be the first track of the Workshop on aerial communication technologies to cope with public safety issues.

The public safety is a timely topic that has showed its paramount importance after the major human-driven and natural disasters witnessed during the last few years. According to the American Institute for Occupational Safety and Health, the majority of the victims in many different scenarios are untrained rescuers and even professional first responders. Accurate information gathered from sensors may allow first-responders and volunteers to make better and faster decisions, understand the situation, identify the rescue actions with higher success probability, correctly allocate resources such as number of ambulances, and prevent or mitigate personal risks. Today, even commonly available technologies, such as cellular phones, could save many lives if properly adopted.

There is a compelling need of exploring the feasibility of new technologies, explicitly designed for working in emergency scenarios. Recently in this wide context, the aerial communication has significantly progressed due to longer battery life-time, new international law regulations and microelectronics evolution with lower prices and higher performance. In particular, Unmanned Aerial Vehicles (UAVs) can easily and quickly reach far-away locations, scan carefully the area looking for injured people and autonomously create a communication bridge between first responder networks and victims. However, there are several unaddressed challenges on both communication and computational means that might further improve the reactiveness and efficiency of the first response after a natural disaster or human-driven threat.

The workshop is focused on main upcoming activities about the involvement of UAVs as emergency communication means during emergency situations. It is open to both scientific and industrial communities, and will disclose the latest research achievements in the research field of fine-grained localization, advanced communication between moving objects and optimal UAV-cell coverage. The main motivation is to gather people involved in public safety innovative actions, encompassing both the mathematical frameworks and realistic solutions to bring intelligence and efficiency on board of UAVs.



{% include dates2.html dates=page.dates %}

<div class="row">
  <div class="col-sm-6 col-sm-offset-3">
    <a href="mailto:{% for person in page.committees[0].people %}{% if person.email and person.email != "" %}{% unless forloop.first %},{% endunless %}{{ person.email }}{% endif %}{% endfor %}?subject=[{{ page.short }}]" class="btn btn-primary btn-block" role="button">Contact Workshop Chairs</a>
  </div>
</div>


### Committees

{% include committees.html committees=page.committees %}
