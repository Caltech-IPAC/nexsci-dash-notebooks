# nexsci-dash-notebooks

A Collection of Jupyter Notebooks for Working with NExScI (and Some Other) Datasets.

Several NASA Exoplanet Science Institute (NExScI) projects provide web services for direct data download.  By combining these with data visualization and dashboarding tools from Plotly / Dash, we can create a set of Jupyter Notebooks for visualization and manipulation of our holdings.  

For most of the Notebooks, the associated dashboard is implemented as a separate pop-up window rather than in-line on the Notebook page.  In these cases, a separate PNG screen-dump is provided that illustrated the functionality.

All the tools needed to run these Notebook are Python pip-installable.  These include: the Plotly Dash packages themselves ('dash', 'dash_bootstrap_components' and 'dash_ag_grid'); Montage ('MontagePy') if the page includes astronomical image manipulation/display; and any associated Dash app code (e.g., 'koaviewer').  The Dash apps are usually part of this repo (e.g., 'koaviewer'.  Montage has its own repo (https://github.com/Caltech-IPAC/Montage) and Dash itself is a (free) commercial product.  The Montage repo includes the source for 'mviewer', a React component that is used in image visualization/interaction and is also directly pip-installable ('viewer').

There is a write-up on the architecture at http://montage.ipac.caltech.edu/docs/mViewer_DASH .
