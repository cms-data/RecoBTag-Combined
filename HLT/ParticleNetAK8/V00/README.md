# ParticleNetAK8-MD-2prong-HLT

This folder contains the ONNX models for the ParticleNet tagger designed for mass-independent (mass decorrelated) 2-prong jet tagging (i.e., X->bb, X->cc, X->qq). The mass decorrelation is achieved by using dedicated signal sample with a scalar resonance decaying into two prongs with flat mass distribution. The model is trained on AK8 PF jets reconstructed at HLT using privately produced `Run3Winter21DRPremixMiniAOD_phase1_2021_realistic` modified miniAOD (containing both RECO and HLT collections) samples in 12_0_X. Below the list of samples adopted:
  - `/XtoHH_hadronic_TuneCP5_pythia8_part1_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/XtoHH_hadronic_TuneCP5_pythia8_part2_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/XtoHH_hadronic_TuneCP5_pythia8_part3_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/XtoHH_hadronic_TuneCP5_pythia8_part4_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/XtoHH_hadronic_TuneCP5_pythia8_part5_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/ggH_Pt_200to300_Flat_TuneCP5_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/ggH_Pt_300to450_Flat_TuneCP5_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/ggH_Pt_450to600_Flat_TuneCP5_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/ggH_Pt_600to750_Flat_TuneCP5_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/ggH_Pt_750to1000_Flat_TuneCP5_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/QCD_Pt_170to300_Flat_TuneCP5_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/QCD_Pt_300to450_Flat_TuneCP5_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/QCD_Pt_450to600_Flat_TuneCP5_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/QCD_Pt_600to750_Flat_TuneCP5_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/QCD_Pt_750to1000_Flat_TuneCP5_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/QCD_Pt_1000to1500_Flat_TuneCP5_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/QCD_Pt_1500to2000_Flat_TuneCP5_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/QCD_Pt_2000to2500_Flat_TuneCP5_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`
  - `/QCD_Pt_2500toInf_Flat_TuneCP5_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_AK8_v1-MINIAODSIM-7fc01a58a48afe2b34364c8423c1519b/USER`

Two models are present in the folder:
  - `particle-net.onnx` and `preprocess.json` refers to ParticleNet trained to distinguish between the following classes: Xbb, Xcc, Xqq, Xgg, and QCD jets (single and double parton).
  - `particle-net-with-tauh.onnx` and `preprocess-with-tauh.json` refers to ParticleNet trained to distinguish between: Xbb, Xcc, Xqq, Xgg, Xtauhtauh, and QCD jets (single and double parton).
