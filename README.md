# US Senate Committees Force Directed Graph
This is a draggable `force directed graph` representing the US Senate committees and their respective members

The graph is built with `D3.JS` and `SVGs`

The data used has been sourced and compiled from [data.world](https://data.world/)

Each node represents a Senator, who is a member of one of the committees selected to be displayed

`Blue` nodes represent `Democrats`, `Red` nodes represent `Republicans`, and `Gray` nodes represent `Independents`

A link connecting `two nodes` represents `two Senators` serving together on at least `one committee`

The `list of checkboxes` on the right of the graph enable someone to select which `Senate committee` to display nodes for

`Hovering` over a node will display a `tooltip` with more detailed information on the respective Senator

This project can also be found here on [CodeSandbox](https://codesandbox.io/s/us-senate-committees-force-directed-graph-pgjls)

Below is a preview of how it looks:

<img src="https://i.ibb.co/68pFRx8/d3-us-senate-committees-force-directed-graph.gif" alt="graph-preview" width="300" height="200" />
