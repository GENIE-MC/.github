GENIE is an [international collaboration of scientists](https://hep.ph.liv.ac.uk/~costasa/genie/collaboration.html) that plays the leading role in**:
 - the development of a modern and universal event generator framework and tools in support of neutrino experiments,
 - the consistent, validated and efficient implementation of a constellation of alternative physics models within a common platform,
 - the development and characterisation of novel comprehensive physics models for the simulation of neutrino and charged lepton interactions, as well as for selected BSM channels, and
 - the development of an advanced global analysis of neutrino scattering data. 

You can find more details in our [mission statement](https://hep.ph.liv.ac.uk/~costasa/genie/mission.html).

The GENIE collaboration maintains a suite of software products for the experimental neutrino community. Repositories for all products are hosted in this official GENIE GitHub organization.

Several GENIE products, including all those related with the service component of our work, such as providing an event generator platform, physics model implementations and associated tools, have source code releases with a permissive license for typical academic use. Other GENIE products, especially those coupled with our dual function of developing a proprietary global analysis of neutrino scattering data do not have source code releases, as it is common practise for several HEP global analyses. Instead, it is our analysis results (physics tunes and uncertainty assignments) which are made publicly available through our event generator platform and associated uncertainty propagation tools.  

Please see the [GENIE copyright notice](http://copyright.genie-mc.org).


## GENIE products and repositories hosted in this GitHub organization

| Product | Description |
|---------|-------------|
| [Generator](https://github.com/GENIE-MC/Generator) | The well-known GENIE Generator product implements a modern framework for Monte Carlo event generators and includes state-of-the-art physics modules. The GENIE physics model is universal and comprehensive: It handles all neutrinos and targets, and all processes relevant from MeV to PeV energy scales. The Generator includes several tools (flux drivers, detector geometry navigation drivers, and specialized event generation apps) to simulate complex experimental setups in full detail. The GENIE Generator is used by nearly all modern neutrino experiments and its predictions serve as standard reference points for the neutrino community. Generators for charged lepton and hadron scattering off nucleons and nuclei, as well as several generators for BSM channels of interest at neutrino experiments, are supported within a unified physics framework.|
| [Comparisons](https://github.com/GENIE-MC/Comparisons) <br /> :key: | The Comparisons product includes very extensive curated archives of neutrino, charged-lepton and hadron scattering data, as well as highly-developed software to produce a comprehensive set of data/MC comparisons. It includes embedded interfaces to the Professor tuning tool which "reduces the exponentially expensive process of brute-force tuning to a scaling closer to a power law in the number of parameters and allows for massive parallelisation". The Comparisons product plays a key role in comprehensive model characterization in GENIE, it underpins the GENIE global analysis, and it enabled the production of several new tunes.| 
| [Tuning](https://github.com/GENIE-MC/Tuning) <br /> :key: | The Tuning product implements the powerfull new GENIE global analysis of neutrino scattering data. The GENIE global analysis produces physics tunes which are fully integrated in the Generator product. |
| [Reweight](https://github.com/GENIE-MC/Reweight) | The Reweight product includes a selection of tools to propagate model uncertainties and to support generator-related analysis tasks. The reweighting procedure has inherent limitations. Important modelling systematics are not reweightable in principle and they have no corresponding weight calculator in the Reweight product. Indeed, the GENIE tuning procedure itself makes no use of the Reweight product but it relies on response functions constructed from brute-force parameter scans made with the aid of the Professor tool. Currently, the Reweight product it does not provide the full systematic error for any GENIE tune. However, we have medium-term plans to overhaul this product and use it for public release of the detailed Professor/YODA response functions constructed from our brute-force systematic parameter scans, as well as to release all covariance matrices from the GENIE global fits of neutrino scattering data. The upgraded Reweight product will support all public GENIE physics tunes! |
| [Prof-GENIE](https://github.com/GENIE-MC/Prof-GENIE) <br /> :key: | The GENIE - Professor interface codes |
| [GENIE-MC.github.io](https://github.com/GENIE-MC/GENIE-MC.github.io) <br /> :key: | The source code for the official GENIE web page |
| [AVS-CI](https://github.com/GENIE-MC/AVS-CI) | Automated Validation Suite - Continuous Integration |

:key:

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

