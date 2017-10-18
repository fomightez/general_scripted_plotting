# general_scripted_plotting

Scripts that plot generalized data.

**NOTE:** This repository is just for scripts that have a very broad ability to make plots from generalized data. I have made many other scripts that plot data that aren't here because they are more nuanced. A few of them are referenced below under the section `Plotting scripts for specific purposes`.

## Scripts in this repository

Descriptions of the residing scripts are below:

## plot_stacked_bar_plots_with_fit.py
> plots a ratio of expression values across chromosomes or scaffolds of a genome to highlight regions of deviation characteristic of aneuploidy or segmental duplication/deletion.

A Python script to plot ratio of expression of experimental condition
This script is my 'hacky' casting of the histogram-generating (actually kernel density estimate curve plot-generating) code of [joypy](https://github.com/sbebo/joypy) as a less automated, fully-customizable plotter of stacked bar graphs with curves fit to the data. Originally written to be as part of a mini-pipeline, [`shepherds_read_starts_at_start_of_origins_thru_to_plotting.py`](https://github.com/fomightez/mini-pipelines), where I plot read starts at the start of origin promoters mined by [`plot_coverage_and_starts.py`]() 




## Plotting scripts for specific purposes

I have made many other scripts that plot data that aren't in this repository becauase they are for specific purposes or deal with specific forms of data. 

Below are links to a few of these:

- 

### Licensing

These scripts are licensed under MIT.
