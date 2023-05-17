# VBS_RDF

This repo contains the code for running the CMS analysis of VBS ssWW with hadronic tau and light lepton in final state, with ROOT's RDataFrame.
It is divided in two steps: 
- a preselection step that filters out events in the basis of triggers and minimal requirements on final state objects, augments the dataset with relevant corrections, and  writes out skimmed and augmented TTrees;
- a postselection that, starting from the output of previous steps, runs the proper event reconstruction and produces histograms for each interesting variable (in this case, lepton pt, tau pt and invariant mass of vbs jet pair), for each nominal and systematic variations, control/signal region,  group of samples, final state.
