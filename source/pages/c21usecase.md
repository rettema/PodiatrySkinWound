---
title: Connectathon 21 Use Case
layout: default
active: guidance
topofpage: true
r3: http://hl7.org/fhir/STU3/
us_r3: http://hl7.org/fhir/us/core/
---

{:.no_toc}

<!-- TOC  the css styling for this is \pages\assets\css\project.css under 'markdown-toc'-->

* Do not remove this line (it will not be displayed)
{:toc}

##  Introduction

Podiatry Wound Assessment Template (WATT) Scenario - User Story 1 (HL7 FHIR Connectathon 21, May 2019, Montreal).

<p>&nbsp;</p>

## Actors

The following actors and FHIR interactions are part of this User Story:

* **Patient**: Person presenting the wound

* **Primary Care Physician (PCP) EHR**
  * _FHIR Interactions to Registry_: create, read, update and search of WATT data
  * _FHIR Interactions to other EHR actors_: read and search of WATT data

* **Wound Care Center Specialist EHR**
  * _FHIR Interactions to Registry_: create, read, update and search of WATT data
  * _FHIR Interactions to other EHR actors_: read and search of WATT data

* **Local Podiatrist EHR**
  * _FHIR Interactions to Registry_: create, read, update and search of WATT data
  * _FHIR Interactions to other EHR actors_: read and search of WATT data

* **Wound Assessment Registry (and Repository)**
  * _FHIR Interactions from other EHR actors_: create, read, update and search of WATT data

<p>&nbsp;</p>

## Summary Workflow

The overall workflow is outlined in the following figure.  The numbered items are the actual FHIR transactions that are the focus of this Guide and are described in detail in the following sections:

{% include img.html img="C21_UseCase_Workflow.jpg" caption="Connectathon 21 Workflow" %}

<p>&nbsp;</p>

## FHIR Interactions

### EHR Server

read and search definitions and examples here

### Registry Server

create, read, update and search definitions and examples here

<p>&nbsp;</p>

**Summary of FHIR Artifacts**

## FHIR Resource Overview

### Resources supported for this use case:
{:.no_toc}

|Resource Type|Profile Name|Link to STU3 Profile|
|---|---|---|
|Patient|US Core Patient Profile|[US Core Patient (STU3)]|
|Practitioner|US Core Practitioner Profile|[US Core Practitioner (STU3)]|
|Encounter|US Core Encounter Profile|[US Core Encounter (STU3)]|
|Condition|US Core Condition Profile|[US Core Condition (STU3)]|
|Observation|FHIR Observation Profile|[FHIR Observation (STU3)]|
|AuditEvent|FHIR AuditEvent Profile|[FHIR AuditEvent (STU3)]|


{% include link-list.md %}
