# Geospatial Data Viewer

A lightweight, browser-based application for viewing and interacting with common geospatial file formats. This application runs entirely client-side with no server components required.

![Flashcard App Screenshot](https://raw.githubusercontent.com/cpickett101/GeospatialDataViewer/main/GeospatialDataViewer.png)

## Features

- **Multiple Format Support**: View Shapefiles (.shp), KML, KMZ, and GeoJSON files
- **Drag & Drop Interface**: Easy file loading with drag and drop functionality
- **Layer Management**: Toggle visibility, change colors, and remove layers as needed
- **Attribute Viewing**: Click on features to view their attribute data
- **Export Capabilities**: Export visible layers as GeoJSON
- **Fully Client-Side**: All processing happens in your browser - no data is sent to any server
- **Responsive Design**: Works on desktop and mobile devices
  
## Usage

### Supported File Types

- **Shapefiles** (.shp, .dbf, .prj) - Upload all components together
- **Zipped Shapefiles** (.zip) - Contains all shapefile components
- **KML files** (.kml) - Google Earth's XML-based format
- **KMZ files** (.kmz) - Compressed KML files
- **GeoJSON files** (.geojson, .json) - Open standard format for geographic data

### Instructions

1. **Loading Files**:
   - Drag and drop files into the designated area, or
   - Click "Select Files" to use the file browser
   - For shapefiles, make sure to select all related files (.shp, .dbf, .prj)

2. **Managing Layers**:
   - Use the checkbox to toggle layer visibility
   - Click the color picker to change layer style
   - Click the × button to remove a layer

3. **Interacting with the Map**:
   - Click on features to view their attribute data
   - Use mouse wheel to zoom in/out
   - Click and drag to pan the map

4. **Exporting Data**:
   - Click "Export GeoJSON" to download all visible layers as a GeoJSON file

## Setup

This is a single HTML file application with no build process required:

1. **Download**: Get the `GeospatialDataViewer.html` file
2. **Open**: Double-click to open in any modern browser, or host it on any web server

### Self-Hosting Options

- GitHub Pages
- Any static file hosting service
- Local web server

## Dependencies

This application uses the following libraries (loaded via CDN):

- [Leaflet](https://leafletjs.com/) - For map display
- [shp.js](https://github.com/calvinmetcalf/shapefile-js) - For Shapefile parsing
- [JSZip](https://stuk.github.io/jszip/) - For KMZ extraction
- [Leaflet-Omnivore](https://github.com/mapbox/leaflet-omnivore) - For KML parsing

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Edge
- Safari (limited support for some file formats)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the below for details:

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Acknowledgments

- [OpenStreetMap](https://www.openstreetmap.org/) for the base map tiles
- All the amazing open-source libraries that make this project possible

## Developer

[Created by Christopher Pickett - 2025]([https://www.linkedin.com/in/christopher-p-a4908979/])
