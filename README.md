# Base Symbology for ArcGIS Dependecy Link Charts in ArcGIS Knowledge

## Overview
### What are Style Files and Symbology Layers?
- A style file stores symbols, colors, color schemes, label placements, and layout items. The style file for this project can be found [here](https://github.com/EsriPS/spire-graph/tree/main/pro) with an `.stylx` file extension.
- A symbology layer contains the symbology that will be applied to the chosen link chart layer. The symbology layer can be found [here](https://github.com/EsriPS/spire-graph/tree/main/pro) with an `.lyrx` file extensions.
  
### Applying Base Symbology to Link Chart in ArcGIS Pro
- Import Enterprise.stylx into ArcGIS Pro
  - The .stylx file is used to store the base symbols created initially for others to use and apply to their own knowledge graphs.
- Open the `Apply Symbology From Layer` Geoprocessing Tool 
- Run the `Apply Symbology From Layer` Geoprocessing Tool using Item.lyrx to Apply the ArcGIS Dependency Base Symbology** (See Image Below)
  - The .lyrx file is used to display the stored based ArcGIS dependency symbols to your link chart.

### Item Types in Symbology Layer 
- **Service**
  - Feature Service
  - Feature Collection
  - Map Service
  - Service Definition
  - Web Map Tile Service (WMTS)
  - Web Map Service (WMS)
  - Web Feature Service (WFS)
  - Scene Service
  - Vector Tile Service
  - Image Service
  - Stream Service
  - Geocoding Service
  - Network Analysis Service
  - Geoprocessing Service
- **Application**
  - Web Mapping Application
  - Dashboard
  - StoryMap
  - Web Experience
  - Hub Site Application
  - Hub Initiative
  - Solution
  - Application
  - Desktop Application
  - Native Application
  - Mobile Application
- **Web Map**
- **Documents**
- **Forms**
- **Packages**
- **Pages**
- **Templates**
- **Databases**
- **Scenes**
- **Layers**
- **Projects**
- **Models**
