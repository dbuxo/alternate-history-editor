## Development

### General
- Leaflet 1.6.0 was used

### Planned functionalities
- [x] Timeline editor (each time point specified will have corresponding map; by default map of new time point inherits those of preceding time point)
- [x] Map colourer (via working with Leaflet, geoJSON)
- [x] Save and load files

### Possible future additional changes (unlikely though in the near future)
- Projection changing dynamically? so save all settings as a temporary variable, and reset entire map
- Improve speed and responsiveness of leaflet
- Easier colouring
  - Colour surrounding adjacent regions
  - Click and drag colouring of regions passed through
  - Region draw circling colour all within
- Make legend into a subclass
- Refactor menu bar
- Generate colouring based on uploaded images
- Exporting to word format with timeline and images
- Importing not entire timelines but only single timepoint or multiple from a timeline file to next cell (Suggest focus on dis as helps merge timeline files)
- Different map layers (e.g. terrain, population density, etc.)
- Allow somehow to read from say images geojson, e.g. get historic borders
- Allow shuffling timeline order around
- Allow timeline duplication entries
- Change colours from legend
- Allow entry adding that doesn't inherit previous as well for non timeline maps
- More parameter customisation, e.g. (parts could come from the geojson data used) (much of some implementable features should already be in geojson data anyway)
  - Flag
  - Population
  - GDP
- GIF generation of timeline (so like those border youtube videos)
- Onmap label functionality
- Loading previously made timelines
- Show large regional labels on map
- Search for groupingg (i think through searching for legend, and then implementing a highlight feature for moving mouse on the the legend entry perhaps)
- Disable zooming when mouse over legend
- Allow switching between different basemaps (with different divisions)
- More border customisation
- Allow custom colour choices
- Statistics page for evaluations of land size and population to well, make one feel good lol like in civ4
- Cinematics mode for playing like a powerpoint with some transitions
- Automatic gif generation
- Get a better interface theme
- Refactor code to reduce coupling, and finish up those optional todos
  - Ideally focus more on functional programming ideas and focus on pure functions and separate data and gui to avoid coupling
- More map options as opposed to just the world map (for faster speeds and also finer regional distinctions, and also to allow use for say different maps in general)
