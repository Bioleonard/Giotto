
# Giotto 0.3.0

  - Default spatial network created with **createSpatialNetwork** is now
    a Delaunay spatial network.

<!-- end list -->

``` r
# to create the old default kNN spatial network use:
createSpatialKNNnetwork(gobject)

# or use this function with the following setting
createSpatialNetwork(gobject, method = 'kNN')
```

  - Fixed multiple bugs
  - Improved speed by changing code to Rcpp and implementing
    parallelization options
  - updated [howto’s](./docs/getting_started.html) tutorials in Start
    section
  - Finished the analysis of 10 different spatial datasets (tutorials
    are a work-in-progress)

# Giotto 0.2.4

  - New examples on mouse kidney and brain using the recently released
    [10X Visium
    datasets](https://www.10xgenomics.com/spatial-transcriptomics/)
    (**NEW**)
  - Added tools to identify spatial enrichment based on cell-type
    specific gene signature lists (**NEW**)

# Giotto 0.2.3

  - New example with 3D-like spatial data of the mouse hypothalamic
    preoptic region using
    [merFISH](https://science.sciencemag.org/content/362/6416/eaau5324)
    (**NEW**)  
  - New example with 3D spatial data
    [STARmap](https://science.sciencemag.org/content/361/6400/eaat5691)
  - New example with the highly sensitive data from
    [osmFISH](https://www.nature.com/articles/s41592-018-0175-z)
  - New example on the Cerebellum with the scalable data from
    [Slideseq](https://science.sciencemag.org/content/363/6434/1463)
  - New example on mouse olfactory bulb using immobilized primers on
    glass slides from [Spatial
    Transcriptomics](https://science.sciencemag.org/content/353/6294/78)
  - Updated seqFISH+ cortex example (**NEW**)
  - Updated STARmap cortex example (**NEW**)

# Giotto 0.2.2

  - Implemented [SpatialDE](https://github.com/Teichlab/SpatialDE) and
    [trendsceek](https://github.com/edsgard/trendsceek)
  - Updated support for 3D spatial data  
  - Added support for the use of global instructions and automatically
    saving your plots (**NEW**)
  - Add wrapper for differential expression with
    [MAST](https://github.com/RGLab/MAST) and
    [SCRAN](https://bioconductor.org/packages/release/bioc/html/scran.html)
