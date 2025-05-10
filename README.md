# Solar System Visualization

DEMO: https://ipagbox.github.io/solar-system-visualization/

A simplified, interactive model of our Solar System built with HTML5 Canvas and JavaScript. This demo preserves approximate **relative scales** of:

- **Planet sizes** (radius in km)  
- **Orbital distances** (semi-major axes in AU)  
- **Orbital periods** (days)

It also includes **major moons** for Jupiter, Saturn, Uranus and Neptune, and a toggleable **asteroid belt** between Mars and Jupiter.

---

## Features

1. **Zoom & Pan**  
   • Mouse wheel zooms smoothly in and out, keeping focus on the selected body.  
   • Click a planet or moon name in the **Focus** menu to center it; click again to release.

2. **Speed Controls**  
   Buttons to simulate time at:  
   - 1 day/sec  
   - 1 week/sec  
   - 1 month/sec  
   - 1 year/sec  
   - 1 century/sec

3. **Day/Night Shading**  
   Toggle on/off realistic half-illumination for all planets and moons (not applied to the Sun or asteroids). The terminator moves as bodies orbit.

4. **Asteroid Belt**  
   Switch a ring of 300 simulated asteroids on/off. Their speed varies slightly (0.8–1.2× base) and each remains at least one pixel in size, regardless of zoom level.

5. **Orbital Trails**  
   Visual “tails” show each planet’s and moon’s recent path:  

6. **Satellite Support**  
   Major moons included:  
   - **Jupiter:** Io, Europa, Ganymede, Callisto  
   - **Saturn:** Titan, Rhea, Iapetus, Dione, Tethys, Enceladus  
   - **Uranus:** Titania, Oberon, Umbriel, Ariel, Miranda  
   - **Neptune:** Triton, Proteus, Nereid, Larissa  

---

> **Note:** This “vibe-coding” demo was generated with the help of ChatGPT. Feel free to tweak parameters (trail length, asteroid count, speeds) for different visual effects!  
