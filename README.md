The MRT is Singapore's urban rail system. Task is built using React to help users plan MRT journeys, which may include walking and changing trains at various stops. The app has the following minimal functionality:

Users enter their origin and destination autocomplete
The app displays a list of routes, with the best one first
The user selects a route to view the detailed steps in that route
Each route is an object which must contain a "steps" array. Each step can represent a "walk", "ride" or "change", and must have at least the following properties:

{ type: "walk", from: stationId or "origin", to: stationId or "destination" }
{ type: "ride", line: lineId, from: stationId, to: stationId }
{ type: "change", station: stationId, from: lineId, to: lineId }
To run the project, run npm install and then npm start . To run automated tests, run npm test .

**Start by searching for places like

From: 1 Jln Anak Bukit, Singapore 588 996

To: 401 Commonwealth Dr, Singapore 1495

From: Dhoby Ghaut

To: Pioneer **

