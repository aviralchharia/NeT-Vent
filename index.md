## NeT-Vent: Providing Affordable Healthcare in Emergency-Disaster Relief

<i>A team of third year undergraduates from [Thapar](https://thapar.edu/), consisting of [Aviral Chharia](https://www.linkedin.com/in/aviralchharia/), Shivu Chauhan, and Shankhaneel Basak recorded a smashing victory at the University of Queensland Engineering Design Hackathon 2020, organized by the School of Mechanical and Mining Engineering, [University of Queensland (UoQ)](https://www.uq.edu.au/), Australia. Around 15 teams from various universities and institutes across India competed in the final round of this hackathon, which began on 8th October, 2020 and lasted two weeks. Dr. Erich Shultz, a Senior Anaesthetist at Brisbane and a team of experts in this area, guided the participating teams during this 2-week journey. The winning team was mentored by [Dr. Bikramjit Sharma](https://med.thapar.edu/facultydetails/MTE3MQ), Assistant Professor. The students also expressed special thanks to [Prof. Ajay Batish](https://med.thapar.edu/facultydetails/MTE1MA), Deputy Director, and [Dr. Vinay Kumar](https://sites.google.com/view/drvinaykumar/home), Associate Professor, for their constant support and words of encouragement throughout the course of this hackathon. Team Net-Vent members brought a variety of skills and experiences to the design challenge. In this blog, they share their experience.</i>

![Fig06](https://user-images.githubusercontent.com/62457915/148015966-5d2d6d88-ae54-45e6-8446-d024b859ac7f.jpg)

## Highlights

• Project NeT-Vent- An Open-Source, Low-Cost, Easy to use and Manufacture Ventilator Design initiative of 03 undergraduates for COVID-19 patients in Emergency Disaster-Relief.

• Designed the Ventilator in PTC-Creo and Control System in Simulink. Made Design improvements and demonstrated correction of airway pressure and volume flow as per patient's requirement in real time with automatic reduction of Pulmonary Barotrauma, a Ventilator-induced Lung Injury.

• IoT-enabling to drastically reduce PPE-Kit requirement and exposure of medical-staff to COVID-19.

• Developed our own PCB Board and circuits in Autodesk-EAGLE. Obtained results were verified through simulation.

### How we Began

In the first master class, we were briefed about the challenge of designing an open-source, low-cost, and easy to manufacture Ventilator that can serve COVID-19 patients requiring emergency mechanical ventilation. At first, we felt a bit overwhelmed about the challenge since we had the mental barrier that we did not have the skills to design an 'Invasive Mechanical Ventilator.' Initially, we started with the BVM- a Bag Valve Mask Ventilation and did an in-depth literature review of the existing techniques and methods while thinking of something novel that we could introduce in existing ventilator designs to make them better. Shankhaneel and I did the research involved and prepared the Computer-Aided Design (CAD) Model of the BVM Ventilator in PTC-Creo, while Shivu designed the Printed Circuit Boards (PCBs) and the Control System for the Ventilator.

### A positive 'can do' approach

In the second master session, Dr. Erich Shultz, MD, impressed upon us the need for research in present-day high-end ventilators instead of BVMs. He told by his experience that BVM-based ventilators should only be used during emergencies when there is a shortage of high-end ventilators. We also had come across enormous disadvantages of BVMs during our literature review. Thus he advised us to research high-end ventilators instead of BVMs. Therefore the news came as a great disappointment since we had nearly completed the CAD model and the control system by this time. We needed to discard our initial idea entirely and start from scratch. Mid Semester Tests were quickly approaching, and we were finding it hard to stick to our project schedule. However, the idea of contributing to the cause of COVID-19 patients provided us with constant motivation. Thus, we tried our best and worked hard even though time was scarce. We told the developments to our faculty advisor Dr. Bikramjit Sharma, who has been guiding us throughout this project. He motivated us to start with the same enthusiasm as before, thus instilling confidence and motivating us. We started afresh, working on the literature review of the current challenges faced in invasive-type high-end mechanical ventilators and thought of some novel ideas to address these challenges while making our Ventilator low-cost and easy to manufacture.

### Working all Nighters
 
The literature review was one of the most important parts, where we re-defined our project based on the new problem statement. After reading various journal papers and research articles, we did a brainstorming session to come up with a novel design idea. We identified the complications on lung health under constant mechanical ventilation and took this as our primary research problem for the journey. With a 48-hour continuous study about various industrial components and parts used in ventilators, we re-designed our CAD model in PTC-Creo and performed its 3D rendering. We also analyzed its performance under standard test conditions. The parts we used in our design are readily available in the market and can be assembled quickly. This made our ventilator design low-cost and easy to manufacture while providing support to patients requiring emergent endotracheal intubation. We noticed that Pulmonary Barotrauma is an issue caused and aggravated with continuous mechanical ventilation of patients. It is caused by incorrect monitoring and the inability of the Ventilator to change according to a patient's breathing cycle resulting in damage to the lungs. This situation is medically known as ventilator-induced lung injury (VILI). So, we took the challenge to design an appropriate control system that will generate feedback to maintain the continuous opening and closing of the associated valves with greater accuracy. The actual control system was modeled and validated in MATLAB and Simulink with various sensors, gains, and feedback systems. We took an input based on real-time clinical data from a reliable source to test our control system. The gains were added according to their proportionality using the control algorithm approach. Finally, we could attain a pattern as to how our mechanical system will perform. At last, we were confident that our design could be helpful to the medical community.

### A day before the final presentation

It was the final presentation day that was the scariest of all. We were confident about the success of our design. However, loading the complete details of our project, the research problem, our simulation results, and other vast amounts of information into a tiny 5-min presentation was a daunting task and demanded much practice. Finally, it was our turn, and we delivered the presentation as per our expectations, hoping for a positive outcome. Our sessions with our faculty advisor Dr. Bikramjit Sharma were where we identified the loopholes in our approach. He guided us on how to approach various research articles in regular meetings. He also enlightened us to find out new domains within our challenge. The very idea of Internet-of-Things (IoT) was not initially a part of our plan. However, deep down, we all knew that if we introduced IoT, we would massively organize and amp our design to higher comfort levels for both patients and healthcare staff. This would also help reduce the requirement of high-cost personal protective equipment (PPEs) and the exposure of medical staff to COVID-19. Therefore we found our way into integrating IoT with our ventilator design. Our final project definition revolved around the basic idea that we chose to work upon, i.e., 'NeT-Vent: Low-Cost, Rapidly Scalable and IoT-enabled Smart Invasive Mechanical Ventilator with adaptive control to reduce incidences of Pulmonary Barotrauma in SARS-CoV-2 patients.'

Another challenging part was to find the exact market price of various components, their suppliers, and the shortcomings of many open-source ventilators that had been up there earlier. We invested a reasonable amount of time and ensured that our ideas were presented very well in the Hackathon. The presentation went on pretty smoothly, and we were able to explain our design concept and simulation results to the jury members and finish our presentation within the stipulated time. At the start of our design process, we were anxious enough and never thought about a fruitful result. Our sole intention was to contribute to an open-source solution to perhaps one of the biggest challenges: the COVID-19 pandemic. We were extremely thankful to the jury for showing interest in our ventilator design, our proposed solution and rewarding us for our hard work.

<p align="center">

 <iframe width="600px" height="338px" src="https://www.youtube.com/embed/aH61JyB22LA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</p>

### Looking back from where it all started and the way ahead

The most important aspect of designing an engineering solution is to identify loopholes in current designs and then improve upon them. Design iterations to address the identified problem are an integral part of the process. Through Net-Vent, we targeted the low-resourced regions and poor backgrounds where high-end ventilators are not available easily. While designing it, we consider developing an easy User Interface of the machine so that everyone can understand it easily. When like-minded people come together to solve a problem, innovation happens, team effort plays a vital role in the success of any project. Operating on such a tight deadline and at a distance from each other was challenging. However, it is not essential to know everything yourself as long as you have a team of motivated people from various backgrounds possessing different skill sets with a common goal and a unique vision. Now that our team has successfully tested the project through various computer simulations, we will be testing our design on a breathing simulator. We plan to send the designs to the Indian Council of Medical Research to be used in under-resourced locations across the country.

<!-- <style>
 .container{padding: 30px;}
</style>

<div class="container">

 <iframe src="NeT-Vent_IEEE_Paper.pdf" type="application/pdf" width="100%" height="600px"></iframe>
</div> -->


<object data="NeT-Vent_IEEE_Paper.pdf" type="application/pdf" width="100%" height="600px">
  <p>Your web browser doesn't have a PDF plugin.
  Instead you can <a href="NeT-Vent_IEEE_Paper.pdf">click here to
  download the NeT-Vent IEEE Paper.</a></p>
</object>


## Recognition

• Won the University of Queensland (UQ) Engineering Design Hackathon 2020, Brisbane which had more than 15 teams from top universities.

• Research results published as a [Full Paper](https://ieeexplore.ieee.org/document/9587553) at the IEEE Global Conference for Advancement in Technology (GCAT) 2021.

• Got the appreciation of Institute Directors and the organizing committee which included Professors, Anesthetists and Medical experts in the domain of Ventilation.

• Featured in Thapar Institute of Engineering and Technology's Pulse Volume. XII quarterly publication.

• Recieved International Recognition. Featured on [TIET's LinkedIn](https://www.linkedin.com/posts/tietofficial_thaparinstitute-tiet2020-hackathon2020-activity-6728971807958937600-uqHe) and [UoQ's official Facebook](https://www.facebook.com/watch/?v=1273994709603672) pages.

<div id="fb-root"></div>
<script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_GB/sdk.js#xfbml=1&version=v12.0" nonce="hQNlbeg4"></script>

<iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:6728971807346561024" height="400" width="50%" frameborder="0" allowfullscreen="" title="Embedded post"></iframe> <div class="fb-post" data-href="https://www.facebook.com/watch/?v=1273994709603672" data-width="400" data-show-text="true"><blockquote cite="https://www.facebook.com/uniofqldind/videos/1273994709603672/" class="fb-xfbml-parse-ignore"><p>UQ congratulates Aviral Chharia, Shivu Chauhan and Shankhaneel Basak from Thapar Institute of Engineering &amp; Technology...</p>Posted by <a href="https://www.facebook.com/uniofqldind/">The University of Queensland – India</a> on&nbsp;<a href="https://www.facebook.com/uniofqldind/videos/1273994709603672/">Monday, 26 October 2020</a></blockquote></div>

## The Team

![Net_Vent_Team](https://user-images.githubusercontent.com/62457915/148018879-ce376665-de8f-4cbd-80c1-40e7aad40f3e.jpg)

Aviral Chharia, Shivu Chauhan, Shankhaneel Basak, Bikramjit Sharma <i>(from left to right)</i>

## Contact Us

Find the [Paper](https://ieeexplore.ieee.org/document/9587553), [Slides](https://aviralchharia.github.io/data/Net_Vent_Slides.pdf), Design Files and codes on Github. Contact us at [aviral.chharia@gmail.com](mailto:aviral.chharia@gmail.com)

<div align="center">

 <div style="display:inline-block;width:300px;"><script type="text/javascript" src="//rf.revolvermaps.com/0/0/7.js?i=516vso7twce&amp;m=0&amp;c=ff0000&amp;cr1=ffffff&amp;sx=0" async="async"></script></div>

</div>
