# FunctionalAnalysisTool

This is a functional analysis Excel-based tool for creating GraphViz models.

You enter your functional flow model as a database in an Excel worksheet.  For each function, you specify taskID, parent, predecessors, and description:

![Alt text](ToolView.png?raw=true "Excel View")

The Excel VBA code then produces dot markup:

![Alt text](markup.png?raw=true "Markup output  View")

Which renders as:

![Alt text](FFGViz.png?raw=true "GraphViz View")


**Need a GraphViz viewer?**  Checkout https://github.com/stevehenderson/GraphVizViewer for a php GraphVizViewer web application

