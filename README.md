![Aryan Maheshwari. Madison, Wisconsin.](./assets/dispatch.svg)

I’m Aryan, a computer science and data science student at UW–Madison. I’ve built a 3D ambulance dispatch simulator, a mobile training and nutrition coach, and firmware for a wind-tunnel calibration rig.

[Explore my interactive portfolio](https://arymaheshwari.com/) · [LinkedIn](https://www.linkedin.com/in/arymaheshwari) · [Email](mailto:ary.maheshwari24@gmail.com)

## 01 / emergencyMadison

**Hackathon winner · C3 Isthmus**

**What happens to an ambulance route when John Nolen Drive floods right after a Badgers game?**

Drop an incident on a 3D map of Madison, switch from normal traffic to the post-game flood scenario, and ride along as the simulator recalculates the trip. The routing engine searches both legs of the trip, from the responding station to the incident and from the incident to the fastest reachable emergency department.

<details>
<summary>How the routing works</summary>

OpenStreetMap data supplies the road network. Scenario overlays close or slow individual segments, and Dijkstra searches compute the response and transport legs. An impact analysis compares the scenario with the baseline across 2,436 modeled intersections. MapLibre GL renders the routes and plays back the dispatch.

</details>

[Explore the implementation](https://github.com/arymaheshwari/emergencyMadison/tree/workspace/7be4fcdc-0f45-4258-aa15-a5c62266cd65)

## 02 / Your AI Health Coach & Trainer

**Mobile app · Expo, React Native, Supabase**

Generate a running or gym program, follow it with a workout timer, and log meals by scanning a barcode, photographing a nutrition label, or taking a picture of the meal. Workout history and nutrition goals live in the same app.

[View the source](https://github.com/arymaheshwari/Trainy)

## 03 / Five-hole probe calibration rig

**Embedded systems · ESP32, Arduino, Python**

An Arduino-controlled gimbal sweeps through pitch and yaw angles while an ESP32 streams differential pressure readings. A Python logger coordinates the sweep and writes raw readings and per-angle summaries to CSV for calibration.

[Inspect the firmware and logger](https://github.com/arymaheshwari/pitot_tube_code)
