# Jean-Jacques' Skyhawk School — Flight Simulator

Browser-based Cessna 182Q Skylane (N4975F, 230 hp) flight simulator at KMYF Montgomery-Gibbs, San Diego. v1.49.0.

## Run it

Open `index.html` in a browser, or serve it (e.g. `python3 -m http.server`) and open http://localhost:8000/

No build step, no install. Single self-contained HTML file.

## What is in it

- Real Esri satellite imagery draped over San Diego terrain (coastline, Mission Bay, Mt. Soledad, Cowles Mountain, Miramar, Gillespie, Lindbergh / downtown), with painted-terrain fallback offline; runways georeferenced to real airports
- Full instrument panel: airspeed, Garmin G5 attitude indicator, altimeter, DG, VSI, turn coordinator, GNS 430W, COM 119.20 / NAV 117.80, engine gauges, moving map with GPS Direct-To
- Throttle / mixture / carb heat / flaps (UP–40°), trim, forgiving stall, ground effect, wind, carb ice
- Lessons, checklists, V-speeds, engine and avionics tabs, Jean-Jacques' log
- Graded checkrides: 7-maneuver mock checkride and ACS Area IV takeoff & landing ride
- Moving cars on freeways, boats and ships with wakes in Mission Bay, San Diego Bay and along the coast
- Keyboard / mouse / on-screen yoke controls, sound, pause

Built with Muse.
