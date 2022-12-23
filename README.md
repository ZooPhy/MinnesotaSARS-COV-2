# README for Genomic Epidemiology of SARS-CoV-2 in Minnesota

BEAST XML Files for Minnesota SARS-CoV-2 phylodynamics

1. MN-thorney.xml - Uses BEAST v1.10.5 (ThorneyTreeLikelihood v0.1.1), https://github.com/beast-dev/beast-mcmc/releases/tag/v1.10.5pre_thorney_v0.1.1
2. global1k.trees - 1,000 trees from posterior distribution of #1 and used as emmpirical trees in #3.
3. DTA.xml - Performs discrete state location analysis using 1,000 trees from #2.
