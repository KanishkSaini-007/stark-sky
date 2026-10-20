# Stark Sky

A living stylized New York City flight portfolio built while learning three.js. Fly an original red-and-gold armored hero with a full helmet, over avenues with moving traffic, past walking pedestrians, visit NYC landmarks and open 12 interactive project towers.

**Play:** https://kanishksaini-007.github.io/stark-sky/

## Explore
Manhattan's geographic island outline, Hudson and East River, Central Park and its reservoir, Times Square billboards, Empire State Building, Chrysler Building, One World Trade Center, Statue of Liberty, Flatiron, Rockefeller Plaza and Washington Square. Four rebuilt stylized bridges with support towers, trusses, cables, lanes and traffic: Brooklyn, Manhattan, Williamsburg and Queensboro.

Daylight, neutral masonry facades, coastal edging, dark-teal textured water and moving boats replace the neon water reflections. Liberty Island has a green-patina statue with robe folds, tablet, torch, crown and a star-fort base. Flatiron is a wedge with windows and cornices. Rounded trees, park paths and small-island landscaping fill out the world.

Real streets now cut the grid: avenues and cross streets with lane markings, cars and taxis driving both directions, pedestrians walking the sidewalks, street lamps, rooftop water towers, AC units and blinking antenna beacons.

Use the **Visit NYC landmark** menu to jump to a place. Project rings open descriptions with live and source links. The Projects menu can take you to any project. Building collision, roof landing, energy cores, sound and touch controls remain.

## Controls
WASD move, Space up, C down, Shift boost, E open a nearby ring, drag to look. Mobile: left stick, drag the right side, up/down/boost buttons. Sound toggle is at the top. Suit ON/OFF cuts power and enables gravity, then turns flight back on. SKY AI (J) embeds the existing Ask Kanishk chatbot using its protected backend. The Quality button switches to a reduced-resolution, lower-population mode. Flight is bounded to a marked 6.4 km-wide game area.

## What's accurate, what's stylized
- Coastline is simplified from geographic borough polygon data. Landmark positions are based on latitude/longitude, rotated into Manhattan's avenue direction.
- Horizontal geography is compressed to 22% of real distance. Landmark heights and shapes are artistically simplified and exaggerated for play. It is not a full-scale city, photogrammetry, or a navigation map.
- The avenue/cross-street pattern is procedural and Manhattan-aligned, not real street-by-street data. Traffic and pedestrians are simple loops, not a simulation; cars keep minimum spacing on fixed lanes and obey timed stops, but have no vehicle physics, turning or city-wide pathfinding. Ordinary buildings, block heights, park paths, bridge details and all 12 project towers are invented. The project towers are not actual NYC landmarks.
- The character is an original basic-shape design with a full armored helmet and glowing eyes. It is not Robert Downey Jr., an actor likeness, an official Marvel model or official artwork.
- Tested in desktop Chrome and a phone-sized touch emulation. Real-phone GPU performance is unverified. No real-time shadows; reduced trees and resolution on mobile.

## Sources
- Simplified borough outlines: https://github.com/dwillis/nyc-maps/blob/master/boroughs.geojson (NYC geographic borough data mirror).
- Geography: https://en.wikipedia.org/wiki/Manhattan
- Park: https://en.wikipedia.org/wiki/Central_Park
- Landmark positions and forms: https://en.wikipedia.org/wiki/Empire_State_Building , https://en.wikipedia.org/wiki/Chrysler_Building , https://en.wikipedia.org/wiki/One_World_Trade_Center , https://en.wikipedia.org/wiki/Statue_of_Liberty , https://en.wikipedia.org/wiki/Times_Square
- Bridges: https://en.wikipedia.org/wiki/Brooklyn_Bridge , https://en.wikipedia.org/wiki/Manhattan_Bridge

Plain HTML/CSS/JavaScript, three.js via CDN, no game engine. Learning project.

## Next phases
Helmet HUD, supersonic effects, reactor power routing, drone combat, sky lanes, trains, power nodes and orbital-drop gameplay are planned, not included in this visual-world release. No claim of GTA V fidelity or simulation.
