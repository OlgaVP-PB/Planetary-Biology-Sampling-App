# ✍️ FieldScribe

**Field Data Collection for Planetary Biology**

A mobile-friendly web application for collecting biological and environmental sample metadata in the field. Designed for biodiversity researchers, genomics projects, and ecological surveys.

🔗 **Live App:** [https://olgavp-pb.github.io/FieldScribe/](https://olgavp-pb.github.io/FieldScribe/)

---

## Features

### 📱 Mobile-First Design
- Works on any smartphone or tablet
- Large touch targets for field conditions
- Responsive interface optimized for outdoor use
- Can be added to home screen as a web app

### 🔬 Dual Sample Types
**Organism/Specimen Collection:**
- NCBI Taxonomy integration (TaxID support)
- Kingdom-based life stages and tissue types
- Scientific and common names
- Sex, life stage, tissue type tracking

**Environmental Sample Collection:**
- Water (freshwater, marine, brackish)
- Soil, sediment, air filters
- Malaise traps, spider webs, plant debris
- Collection method and volume tracking
- Environmental parameters (salinity, dissolved oxygen, turbidity)

### 📍 Location & Environmental Data
- GPS coordinate capture with accuracy tracking
- Altitude and depth measurements
- Habitat/ecosystem classification
- Temperature, pH, and other parameters
- Field notes and observations

### 💾 Smart Data Management
- **Offline-capable** - works without internet connection
- Auto-fill collector name and location for repeated collections
- "Use Last Location" for same-site sampling
- Local storage with browser persistence
- CSV export for analysis and database import

### 🎯 Field-Optimized Features
- Required vs. optional fields for flexibility
- Barcode/sample ID entry
- GPS status indicators
- Toast notifications for user feedback
- Clean, distraction-free interface

---

## Quick Start

### Use Immediately (No Installation)
1. Visit: [https://olgavp-pb.github.io/FieldScribe/](https://olgavp-pb.github.io/FieldScribe/)
2. Works in any modern web browser
3. No signup or login required

### Add to Home Screen (Recommended)
**iPhone/iPad:**
1. Open in Safari
2. Tap Share button (□↑)
3. Select "Add to Home Screen"
4. App icon appears on your home screen

**Android:**
1. Open in Chrome
2. Tap menu (⋮)
3. Select "Add to Home Screen"
4. App icon appears on your home screen

---

## Usage Guide

### Collecting an Organism Sample

1. **Select Sample Category:** Choose "Organism/Specimen"
2. **Sample Information:**
   - Enter Sample ID (or scan barcode)
   - Collector name (auto-fills from last sample)
   - Collection date (defaults to today)
3. **Taxonomy:**
   - Select Kingdom (Animalia, Plantae, Fungi, Protista)
   - Enter Scientific Name
   - Optional: NCBI TaxID, Common Name
   - Select Sex, Life Stage, Tissue Type
4. **Location:**
   - Capture GPS coordinates
   - Or use "Use Last Location" for same-site samples
   - Add altitude, depth, habitat type
5. **Environmental Data:** Temperature, pH, etc.
6. **Notes:** Field observations
7. **Save Sample**

### Collecting an Environmental Sample

1. **Select Sample Category:** Choose "Environmental Sample"
2. **Sample Information:** Same as above
3. **Environmental Details:**
   - Sample Type (water, soil, air, etc.)
   - Collection Method
   - Volume/Mass with units
   - Filtration details, deployment duration
   - Sample depth, salinity, dissolved oxygen
4. **Location & Notes:** Same as organisms
5. **Save Sample**

### Exporting Data

1. Scroll to "Saved Samples" section
2. Click "📊 Export to CSV"
3. Opens spreadsheet with all sample data
4. Compatible with Excel, R, Python, databases

---

## Data Fields

### Core Fields (All Samples)
- Sample ID/Barcode ✱
- Collector Name ✱
- Collection Date ✱
- GPS Coordinates (Lat/Long/Accuracy) ✱
- Sample Category ✱
- Altitude, Water Depth
- Habitat Type
- Temperature, pH
- Field Notes
- Timestamp

✱ = Required field

### Organism-Specific Fields
- Kingdom ✱
- Scientific Name ✱
- NCBI Taxonomy ID
- Common Name
- Sex
- Life Stage (kingdom-dependent)
- Tissue/Sample Type (kingdom-dependent)

### Environmental-Specific Fields
- Environmental Sample Type ✱
- Collection Method
- Sample Volume/Mass
- Sample Unit
- Filtration Details
- Deployment Duration
- Sample/Core Depth
- Salinity (ppt)
- Dissolved Oxygen (mg/L)
- Turbidity

---

## Technical Details

### Technology Stack
- Pure HTML5/CSS3/JavaScript
- No backend required
- No dependencies or frameworks
- Client-side only - data never leaves your device

### Browser Compatibility
- ✅ Chrome/Edge (mobile & desktop)
- ✅ Safari (iOS & macOS)
- ✅ Firefox (mobile & desktop)
- ⚠️ Requires JavaScript and GPS permissions

### Data Storage
- LocalStorage API for offline persistence
- Data stored locally on your device
- Export to CSV for backup and analysis
- No cloud sync (intentional for data privacy)

### Privacy & Security
- No user tracking or analytics
- No data sent to external servers
- No cookies or third-party scripts
- All data remains on your device

---

## Use Cases

- **Biodiversity surveys** - Track specimens across field sites
- **Genomics projects** - Collect sample metadata for sequencing
- **Ecological monitoring** - Environmental sample documentation
- **Conservation work** - Species occurrence records
- **Research expeditions** - Multi-site data collection
- **Museum collections** - Field collection documentation
- **Citizen science** - Standardized data capture

---

## Development & Contribution

### Project Background
Developed for the Planetary Biology Capability at SciLifeLab (Sweden), in collaboration with the European Reference Genome Atlas (ERGA) initiative. Designed to address the common problem of incomplete metadata in field-collected biological samples.

**Project Lead & Design:** Olga Vinnere Pettersson (SciLifeLab, Uppsala University)  
**Development Support:** Built with assistance from Claude AI (Anthropic)

This project demonstrates the potential of human-AI collaboration in scientific tool development, combining domain expertise in biodiversity genomics with AI-assisted software engineering.

### Future Features (Planned)
- 📷 Photo capture and attachment
- 🎤 Voice notes for observations
- 📋 Project templates and presets
- 🔍 Search and filter saved samples
- 🗺️ Map view of collection sites
- 📊 Data validation and duplicate detection
- 🔄 Cloud backup and sync options
- 👥 Multi-collector team mode

### Feedback & Bug Reports
Please open an issue on GitHub or contact the development team.

---

## Citation

If you use FieldScribe in your research, please cite:

```
FieldScribe: Field Data Collection for Planetary Biology
Developed by Olga Vinnere Pettersson (SciLifeLab, Uppsala University)
https://github.com/OlgaVP-PB/FieldScribe
```

---

## License

Open source - free to use for research and education.

---

## Contact

**Developer:** Olga Vinnere Pettersson  
**Institution:** SciLifeLab - Planetary Biology Capability, Uppsala University  
**GitHub:** [@OlgaVP-PB](https://github.com/OlgaVP-PB)

---

## Acknowledgments

**Development:**
- Conceived and designed by Olga Vinnere Pettersson (SciLifeLab, Uppsala University)
- Built with development assistance from Claude AI (Anthropic)

**Institutional Support:**
- SciLifeLab Planetary Biology Capability
- European Reference Genome Atlas (ERGA)
- Uppsala Genome Center, National Genomics Infrastructure

---

*FieldScribe - Making field data collection simple, accurate, and standardized.* ✍️🌍
