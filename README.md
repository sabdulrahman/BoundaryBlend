# BoundaryBlend

BoundaryBlend is a research prototype for exploring **boundary blending in multiple-view visualizations**. It investigates ways to reduce the separation between visualization views and make it easier to explore relationships across multiple views.

The system provides coordinated views for exploring entities and relationships in document-based datasets, including people, locations, and organizations.

## Features

- Multiple coordinated visualization views
- Person, location, and organization exploration
- Cross-view relationship visualization
- Interactive linking and highlighting between views
- Draggable and rearrangeable visualization views
- Interactive grouping and boundary-based exploration
- Relationship and cluster exploration
- FCA-based cluster and related-entity exploration
- Support for multiple datasets and relationship configurations

The interface includes Person, Location, Organization, Matrix, and Relationship views. It also supports different datasets and relationship configurations.

## Technologies

BoundaryBlend is primarily implemented using:

- JavaScript
- Node.js
- Express
- EJS
- D3.js
- HTML/CSS

The visualization interface also uses supporting libraries for interaction, pan/zoom, timelines, maps, and other visualization components.

## Installation

Clone the repository:

```bash
git clone https://github.com/sabdulrahman/BoundaryBlend.git
cd BoundaryBlend
```

Install the required dependencies:

```bash
npm install
```

## Running BoundaryBlend

Start the application with:

```bash
node index.js
```

Then open:

```text
http://localhost:3000
```

in your browser.


## Status

BoundaryBlend is a research prototype developed for visualization research and experimentation. It is not intended to be a production-ready application.