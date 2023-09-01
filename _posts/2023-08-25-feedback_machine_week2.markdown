---
layout: post
title:  "Feedback Machine"
date:   2023-08-25 12:07:02 -0400
categories: Electronic_Ensemble
---

Here is the second iteration of a feedback machine we are creating in the ensemble. The notion is to create feedback loops of control data and audio to create a system that opens many parameters for compositional / improvisational control. Total control of the system should remain just out of reach.

This system currently uses:
Yamaha DX7 <br>
MoogerFooger Delay <br>
Electrocomp EML 200 analog synthesizer <br>
Guitar Rig 6 plugin <br>

Routing Path:
Electrocomp: 
- It has Two VCO Loop among each other.
- The Master Oscillator Square Wave goes to the Input of VCO 1 and the Sine Wave goes to the Input of VCO 2.
- The Output goes to the MoogerFooger Delay Time parameter.

MoogerFooger Delay:
- It has is own LFO but we have to put the amount to 0.

Yamaha DX7: 
- The output goes into the Audio Input of the MoogerFooger Delay.

<iframe width="560" height="315" src="https://www.youtube.com/embed/IgNNpzlohfI?si=ezLTb9ZS2sogrgWM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
