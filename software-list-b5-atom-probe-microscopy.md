# Atom probe microscopy<br>
<table style="width:100%"><br>
<tr><br>
<th>ToolName</th><br>
<th>Link</th><br>
<th>License</th><br>
<th>Importance</th><br>
<th>Description</th><br>
<th>Category</th><br>
<th>Python?</th><br>
<th>Matlab?</th><br>
<th>R?</th><br>
<th>C/C++?</th><br>
<th>OtherLanguage?</th><br>
<th>VersionToStartWith</th><br>
<th>SupportedOS</th><br>
<th>MostImportantUserInterfaceStyle</th><br>
<th>Dependencies</th><br>
<th>Visualization</th><br>
</tr><br>
<tr><br>
<th>IVAS / AP Suite</th><th><a href="atomprobe.com" target="_top">atomprobe.com</a></th><th>Proprietary</th><th>1</th><th>Reconstruction and Visualisation for CAMECA atom probes</th><th>Visualization, Analysis</th><th></th><th></th><th></th><th>x</th><th>Java</th><th>AP Suite 6</th><th>Win</th><th>GUI, C# scripting, Python planned mid-term</th><th>tools coming with Win</th><th>2D graphs, 3D point clouds, 3D mesh data, volumetric rendering</th></tr><br>
<tr><br>
<th>libatomprobe</th><th><a href="https://hg.sr.ht/~mycae/libatomprobe" target="_top">https://hg.sr.ht/~mycae/libatomprobe</a></th><th>Open Source</th><th>1</th><th>Base library for writing atom probe programs</th><th>Analysis</th><th>x</th><th></th><th></th><th>x</th><th></th><th>n/a, multiple tools in the repo</th><th>Win,Linux</th><th>CLI</th><th>n/a</th><th>2D graphs</th></tr><br>
<tr><br>
<th>PARAPROBE</th><th><a href="https://gitlab.mpcdf.mpg.de/mpie-aptfim-toolbox/paraprobe " target="_top">https://gitlab.mpcdf.mpg.de/mpie-aptfim-toolbox/paraprobe </a></th><th>Open source</th><th>1</th><th>Parallelized tools for scalable processing of APT data</th><th>Analysis</th><th></th><th></th><th></th><th>x</th><th></th><th>v0.2</th><th>Linux, Win (via WSL)</th><th>Scripting</th><th>self-contained package which includes HDF5, CGAL, GammaPNC, Eigen, boost, TetGen</th><th>2D graphs via Python/Jupyter, 3D point clouds and 3D mesh data via HDF5/XDMF </th></tr><br>
<tr><br>
<th>APT-Tools (Oscarbranson)</th><th><a href="https://github.com/oscarbranson/apt-tools " target="_top">https://github.com/oscarbranson/apt-tools </a></th><th>Open source</th><th>1</th><th>Python tools for importing, processing APT data</th><th>Analysis</th><th>x</th><th></th><th></th><th></th><th></th><th>n/a</th><th>Win,Linux,Mac</th><th>Scripting</th><th>none</th><th>2D graphs, rudimentary 3D volume via Python/Jupyter</th></tr><br>
<tr><br>
<th>Benjamin Caplins’/NIST APT tools</th><th><a href="https://github.com/bcaplins/NIST_APT_TOOLS " target="_top">https://github.com/bcaplins/NIST_APT_TOOLS </a></th><th>Open source</th><th>1</th><th>Calibration methods for ToF and mass-to-charge among others</th><th>Analysis</th><th>x</th><th></th><th></th><th></th><th></th><th>n/a</th><th>Win,Linux,Mac</th><th>Scripting</th><th>n/a</th><th>2D graphs</th></tr><br>
<tr><br>
<th>3Depict</th><th><a href="http://threedepict.sourceforge.net" target="_top">http://threedepict.sourceforge.net</a></th><th>Open Source</th><th>2</th><th>Visualisation and analysis for reconstructed data</th><th>Visualization, Analysis</th><th></th><th></th><th></th><th>x</th><th>WxWidgets</th><th>0.0.23</th><th>Win,Linux?,Mac?</th><th>GUI</th><th>tools coming with Win</th><th>3D point clouds, 3D mesh data</th></tr><br>
<tr><br>
<th>APT Tools</th><th><a href="http://apttools.sourceforge.net" target="_top">http://apttools.sourceforge.net</a></th><th>Open Source</th><th>2</th><th>Mixture of small utilities for atom probe data analysis, includes libatomprobe and posgen (see other entries)</th><th>Analysis</th><th></th><th></th><th></th><th>x</th><th></th><th>n/a, multiple tools in the repo</th><th>Case-dependent</th><th>Case-dependent</th><th>n/a</th><th>2D graphs, interactive</th></tr><br>
<tr><br>
<th>Atomprobelab</th><th><a href="https://sourceforge.net/projects/atomprobelab/" target="_top">https://sourceforge.net/projects/atomprobelab/</a></th><th>Open Source</th><th>2</th><th>Mass-spectra analysis for complex multi-peak datasets, plus other misc tools</th><th>Mass-peak overlap solving</th><th></th><th>x</th><th></th><th></th><th></th><th>n/a</th><th>Case-dependent</th><th>Case-dependent</th><th>n/a</th><th>Matlab-based visualization</th></tr><br>
<tr><br>
<th>CASRA</th><th><a href="https://gitlab.com/fletchie/casra" target="_top">https://gitlab.com/fletchie/casra</a></th><th>Open Source</th><th>2</th><th>2D Fast continuum evaporation simulator</th><th>Evaporation simulator</th><th>x</th><th></th><th></th><th></th><th></th><th>v1.1</th><th>Win,Linux?</th><th>Scripting</th><th>needs src inspection to clarify</th><th>2D and 3D graphs via Python/Jupyter</th></tr><br>
<tr><br>
<th>CASRA3D</th><th><a href="https://gitlab.com/fletchie/casra-3d/" target="_top">https://gitlab.com/fletchie/casra-3d/</a></th><th>Open Source, by a proprietary version is currently developed jointly with Cameca</th><th>2</th><th>3D Fast continuum evaporation simulator</th><th>Evaporation & reconstruction simulator</th><th>x</th><th></th><th></th><th></th><th></th><th>bd56e07fcf67cd57e47b0c709944c088aeaf7cb3</th><th>Win,Linux?</th><th>Scripting</th><th>needs src inspection to clarify</th><th>2D and 3D graphs via Python/Jupyter</th></tr><br>
<tr><br>
<th>CVL</th><th><a href="https://www.cvl.org.au/cvl-desktop/workbenches/atom-probe-workbench" target="_top">https://www.cvl.org.au/cvl-desktop/workbenches/atom-probe-workbench</a></th><th>Mixed</th><th>2</th><th>Web host/service for atom probe programs. Allows login for users to access various APT software, and for developers to host "live" versions of software</th><th>Program sharing platform</th><th></th><th></th><th></th><th></th><th>Mixed</th><th>n/a, own cloud service of UNSW behind which multiple tools are available on a workstation, manual account management UNSW</th><th>Win,Linux,Mac?</th><th>Cloud</th><th>does not apply, individual source code tools on the CVL workstation has mainly be implemented in other tools already or can moderately easily be reimplemented via Python or C/C++ into paraprobe</th><th>2D and 3D graphs</th></tr><br>
<tr><br>
<th>Scito</th><th><a href="http://inspico.de/ " target="_top">http://inspico.de/ </a></th><th>Proprietary/Some open</th><th>2</th><th>Reconstruction software for M-TAP systems</th><th>Analysis</th><th></th><th></th><th></th><th></th><th>?</th><th>?</th><th>Win</th><th>GUI</th><th>n/a</th><th>3D point clouds, 3D mesh data</th></tr><br>
<tr><br>
<th>EPOSA</th><th><a href="Jens Keutgen is the contact person" target="_top">Jens Keutgen is the contact person</a></th><th>Mixed</th><th>2</th><th>Matlab GUI for APT processing</th><th>Visualization, Analysis</th><th></th><th>x</th><th></th><th></th><th></th><th>no open repo, so unclear</th><th>Win,Linux?,Mac?</th><th>GUI</th><th>none expected ?</th><th>Matlab-based visualization</th></tr><br>
<tr><br>
<th>APyT and related Python tools from the MPIE in Düsseldorf</th><th><a href="Shyam Katnagallu, Isabell Mouton, Andrew Breen, Murat Han Celik" target="_top">Shyam Katnagallu, Isabell Mouton, Andrew Breen, Murat Han Celik</a></th><th>Open source</th><th>2</th><th>Collection of Python and Matlab scripts for correlative analyses of Max-Planck-Institut für Eisenforschung GmbH, Düsseldorf</th><th>Visualization, Analysis</th><th>x</th><th>x</th><th></th><th></th><th></th><th>no open repo, so unclear</th><th>Win,Linux?</th><th>Scripting</th><th>n/a</th><th>2D graphs via Python/Jupyter</th></tr><br>
<tr><br>
<th>Atom Probe Code</th><th><a href="https://github.com/peterfelfer/atom-probe-code" target="_top">https://github.com/peterfelfer/atom-probe-code</a></th><th>Open source</th><th>2</th><th>Peter Felfer: Code for analysis of atom probe data</th><th>Analysis</th><th></th><th>x</th><th></th><th></th><th></th><th>use Peter Felfers Atom-Probe-Toolbox instead</th><th>Win,Linux?,Mac?</th><th>GUI</th><th>deprecated</th><th>n/a</th></tr><br>
<tr><br>
<th>Atom probe toolbox</th><th><a href="https://github.com/peterfelfer/Atom-Probe-Toolbox " target="_top">https://github.com/peterfelfer/Atom-Probe-Toolbox </a></th><th>Open source</th><th>2</th><th>Peter Felfer: Matlab atom probe toolbox</th><th>Analysis</th><th></th><th>x</th><th></th><th></th><th></th><th>c41f360a08219fe675e3b652c9d3f6cd2fe05cd5</th><th>Win,Linux?,Mac?</th><th>GUI</th><th>tools coming with Matlab</th><th>Matlab-based visualization</th></tr><br>
<tr><br>
<th>OPTICS-APT</th><th><a href="https://github.com/pnnl/apt/tree/master/OPTICS-APT" target="_top">https://github.com/pnnl/apt/tree/master/OPTICS-APT</a></th><th>Open source</th><th>2</th><th>Implementation of the OPTICS algorithm and associated visualisation tools</th><th>Visualization, Analysis</th><th>x</th><th></th><th></th><th></th><th></th><th>fb0f4b6474f9b8370e1bcdec35bdaedf3138de1b</th><th>Linux,Win?</th><th>Scripting</th><th>needs src inspection to clarify</th><th>2D and 3D graphs via Python/Jupyter</th></tr><br>
<tr><br>
<th>RangerApp</th><th><a href="http://apttools.sourceforge.net/" target="_top">http://apttools.sourceforge.net/</a></th><th>Open source</th><th>2</th><th>Simple Range-file editor</th><th>Analysis</th><th></th><th></th><th></th><th>x</th><th></th><th>n/a, multiple tools in the repo</th><th>Case-dependent</th><th>Case-dependent</th><th>n/a</th><th>2D graphs</th></tr><br>
<tr><br>
<th>Clara Tan’s tools</th><th><a href="https://github.com/tanosaur/massreproduction " target="_top">https://github.com/tanosaur/massreproduction </a></th><th>Open source</th><th>1</th><th>Ranging</th><th>Analysis</th><th>x</th><th></th><th></th><th></th><th></th><th>932879421a05780fe2a6619405a8b294109eb562</th><th>Linux</th><th>Scripting</th><th>needs src inspection to clarify</th><th>2D graphs with pyQt interaction</th></tr><br>
<tr><br>
<th>Xuyang Zhou’s tools</th><th><a href="https://github.com/RhettZhou/APT_GB " target="_top">https://github.com/RhettZhou/APT_GB </a></th><th>Open source</th><th>2</th><th>CNN-based composition analyses for (planar) interfaces</th><th>Analysis</th><th>x</th><th>x</th><th></th><th></th><th></th><th>08cfe33337ab5df2068db7b70eb43d478c9240ac</th><th>Win</th><th>GUI</th><th>Blender, AI toolkit, tensorflow</th><th>Matlab-/Blender-/Python-based visualization</th></tr><br>
<tr><br>
<th>Yu Lie’s tools</th><th><a href="https://github.com/a356617605/Convolutional-neural-network-assisted-recognition-of-nanoscale-L12-ordered-structures-in-face-centre " target="_top">https://github.com/a356617605/Convolutional-neural-network-assisted-recognition-of-nanoscale-L12-ordered-structures-in-face-centre </a></th><th>Open source</th><th>2</th><th>CNN-based crystal structure analysis for APT data specific for L1_2/fcc</th><th>Analysis</th><th>x</th><th></th><th></th><th></th><th></th><th>544ff004fd6a581d5972333f7a7efc501cb0b866</th><th>Win</th><th>Scripting</th><th>Tensorflow and maybe further, needs src inspection</th><th>2D and 3D graphs via Python/Jupyter</th></tr><br>
<tr><br>
<th>DeepHeisenberg</th><th><a href="https://github.com/DeepHeisenberg/Atom-Probe-Tomgrophy " target="_top">https://github.com/DeepHeisenberg/Atom-Probe-Tomgrophy </a></th><th>Open source</th><th>2</th><th>AI crystal structure analysis in detector space based on pole pattern</th><th>Analysis</th><th>x</th><th></th><th></th><th></th><th></th><th>7efba039e46ddb8812303903b6eb51af5d064da0</th><th>Win</th><th>Scripting</th><th>unclear AI toolkit, needs src inspection to be sure</th><th>2D graphs via Python/Jupyter</th></tr><br>
<tr><br>
<th>Iman Ghamarian/Emmanuelle Marquis tool object segmentation</th><th><a href="https://zenodo.org/record/3724970#.YVGTh3uxXjB " target="_top">https://zenodo.org/record/3724970#.YVGTh3uxXjB </a></th><th>Open source</th><th>2</th><th>segmentation of dense morphological objects like precipitates or dislocations in point clouds</th><th>Analysis</th><th></th><th>x</th><th></th><th></th><th></th><th>v1</th><th>Mac?, Win?</th><th>GUI, scripting</th><th>needs src inspection to clarify</th><th>2D graphs and 3D graphs via Python/Jupyter</th></tr><br>
<tr><br>
<th>Iman Ghamarian/Emmanuelle Marquis tool hierarchical clustering</th><th><a href="https://zenodo.org/record/3572572#.YVGTxXuxXjB " target="_top">https://zenodo.org/record/3572572#.YVGTxXuxXjB </a></th><th>Open source</th><th>2</th><th>hierarchical clustering algorithm</th><th>Analysis</th><th>x</th><th>x</th><th></th><th></th><th></th><th>v1</th><th>Mac, Win</th><th>GUI, scripting</th><th>needs src inspection to clarify</th><th>2D graphs and 3D graphs via Python/Jupyter</th></tr><br>
<tr><br>
<th>Ye Wei’s AI ranging tool</th><th><a href="?" target="_top">?</a></th><th>Open source</th><th>2</th><th>auomated ranging via boosting AI techniques</th><th>Analysis</th><th>x</th><th></th><th></th><th></th><th></th><th>n/a</th><th>?</th><th>?</th><th>no longer maintained</th><th>n/a</th></tr><br>
<tr><br>
<th>APTO</th><th><a href="http://apto.sourceforge.net/" target="_top">http://apto.sourceforge.net/</a></th><th>Open source</th><th>3</th><th>Atom probe visualisation for .POS files</th><th>Visualization</th><th></th><th></th><th></th><th>x</th><th></th><th></th><th></th><th></th><th></th><th></th></tr><br>
<tr><br>
<th>Atomblend</th><th><a href="https://github.com/annacegu/atomblend" target="_top">https://github.com/annacegu/atomblend</a></th><th>Open Source</th><th>3</th><th>Blender plugin to import APT data (pos, rng)</th><th>Visualization</th><th>x</th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th></tr><br>
<tr><br>
<th>POSAP</th><th><a href="n/a (was Oxford Nanoscience, now is AMETEK/Cameca)" target="_top">n/a (was Oxford Nanoscience, now is AMETEK/Cameca)</a></th><th>Proprietary</th><th>3</th><th>Reconstruction and visualisation for APT</th><th>Visualization, Analysis</th><th></th><th></th><th></th><th></th><th>?</th><th></th><th></th><th></th><th></th><th></th></tr><br>
<tr><br>
<th>VSA</th><th><a href="?" target="_top">?</a></th><th>Proprietary</th><th>3</th><th>Data analysis for APT data</th><th>Analysis</th><th></th><th></th><th></th><th></th><th>Java</th><th></th><th></th><th></th><th></th><th></th></tr><br>
<tr><br>
<th>GPM3D</th><th><a href="?" target="_top">?</a></th><th>Proprietary</th><th>3</th><th>Data analysis software for TAP/LAWATAP systems (Rouen)</th><th>Analysis</th><th></th><th></th><th></th><th></th><th>?</th><th></th><th></th><th></th><th></th><th></th></tr><br>
<tr><br>
<th>TAPSIM</th><th><a href="http://www.uni-stuttgart.de/imw/mp/forschung/atom_probe_RD_center/software.en.html" target="_top">http://www.uni-stuttgart.de/imw/mp/forschung/atom_probe_RD_center/software.en.html</a></th><th>Open source</th><th>3</th><th>Field evaporation simulation tool</th><th>Simulation</th><th></th><th></th><th></th><th>x</th><th></th><th></th><th></th><th></th><th></th><th></th></tr><br>
<tr><br>
<th>APEX</th><th><a href="https://tomographic.wordpress.com/about/" target="_top">https://tomographic.wordpress.com/about/</a></th><th>Mixed</th><th>3</th><th>Visualisation and analysis for reconstructed data</th><th>Visualization, Analysis</th><th></th><th></th><th></th><th></th><th>?</th><th></th><th></th><th></th><th></th><th></th></tr><br>
<tr><br>
<th>Posgen</th><th><a href="http://apttools.sourceforge.net/" target="_top">http://apttools.sourceforge.net/</a></th><th>Open source</th><th>3</th><th>XML script based generation and analysis of POS files</th><th>Analysis</th><th></th><th></th><th></th><th>x</th><th></th><th></th><th></th><th></th><th></th><th></th></tr><br>
<tr><br>
<th>RAPT</th><th><a href="https://github.com/aproudian2/rapt" target="_top">https://github.com/aproudian2/rapt</a></th><th>Open source</th><th>3</th><th>Atom Probe Tomography Analysis for R</th><th>Analysis</th><th></th><th></th><th>x</th><th></th><th></th><th></th><th></th><th></th><th></th><th></th></tr><br>
<tr><br>
<th>Blender plugin for visualizing APM data</th><th><a href="https://github.com/echus/atomblend " target="_top">https://github.com/echus/atomblend </a></th><th>Open source</th><th>3</th><th>Blender plugin for visualizing APM data</th><th>Visualization</th><th>x</th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th></tr><br>
<tr><br>
<th>Arpan Mukherjee’s tools</th><th><a href="https://github.com/arpanisi/Atom_Probe " target="_top">https://github.com/arpanisi/Atom_Probe </a></th><th>Open source</th><th>3</th><th>Microstructure feature detection</th><th>Analysis</th><th>x</th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th></tr><br>
<tr><br>
<th>pyAPT</th><th><a href="https://github.com/atomprobempie/pyAPT " target="_top">https://github.com/atomprobempie/pyAPT </a></th><th>Open source</th><th>3</th><th>Background correction proof-of-concept</th><th>Analysis</th><th>x</th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th></tr><br>
</table><br>
