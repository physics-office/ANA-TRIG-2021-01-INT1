
# NeuralRinger: An Ensemble of Neural Networks Fed from Calorimeter Ring Sums for Triggering on Electrons

The ATLAS experiment implemented an ensemble of neural networks (NeuralRinger algorithm) dedicated to early removal of fake electrons in its first, fast, online software (HLT) selection stage. In the second half of 2017, the NeuralRinger was set to operate for the selection of electrons above 15 GeV, as part of the efforts in a CPU reduction campaign dedicated to comply with more stringent data taking conditions. Inspired in the ensemble of likelihood models currently operating in the offline and final HLT selections, the ensemble comprises Multi-Layer Perceptron (MLP) models tuned for pseudo-rapidity and transverse energy bins, in order to minimize detector response and shower development fluctuations. The MLPs are fed from calorimetry information formatted into concentric ring energy sums, which are built around the particle axis and normalized by its total transverse energy. This note describes the algorithm, its operation efficiency and the analyses performed. It results in a 60 % decrease in CPU demands for the lowest-threshold unprescaled single-electron trigger while maintaining electron efficiency nearly unchanged. Estimated results show an overall CPU saving of 8 %, when considering the demands of all electron and photon triggers. In contrast to typical trigger algorithms, the NeuralRinger development was started from the online perspective. To ensure that this strategy did not affect the trigger behavior, statistical tests were performed on crucial offline discriminant variables typically employed for physics analysis. It is shown that NeuralRinger trigger had negligible impact in the profiles of the variables employed in the offline selection.

**NOTE**: Support note for ATLAS TrigEgamma Run 2 paper

## Link:

https://cds.cern.ch/record/2652142/

https://atlas-glance.cern.ch/atlas/analysis/analyses/details.php?id=6220

https://cds.cern.ch/record/2809666?ln=pt

## Compile:
```
make
```

## Clean:

```
make cleanall
```


# Links:

* How to update version: https://twiki.cern.ch/twiki/bin/view/AtlasProtected/PaperChecklist_POGitLab#Template_up_to_date
* ATLAS latex repository: https://gitlab.cern.ch/atlas-physics-office/atlaslatex

# Sync

Use the `sync.sh` script to sincronize with https://gitlab.cern.ch/atlas-physics-office/TRIG/ANA-TRIG-2021-01/ANA-TRIG-2021-01-INT1 
