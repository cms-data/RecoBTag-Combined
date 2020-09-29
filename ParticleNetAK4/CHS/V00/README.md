# ParticleNetAK4-CHS-V00

This folder contains the ONNX models for the `ParticleNetAK4` tagger designed for AK4 jet tagging (i.e., b-/c-tagging, q/g-tagging, PU jet ID). The model is trained on AK4CHS jets using `RunIISummer19UL18MiniAOD` the following samples:
  - `/TTToSemiLeptonic_mtop171p5_TuneCP5_13TeV-powheg-pythia8/RunIISummer19UL18MiniAOD-106X_upgrade2018_realistic_v11_L1v1-v2/MINIAODSIM` (300 files)
  - `/TTToSemiLeptonic_mtop173p5_TuneCP5_13TeV-powheg-pythia8/RunIISummer19UL18MiniAOD-106X_upgrade2018_realistic_v11_L1v1-v2/MINIAODSIM` (300 files)
  - `/QCD_Pt_XtoY_TuneCP5_13TeV_pythia8/RunIISummer19UL18MiniAOD-PUForMUOVal_106X_upgrade2018_realistic_v11_L1v1-v3/MINIAODSIM` (min_X=30, maxY=1400, 50 files each)
  - `/BulkGravitonToHHTo4Q_MX-600to6000_MH-15to250_part*_TuneCP5_13TeV-madgraph_pythia8/RunIISummer19UL18MiniAOD-multigridpack_106X_upgrade2018_realistic_v11_L1v1-v1/MINIAODSIM` (300 files each)

The output classes of the DNN can be found in the `preprocess.json` file.
