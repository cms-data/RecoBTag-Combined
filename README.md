# Repository for cmssw package RecoBTag/Combined data.

Models for trigger level are inside the HLT directory.


## Summary of models
| Model    | Path | Description | Slides | PR |
| -------- | ------- | -------- | ------- | ------- | 
| HLT ParticleNet AK8 MD V3 | [link](https://github.com/cms-data/RecoBTag-Combined/tree/master/HLT/ParticleNetAK8/V02) | Trained on Run 3 samples / decorrelated wrt. mSD and pT | [TSG](https://indico.cern.ch/event/1590920/#34-btv-status-of-the-ak8-pnet) [BTV](https://indico.cern.ch/event/1578596/#34-btv-status-of-the-ak8-pnet) | [link](https://github.com/cms-data/RecoBTag-Combined/pull/72) | 
| HLT + HLT Scouting GlobalParticleTransformer AK15 MD V0 | [link](https://github.com/cms-data/RecoBTag-Combined/tree/master/HLT/GlobalParticleTransformerAK15/V00/) | Training using HLT scouting AK15 jets, MD, only cPF+nPF features. Classification + mass regression. | [TSG](https://indico.cern.ch/event/1606783/#36-btv-gloparthlt-for-large-ra) | [link](https://github.com/cms-data/RecoBTag-Combined/pull/71) |