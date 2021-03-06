# Flight computer or "autopilot"


An **autopilot is the software that provides assistance while controlling a drone**. While many autopilots allow the drone to fly/move autonomously following some pre-specified geographical points (e.g. using GPS), the autonomous movement is a characeristic of the autopilot but not the autopilot itself.


According to the [Wikipedia](http://en.wikipedia.org/wiki/Autopilot):

>An autopilot is a system used to control the trajectory of a vehicle without constant 'hands-on' control by a human operator being required. Autopilots do not replace a human operator, but assist them in controlling the vehicle, allowing them to focus on broader aspects of operation, such as monitoring the trajectory, weather and systems.[1] Autopilots are used in aircraft, boats (known as self-steering gear), spacecraft, missiles, and others. Autopilots have evolved significantly over time, from early autopilots that merely held an attitude to modern autopilots capable of performing automated landings under the supervision of a pilot.

To understand this better, let's analyze different ways of controlling a **quadcopter**, a rotary flying drone:

![quad-control](http://erlerobotics.gitbooks.io/erlerobot/content/en/img/software/quad-control.png)

Depending on the controlled variable the perception of the control of a quadrotor by a pilot is perceived diﬀerently. According to the image, the easiest case for the pilot is controlling the **desired ($$_d$) positions** through $$x_d$$, $$y_d$$ and $$z_d$$ (there's still one more level which corresponds to complete autonomous flight where the pilot can set desired begin and endpoint).

----

**The task of an autopilot is to abstract the user from the different physical parameters (such as velocity, angular rates or moments) and offer a simple interface so that the piloting is as easy as possible.**

----

### Erle-brain flight computer

![](https://erlerobotics.com/blog/wp-content/uploads/2014/12/IMG_6335.jpg)

Inspired by the BeagleBone development board, we have designed a small flight computer with about 36+ sensors, plenty of I/O and processing power for real-time analysis. [Erle-brain](http://erlerobotics.com/blog/erle-brain) is the enabling technology for the next generation of aerial and terrestrial robots.