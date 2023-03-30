@kineviz/graphxr-api / [Exports](modules.md)

# graphxr-api

[![npm version](https://badge.fury.io/js/@kineviz%2Fgraphxr-api.svg)](https://badge.fury.io/js/@kineviz%2Fgraphxr-api)

`graphxr-api` is a module which provides an API to GraphXR internals

# Documentation

Documentation is hosted on [GitHub](https://kineviz.github.io/graphxr-api-docs/)

# Table of Contents

* Algorithm
  * Centrality
    * [betweenness](https://kineviz.github.io/graphxr-api-docs/modules.html#betweenness)
    * [closeness](https://kineviz.github.io/graphxr-api-docs/modules.html#closeness)
    * [pageRank](https://kineviz.github.io/graphxr-api-docs/modules.html#pagerank)
  * Community Detection
    * [connectedComponent](https://kineviz.github.io/graphxr-api-docs/modules.html#connectedcomponent)
    * [louvain](https://kineviz.github.io/graphxr-api-docs/modules.html#louvain)
    * [stronglyConnectedComponent](https://kineviz.github.io/graphxr-api-docs/modules.html#stronglyconnectedcomponent)
  * Path Finding
    * [dijkstra](https://kineviz.github.io/graphxr-api-docs/modules.html#dijkstra)
    * [traceNeighbors](https://kineviz.github.io/graphxr-api-docs/modules.html#traceneighbors) // Highlight all paths of a certain depth from the root node
* Camera
  * [flyToCenter](https://kineviz.github.io/graphxr-api-docs/modules.html#flytocenter) // Fly to the center of a group of nodes
  * [flyToPosition](https://kineviz.github.io/graphxr-api-docs/modules.html#flytoposition) // Fly to a specific node
  * [setCameraRotating](https://kineviz.github.io/graphxr-api-docs/modules.html#setcamerarotating)
* Events
  * [observe](https://kineviz.github.io/graphxr-api-docs/modules.html#observe) // Create a reactive Grove variable. Wraps `on()`
  * [on](https://kineviz.github.io/graphxr-api-docs/modules.html#on) // Register a callback function with a GraphXR event
* Filter
  * Handy filter functions e.g. `GraphXR.getLayoutGraph().getNodes().filter(GraphXR.nodesByCategory("Episodes"))`
  * [nodesByCategory](https://kineviz.github.io/graphxr-api-docs/modules.html#nodesbycategory)
  * [edgesByRelationship](https://kineviz.github.io/graphxr-api-docs/modules.html#edgesbyrelationship)
* Graph
  * e.g. `GraphXR.getLayoutGraph()` -> [LayoutGraph](https://kineviz.github.io/graphxr-api-docs/interfaces/layoutgraph.html) // an API to the main graph rendered in GraphXR
    * Some member functions include
    * addEdges, addNodes, removeEdges, removeNodes
    * getEdges // Returns only visible edges
    * getNodes // Returns only visible nodes
    * Visibility
      * hideEdges, hideNodes
      * showEdges, showNodes
    * Nodes and Edges returned from API functions are immutable, so you need to use these setters
      * setEdgeProperties, setNodeProperties
      * node.setStyle, edge.setStyle
      * setNodeCollection
  * Category
    * [getCategoryColor](https://kineviz.github.io/graphxr-api-docs/modules.html#getcategorycolor)
    * [setCategoryCaptionProperties](https://kineviz.github.io/graphxr-api-docs/modules.html#setcategorycaptionproperties)
  * Edge
    * [makeEdge](https://kineviz.github.io/graphxr-api-docs/modules.html#makeedge)
  * Node
    * [makeNode](https://kineviz.github.io/graphxr-api-docs/modules.html#makenode)
    * [makeNodeId](https://kineviz.github.io/graphxr-api-docs/modules.html#makenodeid)
* Layout
  * e.g. `GraphXR.getLayoutGraph().applyLayout(GraphXR.cube())`
  * [alignBy](https://kineviz.github.io/graphxr-api-docs/modules.html#alignby)
  * [circle](https://kineviz.github.io/graphxr-api-docs/modules.html#circle)
  * [cube](https://kineviz.github.io/graphxr-api-docs/modules.html#cube)
  * [distributionBy](https://kineviz.github.io/graphxr-api-docs/modules.html#distributionby)
  * [ego](https://kineviz.github.io/graphxr-api-docs/modules.html#ego)
  * [grid](https://kineviz.github.io/graphxr-api-docs/modules.html#grid)
  * [line](https://kineviz.github.io/graphxr-api-docs/modules.html#line)
  * Parametric
    * [parametric](https://kineviz.github.io/graphxr-api-docs/modules.html#parametric)
    * [setParametricAxesOptions](https://kineviz.github.io/graphxr-api-docs/modules.html#setcamerarotating)
  * [random](https://kineviz.github.io/graphxr-api-docs/modules.html#random)
  * [rotate](https://kineviz.github.io/graphxr-api-docs/modules.html#rotate)
  * [scale](https://kineviz.github.io/graphxr-api-docs/modules.html#scale)
  * [shift](https://kineviz.github.io/graphxr-api-docs/modules.html#shift)
  * [spiral](https://kineviz.github.io/graphxr-api-docs/modules.html#spiral)
  * [triggerForceLayout](https://kineviz.github.io/graphxr-api-docs/modules.html#triggerforcelayout)
* Legend
  * [colorNodesByProperty](https://kineviz.github.io/graphxr-api-docs/modules.html#colornodesbyproperty)
* Neo4j
  * [expandNodes](https://kineviz.github.io/graphxr-api-docs/modules.html#expandnodes)
  * [neo4j](https://kineviz.github.io/graphxr-api-docs/modules.html#neo4j) // Execute a Neo4j Through Server query
* Project Settings
  * [setAutoShowImage](https://kineviz.github.io/graphxr-api-docs/modules.html#setautoshowimage)
  * [setEdgeScale](https://kineviz.github.io/graphxr-api-docs/modules.html#setedgescale)
* Render (THREE.js helpers)
  * [getScene](https://kineviz.github.io/graphxr-api-docs/modules.html#getscene)
* Sort
  * [comparePropertyValues](https://kineviz.github.io/graphxr-api-docs/modules.html#comparepropertyvalues)
  * [sortByProperty](https://kineviz.github.io/graphxr-api-docs/modules.html#sortbyproperty)
* Styles
  * [makeColor](https://kineviz.github.io/graphxr-api-docs/modules.html#makecolor)
  * [makePosition](https://kineviz.github.io/graphxr-api-docs/modules.html#makeposition)
  * [makeRandomPosition](https://kineviz.github.io/graphxr-api-docs/modules.html#makerandomposition)
* Transform
  * e.g. `GraphXR.getLayoutGraph().applyTransform(GraphXR.collectNodes())`
  * [aggregate](https://kineviz.github.io/graphxr-api-docs/modules.html#aggregate)
  * [collectNodes](https://kineviz.github.io/graphxr-api-docs/modules.html#collectnodes)
  * [explodeCollections](https://kineviz.github.io/graphxr-api-docs/modules.html#explodecollections)
  * [uncollectNodes](https://kineviz.github.io/graphxr-api-docs/modules.html#uncollectNodes)
  * [extract](https://kineviz.github.io/graphxr-api-docs/modules.html#extract)
  * [filter](https://kineviz.github.io/graphxr-api-docs/modules.html#filter)
  * [link](https://kineviz.github.io/graphxr-api-docs/modules.html#link)
  * [map](https://kineviz.github.io/graphxr-api-docs/modules.html#map)
  * [merge](https://kineviz.github.io/graphxr-api-docs/modules.html#merge)
  * [shortcut](https://kineviz.github.io/graphxr-api-docs/modules.html#shortcut)
* Utility
  * [sleep](https://kineviz.github.io/graphxr-api-docs/modules.html#sleep) // Returns a Promise which resolves in a number of milliseconds
* Window
  * [setFullscreen](https://kineviz.github.io/graphxr-api-docs/modules.html#setfullscreen)

# Examples

```
// Latest
GraphXR = (await require('graphxr-api')).getApi()

// Target a version
GraphXR = (await require('graphxr-api@0.0.3')).getApi()

// Get nodes
GraphXR.getLayoutGraph().getNodes()

// Apply Layout
const view = GraphXR.getLayoutGraph()
view.applyLayout(GraphXR.line({
  sort: 'price',
  filter: (node: Node) => node.properties.price > 13,
}))
view.applyLayout(GraphXR.rotate({
  dimension: 'x',
  theta: 90,
}))
view.applyLayout(GraphXR.parametric({
  x: 'price',
}))
view.applyLayout(GraphXR.distributionBy({
  dimension: 'y',
  bin: 'seasonNumber',
}))

// Apply Transform
const view = GraphXR.getLayoutGraph()
view.applyTransform(GraphXR.extract({
  category: "Episodes",
  props: [
    {
      name: "seasonNumber",
      newName: "seasonNumber",
      isSplit: false,
      splitChar: "",
      isKey: true,
    }
  ],
  newCategory: "Season Number",
  newRelationship: "inSeason",
  inheritLinks: false,
  skipEmpty: true,
}))
```

# Minimum Version Requirements

If a version of the API depends on a version of GraphXR which has not been released, please increase the minimum required version in `src/minimumRequirements.ts`. For example:

```
export const MINIMUM_GRAPHXR_VERSION = "2.11.0";
```

On `init`, the API will ask GraphXR for its version by fetching `/api/install/version`. If the version is greater than the minimum version, the API will throw an exception.

If GraphXR cannot be detected, `init` will log a warning to the console.

If the minimum requirements are met, `init` will return the API.

# Build

`yarn build`

# Testing

## Integration (`cypress/`)

The integration tests run the API against a local GraphXR instance.

It assumes auth is disabled. Comment out adminEmail in GraphXR's config.js to disable auth.

First create file `.env` in the root folder (web/api/.env) with contents.

```
# Points at a GraphXR instance
CYPRESS_baseUrl=https://localhost:3000
```

Run once: `yarn test` or `yarn test:integration`

## Coverage

Running the tests will result in a text report:

```
-------------------|---------|----------|---------|---------|-------------------
File               | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s
-------------------|---------|----------|---------|---------|-------------------
All files          |     100 |      100 |     100 |     100 |
 addNodes.ts       |     100 |      100 |     100 |     100 |
 clearGraph.ts     |     100 |      100 |     100 |     100 |
 getNodes.ts       |     100 |      100 |     100 |     100 |
 getScene.ts       |     100 |      100 |     100 |     100 |
 index.ts          |     100 |      100 |     100 |     100 |
 makeNode.ts       |     100 |      100 |     100 |     100 |
 removeNodeById.ts |     100 |      100 |     100 |     100 |
 setRuntime.ts     |     100 |      100 |     100 |     100 |
-------------------|---------|----------|---------|---------|-------------------
```

This project tries to have as near 100% code coverage as possible.

A more detailed report is located at `coverage/lcov-report/index.html`.

Note: some code is ignored. e.g. anything using observablehq.

# Documentation

`yarn build:docs` will run tsdoc and generate html at docs/index.html

# Publishing to NPM

This process will do the following

- ensure you are logged into npm
- ensure working directory is clean
- run tests
- build the API bundle
- build the documentation
- bump the package.json version
- commit the bundle, docs, and package.json
- tag the commit with the new version
- push the commits
- push the tag
- publish the package to npm

In a terminal:

1. `yarn login`
2. `yarn release`

Most of the time you will run `yarn release`

## Optional arguments to `yarn release`

- `--no-verify` Skips the tests.
- `--no-publish-docs` Skips building and publishing docs.
- `--beta` Publishes a new version tagged "beta" so that require("graphxr-api@beta") loads that version, and require("graphxr-api") does not.
- `-v, --version <version>` Release type: [v]1.0.34 | patch | minor | major.
- `-m, --tag-message <message>` Tag message. Default is "".
