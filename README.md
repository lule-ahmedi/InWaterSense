# InWaterSense
<b>Ontologies for Water Quality Management</b>
            <p>
                An ontology for water quality management has been developed, named InWaterSense ontology. It is an OWL 2 ontology
                 which bases on the SSN ontology developed by W3C Semantic Sensor Network Incubator Group (SSN-XG), and is publicly
                 available <a class='' href="https://github.com/InWaterSense/lule-ahmedi/Ontologies/inws-core-regulations-pollutants.owl">here</a>.
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

<div align=center><img src="https://inwatersense.uni-pr.edu/Images/Ontology.png" align="center" width=700px></br>
                    <p align=center>Ontology framework modules</p>
</div>
            
<p>
  Two use cases were approached to illustrate the usability of InWaterSense ontologies. In particular, a stream data 
  scenario from the domain of surface water quality management and static data scenario from the domain of drinking 
  water quality management. A simulated rivers quality data sample can be found 
  <a class='' href="https://github.com/InWaterSense/Ontologies/Use-Cases/rivers_sampledata.owl">here</a> while a drinking waters quality  sample can be found <a class='' href="https://github.com/InWaterSense/lule-ahmedi/Ontologies/Use-Cases/drinking_sampledata.owl">here</a>.
</p>
