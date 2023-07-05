---
title: Terminology
layout: default
name: terminology
---

This page lists all the ValueSets defined as part of the this implementation Guide. For more information on using codes in resources, see the [FHIR specification]({{site.data.fhir.path}}terminologies.html).

### CodeSystem

These codesystems have been defined for this implementation guide.

<!-- <ul>
	<li>
		<strong>PM-JAY CodeSystems</strong>
		<br/>	
	</li>
</ul> -->

<!-- <table class="table table-bordered table-striped table-hover"><thead style="background: lightsteelblue;"><tr><th style="width:20%;">Name</th><th>Definition</th></tr></thead><tbody> -->

<!-- <tr><td><a href="CodeSystem-pmjay-benefitcategory.html">PMJAY-Benefit-Category</a></td><td>This CodeSystem contains PMJAY category codes for insurance claims </td></tr> 

<tr><td><a href="CodeSystem-pmjay-modifier.html">PMJAY-Modifier</a></td><td>This CodeSystem contains PMJAY modifier codes for insurance claims </td></tr> 

<tr><td><a href="CodeSystem-pmjay-procedure.html">PMJAY-Procedure</a></td><td>This CodeSystem contains PMJAY Procedure for insurance claims </td></tr> 

<tr><td><a href="CodeSystem-pmjay-procedure-type.html">PMJAY-ProcedureType</a></td><td>This CodeSystem contains PMJAY Procedure Type for insurance claims </td></tr> 

<tr><td><a href="CodeSystem-pmjay-productorservice.html">PMJAY-ProductorService</a></td><td>This CodeSystem contains PMJAY Product or Service codes for insurance claims </td></tr>  -->

<!-- <tr><td><a href="CodeSystem-pmjay-programcode.html">PMJAY-ProgramCode</a></td><td>This CodeSystem contains PMJAY Program Codes for insurance claims </td></tr>  -->

<!-- </tbody></table> -->

<ul>
	<li>
		<strong>Administrative CodeSystems</strong>
		<br/>	
	</li>
</ul>

<table class="table table-bordered table-striped table-hover"><thead style="background: lightsteelblue;"><tr><th style="width:20%;">Name</th><th>Definition</th></tr></thead><tbody>

<!-- <tr><td><a href="CodeSystem-ndhm-facility-type-code.html">Facility Type Code</a></td><td>This CodeSystem Contain facility type codes</td></tr>  -->

<tr><td><a href="CodeSystem-ndhm-identifier-type-code.html">Identifier Type Code</a></td><td>This CodeSystem contains coded type for an identifier that can be used to determine which identifier to use for a specific purpose</td></tr> 

<tr><td><a href="CodeSystem-ndhm-program-code.html">Program Code</a></td><td>This CodeSystem contains set of codes that can be used to classify groupings of service-types/specialties</td></tr> 

<tr><td><a href="CodeSystem-ndhm-supportinginfo-category.html">SupportingInfo Category</a></td><td>This CodeSystem contains classification of the information supplied for the processing of different workflows like claims etc.</td></tr> 

<tr><td><a href="CodeSystem-ndhm-supportinginfo-code.html">SupportingInfo Code</a></td><td>This CodeSystem contains code pertaining to the specific information mentioned with the category of supporting info</td></tr>

<tr><td><a href="CodeSystem-ndhm-insuranceplan-type.html">InsurancePlan Type</a></td><td>This CodeSystem is composed of codes that are used to classify the various types of InsurancePlans.</td></tr>

<tr><td><a href="CodeSystem-ndhm-coverage-type.html">Coverage Type</a></td><td>This CodeSystem consists of a set of codes that can be utilized to categorize the insurance coverage type.</td></tr>

<tr><td><a href="CodeSystem-ndhm-benefit-type.html">Benefit Type</a></td><td>This CodeSystem includes a collection of codes that can be used to categorize the type of benefits provided by an insurance.</td></tr>


<tr><td><a href="CodeSystem-ndhm-plan-type.html">Plan Type</a></td><td>This CodeSystem contains a set of codes that can be utilized to categorize the type of insurance plans.</td></tr>


</tbody></table>

### ValueSets

These value sets have been defined for this implementation guide.



<ul>
	<li>
		<strong>Administrative ValueSets</strong>
		<br/>	
	</li>
</ul>


<!-- {% raw %}{% include list-simple-valuesets.xhtml %}{% endraw %} -->
<table class="table table-bordered table-striped table-hover"><thead style="background: lightsteelblue;"><tr><th style="width:20%;">Name</th><th>Definition</th></tr></thead><tbody>

<tr><td><a href="ValueSet-ndhm-identifier-type-code.html">Identifier Type Code</a></td><td>This Valueset contains coded type for an identifier that can be used to determine which identifier to use for a specific purpose</td></tr>


<tr><td><a href="ValueSet-ndhm-program-code.html">Program Code</a></td><td>This Valueset contains set of codes that can be used to classify groupings of service-types/specialties.</td></tr>


<tr><td><a href="ValueSet-ndhm-supportinginfo-category.html">SupportingInfo Category</a></td><td>This Valueset contains classification of the information supplied for the processing of different workflows like claims etc.</td></tr>

<tr><td><a href="ValueSet-ndhm-supportinginfo-code.html">SupportingInfo Code</a></td><td>This Valueset contains code pertaining to the specific information mentioned with the category of supporting info.</td></tr>

<tr><td><a href="ValueSet-ndhm-benefitcategory.html">Benefit Category</a></td><td>This Valueset includes a collection of SNOMEDCT codes related to BenefitCategory.</td></tr> 

<tr><td><a href="ValueSet-ndhm-productorservice.html">ProductOrService</a></td><td>This Valueset consists of a set of SNOMEDCT codes that pertain to ProductorService.</td></tr> 


<tr><td><a href="ValueSet-ndhm-insuranceplan-type.html">InsurancePlan Type</a></td><td>This Valueset is composed of codes that are used to classify the various types of InsurancePlans.</td></tr> 


<tr><td><a href="ValueSet-ndhm-coverage-type.html">Coverage Type</a></td><td>This ValueSet consists of a set of codes that can be utilized to categorize the insurance coverage type.</td></tr> 

<tr><td><a href="ValueSet-ndhm-benefit-type.html">Benefit Type</a></td><td>This ValueSet includes a collection of codes that can be used to categorize the type of benefits provided by an insurance.</td></tr> 

<tr><td><a href="ValueSet-ndhm-plan-type.html">Plan Type</a></td><td>This ValueSet contains a set of codes that can be utilized to categorize the type of insurance plans.</td></tr> 




</tbody></table>


<ul>
	<li>
		<strong>Clinical ValueSets</strong>
		<br/>	
	</li>
</ul>


<table class="table table-bordered table-striped table-hover"><thead style="background: lightsteelblue;"><tr><th style="width:20%;">Name</th><th>Definition</th></tr></thead><tbody>


<tr><td><a href="ValueSet-ndhm-alcohol-drinking-status.html">Alcohol Drinking Status</a></td><td>This value set covers : All childrens (preferred term) of finding relating to alcohol drinking behavior (finding) of the SNOMED CT.</td></tr>

<tr><td><a href="ValueSet-ndhm-body-measurement.html">Body Measurement</a></td><td>This value set covers LOINC Codes for Body Measurement.</td></tr>

<tr><td><a href="ValueSet-ndhm-diagnosis-use.html">Diagnosis Use</a></td><td>This value set contains a set of SNOMED CT codes for Diagnosis type</td></tr>


<tr><td><a href="ValueSet-ndhm-diagnostic-report-type.html">Diagnostic Report Type</a></td><td>The Diagnostic Report Type Value Set is a set of types supported for Diagnostic Reports and notes.</td></tr>


<tr><td><a href="ValueSet-ndhm-diet-type.html">Diet Type</a></td><td>This value set covers : All childrens (preferred term) of finding relating to Dietary finding (finding) of the SNOMED CT.</td></tr>


<tr><td><a href="ValueSet-ndhm-encounter-type.html">Encounter Type</a></td><td>This value set contains a set of SNOMED CT codes for Encounter type</td></tr>


<tr><td><a href="ValueSet-ndhm-general-assessment.html">General Assessment</a></td><td>This value set covers LOINC and SNOMED CT Codes for General Assessment.</td></tr>

<tr><td><a href="ValueSet-ndhm-general-well-being.html">General Wellbeing</a></td><td>This value set covers : All childrens (preferred term) of General well-being finding (finding) of the SNOMED CT.</td></tr>

<tr><td><a href="ValueSet-ndhm-lifestyle.html">Lifestyle</a></td><td>This value set covers LOINC Codes for type of Lifestyle.</td></tr>


<tr><td><a href="ValueSet-ndhm-medicine-codes.html">Medicine Codes</a></td><td>This Value Set covers: Clinical Drugs from SNOMED CT International Edition, Clinical Drugs and Branded Medicines (Real Clinical Drugs) from Common Drug Codes for India (National Extension). For more information refer: <a href="https://www.nrces.in/services/national-releases">https://www.nrces.in/services/national-releases</a></td></tr>

<tr><td><a href="ValueSet-ndhm-mental-status.html">Mental Status</a></td><td>This value set covers : All childrens (preferred term) of finding relating to Emotional state finding (finding) of the SNOMED CT.</td></tr>



<tr><td><a href="ValueSet-ndhm-practitioner-role.html">Practitioner Role</a></td><td>This value set defines a set of codes that can be used to indicate the role of a Practitioner.</td></tr>


<tr><td><a href="ValueSet-ndhm-physical-activity.html">Physical Activity</a></td><td>This value set covers LOINC Codes for Physical Activity.</td></tr>


<tr><td><a href="ValueSet-ndhm-route-of-administration.html">Route Of Administration</a></td><td>This value set contains a set of SNOMED CT codes for Route Of Administration.</td></tr>

<tr><td><a href="ValueSet-ndhm-specimen-types.html">Specimen Types</a></td><td>This value set contains a set of SNOMED CT codes for Specimen Types.</td></tr>

<tr><td><a href="ValueSet-ndhm-tobacco-smoking-status.html">Tobacco Smoking Status</a></td><td>This value set covers : All childrens (preferred term) of Finding relating to tobacco smoking behavior (finding) of the SNOMED CT.</td></tr>

<tr><td><a href="ValueSet-ndhm-tobacco-chewing-status.html">Tobacco Chewing Status</a></td><td>This value set covers : All childrens (preferred term) of Finding relating to tobacco chewing of the SNOMED CT.</td></tr>

<tr><td><a href="ValueSet-ndhm-vaccine-codes.html">Vaccine Codes</a></td><td>This value set covers : All leafe nodes (preferred term) of childrens of Vaccine product containing bacteria antigen (medicinal product) and Vaccine product containing virus antigen (medicinal product) of the SNOMED CT.</td></tr>


<tr><td><a href="ValueSet-ndhm-vital-signs.html">Vital Signs</a></td><td>This value set covers LOINC Codes for Vital Signs.</td></tr>


<tr><td><a href="ValueSet-ndhm-women-health.html">Women Health</a></td><td>This value set covers LOINC Codes for Women Health.</td></tr>

</tbody></table>