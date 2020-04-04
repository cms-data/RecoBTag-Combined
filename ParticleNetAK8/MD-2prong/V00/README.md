# ParticleNetAK8-MD-2prong-V00

This folder contains the MXNet models for the ParticleNet tagger designed for mass-independent 2-prong jet tagging (i.e., X->bb, X->cc, X->qq). The mass decorrelation is achieved by using a dedicated signal sample w/ a flat mass distribution (`/BulkGravitonToHHTo4Q_MX-600to6000_MH-15to250_part*_TuneCP5_13TeV-madgraph_pythia8/RunIIFall17MiniAODv2-PU2017_12Apr2018_multigridpack_94X_mc2017_realistic_v14-v1/MINIAODSIM`). The model is trained on AK8Puppi jets using `RunIIFall17MiniAODv2` samples. 

The output classes of the DNN are:
 - probXbb
 - probXcc
 - probXqq
 - probQCDbb
 - probQCDcc
 - probQCDb
 - probQCDc
 - probQCDothers

