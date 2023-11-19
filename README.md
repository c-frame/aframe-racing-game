# A-Frame Racing Game

Port of [pmndrs's racing-game](https://github.com/pmndrs/racing-game) (r3f and cannon) rewritten in A-Frame with reusable components.

This port is using ammo.js for the vehicle. The `vehicle-controls` component is a port of the [ammo.js webgl_demo_vehicle three.js example](https://rawcdn.githack.com/kripken/ammo.js/8f8b7187ef74994093318645e5e96b11d982688a/examples/webgl_demo_vehicle/index.html) ([code](https://github.com/kripken/ammo.js/blob/main/examples/webgl_demo_vehicle/index.html))

The assets of the desert and car come from the original pmndrs's racing-game repo and are CC0 licenced.

TODO:

- [ ] don't hard code the wheels values in vehicle-controls so we can support a vehicle like a bus or fire truck
- [ ] tune the car physics (for cannon [Jaagrav's raycast-vehicle-engine](https://github.com/Jaagrav/raycast-vehicle-engine) is great)
- [ ] physics on the track, and not a big plane
- [ ] quid integration with aframe-physics-system?
- [ ] create a wall component
- [ ] create a ramp component
- [ ] create a boost component
- [ ] play sound when you accelerate and brake
- [ ] change camera view: from above, inside the car
- [ ] multi-users with networked-aframe
- [ ] leaderboard
- [ ] make it work in VR with view inside the car like [coconut auto demo](https://twitter.com/coconut_xr/status/1697613919617995254)