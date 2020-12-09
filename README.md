# 2020-ct-tacaro-final
How does spatial patterning of termite mounds in the African savanna affect local Nitrogen cycling?
How does ungulate grazing factor into this?
Let's find out!

## Learning Goals
- Use numpy arrays to represent geospatial data
- Manipulate geospatial data and interpret using stable isotope notation and operations
- Visualize landscape qualities using 3D modeling, both for data and topographic representation

## Status
- Landscapes were generated based on the agent-based model of herbivore grazing sourced from the `TeamTermite` submodule.
- Landscapes were converted into binary isoscapes by assigning enriched d15N values to termite mound areas.
- Percentage of nitrogen sourced from fixation was determined using the d15N Natural Abundance Method
- A scenario in which model agents over-grazed the landscape was tested to see whether an isotopic signature of grazing could be observed.
- Need more highly resolved isotopic data in order to create a mixing model - this would provide a more accurate isoscape that is not based on binary values.
- Rayshader was used to visualize topographic data as well as generated isoscape data.

## Contents
- 2020-ct-tacaro-final.Rproj: R project file
- termiteN.Rmd: Walkthrough of Nitrogen isoscape calculations
- termiteN.html: Knitted version of termiteN.Rmd
- advanced_landcape_visual.Rmd: Advanced topographic plotting using Rayshader
- advanced_landscape_visual.html: Advanced topographic plotting using Rayshader (knitted)
- interactive plotting.Rmd: Plotly plotting (CT Lecture)
- interactive-plotting.html: Plotly plotting (CT lecture) (knitted)
- python_3d_plotting_tutorial.Rmd: 3d surface and wire plotting in python
- python_3d_plotting_tutorial.html: 3d surface and wire plotting in python (knitted)
- README.md: This file!
- /TeamTermite: A submodule linked to the MATLAB model that is referenced in this work
- .gitmodules: submodule commits
