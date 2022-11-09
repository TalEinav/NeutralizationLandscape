# Neutralization Landscapes
**Harnessing Low Dimensionality to Visualize the Antibody-Virus Landscape for Influenza**<br/>
*Authors*: Tal Einav, Adrian Creanga, Sarah F. Andrews, Adrian B. McDermott, Masaru Kanekiyo

In this work, we use multidimensional scaling to visualize the interactions between influenza viruses and antibodies targeting the hemagglutinin stem. The repository is structured as follows:
* *Data*: The raw measurements and results from our analysis
  * **(1) Neutralization Landscape Coordinates for the HA Stem.csv** contains the (x,y) coordinates of the 51 influenza viruses and 27 antibodies studied in this work. Smaller distances between an antibody and virus represent a more potent interaction.
  * **(2) Neutralization Data for Monoclonal Antibodies and Mixtures.csv** contains the raw neutralization measurements given as 50 inhibitory concentrations (IC50s) in Molar units. Smaller values indicate that the antibody potently neutralizes a virus. Weak antibody-virus interactions outside the dynamic range of our assay are given as lower bounds (IC<sub>50</sub>>1.65·10<sup>-7</sup> Molar). Values can be converted into μg/mL using (1 μg/mL = 6.6·10<sup>-9</sup> Molar).
  * **(3) Decomposition Results.csv** Results from our decomposition analysis of individual antibodies and mixtures of 2-3 antibodies.
  * **(4) Virus HA Sequence Alignment.txt** Aligned  sequences from the 51 viruses studied in this work.
* *Code*: A Mathematica notebook that contains the full analysis and reproduces all plots from this work.
  * All methods and results in the notebook are extensively annotated, and all code should run within less than a minute.
  * Analysis was performed using Mathematica version 13.0 for Windows, but should run on any platform and with any later version. There is no need for any installation beyond the standard Mathematica programming language.