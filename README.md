# GSoC 2025 - KML Tasks (Challenge 3 & 4)

This repository contains the code and resources for the tasks completed as part of the GSoC 2025 challenge for KML generation.

## Task 5 - Challenges 3 and 4 Overview

### Challenge 3: India KML Generation (Random Points and Styles)
In this task, I generated a KML file that includes random points with various styles. Here's a summary of what was done:

- **Python Code**: A Python script was used to generate random points and assign random styles. There are 5 different sizes used for the points.
- **Placemark Generation**: I placed these points as placemarks in the KML file.
- **Style**: Randomized styles, including varying sizes and a yellow color for the points, were applied.
- **Black Overlay**: I added a black overlay on the entire Earth for better contrast and visibility of the points.
- **GeoJSON Source**: India's geoJSON data was used as the geographical reference for generating these points within India's boundaries.
- **Polygon**: The country’s boundary was visualized using India’s polygon outline.
<img width="741" alt="{D2D3DEB4-F3DB-441A-8879-EB42ED485B0E}" src="https://github.com/user-attachments/assets/d5184ae9-3c90-4a1a-9760-0bcbcef1c539" />


### Challenge 4: KML Using Blender
For this task, I created a 3D model of a house using Blender and exported it as a KML file for use in Google Earth. Here's a breakdown of the approach:

- **Blender Model**: I modeled a house in Blender by watching tutorials on YouTube to guide my design.
- **Location**: The KML was created for a location in Nagpur, India.
- **Export**: The Blender model was exported as a `.dae` file.
- **KMZ Packaging**: The `.dae` and `.kml` files were zipped together and renamed as `.kmz` for compatibility with Google Earth.
  
#### Files:
- `sample.kml` - Generated KML with random points and styles.
- `model.dae` - Collada file for the 3D model (if required for visualization).
- `model.kmz` - Final packaged KMZ file that includes the model and KML. **Use `model.kmz` as your final submission.**
<img width="498" alt="{CA82DD75-0C03-4DA1-8F72-B3674BC6E56F}" src="https://github.com/user-attachments/assets/b23aecfd-095d-46b2-9f36-d59e73908d2e" />

<img width="741" alt="{F4EC99E4-A43F-4EF0-B1B9-D31FB168B051}" src="https://github.com/user-attachments/assets/da80b383-c470-411e-b8b1-5129c822e8d5" />

