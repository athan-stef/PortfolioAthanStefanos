## Ballute Testing
### Brief
During my time at Monash High Powered Rocketry I designed a high alttitude recovery parachute. This is a novel concept called a ballute. For more details see the [report](../ballute.md) I wrote on it. 

<img src="ballute_diagram_airflow.png" alt="Ballute Airflow Diagram" width="500">

The parachute was designed for a 100,000 ft (30 km) rocket. A ballute was selected over a traditional drogue parachute due to the inability to model low density inflation dynamics that could lead to a irrecoverable canopy collapse. The ballute addresses this problem by using an inflatable design that can inherently not enter an unstable collapsed configuration, using the weight of the rocket to allign vents with incoming airflow. 

Now that I have graduated others will carry on the final manufacturing and testing of the ballute. I want to manufacture this parachute at home to test it, purely out of curiosity and passion.

### Goals and Expectations
There are a few things I want to get from manufacturing and testing this parachute.

#### Manufacturability 
Clearly this is a strange parachute, and it will be strange to make. It has been made on the hobby level and [professional level](https://www.youtube.com/watch?v=4WhBfoOEUjY) so it is certainly possible. The student team is currently manufacturing one, the steps are clear and feasible. I wish to try and improve upon this process and find downfalls that can be improved through trial and error.

#### Behaviour
The ballute is a device made for high subsonic and supersonic airflow, so its behaviour in lower speed regimes is of great interest. Companies such as [Copenhagen Sub-orbitals](https://copenhagensuborbitals.com/) have done low speed drop tests and the ballute performed well, inflating and effectively slowing the payloads descent. Doing further drop tests will validate estimates of inflation pressure at certain flight stages as detailed in the [report](../ballute.md).  

<img src="ballute_vel_CFD.png" alt="Ballute Airflow CFD" width="300">

The rigid-body airflow simulation of the ballute, conducted at an airspeed of 129 m/s and an altitude of 27 km, indicates an expected stagnation region along the leading edge of the burble fence, followed by extensive flow separation downstream. This separated flow is the primary mechanism contributing to the ballute’s aerodynamic drag. The resulting pressure distribution may also influence the ballute’s structural deformation, causing the forward surface to flex inward while the aft region bulges outward in response to the lower pressures along the sides.

As seen below, this flow structure can be expected for high and low speed flight, indicating a low speed test will be qualitatively valuable.

