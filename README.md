# Apollo-Implant-for-Non-Neuropixel-Silicon-Probes
A modification of the Apollo chronic implant system which allows Neuronexus and Cambridge Neurotech probes to be chronically implanted with dental cement, yet recovered after the experiment for cleaning and reuse. 
<img width="1024" height="739" alt="image" src="https://github.com/user-attachments/assets/a4b98195-03b9-4934-b329-263b31ada615" />


The original e-life paper can be found [here](<https://elifesciences.org/articles/98522>), and the github with the files is [here](https://github.com/Coen-Lab/chronic-neuropixels)

The original apollo implant was designed for neuropixels, and consists  of 2 parts:

1)The payload module<br>
2)The docking module

Neuropixel probes get glued/cemented onto the payload module, which slides and screws into the docking module. During the surgery, you implant this docking + payload module assembly, and apply cement ONLY to the docking module. After your experiment, you anesthetize, unscrew the payload module from the docking module and slowly explant the probe from the brain.

This gives the stability of a probe that is cemented onto the skull, while allowing for recovery and reuse.

Unfortunately, the Apollo implant was designed only for neuropixel probes, which have a detatchable ribbon cable. This is NOT the case for Neuronexus and Cambridge Neurotech silicon probes, and posed an immense challenge.

Therefore, my modifications have 3 parts:
1)A payload module<br>
2)A docking module with front panel<br>
3)A back panel

The steps for assembly are as follows:

1) Superglue the probe interface (the part where the shanks are coming from) to the docking module<br>
2) Carefully insert the payload module with the probe into the docking module w/ front panel (I do this by hand, its actually not bad if you do it slowly on a flat table).<br>
3) Gently slide the ribbon cable + board (by board I mean the green board containing the Omnetics connector for Neuronexus probes, or the ASSY 350 128ch integrated headstage for Cambridge Neuro probes) into the front panel.<br>
4) Combine the back panel with the front panel  

My modifications were done on top another modification of the original Apollo implant ([the NP2_SingleProbeDockingWithHeadstage_ANGLED](https://github.com/Coen-Lab/chronic-neuropixels/tree/main/XtraModifications/Mouse_FreelyMoving) redesign by Shahaf Weiss (Max-Planck institute for brain-research, Frankfurt am Main, Germany Email: shahaf.weiss@brain.mpg.de)

Note: there is a newer attempt at a screwless solution (screwing/unscrewing exerts off-axis forces to probes, posing a risk to fragile probes like the 15um thick Buzsaki multi-shank probes), called ScrewX [github link](https://github.com/NP-HarrisLab/Harris-Lab-Neuropixels-Fixture-Design), [BioRxiv link](https://www.biorxiv.org/content/10.64898/2026.01.06.697790v1), but I haven't played around with re-designing that yet.

The original files were made in Autodesk Inventor.<br>
As of 7/2026, the CA2 implant pieces are Inventor .ipt files (TODO import to Fusion),br.
The mPFC implant pieces are Fusion.f3z (with .3mf and .stl files for direct printing) 
