---
title: "Traffic Flow Oscillation and Shockwave Mitigation"
description: "Detailed explanation and results for traffic shockwave control using RC car experiments"
image: "/images/RC.png"
image: "/images/rc1.png"
image: "/images/rc2.png"
draft: false
---

Stop-and-go traffic, caused by repeated braking and acceleration, produces annoying shockwaves even without any bottlenecks, once vehicle density exceeds a critical threshold. Mitigation strategies include: Infrastructure-based: Ramp meters, variable speed limits, passing lanes. Vehicle-based: Adaptive cruise control, Connected & Automated Vehicles (CAVs). CAVs can raise critical density through smoother speed transitions, reduced space headway, and precise perception of its surrounding, dissipating oscillations and improving flow. To study this, we developed a 1/10-scale RC car platform that captures real-world dynamics with vehicle mechanics, control noise & errors, and communication delays. Cars are driven by AdaptiveSeek, a multi-agent decision-making framework mimicking human driving. Using this platform, we reproduced traffic shockwaves without bottleneck and demonstrated that a single automated vehicle, regulating speed, can smooth traffic waves - improving speed, stability, and overall flow without additional infrastructure.


<p align="center">
  <img src="/images/RC.png" alt="RC Car Experiment" width="60%">
</p>
<p align="center">
  {{< image src="/images/rc1.png" alt="data1" >}}
  {{< image src="/images/rc2.png" alt="data1" >}}
<p>




