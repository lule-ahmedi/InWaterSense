# InWaterSense
<p>This project comprises the whole Intelligent Wireless Sensor Networks for Monitoring Surface Water Quality (InWaterSense). For a detailed description of the InWaterSense project, please visit https://inwatersense.uni-pr.edu/.</p>

<h3>Contact</h3>
<p>
For any questions related to the project in general or ontologies in particular, contact Professor Lule Ahmedi (Founder, Project Owner) at <a href="mailto:lule.ahmedi@uni-pr.edu?subject=InWaterSense">lule.ahmedi@uni-pr.edu</a>
</p>

<h3>The InWaterSense Ontologies</h3>
<p>In this repositoy, currently only the ontologies (identified shortly as INWS ontologies) developed are provided (the Ontologies folder in this GitHub repository), namely:
<ul>
	<li>The set of three ontologies, <b>core, regulations, and pollutants ontologies</b> for supporting water quality management in general in an Internet of Things scenario like with wireless sensor networks (WSNs) deployed statically, and,</li>
	<li>A lightweight <b>mobile version ontology</b> to rather support monitoring water quality via so-called mobile wireless sensors component which is flexible and can be carried out with ease into different locations for sensing the water.</li>
</ul>

Following is a brief description of these ontologies. The project site https://inwatersense.uni-pr.edu/ can be checked to find out more about the ontologies and the whole framework itself.
</p>

<h4>The INWS Ontologies for Water Quality Management through Wireless Sensor Networks</h4>
            <p>
                An ontology for water quality management has been developed, named InWaterSense ontology. It is an OWL 2 ontology
                 which bases on the SSN ontology developed by W3C Semantic Sensor Network Incubator Group (SSN-XG), and is publicly
                 available <a class='' href="https://github.com/InWaterSense/lule-ahmedi/Ontologies/inws-all3ontologies.owl">here</a>.
            </p>
            <p>
                The ontology, as depicted in figure below, consists of four modules:
            <ol>
                <li>The <b>core ontology</b> <a class='' href="https://github.com/lule-ahmedi/InWaterSense/Ontologies/inws-core.owl">[download]</a>, 
			consisting of classes and relationships for deploying real-time observational water 
                        quality data coming from data sources, i.e., sensors or lab measurements.</li>
                <li>The <b>regulations ontology</b> <a class='' href="https://github.com/lule-ahmedi/InWaterSense/Ontologies/inws-regulations.owl">[download]</a>, 
			a module which deals with permitted water parameter thresholds regulated by 
                        different authorities, like is the Water Framework Directive.</li>
                <li>The <b>pollutants ontology</b> <a class='' href="https://github.com/InWaterSense/lule-ahmedi/Ontologies/inws-pollutants.owl">[download]</a>, 
			a module representing pollution entities and their attributes, 
                        like is facilities discharging wastes in water bodies.</li>
                <li><b>Water expert rules</b>, a module consisting of if-then water expert rules, say, if a particular water
                             quality thresholds has been passed then the water body should be classified in a specified status.</li>
            </ol>
            </p>

<div align=center><img src="https://inwatersense.uni-pr.edu/Images/inws-all3ontologies.png" align="center" width=500px></br>
</div>
            
<p>
  Two use cases were approached (the Use-Cases folder in this GitHub repository) to illustrate the usability of InWaterSense ontologies. In particular, a stream data 
  scenario from the domain of surface water quality management and static data scenario from the domain of drinking 
  water quality management. A simulated rivers quality data sample can be found 
  <a class='' href="https://github.com/InWaterSense/Ontologies/Use-Cases/rivers_sampledata.owl">here</a> while a drinking waters quality  sample can be found <a class='' href="https://github.com/InWaterSense/lule-ahmedi/Ontologies/Use-Cases/drinking_sampledata.owl">here</a>.
</p>
	

<h4>LMINWS - A Lightweight Context-Aware Ontology for Water Quality Management through Mobile Sensors</h4>
<p>An ontology for water quality management through mobile wireless sensors has further been developed, namelly the lightweight mobile InWaterSense (LMINWS) ontology depicted below. It is an OWL ontology modeling the rather more rich-in-context but simple mobile portable sensors of a wireless sensor network (WSN), and is publicly available <a class='' href="https://github.com/InWaterSense/lule-ahmedi/Ontologies/lminws.owl">here</a>.</p>

<div align=center><img src="https://inwatersense.uni-pr.edu/Images/lminws-ontology.png" align="center" width=800px></br>
</div>

<p>The classes of our lightweight ontology are depicted in black color, while the ones in white represent imports from other ontologies. For example, the Time ontology, its class DateTimeDescription has been extended with introducing two new subclasses in order to distinguish between the Day and the Night context.</p>

<p>For more informaiton about the LMINWS ontology, see the publication https://inwatersense.uni-pr.edu/publications/MTSR2016.pdf .</p>
