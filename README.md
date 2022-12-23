# README for Genomic Epidemiology of SARS-CoV-2 in Minnesota

BEAST XML Files for Minnesota SARS-CoV-2 phylodynamics

1. Run MN-thorney.xml - Uses BEAST v1.10.5 (ThorneyTreeLikelihood v0.1.1), https://github.com/beast-dev/beast-mcmc/releases/tag/v1.10.5pre_thorney_v0.1.1
2. Use LogCombiner (https://beast.community/logcombiner) to resample "thorney.trees" (an output of #1) at a lower frequenct of every 1M steps. This should produce 1,000 trees from the posterior sample. Name the new file  "global1k.trees" and place it in your working directory.
3. DTA.xml - Performs discrete state location analysis using 1,000 trees from #2 (global1k.trees).
