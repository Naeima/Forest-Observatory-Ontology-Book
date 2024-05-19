<?xml version="1.0"?>
<rdf:RDF xmlns="http://www.foo/ns#"
     xml:base="http://www.foo/ns"
     xmlns:ns="http://creativecommons.org/ns#"
     xmlns:wo="http://purl.org/ontology/wo/"
     xmlns:ns1="http://www.w3.org/2003/06/sw-vocab-status/ns#"
     xmlns:owl="http://www.w3.org/2002/07/owl#"
     xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
     xmlns:xml="http://www.w3.org/XML/1998/namespace"
     xmlns:xsd="http://www.w3.org/2001/XMLSchema#"
     xmlns:rdfs="http://www.w3.org/2000/01/rdf-schema#"
     xmlns:skos="http://www.w3.org/2004/02/skos/core#"
     xmlns:sosa="http://www.w3.org/ns/sosa/"
     xmlns:terms="http://purl.org/dc/terms/"
     xmlns:schema="http://schema.org/"
     xmlns:iot-lite="http://purl.oclc.org/NET/UNIS/fiware/iot-lite#"
     xmlns:metadata="http://data.bioontology.org/metadata/"
     xmlns:ontology="http://www.ns/ontology/2021/1.0#"
     xmlns:wgs84_pos="http://www.w3.org/2003/01/geo/wgs84_pos#">
    <owl:Ontology rdf:about="http://www.foo/ns#">
        <owl:versionIRI rdf:resource="http://www.foo/ns/1.0#"/>
    </owl:Ontology>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Annotation properties
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://creativecommons.org/ns#license -->

    <owl:AnnotationProperty rdf:about="http://creativecommons.org/ns#license">
        <rdfs:subPropertyOf rdf:resource="http://purl.org/dc/terms/license"/>
        <rdfs:range rdf:resource="http://creativecommons.org/ns#License"/>
    </owl:AnnotationProperty>
    


    <!-- http://creativecommons.org/ns#morePermissions -->

    <owl:AnnotationProperty rdf:about="http://creativecommons.org/ns#morePermissions">
        <rdfs:subPropertyOf rdf:resource="http://purl.org/dc/terms/relation"/>
        <rdfs:range rdf:resource="http://www.w3.org/2000/01/rdf-schema#Resource"/>
    </owl:AnnotationProperty>
    


    <!-- http://creativecommons.org/ns#useGuidelines -->

    <owl:AnnotationProperty rdf:about="http://creativecommons.org/ns#useGuidelines">
        <rdfs:subPropertyOf rdf:resource="http://purl.org/dc/terms/relation"/>
        <rdfs:range rdf:resource="http://www.w3.org/2000/01/rdf-schema#Resource"/>
    </owl:AnnotationProperty>
    


    <!-- http://data.bioontology.org/metadata/prefixIRI -->

    <owl:AnnotationProperty rdf:about="http://data.bioontology.org/metadata/prefixIRI"/>
    


    <!-- http://purl.oclc.org/NET/UNIS/fiware/iot-lite#hasSensingDevice -->

    <owl:AnnotationProperty rdf:about="http://purl.oclc.org/NET/UNIS/fiware/iot-lite#hasSensingDevice"/>
    


    <!-- http://purl.oclc.org/NET/UNIS/fiware/iot-lite#relativeLocation -->

    <owl:AnnotationProperty rdf:about="http://purl.oclc.org/NET/UNIS/fiware/iot-lite#relativeLocation"/>
    


    <!-- http://purl.org/dc/terms/description -->

    <owl:AnnotationProperty rdf:about="http://purl.org/dc/terms/description"/>
    


    <!-- http://purl.org/dc/terms/license -->

    <owl:AnnotationProperty rdf:about="http://purl.org/dc/terms/license">
        <terms:license rdf:resource="http://www.opengeospatial.org/ogc/Software"/>
        <terms:license rdf:resource="http://www.w3.org/Consortium/Legal/2015/copyright-software-and-document"/>
    </owl:AnnotationProperty>
    


    <!-- http://purl.org/dc/terms/relation -->

    <owl:AnnotationProperty rdf:about="http://purl.org/dc/terms/relation"/>
    


    <!-- http://purl.org/dc/terms/title -->

    <owl:AnnotationProperty rdf:about="http://purl.org/dc/terms/title"/>
    


    <!-- http://schema.org/domainIncludes -->

    <owl:AnnotationProperty rdf:about="http://schema.org/domainIncludes"/>
    


    <!-- http://schema.org/rangeIncludes -->

    <owl:AnnotationProperty rdf:about="http://schema.org/rangeIncludes"/>
    


    <!-- http://www.w3.org/2003/06/sw-vocab-status/ns#term_status -->

    <owl:AnnotationProperty rdf:about="http://www.w3.org/2003/06/sw-vocab-status/ns#term_status"/>
    


    <!-- http://www.w3.org/2004/02/skos/core#definition -->

    <owl:AnnotationProperty rdf:about="http://www.w3.org/2004/02/skos/core#definition"/>
    


    <!-- http://www.w3.org/2004/02/skos/core#example -->

    <owl:AnnotationProperty rdf:about="http://www.w3.org/2004/02/skos/core#example"/>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Object Properties
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://creativecommons.org/ns#attributionURL -->

    <owl:ObjectProperty rdf:about="http://creativecommons.org/ns#attributionURL">
        <rdfs:domain rdf:resource="http://creativecommons.org/ns#Work"/>
        <rdfs:range rdf:resource="http://www.w3.org/2000/01/rdf-schema#Resource"/>
    </owl:ObjectProperty>
    


    <!-- http://creativecommons.org/ns#deprecatedOn -->

    <owl:ObjectProperty rdf:about="http://creativecommons.org/ns#deprecatedOn">
        <rdfs:domain rdf:resource="http://creativecommons.org/ns#License"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema-datatypes#date"/>
        <rdfs:label xml:lang="en-us">deprecated
          on</rdfs:label>
    </owl:ObjectProperty>
    


    <!-- http://creativecommons.org/ns#jurisdiction -->

    <owl:ObjectProperty rdf:about="http://creativecommons.org/ns#jurisdiction">
        <rdfs:domain rdf:resource="http://creativecommons.org/ns#License"/>
        <rdfs:range rdf:resource="http://creativecommons.org/ns#Jurisdiction"/>
        <rdfs:label xml:lang="en-us">jurisdiction</rdfs:label>
    </owl:ObjectProperty>
    


    <!-- http://creativecommons.org/ns#legalcode -->

    <owl:ObjectProperty rdf:about="http://creativecommons.org/ns#legalcode">
        <rdfs:domain rdf:resource="http://creativecommons.org/ns#License"/>
        <rdfs:range rdf:resource="http://www.w3.org/2000/01/rdf-schema#Resource"/>
    </owl:ObjectProperty>
    


    <!-- http://creativecommons.org/ns#license -->

    <owl:ObjectProperty rdf:about="http://creativecommons.org/ns#license">
        <rdfs:domain rdf:resource="http://creativecommons.org/ns#Work"/>
    </owl:ObjectProperty>
    


    <!-- http://creativecommons.org/ns#morePermissions -->

    <owl:ObjectProperty rdf:about="http://creativecommons.org/ns#morePermissions">
        <rdfs:domain rdf:resource="http://creativecommons.org/ns#Work"/>
    </owl:ObjectProperty>
    


    <!-- http://creativecommons.org/ns#permits -->

    <owl:ObjectProperty rdf:about="http://creativecommons.org/ns#permits">
        <rdfs:domain rdf:resource="http://creativecommons.org/ns#License"/>
        <rdfs:range rdf:resource="http://creativecommons.org/ns#Permission"/>
        <rdfs:label xml:lang="en-us">permits</rdfs:label>
    </owl:ObjectProperty>
    


    <!-- http://creativecommons.org/ns#prohibits -->

    <owl:ObjectProperty rdf:about="http://creativecommons.org/ns#prohibits">
        <rdfs:domain rdf:resource="http://creativecommons.org/ns#License"/>
        <rdfs:range rdf:resource="http://creativecommons.org/ns#Prohibition"/>
        <rdfs:label xml:lang="en-us">prohibits</rdfs:label>
    </owl:ObjectProperty>
    


    <!-- http://creativecommons.org/ns#requires -->

    <owl:ObjectProperty rdf:about="http://creativecommons.org/ns#requires">
        <rdfs:domain rdf:resource="http://creativecommons.org/ns#License"/>
        <rdfs:range rdf:resource="http://creativecommons.org/ns#Requirement"/>
        <rdfs:label xml:lang="en-us">requires</rdfs:label>
    </owl:ObjectProperty>
    


    <!-- http://creativecommons.org/ns#useGuidelines -->

    <owl:ObjectProperty rdf:about="http://creativecommons.org/ns#useGuidelines">
        <rdfs:domain rdf:resource="http://creativecommons.org/ns#Work"/>
    </owl:ObjectProperty>
    


    <!-- http://purl.org/ontology/wo/class -->

    <owl:ObjectProperty rdf:about="http://purl.org/ontology/wo/class">
        <rdfs:domain rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <rdfs:range rdf:resource="http://purl.org/ontology/wo/Class"/>
        <rdfs:comment xml:lang="en-gb">associates a taxon rank with a class</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">class</rdfs:label>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:ObjectProperty>
    


    <!-- http://purl.org/ontology/wo/family -->

    <owl:ObjectProperty rdf:about="http://purl.org/ontology/wo/family">
        <rdfs:domain rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <rdfs:range rdf:resource="http://purl.org/ontology/wo/Family"/>
        <rdfs:comment xml:lang="en-gb">associates a taxon rank with a family</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">family</rdfs:label>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:ObjectProperty>
    


    <!-- http://purl.org/ontology/wo/genus -->

    <owl:ObjectProperty rdf:about="http://purl.org/ontology/wo/genus">
        <rdfs:domain rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <rdfs:range rdf:resource="http://purl.org/ontology/wo/Genus"/>
        <rdfs:comment xml:lang="en-gb">associates a taxon rank with a genus</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">genus</rdfs:label>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:ObjectProperty>
    


    <!-- http://purl.org/ontology/wo/habitat -->

    <owl:ObjectProperty rdf:about="http://purl.org/ontology/wo/habitat">
        <rdfs:domain rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <rdfs:range rdf:resource="http://purl.org/ontology/wo/Habitat"/>
        <rdfs:comment xml:lang="en-gb">associates a taxon rank with a habitat in which it may typically be found</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">habitat</rdfs:label>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:ObjectProperty>
    


    <!-- http://purl.org/ontology/wo/kingdom -->

    <owl:ObjectProperty rdf:about="http://purl.org/ontology/wo/kingdom">
        <rdfs:domain rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <rdfs:range rdf:resource="http://purl.org/ontology/wo/Kingdom"/>
        <rdfs:comment xml:lang="en-gb">associates a taxon rank with a kingdom</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">kingdom</rdfs:label>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:ObjectProperty>
    


    <!-- http://purl.org/ontology/wo/livesIn -->

    <owl:ObjectProperty rdf:about="http://purl.org/ontology/wo/livesIn">
        <rdfs:domain rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <rdfs:range rdf:resource="http://purl.org/ontology/wo/Habitat"/>
        <rdfs:comment xml:lang="en-gb">associates a taxon rank with a habitat in which it lives. Sub-property of wo:habitat to be used for members of the animal kingdom</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">lives in</rdfs:label>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:ObjectProperty>
    


    <!-- http://purl.org/ontology/wo/order -->

    <owl:ObjectProperty rdf:about="http://purl.org/ontology/wo/order">
        <rdfs:domain rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <rdfs:range rdf:resource="http://purl.org/ontology/wo/Kingdom"/>
        <rdfs:comment xml:lang="en-gb">associates a taxon rank with an order</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">order</rdfs:label>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:ObjectProperty>
    


    <!-- http://purl.org/ontology/wo/phylum -->

    <owl:ObjectProperty rdf:about="http://purl.org/ontology/wo/phylum">
        <rdfs:domain rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <rdfs:range rdf:resource="http://purl.org/ontology/wo/Phylum"/>
        <rdfs:comment xml:lang="en-gb">associates a taxon rank with a phylum</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">phylum</rdfs:label>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:ObjectProperty>
    


    <!-- http://purl.org/ontology/wo/species -->

    <owl:ObjectProperty rdf:about="http://purl.org/ontology/wo/species">
        <rdfs:domain rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <rdfs:range rdf:resource="http://purl.org/ontology/wo/Species"/>
        <rdfs:comment xml:lang="en-gb">associates a taxon rank with a species</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">species</rdfs:label>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:ObjectProperty>
    


    <!-- http://www.w3.org/2003/01/geo/wgs84_pos#alt -->

    <owl:ObjectProperty rdf:about="http://www.w3.org/2003/01/geo/wgs84_pos#alt">
        <rdfs:domain rdf:resource="http://www.w3.org/2003/01/geo/wgs84_pos#Point"/>
        <rdfs:range>
            <owl:Restriction>
                <owl:onProperty rdf:resource="http://www.ns/ontology/2021/1.0#hasValue"/>
                <owl:someValuesFrom rdf:resource="http://www.w3.org/2000/01/rdf-schema#Literal"/>
            </owl:Restriction>
        </rdfs:range>
    </owl:ObjectProperty>
    


    <!-- http://www.w3.org/2003/01/geo/wgs84_pos#lat -->

    <owl:ObjectProperty rdf:about="http://www.w3.org/2003/01/geo/wgs84_pos#lat">
        <rdfs:domain rdf:resource="http://www.w3.org/2003/01/geo/wgs84_pos#Point"/>
        <rdfs:range>
            <owl:Restriction>
                <owl:onProperty rdf:resource="http://www.w3.org/2003/01/geo/wgs84_pos#lat"/>
                <owl:someValuesFrom rdf:resource="http://www.w3.org/2001/XMLSchema#float"/>
            </owl:Restriction>
        </rdfs:range>
    </owl:ObjectProperty>
    


    <!-- http://www.w3.org/2003/01/geo/wgs84_pos#location -->

    <owl:ObjectProperty rdf:about="http://www.w3.org/2003/01/geo/wgs84_pos#location">
        <rdfs:subPropertyOf rdf:resource="http://xmlns.com/foaf/0.1/based_near"/>
        <rdfs:domain rdf:resource="http://www.w3.org/ns/sosa/Observation"/>
        <rdfs:range rdf:resource="http://www.w3.org/2003/01/geo/wgs84_pos#SpatialThing"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The relation between something and the point, 
 or other geometrical thing in space, where it is.  For example, the realtionship between
 a radio tower and a Point with a given lat and long.
 Or a relationship between a park and its outline as a closed arc of points, or a road and
 its location as a arc (a sequence of points).
 Clearly in practice there will be limit to the accuracy of any such statement, but one would expect
 an accuracy appropriate for the size of the object and uses such as mapping .
 </rdfs:comment>
        <rdfs:label rdf:datatype="http://www.w3.org/2001/XMLSchema#string">location</rdfs:label>
    </owl:ObjectProperty>
    


    <!-- http://www.w3.org/2003/01/geo/wgs84_pos#long -->

    <owl:ObjectProperty rdf:about="http://www.w3.org/2003/01/geo/wgs84_pos#long">
        <rdfs:domain rdf:resource="http://www.w3.org/2003/01/geo/wgs84_pos#Point"/>
        <rdfs:range>
            <owl:Restriction>
                <owl:onProperty rdf:resource="http://www.w3.org/2003/01/geo/wgs84_pos#long"/>
                <owl:someValuesFrom rdf:resource="http://www.w3.org/2001/XMLSchema#float"/>
            </owl:Restriction>
        </rdfs:range>
    </owl:ObjectProperty>
    


    <!-- http://www.w3.org/ns/sosa/hasFeatureOfInterest -->

    <owl:ObjectProperty rdf:about="http://www.w3.org/ns/sosa/hasFeatureOfInterest">
        <rdfs:domain rdf:resource="http://www.w3.org/ns/sosa/Observation"/>
        <rdfs:range rdf:resource="http://www.w3.org/ns/sosa/FeatureOfInterest"/>
    </owl:ObjectProperty>
    


    <!-- http://www.w3.org/ns/sosa/hasSample -->

    <owl:ObjectProperty rdf:about="http://www.w3.org/ns/sosa/hasSample">
        <rdfs:domain rdf:resource="http://www.w3.org/ns/sosa/FeatureOfInterest"/>
        <rdfs:range rdf:resource="http://www.w3.org/ns/sosa/Observation"/>
    </owl:ObjectProperty>
    


    <!-- http://www.w3.org/ns/sosa/hosts -->

    <owl:ObjectProperty rdf:about="http://www.w3.org/ns/sosa/hosts">
        <rdfs:domain rdf:resource="http://www.w3.org/ns/sosa/Platform"/>
        <rdfs:range rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <owl:propertyDisjointWith rdf:resource="http://www.w3.org/ns/sosa/observes"/>
    </owl:ObjectProperty>
    


    <!-- http://www.w3.org/ns/sosa/isFeatureOfInterestOf -->

    <owl:ObjectProperty rdf:about="http://www.w3.org/ns/sosa/isFeatureOfInterestOf">
        <rdfs:domain rdf:resource="http://www.w3.org/ns/sosa/Observation"/>
        <rdfs:range rdf:resource="http://www.w3.org/ns/sosa/FeatureOfInterest"/>
        <skos:definition xml:lang="en">A relation between a FeatureOfInterest and an Observation about it, an Actuation acting on it, or an act of Sampling that sampled it.</skos:definition>
    </owl:ObjectProperty>
    


    <!-- http://www.w3.org/ns/sosa/isObservedBy -->

    <owl:ObjectProperty rdf:about="http://www.w3.org/ns/sosa/isObservedBy">
        <rdfs:domain rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <rdfs:range rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
    </owl:ObjectProperty>
    


    <!-- http://www.w3.org/ns/sosa/madeBySensor -->

    <owl:ObjectProperty rdf:about="http://www.w3.org/ns/sosa/madeBySensor">
        <rdfs:domain rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <rdfs:range rdf:resource="http://www.w3.org/ns/sosa/Observation"/>
    </owl:ObjectProperty>
    


    <!-- http://www.w3.org/ns/sosa/madeObservation -->

    <owl:ObjectProperty rdf:about="http://www.w3.org/ns/sosa/madeObservation">
        <rdfs:domain rdf:resource="http://www.w3.org/ns/sosa/Observation"/>
        <rdfs:range rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
    </owl:ObjectProperty>
    


    <!-- http://www.w3.org/ns/sosa/observedProperty -->

    <owl:ObjectProperty rdf:about="http://www.w3.org/ns/sosa/observedProperty">
        <rdfs:domain rdf:resource="http://www.w3.org/ns/sosa/Observation"/>
        <rdfs:range rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
    </owl:ObjectProperty>
    


    <!-- http://www.w3.org/ns/sosa/observes -->

    <owl:ObjectProperty rdf:about="http://www.w3.org/ns/sosa/observes">
        <rdfs:domain rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <rdfs:range rdf:resource="http://www.w3.org/ns/sosa/Observation"/>
    </owl:ObjectProperty>
    


    <!-- http://xmlns.com/foaf/0.1/based_near -->

    <owl:ObjectProperty rdf:about="http://xmlns.com/foaf/0.1/based_near">
        <rdfs:domain rdf:resource="http://www.w3.org/2003/01/geo/wgs84_pos#SpatialThing"/>
        <rdfs:range rdf:resource="http://www.w3.org/ns/sosa/FeatureOfInterest"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A location that something is based near, for some broadly human notion of near.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://xmlns.com/foaf/0.1/"/>
        <rdfs:label rdf:datatype="http://www.w3.org/2001/XMLSchema#string">based near</rdfs:label>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:ObjectProperty>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Data properties
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://creativecommons.org/ns#attributionName -->

    <owl:DatatypeProperty rdf:about="http://creativecommons.org/ns#attributionName">
        <rdfs:domain rdf:resource="http://creativecommons.org/ns#Work"/>
        <rdfs:range rdf:resource="http://www.w3.org/2000/01/rdf-schema#Literal"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.ns/ontology/2021/1.0#hasResult -->

    <owl:DatatypeProperty rdf:about="http://www.ns/ontology/2021/1.0#hasResult">
        <rdfs:domain rdf:resource="http://www.w3.org/ns/sosa/Observation"/>
        <rdfs:range rdf:resource="http://www.w3.org/2000/01/rdf-schema#Literal"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.ns/ontology/2021/1.0#hasValue -->

    <owl:DatatypeProperty rdf:about="http://www.ns/ontology/2021/1.0#hasValue">
        <rdfs:domain rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <rdfs:range rdf:resource="http://www.w3.org/2000/01/rdf-schema#Literal"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.w3.org/2003/01/geo/wgs84_pos#lat -->

    <owl:DatatypeProperty rdf:about="http://www.w3.org/2003/01/geo/wgs84_pos#lat"/>
    


    <!-- http://www.w3.org/2003/01/geo/wgs84_pos#long -->

    <owl:DatatypeProperty rdf:about="http://www.w3.org/2003/01/geo/wgs84_pos#long"/>
    


    <!-- http://www.w3.org/ns/sosa/resultTime -->

    <owl:DatatypeProperty rdf:about="http://www.w3.org/ns/sosa/resultTime">
        <rdfs:domain rdf:resource="http://www.w3.org/ns/sosa/Observation"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#dateTime"/>
    </owl:DatatypeProperty>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Classes
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://creativecommons.org/ns#Jurisdiction -->

    <owl:Class rdf:about="http://creativecommons.org/ns#Jurisdiction">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ns1:Jurisdiction</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-us">the legal jurisdiction
            of a license</rdfs:comment>
        <rdfs:label xml:lang="en-us">Jurisdiction</rdfs:label>
    </owl:Class>
    


    <!-- http://creativecommons.org/ns#License -->

    <owl:Class rdf:about="http://creativecommons.org/ns#License">
        <owl:equivalentClass rdf:resource="http://web.resource.org/cc/License"/>
        <rdfs:subClassOf rdf:resource="http://purl.org/dc/terms/LicenseDocument"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ns1:License</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-us">a set of
            requests/permissions to users of a Work, e.g. a
            copyright license, the public domain, information
            for distributors</rdfs:comment>
        <rdfs:label xml:lang="en-us">License</rdfs:label>
    </owl:Class>
    


    <!-- http://creativecommons.org/ns#Permission -->

    <owl:Class rdf:about="http://creativecommons.org/ns#Permission">
        <owl:equivalentClass rdf:resource="http://web.resource.org/cc/Permission"/>
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ns1:Permission</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-us">an action that may or
            may not be allowed or desired</rdfs:comment>
        <rdfs:label xml:lang="en-us">Permission</rdfs:label>
    </owl:Class>
    


    <!-- http://creativecommons.org/ns#Prohibition -->

    <owl:Class rdf:about="http://creativecommons.org/ns#Prohibition">
        <owl:equivalentClass rdf:resource="http://web.resource.org/cc/Prohibition"/>
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ns1:Prohibition</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-us">something you may be
            asked not to do</rdfs:comment>
        <rdfs:label xml:lang="en-us">Prohibition</rdfs:label>
    </owl:Class>
    


    <!-- http://creativecommons.org/ns#Requirement -->

    <owl:Class rdf:about="http://creativecommons.org/ns#Requirement">
        <owl:equivalentClass rdf:resource="http://web.resource.org/cc/Requirement"/>
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ns1:Requirement</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-us">an action that may or
            may not be requested of you</rdfs:comment>
        <rdfs:label xml:lang="en-us">Requirement</rdfs:label>
    </owl:Class>
    


    <!-- http://creativecommons.org/ns#Work -->

    <owl:Class rdf:about="http://creativecommons.org/ns#Work">
        <owl:equivalentClass rdf:resource="http://web.resource.org/cc/Work"/>
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ns1:Work</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-us">a potentially
            copyrightable work</rdfs:comment>
        <rdfs:label xml:lang="en-us">Work</rdfs:label>
    </owl:Class>
    


    <!-- http://purl.org/dc/terms/Frequency -->

    <owl:Class rdf:about="http://purl.org/dc/terms/Frequency">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">terms:Frequency</metadata:prefixIRI>
        <rdfs:comment xml:lang="en">A rate at which something recurs.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/dc/terms/"/>
        <rdfs:label xml:lang="en">Frequency</rdfs:label>
    </owl:Class>
    


    <!-- http://purl.org/dc/terms/LicenseDocument -->

    <owl:Class rdf:about="http://purl.org/dc/terms/LicenseDocument">
        <rdfs:subClassOf rdf:resource="http://purl.org/dc/terms/RightsStatement"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">terms:LicenseDocument</metadata:prefixIRI>
        <rdfs:comment xml:lang="en">A legal document giving official permission to do something with a resource.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/dc/terms/"/>
        <rdfs:label xml:lang="en">License Document</rdfs:label>
    </owl:Class>
    


    <!-- http://purl.org/dc/terms/PhysicalResource -->

    <owl:Class rdf:about="http://purl.org/dc/terms/PhysicalResource">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">terms:PhysicalResource</metadata:prefixIRI>
        <rdfs:comment xml:lang="en">A material thing.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/dc/terms/"/>
        <rdfs:label xml:lang="en">Physical Resource</rdfs:label>
    </owl:Class>
    


    <!-- http://purl.org/dc/terms/Policy -->

    <owl:Class rdf:about="http://purl.org/dc/terms/Policy">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <owl:disjointWith rdf:resource="http://purl.org/dc/terms/ProvenanceStatement"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">terms:Policy</metadata:prefixIRI>
        <rdfs:comment xml:lang="en">A plan or course of action by an authority, intended to influence and determine decisions, actions, and other matters.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/dc/terms/"/>
        <rdfs:label xml:lang="en">Policy</rdfs:label>
    </owl:Class>
    


    <!-- http://purl.org/dc/terms/ProvenanceStatement -->

    <owl:Class rdf:about="http://purl.org/dc/terms/ProvenanceStatement">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">terms:ProvenanceStatement</metadata:prefixIRI>
        <rdfs:comment xml:lang="en">Any changes in ownership and custody of a resource since its creation that are significant for its authenticity, integrity, and interpretation.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/dc/terms/"/>
        <rdfs:label xml:lang="en">Provenance Statement</rdfs:label>
    </owl:Class>
    


    <!-- http://purl.org/dc/terms/RightsStatement -->

    <owl:Class rdf:about="http://purl.org/dc/terms/RightsStatement">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">terms:RightsStatement</metadata:prefixIRI>
        <rdfs:comment xml:lang="en">A statement about the intellectual property rights (IPR) held in or over a resource, a legal document giving official permission to do something with a resource, or a statement about access rights.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/dc/terms/"/>
        <rdfs:label xml:lang="en">Rights Statement</rdfs:label>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Class -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Class">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wo:Class</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-gb">A class is a scientific way to group related organisms together, some examples of classes being jellyfish, reptiles and sea urchins. Classes are big groups and contain within them smaller groupings called orders, families, genera and species.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">Class</rdfs:label>
        <rdfs:seeAlso rdf:resource="http://en.wikipedia.org/wiki/Class_%28biology%29"/>
        <rdfs:seeAlso rdf:resource="http://www.bbc.co.uk/nature/class"/>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Family -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Family">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wo:Family</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-gb">A family is a scientific grouping of closely related organisms. It has smaller groups, called genera and species, within it. A family can have a lot of members or only a few. Examples of families include the cats (Felidae), the gulls (Laridae) and the grasses (Poaceae).</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">Family</rdfs:label>
        <rdfs:seeAlso rdf:resource="http://en.wikipedia.org/wiki/Family_%28biology%29"/>
        <rdfs:seeAlso rdf:resource="http://www.bbc.co.uk/nature/family"/>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/FreshwaterHabitat -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/FreshwaterHabitat">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/Habitat"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wo:FreshwaterHabitat</metadata:prefixIRI>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Freshwater habitats include bogs, ponds, lakes, rivers and streams. About 3% of Earth&apos;s water is freshwater, but this includes the water locked up in the ice caps and trapped in rocks and soil as groundwater. Only a tiny fraction (0.014%) is surface water in the form of rivers, lakes and swamps.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">Freshwater Habitat</rdfs:label>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Genus -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Genus">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wo:Genus</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-gb">A genus is a scientific way of showing that species are very closed related to each other. In fact the first word of the species&apos; scientific name is its genus. So for lions (Panthera leo), Panthera is the genus and tells us that they are closely related to tigers (Panthera tigris), because they share the name</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">Genus</rdfs:label>
        <rdfs:seeAlso rdf:resource="http://en.wikipedia.org/wiki/Genus"/>
        <rdfs:seeAlso rdf:resource="http://www.bbc.co.uk/nature/genus"/>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Habitat -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Habitat">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wo:Habitat</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-gb">A habitat, or biome, is the type of environment in which plant and animals live. Habitat is dictated by what kinds of plants grow there, the climate and the geography. Rainforest, coral reefs and the tundra are all habitats where particular kinds of plants and animals might be found.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">Habitat</rdfs:label>
        <rdfs:seeAlso rdf:resource="http://en.wikipedia.org/wiki/Habitat"/>
        <rdfs:seeAlso rdf:resource="http://www.bbc.co.uk/nature/habitats"/>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Kingdom -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Kingdom">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wo:Kingdom</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-gb">Kingdoms are the major categories into which scientists divide up all living things. The main kingdoms are animals, plants, fungi and bacteria, although there are others. Each kingdom has its own suite of defining characteristics - for instance plants have rigid cell walls, whilst animals do not.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">Kingdom</rdfs:label>
        <rdfs:seeAlso rdf:resource="http://en.wikipedia.org/wiki/Kingdom_%28biology%29"/>
        <rdfs:seeAlso rdf:resource="http://www.bbc.co.uk/nature/kingdom"/>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/MarineHabitat -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/MarineHabitat">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/Habitat"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wo:MarineHabitat</metadata:prefixIRI>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Approximately 71% of the Earth&apos;s surface is covered by the oceans, an area of some 223698816km/sq. Although marine life evolved around three billion years before life on land, marine habitats are relatively poorly studied and much of the ocean&apos;s depths remains unexplored.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">Marine Habitat</rdfs:label>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Order -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Order">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wo:Order</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-gb">An order is a scientific way to categorise related organisms. An order is a smaller grouping than a class, but bigger than a family or genus. Examples of orders are willows, cockroaches and primates.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">Order</rdfs:label>
        <rdfs:seeAlso rdf:resource="http://en.wikipedia.org/wiki/Order_%28biology%29"/>
        <rdfs:seeAlso rdf:resource="http://www.bbc.co.uk/nature/order"/>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Phylum -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Phylum">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wo:Phylum</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-gb">A phylum - also known as a division when referring to plants - is a scientfic way of grouping together related organisms. All the members of a phylum have a common ancestor and anatomical similarities. For instance, all the arthropods have external skeletons. Phlya are large groups and are further subdivided into classes, orders, families and so on.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">Phylum</rdfs:label>
        <rdfs:seeAlso rdf:resource="http://en.wikipedia.org/wiki/Phylum"/>
        <rdfs:seeAlso rdf:resource="http://www.bbc.co.uk/nature/phylum"/>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Species -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Species">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wo:Species</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-gb">Generic class defining a biological species</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">species</rdfs:label>
        <rdfs:seeAlso rdf:resource="http://en.wikipedia.org/wiki/Species"/>
        <rdfs:seeAlso rdf:resource="http://www.bbc.co.uk/nature/species"/>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/TaxonName -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/TaxonName">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <owl:disjointWith rdf:resource="http://purl.org/ontology/wo/TaxonRank"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wo:TaxonName</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-gb">A taxonomic name, describing the structure and provenance of a taxonomic name.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">Taxon Name</rdfs:label>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/TaxonRank -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/TaxonRank">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wo:TaxonRank</metadata:prefixIRI>
        <rdfs:comment xml:lang="en-gb">Generic concept for a taxonomic rank such as a Genus or Species.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">Taxonomic Rank</rdfs:label>
        <rdfs:seeAlso rdf:resource="http://en.wikipedia.org/wiki/Taxonomic_rank"/>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/TerrestrialHabitat -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/TerrestrialHabitat">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/Habitat"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wo:TerrestrialHabitat</metadata:prefixIRI>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Terrestrial habitats include forests, grasslands, deserts and rainforests. They are typically defined by factors such as plant structure (trees and grasses), leaf types (eg broadleaf and needleleaf), plant spacing (forest, woodland, savanna) and climate.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/ontology/wo/"/>
        <rdfs:label xml:lang="en-gb">Terrestrial Habitat</rdfs:label>
        <ns1:term_status rdf:datatype="http://www.w3.org/2001/XMLSchema#string">testing</ns1:term_status>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Class/Mammalia -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Class/Mammalia">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/Class"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The highest class of the subphylum Vertebrata comprising humans and all other animals that nourish their young with milk secreted by mammary glands.
https://www.merriam-webster.com/dictionary/Elephantidae</rdfs:comment>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Class/Reptilia -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Class/Reptilia">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/Class"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Reptilia is a vertebrate animal of a class that includes snakes, lizards, crocodiles, turtles, and tortoises. They are distinguished by having a dry scaly skin and typically laying soft-shelled eggs on land.</rdfs:comment>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Family/Elephantidae -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Family/Elephantidae">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/Family"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">ELEPHANTIDAE is a family of bulky mammals (order Proboscidea) comprising the recent elephants and related extinct forms.
Source: https://www.merriam-webster.com/dictionary/Elephantidae</rdfs:comment>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Family/Viverridae -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Family/Viverridae">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/Family"/>
        <rdfs:isDefinedBy rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Viverridae is a family of small to medium-sized, feliform mammals. The viverrids comprise 33 species placed in 14 genera. This family was named and first described by John Edward Gray in 1821. Viverrids occur all over Africa, southern Europe, and South and Southeast Asia, across the Wallace Line</rdfs:isDefinedBy>
        <rdfs:isDefinedBy rdf:datatype="http://www.w3.org/2001/XMLSchema#string">https://en.wikipedia.org/wiki/Viverridae</rdfs:isDefinedBy>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Kingdom/Animalia -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Kingdom/Animalia">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/Kingdom"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Animalia is the scientific grouping that includes all animals. Scientists, historians, and others classify similar things together, using a taxonomy.

All members of the kingdom Animalia share three key traits. They are multicellular organisms, and they are all eukaryotic, meaning their cells have membrane-enclosed organelles and a nucleus. All animals are heterotrophic and must feed on other organisms to survive.
source:https://study.com/learn/lesson/animalia-kingdom-examples-characteristics-facts.html</rdfs:comment>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Order/Carnivora -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Order/Carnivora">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/Order"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Carnivora is a monophyletic order of placental mammals consisting of the most recent common ancestor of all cats and dogs, and all descendants of that ancestor. Members of this group are formally referred to as carnivorans, and have evolved to specialize in eating flesh.</rdfs:comment>
        <rdfs:isDefinedBy rdf:datatype="http://www.w3.org/2001/XMLSchema#string">https://en.wikipedia.org/wiki/Carnivora</rdfs:isDefinedBy>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Order/Proboscidea -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Order/Proboscidea">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/Order"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Any of an order (Proboscidea) of large mammals comprising the elephants and extinct related forms.
https://www.merriam-webster.com/dictionary/proboscidean</rdfs:comment>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Order/Squamata -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Order/Squamata">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/Order"/>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/Phylum/Chordata -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/Phylum/Chordata">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/Phylum"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A large phylum of animals that includes the vertebrates together with the sea squirts and lancelets. They are distinguished by the possession of a notochord at some stage during their development.
Source: google.com</rdfs:comment>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/TaxonName/Civettictis -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/TaxonName/Civettictis">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/TaxonName"/>
    </owl:Class>
    


    <!-- http://purl.org/ontology/wo/TaxonName/Loxodonta -->

    <owl:Class rdf:about="http://purl.org/ontology/wo/TaxonName/Loxodonta">
        <rdfs:subClassOf rdf:resource="http://purl.org/ontology/wo/TaxonName"/>
    </owl:Class>
    


    <!-- http://web.resource.org/cc/License -->

    <owl:Class rdf:about="http://web.resource.org/cc/License">
        <rdfs:subClassOf rdf:resource="http://purl.org/dc/terms/LicenseDocument"/>
    </owl:Class>
    


    <!-- http://web.resource.org/cc/Permission -->

    <owl:Class rdf:about="http://web.resource.org/cc/Permission">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
    </owl:Class>
    


    <!-- http://web.resource.org/cc/Prohibition -->

    <owl:Class rdf:about="http://web.resource.org/cc/Prohibition">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
    </owl:Class>
    


    <!-- http://web.resource.org/cc/Requirement -->

    <owl:Class rdf:about="http://web.resource.org/cc/Requirement">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
    </owl:Class>
    


    <!-- http://web.resource.org/cc/Work -->

    <owl:Class rdf:about="http://web.resource.org/cc/Work">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
    </owl:Class>
    


    <!-- http://www.w3.org/2000/01/rdf-schema#Resource -->

    <owl:Class rdf:about="http://www.w3.org/2000/01/rdf-schema#Resource">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">rdfs:Resource</metadata:prefixIRI>
    </owl:Class>
    


    <!-- http://www.w3.org/2001/XMLSchema-datatypes#date -->

    <owl:Class rdf:about="http://www.w3.org/2001/XMLSchema-datatypes#date">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
    </owl:Class>
    


    <!-- http://www.w3.org/2003/01/geo/wgs84_pos#Point -->

    <owl:Class rdf:about="http://www.w3.org/2003/01/geo/wgs84_pos#Point">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2003/01/geo/wgs84_pos#SpatialThing"/>
    </owl:Class>
    


    <!-- http://www.w3.org/2003/01/geo/wgs84_pos#SpatialThing -->

    <owl:Class rdf:about="http://www.w3.org/2003/01/geo/wgs84_pos#SpatialThing">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wgs84_pos:SpatialThing</metadata:prefixIRI>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Anything with spatial extent, i.e. size, shape, or position.
 e.g. people, places, bowling balls, as well as abstract areas like cubes.
</rdfs:comment>
        <rdfs:label rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Spatial Thing</rdfs:label>
        <rdfs:label rdf:datatype="http://www.w3.org/2001/XMLSchema#string">SpatialThing</rdfs:label>
    </owl:Class>
    


    <!-- http://www.w3.org/ns/sosa/FeatureOfInterest -->

    <owl:Class rdf:about="http://www.w3.org/ns/sosa/FeatureOfInterest">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">sosa:FeatureOfInterest</metadata:prefixIRI>
        <rdfs:comment xml:lang="en">The thing whose property is being estimated or calculated in the course of an Observation to arrive at a Result or whose property is being manipulated by an Actuator, or which is being sampled or transformed in an act of Sampling.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://www.w3.org/ns/sosa/"/>
        <rdfs:label xml:lang="en">Feature Of Interest</rdfs:label>
        <skos:definition xml:lang="en">The thing whose property is being estimated or calculated in the course of an Observation to arrive at a Result or whose property is being manipulated by an Actuator, or which is being sampled or transformed in an act of Sampling.</skos:definition>
        <skos:example xml:lang="en">When measuring the height of a tree, the height is the observed ObservableProperty, 20m may be the Result of the Observation, and the tree is the FeatureOfInterest. A window is a FeatureOfInterest for an automatic window control Actuator.</skos:example>
    </owl:Class>
    


    <!-- http://www.w3.org/ns/sosa/ObservableProperty -->

    <owl:Class rdf:about="http://www.w3.org/ns/sosa/ObservableProperty">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">sosa:ObservableProperty</metadata:prefixIRI>
        <rdfs:comment xml:lang="en">An observable quality (property, characteristic) of a FeatureOfInterest.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://www.w3.org/ns/sosa/"/>
        <rdfs:label xml:lang="en">Observable Property</rdfs:label>
        <skos:definition xml:lang="en">An observable quality (property, characteristic) of a FeatureOfInterest.</skos:definition>
        <skos:example xml:lang="en">The height of a tree, the depth of a water body, or the temperature of a surface are examples of observable properties, while the value of a classic car is not (directly) observable but asserted.</skos:example>
    </owl:Class>
    


    <!-- http://www.w3.org/ns/sosa/Observation -->

    <owl:Class rdf:about="http://www.w3.org/ns/sosa/Observation">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">sosa:Observation</metadata:prefixIRI>
        <rdfs:comment xml:lang="en">Act of carrying out an (Observation) Procedure to estimate or calculate a value of a property of a FeatureOfInterest. Links to a Sensor to describe what made the Observation and how; links to an ObservableProperty to describe what the result is an estimate of, and to a FeatureOfInterest to detail what that property was associated with.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://www.w3.org/ns/sosa/"/>
        <rdfs:label xml:lang="en">Observation</rdfs:label>
        <skos:definition xml:lang="en">Act of carrying out an (Observation) Procedure to estimate or calculate a value of a property of a FeatureOfInterest. Links to a Sensor to describe what made the Observation and how; links to an ObservableProperty to describe what the result is an estimate of, and to a FeatureOfInterest to detail what that property was associated with.</skos:definition>
        <skos:example xml:lang="en">The activity of estimating the intensity of an Earthquake using the Mercalli intensity scale is an Observation as is measuring the moment magnitude, i.e., the energy released by said earthquake.</skos:example>
    </owl:Class>
    


    <!-- http://www.w3.org/ns/sosa/Platform -->

    <owl:Class rdf:about="http://www.w3.org/ns/sosa/Platform">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">sosa:Platform</metadata:prefixIRI>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A Platform is an entity that hosts other entities, particularly Sensors, Actuators, Samplers, and other Platforms.&quot;@en ;</rdfs:comment>
        <rdfs:isDefinedBy rdf:datatype="http://www.w3.org/2001/XMLSchema#string">sosa</rdfs:isDefinedBy>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">&quot;A Platform is an entity that hosts other entities, particularly Sensors, Actuators, Samplers, and other Platforms.&quot;@en ;</skos:definition>
        <skos:example rdf:datatype="http://www.w3.org/2001/XMLSchema#string">&quot;A post, buoy, vehicle, ship, aircraft, satellite, cell-phone, human or animal may act as platforms for (technical or biological) sensors or actuators.&quot;@en ;</skos:example>
    </owl:Class>
    


    <!-- http://www.w3.org/ns/sosa/Sensor -->

    <owl:Class rdf:about="http://www.w3.org/ns/sosa/Sensor">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">sosa:Sensor</metadata:prefixIRI>
        <rdfs:comment xml:lang="en">Device, agent (including humans), or software (simulation) involved in, or implementing, a Procedure. Sensors respond to a stimulus, e.g., a change in the environment, or input data composed from the results of prior Observations, and generate a Result. Sensors can be hosted by Platforms.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://www.w3.org/ns/sosa/"/>
        <rdfs:label xml:lang="en">Sensor</rdfs:label>
        <skos:definition xml:lang="en">Device, agent (including humans), or software (simulation) involved in, or implementing, a Procedure. Sensors respond to a stimulus, e.g., a change in the environment, or input data composed from the results of prior Observations, and generate a Result. Sensors can be hosted by Platforms.</skos:definition>
        <skos:example xml:lang="en">Accelerometers, gyroscopes, barometers, magnetometers, and so forth are Sensors that are typically mounted on a modern smart phone (which acts as Platform). Other examples of sensors include the human eyes.</skos:example>
    </owl:Class>
    


    <!-- http://xmlns.com/foaf/0.1/Image -->

    <owl:Class rdf:about="http://xmlns.com/foaf/0.1/Image">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
    </owl:Class>
    


    <!-- http://xmlns.com/foaf/0.1/Person -->

    <owl:Class rdf:about="http://xmlns.com/foaf/0.1/Person">
        <rdfs:subClassOf rdf:resource="http://www.w3.org/2002/07/owl#Thing"/>
    </owl:Class>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Individuals
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://creativecommons.org/ns#Attribution -->

    <owl:NamedIndividual rdf:about="http://creativecommons.org/ns#Attribution">
        <rdf:type rdf:resource="http://creativecommons.org/ns#Requirement"/>
        <rdfs:comment xml:lang="en-us">credit be given to
            copyright holder and/or author</rdfs:comment>
        <rdfs:label xml:lang="en-us">Attribution</rdfs:label>
    </owl:NamedIndividual>
    


    <!-- http://creativecommons.org/ns#CommercialUse -->

    <owl:NamedIndividual rdf:about="http://creativecommons.org/ns#CommercialUse">
        <rdf:type rdf:resource="http://creativecommons.org/ns#Prohibition"/>
        <rdfs:comment xml:lang="en-us">exercising rights for
            commercial purposes</rdfs:comment>
        <rdfs:label xml:lang="en-us">Commercial Use</rdfs:label>
    </owl:NamedIndividual>
    


    <!-- http://creativecommons.org/ns#Copyleft -->

    <owl:NamedIndividual rdf:about="http://creativecommons.org/ns#Copyleft">
        <rdf:type rdf:resource="http://creativecommons.org/ns#Requirement"/>
        <rdfs:comment xml:lang="en-us">derivative and
            combined works must be licensed under specified
            terms, similar to those on the original
            work</rdfs:comment>
        <rdfs:label xml:lang="en-us">Copyleft</rdfs:label>
    </owl:NamedIndividual>
    


    <!-- http://creativecommons.org/ns#DerivativeWorks -->

    <owl:NamedIndividual rdf:about="http://creativecommons.org/ns#DerivativeWorks">
        <rdf:type rdf:resource="http://creativecommons.org/ns#Permission"/>
        <rdfs:comment xml:lang="en-us">distribution of
            derivative works</rdfs:comment>
        <rdfs:label xml:lang="en-us">Derivative Works</rdfs:label>
    </owl:NamedIndividual>
    


    <!-- http://creativecommons.org/ns#Distribution -->

    <owl:NamedIndividual rdf:about="http://creativecommons.org/ns#Distribution">
        <rdf:type rdf:resource="http://creativecommons.org/ns#Permission"/>
        <rdfs:comment xml:lang="en-us">distribution, public
            display, and publicly performance</rdfs:comment>
        <rdfs:label xml:lang="en-us">Distribution</rdfs:label>
    </owl:NamedIndividual>
    


    <!-- http://creativecommons.org/ns#HighIncomeNationUse -->

    <owl:NamedIndividual rdf:about="http://creativecommons.org/ns#HighIncomeNationUse">
        <rdf:type rdf:resource="http://creativecommons.org/ns#Prohibition"/>
        <rdfs:comment xml:lang="en-us">use in a
            non-developing country</rdfs:comment>
        <rdfs:label xml:lang="en-us">High Income Nation Use</rdfs:label>
    </owl:NamedIndividual>
    


    <!-- http://creativecommons.org/ns#LesserCopyleft -->

    <owl:NamedIndividual rdf:about="http://creativecommons.org/ns#LesserCopyleft">
        <rdf:type rdf:resource="http://creativecommons.org/ns#Requirement"/>
        <rdfs:comment xml:lang="en-us">derivative works must
            be licensed under specified terms, with at least
            the same conditions as the original work;
            combinations with the work may be licensed under
            different terms</rdfs:comment>
        <rdfs:label xml:lang="en-us">Lesser Copyleft</rdfs:label>
    </owl:NamedIndividual>
    


    <!-- http://creativecommons.org/ns#Notice -->

    <owl:NamedIndividual rdf:about="http://creativecommons.org/ns#Notice">
        <rdf:type rdf:resource="http://creativecommons.org/ns#Requirement"/>
        <rdfs:comment xml:lang="en-us">copyright and license
            notices be kept intact</rdfs:comment>
        <rdfs:label xml:lang="en-us">Notice</rdfs:label>
    </owl:NamedIndividual>
    


    <!-- http://creativecommons.org/ns#Reproduction -->

    <owl:NamedIndividual rdf:about="http://creativecommons.org/ns#Reproduction">
        <rdf:type rdf:resource="http://creativecommons.org/ns#Permission"/>
        <rdfs:comment xml:lang="en-us">making multiple
            copies</rdfs:comment>
        <rdfs:label xml:lang="en-us">Reproduction</rdfs:label>
    </owl:NamedIndividual>
    


    <!-- http://creativecommons.org/ns#ShareAlike -->

    <owl:NamedIndividual rdf:about="http://creativecommons.org/ns#ShareAlike">
        <rdf:type rdf:resource="http://creativecommons.org/ns#Requirement"/>
        <rdfs:comment xml:lang="en-us">derivative works be
            licensed under the same terms or compatible terms
            as the original work</rdfs:comment>
        <rdfs:label xml:lang="en-us">Share Alike</rdfs:label>
    </owl:NamedIndividual>
    


    <!-- http://creativecommons.org/ns#Sharing -->

    <owl:NamedIndividual rdf:about="http://creativecommons.org/ns#Sharing">
        <rdf:type rdf:resource="http://creativecommons.org/ns#Permission"/>
        <rdfs:comment xml:lang="en-us">permits commercial
            derivatives, but only non-commercial
            distribution</rdfs:comment>
        <rdfs:label xml:lang="en-us">Sharing</rdfs:label>
    </owl:NamedIndividual>
    


    <!-- http://creativecommons.org/ns#SourceCode -->

    <owl:NamedIndividual rdf:about="http://creativecommons.org/ns#SourceCode">
        <rdf:type rdf:resource="http://creativecommons.org/ns#Requirement"/>
        <rdfs:comment xml:lang="en-us">source code (the
            preferred form for making modifications) must be
            provided when exercising some rights granted by
            the license.</rdfs:comment>
        <rdfs:label xml:lang="en-us">Source Code</rdfs:label>
    </owl:NamedIndividual>
    


    <!-- http://creativecommons.org/ns#license -->

    <owl:NamedIndividual rdf:about="http://creativecommons.org/ns#license">
        <owl:sameAs rdf:resource="http://www.w3.org/1999/xhtml/vocab#license"/>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Bulk_Density -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Bulk_Density">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#float">0.6</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Measured Bulk Density of soil sample</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#CameraTrap -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#CameraTrap">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:hasFeatureOfInterest rdf:resource="http://www.ns/ontology/2021/1.0#image"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Name"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Path"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#localDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#localTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#make"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#model"/>
        <ontology:hasResult rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Image</ontology:hasResult>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Wildlife cameras with embeded sensors to capture moving objects.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Count -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Count">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">10</ontology:hasValue>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">GPS collar dataset&apos;s observation count per dataset</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Cov -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Cov">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">5</ontology:hasValue>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">GPS collar dataset: satellite coverage, the higher number the stronger coverage.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#DGFC_ID -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#DGFC_ID">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string">111</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">An identifier that is unique for GPS collar sensor observation</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#DateTime -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#DateTime">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#dateTime">2013-07-06T21:03:17</ontology:hasValue>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The date and time of the GPS collar observation</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Direction -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Direction">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#float">90.0</ontology:hasValue>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Direction that the elephant is travelling at the current data collection instant.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Distance -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Distance">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#float">200.0</ontology:hasValue>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Distance (m) travelled from the previous data collection instant to the present.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Disturbance -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Disturbance">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Logged</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">degree of logging at the site, on of &quot;Old-growth&quot;, &quot;Twic logged&quot;, Logged&quot; (when number of logging operations unknown)</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Elephas_maximus -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Elephas_maximus">
        <rdf:type rdf:resource="http://purl.org/ontology/wo/Class/Mammalia"/>
        <rdf:type rdf:resource="http://purl.org/ontology/wo/Family/Elephantidae"/>
        <rdf:type rdf:resource="http://purl.org/ontology/wo/Kingdom/Animalia"/>
        <rdf:type rdf:resource="http://purl.org/ontology/wo/Order/Proboscidea"/>
        <rdf:type rdf:resource="http://purl.org/ontology/wo/Phylum/Chordata"/>
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/FeatureOfInterest"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#ABAW"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Aqeela"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Bikang1"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Bikang2"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Dara"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Guli"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Ita"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Jasmin"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Jasper"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Kasih"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Kuma"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Liun"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Maliau"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Merotai"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Puteri"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Putut"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Sandi"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Sejati"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Seri"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Tulid"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Tunglap"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.schema.org/ns/elephant#Umas2"/>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Asian elephant</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Elevation_masl -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Elevation_masl">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#float">15.5</ontology:hasValue>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Elevation at the plot centre, in metres above sea level</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#ExtTemp -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#ExtTemp">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#double">21.0</ontology:hasValue>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">External Temperature of the elephant at data collection instant</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#First_planting_nearest_OP -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#First_planting_nearest_OP">
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">2005</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Year palm adjacent to the forest site</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Forest_type -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Forest_type">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string">HCV High Conservation Value</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">type of forest site, one of &quot;Continous primary&quot;, &quot;Continous logged&quot;, &quot;HCV&quot; (i.e., High Conservation Value; fragmented sites in oil palm plantations)</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#GMTDate -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#GMTDate">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <sosa:resultTime rdf:datatype="http://www.w3.org/2001/XMLSchema#dateTime">2014-04-12T13:20:00</sosa:resultTime>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The GMT date in Sabah, Malaysia when the GPS collar collected  its readings.</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#GMTTime -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#GMTTime">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <sosa:resultTime rdf:datatype="http://www.w3.org/2001/XMLSchema#dateTime">2014-04-12T13:20:00</sosa:resultTime>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The current local date in Sabah, Malaysia when the image collects its readings.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#HDOP -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#HDOP">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">1</ontology:hasValue>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Horizontal Dilution of Precision (HDOP) measures GPS accuracy in Latitude and Longitude. The lower value the better precision.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Horizon -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Horizon">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Sample_Name</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Soil horizon sampled</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Horizon_Depth -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Horizon_Depth">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#float">2.5</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Depth of the organic soil horizon sampled</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Identifier -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Identifier">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <sosa:hasFeatureOfInterest rdf:resource="http://www.ns/ontology/2021/1.0#image"/>
        <ontology:hasResult rdf:datatype="http://www.w3.org/2001/XMLSchema#string">DGFC_</ontology:hasResult>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Unique Soil Sample Identifier</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Land_Use -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Land_Use">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Unlogged</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Land use of the study plots: Unlogged tropical forest, Logged tropical forest or Oil palm plantation</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Lat -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Lat">
        <rdf:type rdf:resource="http://www.w3.org/2003/01/geo/wgs84_pos#Point"/>
        <wgs84_pos:lat rdf:datatype="http://www.w3.org/2001/XMLSchema#float">5.111245</wgs84_pos:lat>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The geographical latitude of the observation location</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Long -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Long">
        <rdf:type rdf:resource="http://www.w3.org/2003/01/geo/wgs84_pos#Point"/>
        <wgs84_pos:long rdf:datatype="http://www.w3.org/2001/XMLSchema#float">118.11745</wgs84_pos:long>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The geographical longitude of a sensor observation location</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Loxodonta -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Loxodonta">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/FeatureOfInterest"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">African elephant</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Mustelidae -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Mustelidae">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/FeatureOfInterest"/>
        <wo:family rdf:resource="http://www.ns/ontology/2021/1.0#Mustelidae"/>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Name -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Name">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Imahe_name</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The named assigned to an image at collection time</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#PDOP -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#PDOP">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Positional Dilution of Precision (DDOP) describes the error caused by the relative position of the GPS satellites. The more signals a GPS reciever can &quot;see&quot; (speard vs near each other), the more precise it can be.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Path -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Path">
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#anyURI"></ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The URI to point at the location of the image in secure cloud</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Plot_Name -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Plot_Name">
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string"></ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Name of the 1 Ha plot sampled</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Replanting_nearest_OP -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Replanting_nearest_OP">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">2008</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Year of any replanting of oil palm adjacent to the forest site (fragmented sites where adjacent oil palm had undergone a second round of planting)</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Site -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Site">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/FeatureOfInterest"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string"></ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Geographical area/site which samples were taken from</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Site_code -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Site_code">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">18</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">code for the study site, in the format Fa (where a can be 1-18)</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Site_name -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Site_name">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Sabahmas</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">name of the study site</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Site_plot_code -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Site_plot_code">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">3</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">code for the study site and plot at the site, in the format FaPb (where a refers to site code, and can be 1-18; and b refers to plot code, and can be 1-3)</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Soil -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Soil">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/FeatureOfInterest"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Soil or dirt, is a mixture of organic matters, minerals, ases, liquids, and organisms that collectively support life.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Soil_Moisture -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Soil_Moisture">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string"></ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Gravimetric soil moisture</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Soil_Sensor -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Soil_Sensor">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:hasFeatureOfInterest rdf:resource="http://www.ns/ontology/2021/1.0#Soil"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Bulk_Density"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Horizon"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Horizon_Depth"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Land_Use"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Plot_Name"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Site"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Soil_Moisture"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Soil_pH"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Subplot"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#inorganic_P"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#total_C"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#total_N"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#C:N"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#C:P"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Soil sensor data consist of soil properties tropical forests in Sabah, Malaysia. 
The data is a contribution from the BALI collaboration, which is financed by the UK&apos;s Natural Environment Research Council (NERC).</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Soil_identifier -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Soil_identifier">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Unique observation identifier, collected over a set time interval.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Soil_pH -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Soil_pH">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#float">4.87</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Measured pH of the soil sample</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Source_of_dates -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Source_of_dates">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string"></ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">source of &quot;First_planting_nearest_OP&quot;</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Speed -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Speed">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#float">35.5</ontology:hasValue>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Speed of the elephant at current data collection instant.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Subplot -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Subplot">
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string"></ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Number of the subplot sampled within each 1 Ha plot Numeric</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Survey_date -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Survey_date">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string">12/12/2008</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">date of field data collection at the plot, in the plot, in the format dd/mm/yyyy. Note that in some cases measurements were taken on more than one date for a single plot; see the dates provided in the seperate vegetation datasets for the precise date of particular vegetation data collection.</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Temperature -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Temperature">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#double">21.0</ontology:hasValue>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Estimate temperature of the elephant in Celsius at data collection instant.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Vegetation -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Vegetation">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/FeatureOfInterest"/>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#Years_since_frag -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#Years_since_frag">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string">2017</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Years since fragmentation at time of data collection. i.e., 2017 &quot;First_planting_nearest_OP&quot; (fragmented sites only)</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#image -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#image">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/FeatureOfInterest"/>
        <rdf:type rdf:resource="http://xmlns.com/foaf/0.1/Image"/>
        <sosa:isFeatureOfInterestOf rdf:resource="http://www.ns/ontology/2021/1.0#Identifier"/>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#inorganic_P -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#inorganic_P">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#float">36.65</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">inorganic/soluble phosphorus concentration of the soil sample</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#localDate -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#localDate">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#dateTime">2014-04-12T13:20:00-05:00</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The current local date in Sabah, Malaysia when the image collects its readings.</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#localTime -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#localTime">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <sosa:resultTime rdf:datatype="http://www.w3.org/2001/XMLSchema#dateTime">2014-04-12T13:20:00</sosa:resultTime>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The current local time in Sabah, Malaysia when the image collects its readings.</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#make -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#make">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string"></ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The make of the trail camera used to capture the image</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#model -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#model">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#string"></ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The model of the trail camera used to capture the image</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#timestamp -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#timestamp">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The time of the sensor observation.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#total_C -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#total_C">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">total carbon content of the soil sample</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#total_N -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#total_N">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">total nitrogen content of the soil sample</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#C:N -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#C:N">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#float">11.96</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">carbon to nitrogen ratio of the soil sample</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.ns/ontology/2021/1.0#C:P -->

    <owl:NamedIndividual rdf:about="http://www.ns/ontology/2021/1.0#C:P">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/ObservableProperty"/>
        <ontology:hasValue rdf:datatype="http://www.w3.org/2001/XMLSchema#float">0.12</ontology:hasValue>
        <skos:definition rdf:datatype="http://www.w3.org/2001/XMLSchema#string">carbon to inorganic phosphorus ratio of the soil sample</skos:definition>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/Civets -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/Civets">
        <rdf:type rdf:resource="http://purl.org/ontology/wo/Family/Viverridae"/>
        <rdf:type rdf:resource="http://purl.org/ontology/wo/Order/Carnivora"/>
        <rdf:type rdf:resource="http://purl.org/ontology/wo/Phylum/Chordata"/>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/Otter -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/Otter">
        <rdf:type rdf:resource="http://purl.org/ontology/wo/Order/Carnivora"/>
        <rdf:type rdf:resource="http://purl.org/ontology/wo/Phylum/Chordata"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Otter is a carnivorous mammal.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/python -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/python">
        <rdf:type rdf:resource="http://purl.org/ontology/wo/Class/Reptilia"/>
        <rdf:type rdf:resource="http://purl.org/ontology/wo/Order/Squamata"/>
        <rdf:type rdf:resource="http://purl.org/ontology/wo/Phylum/Chordata"/>
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/FeatureOfInterest"/>
        <owl:sameAs rdf:resource="http://www.schema.org/ns/python#Juling"/>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#ABAW -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#ABAW">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:hasFeatureOfInterest rdf:resource="http://www.ns/ontology/2021/1.0#Elephas_maximus"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#ExtTemp"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A female asian elephant called  Abaw, here, the GPS collar (sensor) is named after her.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Aqeela -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Aqeela">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:hasFeatureOfInterest rdf:resource="http://www.ns/ontology/2021/1.0#Elephas_maximus"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#PDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string"></rdfs:comment>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A female asian elephant called  Aqeela, here, the GPS collar (sensor) is named after her.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Bikang1 -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Bikang1">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:hasFeatureOfInterest rdf:resource="http://www.ns/ontology/2021/1.0#Elephas_maximus"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A female asian elephant called Bikang1, here, the GPS collar (sensor) is named after her.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Bikang2 -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Bikang2">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:hasFeatureOfInterest rdf:resource="http://www.ns/ontology/2021/1.0#Elephas_maximus"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A female asian elephant called Bikang2, here, the GPS collar (sensor) is named after her.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Dara -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Dara">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:hasFeatureOfInterest rdf:resource="http://www.ns/ontology/2021/1.0#Elephas_maximus"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#ExtTemp"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A female asian elephant called Dara, here, the GPS collar (sensor) is named after her.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Guli -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Guli">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:hasFeatureOfInterest rdf:resource="http://www.ns/ontology/2021/1.0#Elephas_maximus"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#ExtTemp"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A male asian elephant called Guli, here, the GPS collar (sensor) is named after him.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Ita -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Ita">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#ExtTemp"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A female asian elephant called Ita, here, the GPS collar (sensor) is named after her.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Jasmin -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Jasmin">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A female asian elephant called Jasmin, here, the GPS collar (sensor) is named after her.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Jasper -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Jasper">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#ExtTemp"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A male asian elephant called Jasper here, the GPS collar (sensor) is named after him.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Kasih -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Kasih">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#ExtTemp"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A female asian elephant called Kasih, here, the GPS collar (sensor) is named after her.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Kuma -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Kuma">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#ExtTemp"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A male asian elephant called Kuma, here, the GPS collar (sensor) is named after him.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Liun -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Liun">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#DateTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#PDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A female asian elephant called Liun, here, the GPS collar (sensor) is named after her.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Maliau -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Maliau">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#ExtTemp"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A male asian elephant called Maliau, here, the GPS collar (sensor) is named after him.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Merotai -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Merotai">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#ExtTemp"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A male asian elephant called Merotai, here, the GPS collar (sensor) is named after him.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Puteri -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Puteri">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#ExtTemp"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A female asian elephant called Puteri here, the GPS collar (sensor) is named after her.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Putut -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Putut">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A female asian elephant called Putut, here, the GPS collar (sensor) is named after her.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Sandi -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Sandi">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#ExtTemp"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A female asian elephant called Sandi, here, the GPS collar (sensor) is named after her.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Sejati -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Sejati">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A male asian elephant called Sejati, here, the GPS collar (sensor) is named after him.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Seri -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Seri">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#ExtTemp"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A female asian elephant called Seri, here, the GPS collar (sensor) is named after her.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Tulid -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Tulid">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#ExtTemp"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A female asian elephant called Tulid, here, the GPS collar (sensor) is named after her.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Tunglap -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Tunglap">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#ExtTemp"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A female asian elephant called Tunglap, here, the GPS collar (sensor) is named after her.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/elephant#Umas2 -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/elephant#Umas2">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Count"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Cov"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Direction"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Distance"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#ExtTemp"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTDate"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#GMTTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Temperature"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A male asian elephant called Umas2, here, the GPS collar (sensor) is named after him.</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.schema.org/ns/python#Juling -->

    <owl:NamedIndividual rdf:about="http://www.schema.org/ns/python#Juling">
        <rdf:type rdf:resource="http://www.w3.org/ns/sosa/Sensor"/>
        <sosa:hasFeatureOfInterest rdf:resource="http://www.schema.org/ns/python"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#DateTime"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#HDOP"/>
        <sosa:observedProperty rdf:resource="http://www.ns/ontology/2021/1.0#Speed"/>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A python (snake) called Juling- with tracking device called Juling</rdfs:comment>
    </owl:NamedIndividual>
    


    <!-- http://www.w3.org/1999/xhtml/vocab#license -->

    <owl:NamedIndividual rdf:about="http://www.w3.org/1999/xhtml/vocab#license"/>
    


    <!-- http://www.w3.org/2003/01/geo/wgs84_pos#Point -->

    <owl:NamedIndividual rdf:about="http://www.w3.org/2003/01/geo/wgs84_pos#Point">
        <wgs84_pos:lat rdf:datatype="http://www.w3.org/2001/XMLSchema#string"></wgs84_pos:lat>
        <wgs84_pos:long rdf:datatype="http://www.w3.org/2001/XMLSchema#string"></wgs84_pos:long>
    </owl:NamedIndividual>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Annotations
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    <rdf:Description rdf:about="http://creativecommons.org/ns#license">
        <rdfs:label xml:lang="en-us">has
          license</rdfs:label>
    </rdf:Description>
    <rdf:Description rdf:about="http://purl.org/dc/terms/isPartOf">
        <terms:description xml:lang="en">This property is intended to be used with non-literal values. This property is an inverse property of Has Part.</terms:description>
        <rdfs:comment xml:lang="en">A related resource in which the described resource is physically or logically included.</rdfs:comment>
        <rdfs:isDefinedBy rdf:resource="http://purl.org/dc/terms/"/>
        <rdfs:label xml:lang="en">Is Part Of</rdfs:label>
    </rdf:Description>
    <rdf:Description rdf:about="http://purl.org/dc/terms/rights">
        <terms:license rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Copyright 2017 W3C/OGC.</terms:license>
    </rdf:Description>
    <rdf:Description rdf:about="http://purl.org/vocab/vann/preferredNamespacePrefix">
        <rdfs:comment rdf:resource="http://www.foo/ns"/>
    </rdf:Description>
    <rdf:Description rdf:about="http://purl.org/vocab/vann/preferredNamespaceUri">
        <terms:title rdf:datatype="http://www.w3.org/2001/XMLSchema#string">http://www.foo.org/ns/</terms:title>
    </rdf:Description>
    <rdf:Description rdf:about="http://www.w3.org/2003/01/geo/wgs84_pos#">
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">
Recent changes to this namespace:
$Log: wgs84_pos.rdf,v $
Revision 1.22  2009/04/20 15:00:30  timbl
Remove the time bits which have been deal with elsewhere eg in iCal.

Revision 1.21  2009/04/20 12:52:47  timbl
try again

Revision 1.20  2009/04/20 12:42:11  timbl
Add Event (edited ages ago and never checked in), and location (following discussion http://chatlogs.planetrdf.com/swig/2009-04-20#T12-36-09)

Revision 1.19  2009/04/20 12:36:31  timbl
Add Event (edited ages ago and never checked in), and location (following discussion http://chatlogs.planetrdf.com/swig/2009-04-20#T12-36-09)

Revision 1.18  2006/02/01 22:01:04  danbri
Clarified that lat and long are decimal degrees, and that alt is decimal metres about local reference ellipsoid

Revision 1.17  2004/02/06 17:38:12  danbri
Fixed a bad commit screwup

Revision 1.15  2003/04/19 11:24:08  danbri
Fixed the typo even more.

Revision 1.14  2003/04/19 11:16:56  danbri
fixed a typo

Revision 1.13  2003/02/19 22:27:27  connolly
relaxed domain constraints on lat/long/alt from Point to SpatialThing

Revision 1.12  2003/01/12 01:41:41  danbri
Trying local copy of XSLT doc.

Revision 1.11  2003/01/12 01:20:18  danbri
added a link to morten&apos;s xslt rdfs viewer.

Revision 1.10  2003/01/11 18:56:49  danbri
Removed datatype range from lat and long properties, since they would
have required each occurance of the property to mention the datatype.

Revision 1.9  2003/01/11 11:41:31  danbri
Another typo; repaired rdfs:Property to rdf:Property x4

Revision 1.8  2003/01/11 11:05:02  danbri
Added an rdfs:range for each lat/long/alt property,
http://www.w3.org/2001/XMLSchema#float

Revision 1.7  2003/01/10 20:25:16  danbri
Longer rdfs:comment for Point, trying to be Earth-centric and neutral about
coordinate system(s) at the same time. Feedback welcomed.

Revision 1.6  2003/01/10 20:18:30  danbri
Added CVS log comments into the RDF/XML as an rdfs:comment property of the
vocabulary. Note that this is not common practice (but seems both harmless
and potentially useful).


revision 1.5
date: 2003/01/10 20:14:31;  author: danbri;  state: Exp;  lines: +16 -5
Updated schema:
Added a dc:date, added url for more info. Changed the rdfs:label of the
namespace from gp to geo. Added a class Point, set as the rdfs:domain of
each property. Added XML comment on the lat_long property suggesting that
we might not need it (based on #rdfig commentary from implementors).

revision 1.4
date: 2003/01/10 20:01:07;  author: danbri;  state: Exp;  lines: +6 -5
Fixed typo; several rdfs:about attributes are now rdf:about. Thanks to MortenF in
#rdfig for catching this error.

revision 1.3
date: 2003/01/10 11:59:03;  author: danbri;  state: Exp;  lines: +4 -3
fixed buglet in vocab, added more wgs links

revision 1.2
date: 2003/01/10 11:01:11;  author: danbri;  state: Exp;  lines: +4 -4
Removed alt from the as-a-flat-string property, and switched from
space separated to comma separated.

revision 1.1
date: 2003/01/10 10:53:23;  author: danbri;  state: Exp;
basic geo vocab

</rdfs:comment>
        <rdfs:label rdf:datatype="http://www.w3.org/2001/XMLSchema#string">geo</rdfs:label>
    </rdf:Description>
    <rdf:Description rdf:about="http://www.w3.org/2003/01/geo/wgs84_pos#Point">
        <metadata:prefixIRI rdf:datatype="http://www.w3.org/2001/XMLSchema#string">wgs84_pos:Point</metadata:prefixIRI>
        <iot-lite:relativeLocation rdf:datatype="http://www.w3.org/2001/XMLSchema#string"></iot-lite:relativeLocation>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string"> 
Uniquely identified by lat/long/alt. i.e.

spaciallyIntersects(P1, P2) :- lat(P1, LAT), long(P1, LONG), alt(P1, ALT),
  lat(P2, LAT), long(P2, LONG), alt(P2, ALT).

sameThing(P1, P2) :- type(P1, Point), type(P2, Point), spaciallyIntersects(P1, P2).
  </rdfs:comment>
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A point, typically described using a coordinate system relative to Earth, such as WGS84.
  </rdfs:comment>
        <rdfs:label rdf:datatype="http://www.w3.org/2001/XMLSchema#string">point</rdfs:label>
    </rdf:Description>
    <rdf:Description rdf:about="http://www.w3.org/2003/01/geo/wgs84_pos#lat">
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The WGS84 latitude of a SpatialThing (decimal degrees).</rdfs:comment>
        <rdfs:label rdf:datatype="http://www.w3.org/2001/XMLSchema#string">latitude</rdfs:label>
    </rdf:Description>
    <rdf:Description rdf:about="http://www.w3.org/2003/01/geo/wgs84_pos#lat_long">
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">A comma-separated representation of a latitude, longitude coordinate.</rdfs:comment>
        <rdfs:label rdf:datatype="http://www.w3.org/2001/XMLSchema#string">lat/long</rdfs:label>
    </rdf:Description>
    <rdf:Description rdf:about="http://www.w3.org/2003/01/geo/wgs84_pos#long">
        <rdfs:comment rdf:datatype="http://www.w3.org/2001/XMLSchema#string">The WGS84 longitude of a SpatialThing (decimal degrees).</rdfs:comment>
        <rdfs:label rdf:datatype="http://www.w3.org/2001/XMLSchema#string">longitude</rdfs:label>
    </rdf:Description>
</rdf:RDF>



<!-- Generated by the OWL API (version 4.5.18) https://github.com/owlcs/owlapi -->

- https://github.com/Naeima/Forest-Observatory-Ontology/releases/download/untagged-6c028dded47c721d2b4d/index-en.html