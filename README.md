# Functional Safety of a Lane Assistance System

A safety case collection of documents for a lane assistance system that ensures comliance with the ISO 26262 standard on "Road vehicles – Functional safety".

Here is the [rubric](https://review.udacity.com/#!/rubrics/1043/view) for the project.

## Introduction

The Lane Assistance system is a simple part of an ADAS - Advanced Driver Assistance System which contains two basic functions:

### LDW - Lane Departure Warning

When the vehicle camera senses that the driver it is about to change lane without using the appropriate turn indicator, the Lane Departure Warning function vibrates the steering wheel in order for the driver to get a warning that an involuntary lane change is about to happen.

### LKA - Lane Keeping Assistance

When the vehicle approaches the lane boundary, the Lane Keeping Assistance function takes wheel and adds extra steering torque to help the driver move back towards the centre of the lane.

## Description of Repo Files

The `root` directory contains the safety case documents in pdf format:

* 01_SafetyPlan_LaneAssistance.pdf

* 02_HazardAnalysisAndRiskAssessment.pdf

* 03_FunctionalSafetyConcept_LaneAssistance.pdf

* 04_TechnicalSafetyConcept_LaneAssistance.pdf

* 05_SoftwareRequirementsAndArchitecture_LaneAssistance.pdf

The `Pages` directory contains the safety case documents in apple pages and numbers formats for development:

* 01_SafetyPlan_LaneAssistance.pages

* 02_HazardAnalysisAndRiskAssessment.numbers

* 03_FunctionalSafetyConcept_LaneAssistance.pages

* 04_TechnicalSafetyConcept_LaneAssistance.pages

* 05_SoftwareRequirementsAndArchitecture_LaneAssistance.pages

The `Archtectural_Diagrams` directory contains the visuals that are used throughout the documents
