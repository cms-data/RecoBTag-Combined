# ParticleNetFromMiniAODAK4

This folder contains the ONNX models for the `ParticleNetFromMiniAODAK4` network, which performs jet flavor tagging (b/c tagging, q/g tagging),
hadronic tau ID (vs. jet, vs. muon, vs. electron), tau reconstruction (charge, DM), jet pT regression,
and jet resolution quantile estimation. The training sample consists of about 80M jets sampled uniformly in pT and eta and taken from a large mix of physics processes
including ggH, DY, QCD, and tt from the Run2UL2018 samples.

Four separate trainings are provided, split by jet eta (forward vs. central) and jet source (PUPPI or CHS). The scope of the forward network is reduced
with respect to the central training, performing q vs. g tagging and jet pT regression. The output classes of the DNN can be found in the `preprocess.json` file.
