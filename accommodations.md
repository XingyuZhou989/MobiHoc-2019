---
layout: default
title: Accommodations
group: Attendee Information

hotels:
- id: fourpoints
  name: Marriott Four Points by Sheraton Catania Hotel and Conference Center
  rates: €113 (double single) / €133 (double/twin)
  amenities: [Conference Hotel, Free WiFi]
  address: Via Antonello da Messina 45, Aci Castello, Catania, 95021, Italy
  url: https://www.marriott.com/hotels/travel/ctasi-four-points-catania-hotel-and-conference-center/
  phone: +39 095 7114111 | fax. +39 095 271 380
  reservation-form: "Form_MobiHoc_2019_eng.pdf"
  map: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3163.545421118681!2d15.134358315416778!3d37.542211679802485!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1313fb79d73a3ec9%3A0x47b27df5bd303097!2sFour+Points+by+Sheraton+Catania+Hotel+%26+Conference+Center!5e0!3m2!1sen!2sus!4v1538685222875"
  image: fourpoints.png
  expanded: true
  note: "To get the agreed conference rate, please download, fill, and sign the <a href=\"https://www.sigmobile.org/mobihoc/2019/Form_MobiHoc_2019_eng.pdf\">hotel reservation form</a>  and send it to <a href=\"mailto:booking@fourpointscatania.com\">booking@fourpointscatania.com</a>."

- id: Acicastello
  name: Grand Hotel Baia Verde, Acicastello
  rates: €111+
  amenities: [Free Wifi, Free Parking]
  address: Via Angelo Musco, 8/10, Aci Castello, Catania, 95021, Italy
  url: https://www.baiaverde.it/en/
  reservation-link: https://www.hotels.com/ho242848/?q-check-out=2019-07-06&q-check-in=2019-07-03
  map: "https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d1581.7967858874256!2d15.133151858215141!3d37.54107689495072!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e2!4m5!1s0x1313fb7bdfc29aa7%3A0x89f1c059904c2aab!2sGrand+Hotel+Baia+Verde%2C+Via+Angelo+Musco%2C+Aci+Castello%2C+Province+of+Catania%2C+Italy!3m2!1d37.5399421!2d15.132444699999999!4m5!1s0x1313fb79d73a3ec9%3A0x47b27df5bd303097!2sFour+Points+by+Sheraton+Catania+Hotel+%26+Conference+Center%2C+Via+Antonello+da+Messina+45+Aci+Castello%2C+95021+Catania+CT%2C+Italy!3m2!1d37.542211699999996!2d15.136547!5e0!3m2!1sen!2sus!4v1538690420866"
  image: grand-hotel-baia-verde.jpg
  expanded: true

- id: zeus
  name: Zeus Residence Hotel
  rates: €75 (single, double, or twin)/ €90 (triple room, 1 double bed + 1 bed, up to 4)
  amenities: [Free Wifi, Free Parking]
  address: Via Antonello da Messina, 8, Aci Castello, Catania, 95021, Italy
  url: http://zeusresidencehotel.it/en/
  reservation-link: 
  map: "https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d1581.7863488683083!2d15.13421735818301!3d37.54156884495066!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e2!4m5!1s0x1313fb797a9d8973%3A0xc879b8c8cc771e24!2sZeus+Residence+Hotel%2C+Via+Antonello+da+Messina%2C+Aci+Castello%2C+Province+of+Catania%2C+Italy!3m2!1d37.540926!2d15.1341415!4m5!1s0x1313fb79d73a3ec9%3A0x47b27df5bd303097!2sFour+Points+by+Sheraton+Catania+Hotel+%26+Conference+Center%2C+Via+Antonello+da+Messina+45+Aci+Castello%2C+95021+Catania+CT%2C+Italy!3m2!1d37.542211699999996!2d15.136547!5e0!3m2!1sen!2sus!4v1538690708266"
  image: zeus.jpg
  expanded: true
  note: "Single, Double or Twin Room: 75 euros per night per room. Triple Room (1 double bed+1 bed): 90 euros per night per room up to 4. Occupants with additional bed at 15 euros per night per room. Local taxes not included. Interested attendees who want to book a room can contact the hotel by email at <a href=\"mailto:info@zeusresidencehotel.it\">info@zeusresidencehotel.it</a> mentioning the ACM MobiHoc 2019 conference reservation."

---

# {{ page.title }}

If you are looking for a hotel to stay during ACM MobiHoc 2019, you might want to consider the following hotels which are located in or close to the conference venue:

**Please keep in mind that the listed prices are subject to change daily and/or seasonally**

{% comment %}
- [Marriott Four Points by Sheraton Catania Hotel and Conference Center]() To get the agreed conference rate, please download, fill, and sign the [hotel reservation form]({% asset Form_MobiHoc_2019_eng.pdf @path %}) and send it to [booking@fourpointscatania.com](mailto:booking@fourpointscatania.com).
- [Grand Hotel Baia Verde, Acicastello](https://www.baiaverde.it/en/)
- [Zeus Residence Hotel](http://zeusresidencehotel.it)
{% endcomment %}

<div class="panel-group" id="accordion">
{% for hotel in page.hotels %}
{% include hotel.html expanded=hotel.expanded %}
{% endfor %}
</div>
