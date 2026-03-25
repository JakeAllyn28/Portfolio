# Machine Learning for Building Classification

**Context:** ACTA-SH
**Stack:** Python, TensorFlow, Google Earth, OpenStreetMap
**Focus:** Computer Vision, Data Pipelines, Simulation Integration

---

## Overview

Developed a machine learning pipeline to classify building components from aerial imagery and generate approximate internal building structures.

The system was designed to support simulation workflows by enabling rapid construction of “digital buildings” using only external data sources.

---

## Problem

* Simulation models required structural representations of buildings
* Detailed building data is often unavailable or incomplete
* Manual modeling was too slow for large-scale analysis
* Needed a method to infer internal structure from external observations

---

## Approach

Built an end-to-end pipeline combining:

* aerial + street imagery (Google Earth)
* open-source geographic data + building footprints (OpenStreetMap)
* machine learning-based classification (TensorFlow)

The goal was to infer building composition and generate usable simulation inputs with minimal manual effort.

---

## Dataset Generation

* Collected aerial and street imagery from Google Earth
* Labeled building regions and components for training
* Used OpenStreetMap data for building footprints and layout constraints
* Created a structured dataset for supervised learning

---

## Model Development

* Trained a neural network using TensorFlow for image-based classification
* Focused on identifying building features and structural regions
* Iteratively trained and refined models over extended training cycles (overnight / multi-day runs)

---

## Integration with Simulation

* Combined classification outputs with building footprint data
* Generated approximate internal building representations
* Produced inputs compatible with fast-running simulation models

This enabled simulation workflows to operate on inferred structures rather than manually constructed models.

---

## Key Features

* Automated building classification from aerial imagery
* Integration with open-source geographic data
* Scalable pipeline for generating simulation-ready structures
* Reduced reliance on manual modeling

---

## Limitations

* Model accuracy was sensitive to image quality and perspective
* Unable to reliably detect deceptive or non-structural facades
* Misclassification occurred in intentionally misleading or non-standard structures

---

## Results / Impact

* Enabled rapid generation of building models for simulation workflows
* Supported Air Force-related efforts in scenario modeling and analysis
* Reduced time required to construct simulation environments
* Extended simulation capability to areas with limited structural data
