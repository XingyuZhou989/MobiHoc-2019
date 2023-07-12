---
layout: default
title: AIoT
short: AIoT
group: Workshops and Tutorials

dates:
    - info: Paper submission deadline
      date: July 29, 2023 
    - info: Notification of acceptance
      date: August 5, 2023
    - info: Camera-ready version
      date: August 26, 2023
    - info: Workshop event
      date: October 23
committees:

    - role: General Chairs
      people:
       - name:        Fabio Busacca
         affiliation: "University of Catania"
       - name:        Tony Quek
         affiliation: "Singapore University of Technology and Design"
       - name:        Ivan Seskar
         affiliation: "Rutgers University"
       - name:        Ilenia Tinnirello
         affiliation: "University of Palermo"
---

## The First International Workshop on the Integration between Distributed Machine Learning and the Internet of Things (AIoT)

### [>> Workshop website, call for papers, submission instructions <<](https://sites.google.com/view/aiot2023/home)
{: style="text-align: center; margin-bottom: 1em;" }


<!-- {% include program-online.html type="ws-iFire" %} -->

<!-- ### Call For Papers

The ACM International Workshop on innovative aerial communication solutions for FIrst REsponders network in emergency scenarios (iFIRE '19) will be held on July 2, 2019 in Catania, Italy along with the ACM MobiHoc 2019. It will be the first track of the Workshop on aerial communication technologies to cope with public safety issues.

The public safety is a timely topic that has showed its paramount importance after the major human-driven and natural disasters witnessed during the last few years. According to the American Institute for Occupational Safety and Health, the majority of the victims in many different scenarios are untrained rescuers and even professional first responders. Accurate information gathered from sensors may allow first-responders and volunteers to make better and faster decisions, understand the situation, identify the rescue actions with higher success probability, correctly allocate resources such as number of ambulances, and prevent or mitigate personal risks. Today, even commonly available technologies, such as cellular phones, could save many lives if properly adopted.

There is a compelling need of exploring the feasibility of new technologies, explicitly designed for working in emergency scenarios. Recently in this wide context, the aerial communication has significantly progressed due to longer battery life-time, new international law regulations and microelectronics evolution with lower prices and higher performance. In particular, Unmanned Aerial Vehicles (UAVs) can easily and quickly reach far-away locations, scan carefully the area looking for injured people and autonomously create a communication bridge between first responder networks and victims. However, there are several unaddressed challenges on both communication and computational means that might further improve the reactiveness and efficiency of the first response after a natural disaster or human-driven threat.

The workshop is focused on main upcoming activities about the involvement of UAVs as emergency communication means during emergency situations. It is open to both scientific and industrial communities, and will disclose the latest research achievements in the research field of fine-grained localization, advanced communication between moving objects and optimal UAV-cell coverage. The main motivation is to gather people involved in public safety innovative actions, encompassing both the mathematical frameworks and realistic solutions to bring intelligence and efficiency on board of UAVs. -->



{% include dates2.html dates=page.dates %}

<!-- <div class="row">
  <div class="col-sm-6 col-sm-offset-3">
    <a href="mailto:{% for person in page.committees[0].people %}{% if person.email and person.email != "" %}{% unless forloop.first %},{% endunless %}{{ person.email }}{% endif %}{% endfor %}?subject=[{{ page.short }}]" class="btn btn-primary btn-block" role="button">Contact Workshop Chairs</a>
  </div>
</div> -->


### Committees

{% include committees.html committees=page.committees %}
