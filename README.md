This is a sparse copy of the LatinoAnalysis repository (https://github.com/latinos/LatinoAnalysis) intended for the 2023 LPC CMSDAS.

Setup:

cmsrel CMSSW_10_6_4
cd CMSSW_10_6_4/src/
cmsenv

git clone git@github.com:dittmer/LatinoAnalysisCMSDAS2023.git LatinoAnalysis
source LatinoAnalysis/SetupMultiDraw.sh
scram b -j 10

