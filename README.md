# Solar Cold Store

An interactive 3D model of a modular, solar-powered cold store. Switch between the full cold-room concept and a small thermoelectric prototype model.

[Open the live model](https://tanish1112.github.io/prototypev21/)

## What you can explore

- Compare four regional presets for Northeast India. Presets change design parameters such as PV tilt, insulation and plinth height.
- Adjust the module layout and see the specification panel update with dimensions, PV capacity and estimated crate capacity.
- Toggle components, labels, dimensions and the section cut. Use the exploded-view slider to inspect how parts fit together.
- Orbit and zoom the model, or choose an isometric, front, top or end view.

The specification panel shows design assumptions encoded in the model. It does not calculate thermal performance.

## Technologies

HTML, CSS, JavaScript and Three.js r128. The browser needs WebGL and an internet connection to load Three.js from cdnjs.

## Run locally

Clone the repository and open `index.html` in a modern browser. To serve it over HTTP, run:

```sh
git clone https://github.com/tanish1112/prototypev21.git
cd prototypev21
python3 -m http.server 8000
```

Open [localhost:8000](http://localhost:8000). Python is only needed for the optional local server.
