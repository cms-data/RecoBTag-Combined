# ParticleNetAK4-CHS-V01

This folder contains the ONNX models for the `ParticleNetAK4` taggers designed for AK4 jet tagging. The model is trained on AK4CHS jets using `Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v1` samples privately produced in CMSSW 12_0_X. Below the list of samples adopted:
  - `/ggHHTo4b_kl_1p0_powheg_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v1-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/ggHHTo4c_kl_1p0_powheg_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v1-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/ggHHTo4tt_kl_1p0_powheg_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v1-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/DYToTauTau_M-50_TuneCP5_14TeV-pythia8/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v1-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/TT_powheg_pythia8_14TeV_part1/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v1-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/TT_powheg_pythia8_14TeV_part2/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v1-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/QCD_Pt_30_50_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v2-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/QCD_Pt_30_50_pythia8_14TeV_part2/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v2-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/QCD_Pt_50_80_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v2-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/QCD_Pt_50_80_pythia8_14TeV_part2/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v2-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/QCD_Pt_80_120_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v2-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/QCD_Pt_80_120_pythia8_14TeV_part2/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v2-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/QCD_Pt_120_200_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v2-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/QCD_Pt_120_200_pythia8_14TeV_part2/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v2-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/QCD_Pt_200_350_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v2-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/QCD_Pt_200_350_pythia8_14TeV_part2/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v2-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/QCD_Pt_350_600_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v2-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/QCD_Pt_350_600_pythia8_14TeV_part2/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v2-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/QCD_Pt_600_Inf_pythia8_14TeV/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v2-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/QCD_Pt_600_Inf_pythia8_14TeV_part2/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v2-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/DYToTauTau_M-50_TuneCP5_14TeV-pythia8/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v1-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/DYToTauTau_Pt25to100_M-50_TuneCP5_14TeV-pythia8/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v1-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`
  - `/DYToTauTau_Pt100to500_M-50_TuneCP5_14TeV-pythia8/rgerosa-Run3Winter21DRPremixMiniAOD_phase1_2021_realistic_v1-MINIAODSIM-d6f3ed9457165e59911360db4166f28a/USER`

Two models are present in the folder:
  - `particle-net.onnx` and `preprocess.json` refers to ParticleNet trained to distinguish between the following classes: b-quark, c-quark, uds-quark, and gluon jets.
  - `particle-net-with-tauh.onnx` and `preprocess-with-tauh.json` refers to ParticleNet trained to distinguish between: b-quark, c-quark, uds-quark, gluon, and hadronic tau (tauh) jets.
