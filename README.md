# Chinese Historical RPF: Computational Analysis of Political Allegory and Narrative Reimagination
This repository contains code, data, and analysis for the study "From Metaphor to Literal Romance: Computational Analysis of Political Allegory and Narrative Reimagination in Chinese Historical RPF", investigating how traditional Chinese political allegory is transformed into explicit romantic narratives in digital fan culture.

## Overview
This interdisciplinary project combines computational methods (network analysis, statistical modeling, LLM-based extraction) with humanistic inquiry to analyze Chinese historical Real Person Fiction (RPF) on Archive of Our Own (AO3). The study examines:
-Structural patterns of romantic reimagination through network analysis
-Narrative dynamics of monarch-official relationships using LLM extraction
-Community practices through qualitative interviews with fan creators

## Repository Structure
├── code/
│   ├── ao3_data_statistics.py    # AO3 metadata processing and statistical analysis
│   ├── triple_extraction.py   # LLM-based interaction extraction pipeline
│   ├── model_evaluation.py   # Performance evaluation of LLM extraction
│
├── data/
│   ├── network   # Node and edge list
│   ├── fandom    # Chinese RPF AO3 Fandom data
│   ├── cross_dynasty # Identified cross dynasty pairing
│
├── test_corpus/
│   ├── human_annotations 
│   └── evaluation/
│
├── model_triple_extraction/  # Model triple extraction results
│
├── interview_transcripts/   # Eight interview transcripts
│
└── README.md                         # This file

## Prerequisites
Python 3.9 or higher
Gephi 0.9.7 or higher
LM Studio 0.3.37 or higher
