# general_scripted_plotting

Scripts that plot generalized data.

**NOTE:** This repository is just for scripts that have a very broad ability to make plots from generalized data. I have made many other scripts that plot data that aren't here because they are more nuanced. A few of them are referenced below under the section `Plotting scripts for specific purposes`.

Descriptions of the scripts are below:

## plot_stacked_bar_plots_with_fit.py
> plots a ratio of expression values across chromosomes or scaffolds of a genome to highlight regions of deviation characteristic of aneuploidy or segmental duplication/deletion.

A Python script to plot stacked bar graphs with curve fits.  It uses lists of lists of x & y data. Each set of x & y is plotted to a subplot.
This script is my 'hacky' casting of the histogram-generating (actually kernel density estimate curve plot-generating) code of [joypy](https://github.com/sbebo/joypy) as a less automated, fully-customizable plotter of stacked bar graphs with curves fit to the data. Originally written to be as part of a mini-pipeline, [`shepherds_read_starts_at_start_of_origins_thru_to_plotting.py`](https://github.com/fomightez/mini-pipelines), where I plot read starts at the start of origin promoters mined by [`plot_coverage_and_starts.py`]()  Thus, it was written in a manner to make the core function easily imported elsewhere so that the "data" hard coded in the example can be replaced by real data.

INSERT EXAMPLE COMMAND AND RESULTING PLOT HERE.


## Plotting scripts for specific purposes

I have made many other scripts that plot data that aren't in this repository becauase they are for specific purposes or deal with specific forms of data. 

Below are links to a few of these to aid in organization:

- [plot_expression_across_chromosomes](https://github.com/fomightez/sequencework/tree/master/plot_expression_across_chromosomes)
- [plot_read_data](https://github.com/fomightez/sequencework/tree/master/plot_read_data)
- [scripts to make Venn diagrams for overlapping words or gene data](https://github.com/fomightez/text_mining)
- [Jupyter notebook that plots optical density vs. yeast cell density in addition to making related calculations](https://github.com/fomightez/methods_in_yeast_genetics/tree/master/cell_density_estimator)
- [preliminary Peter de Jong attractor plotting in a Jupyter notebook](https://github.com/fomightez/de_jong-jupyter)

RELATED:
I have a [VPython-jupyter repo where I added the plotting package `Seaborn`](https://github.com/fomightez/vpython-jupyter).

### Licensing

The scripts in this repository are licensed under MIT.
