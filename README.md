Instructions to setup the ExoDiBosonResonances code
========

```
cmsrel CMSSW_7_2_1_patch1
cd CMSSW_7_2_1_patch1/src
cmsenv
git cms-init # This will allow you to checkout packages in official CMSSW.
git clone -b Phys14 git@github.com:cms-edbr/ExoDiBosonResonancesRun2.git ExoDiBosonResonances
scram b -j 9
```

#IMPORTANT: 

These instructions should always be up-to-date with the ones in our Twiki:

`https://twiki.cern.ch/twiki/bin/view/CMS/ExoDiBosonResonancesRun2`
