n---
layout: post
title: Types of EVs and how EVs work
date: 2022-01-03 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: AdobeStock_265185984.jpeg # Add image post (optional)
tags: [EVs, BEVs, PHEVs, HEVs, Fuel Cells, Automotive Engineering] # add tag
---

# ELECTRIC VEHICLES                                                                
There is a paradigm shift in the automotive industry, which is pushing the Automotive industry to change as has never been seen before. Electric Vehicles and Autonomous driving are some of the biggest technologies disrupting the automotive field. Traditional OEMs are faced with a major challenge of shifting to Electric Vehicles to fight off the Electric Vehicles pure-plays while also fighting with technology giants like Apple and Google who are also interested in the autonomous vehicles. In this blog, I will be covering the automotive design and manufacturing.

A brief background about me, I have been in the automotive field for the last 7 years working for a Tier 1 Supplier as well as EV OEM companies for the last 5 years. I have been worked mainly in the Crash analysis and Stamping side of automotive which involves working with CAD from the designers to the buyoff of the tools to be run for production.Manufacturing a vehicle involves various teams: manufacturing, design, stamping, body engineering, general assembly, studio, sales and marketing to name a few. 

What to go through in my blog:
<ul>
<li>	Modern Automotive trends - ICE, BEVs, PHEVs, Hybrids.</li>
<li>	Stages in the Automotive development process – TT, VP, PP, SOP.</li>
<li>	Body Structure - Unibody, Body-On-Frame (BOF).</li>
<li>	Stamping.</li>
<li>	Joining process - Adhesives, welding, brazing etcetera.</li>
<li>	Materials – metals, plastics.</li>
<li>	Crash analysis.</li>
<li>	Geometric Deimensioning and Tolerancing (GD&T).</li>
<li>	Automotive disruptors e.g. Autonomous driving, Car As A Service, Vehicle to Vehicle etcetera.</li>
 </ul>
Types of Automotive:
<ul>
<li> Internal Combustion Engines (ICE) – Powered by an engine.</li>
<li>	Battery Electric Vehicles – Powered by an electric motor.</li>
</ul>

![Technology Life Cycle]({{site.baseurl}}/assets/img/Technology Life Cycle.png)




Electric vehicles are growing in numbers as the technology is reaching technological maturity. Currently, the EVs have matured to become a viable option to the ICE. This is due to drastic improvement in the battery technologies as well as reduction in battery prices. Electric vehicles are environmentally friendly as they do not produce carbon emissions and are also quiet. Electric vehicles are powered by a motor, instead of an engine which powers the Internal Combustion Engines (ICE). 
Whereas ICE vehicles, function by converting the thermal energy to mechanical energy through pistons in the engine, the EVs are powered by electric motors which gets energy from a controller based on the driver’s use of the accelerator. The EVs have rechargeable batteries.

Before going much deeper into the Electric Vehicles, it is important to understand Direct Current (DC) and Alternating Current (AC). Direct Current is current that moves only in one direction, as the electrons flow from the negative charge (-) to the positive charge (+). Any electronic device that utilizes the battery as a power source, uses DC. Rechargable batteries, such as automotive traction batteries, have adapters to convert DC to AC. 

An inverter is used to convert the DC to AC, which is utilized to power the electric motors. An electric motor has 2 sections: stator and rotor. An electric motor works using 2 processes: first, an electric current creates a magnetic field. This field which is created by the stator then rotated the rotor.

In EVs, when the accelerator pedal is pressed, a signal is sent to the controller which adjusts the car speed by changing the frequency of the AC power from the inverter to the motor. The motor then turns the wheel through a cog. When the brakes are pressed or the car is decelerating from removing the pressure from the acceleration pedal, the motor becomes the alternator and produces power which is sent back to the battery. When the car is slowing down, the kinetic energy of the car is turned to electricity and stored in the battery and hence slows down the vehicle. In an EV, we exploit this, and it is called ‘Regenerative Braking’. This way we recapture some of the kinetic energy and improve the overall efficiency of the vehicle. Due to the regenerative braking, it is possible to drive an EV using one pedal.

## Some EV terms to know:
<figure>
<img src="https://github.com/brianAsimba/Automotive-Engineering-Explained/blob/master/assets/img/Skateboard.jpeg" style="display: block; margin: auto;"/>
<figcaption>Chassis</figcaption> 
</figure>


<ul>
<li>Traction battery pack – Function as an electric energy storage system in the form of direct current electricity. The batteries used are rechargeable and are arranged in packs. </li>
<li>Inverter – Function is to change the DC to AC. The AC is then used by an electric motor. It also functions to change the AC to DC during the regenerative braking and to store the energy in the battery.</li>
<li>Electric traction motor - Turn the wheels using power from the traction battery pack. Generally, the brushless motors are used.</li>
<li>Auxiliary battery- Provides electricity to power vehicle accessories.</li>
<li>Charge port – Allows the vehicle to connect to an external power supply to charge the traction battery pack. </li>
<li>DC-DC Converter – Converts the higher voltage power from the traction battery pack to the lower voltage DC power required to run vehicle accessories and needed to recharge the auxiliary battery. </li>
<li>Charger – Battery charging device. They get electricity from outside sources such as solar power, wind power or the utility grids.</li>
<li>Transmission – Transmits power from the electric traction motor to drive the wheels.</li>
<li>kW – Unit of power for how much energy is required for a device to work.</li>
<li>kWH – Unit showing how much energy has been used, e.g., 100 W lightbulb uses 0.1kWH.</li>
<li>Charging speeds:
 <ul>
 <li>Slow charging – Rated up to 3kW, often used to charge overnight.</li>
 <li>Fast charging – Rated at 7-22 kW. Installed at car parks, supermarkets, and houses. 3-4 hrs.</li>
 <li>Rapid charging – Rated up to 43kW. Up to 30-60 mins.</li>
 </ul>
</ul>


<figure>
<img src="https://github.com/brianAsimba/Automotive-Engineering-Explained/blob/master/assets/img/Tesla%20Charging.jpeg" style="display: block; margin: auto;"/>
<figcaption>Rapid Charging</figcaption> 
</figure>

<p>There are different types of Electric vehicles: hybrid electric vehicles (HEVs), Plug-In Hybrid Electric Vehicles (PHEVs), Battery Electric Vehicles (BEVs) and Fuel Cell Electric Vehicles.</p>

## BEVs:
Battery Electric Vehicles (BEVs) run entirely on battery and the electric drive train. The BEVs are charged by plugging into the electricity grid. Traction battery provides the power to one or multiple motors to run the electric vehicles. Vehicles can have a singe motor, dual motor, tri-motor, or quad-motors. 

Examples of BEVs are <strong>Tesla models S, X, Y and 3; Rivian models R1T, R1S, EDV; Ford Mach-E and F150 Lightning, GM's Hummer EV.</strong></p>

## Hybrid Electric Vehicles:
Also known as <strong>Standard Hybrid Vehicles or Parallel Hybrid Vehicles.</strong> 
The Hybrid Vehicles contain both the Internal Combustion Engine and an Electric motor. The ICE gets the energy from fuel such as gasoline and the Electric motor gets the power from the battery. The transmission is powered by both ICE and Electric motors.
In the Hybrid Vehicles, the battery can only be charged by the ICE, the speed of the wheels or a combination of both. There is no way to charge the vehicles externally due to the absence of a charging port.
 
Examples are <strong>Honda Civic Hybrid and Toyota Prius Hybrid.</strong></p>
 
## Plug-In Hybrid Electric Vehicles (PHEVs):
<p>PHEVs contain both an ICE and an Electric motor just like the Hybrid Vehicles. They provide both the gasoline fuel option and a rechargeable battery.
PHEVs have a charging port and hence can be charged externally by plugging into an electrical outlet and an electrical charging station. They can run 2 modes, the all-electric mode where the motors provide all the car’s energy required or hybrid mode where both electricity and gasoline fuels provide are utilized.
 
Examples are <strong>Porsche Cayan SE Hybrid, Audi 13 E-Tron.</strong></p>
 
## Fuel Cell Electric Vehicle:
Known as Zero Emission Electric Vehicles. Utilize the fuel cell technology to generate electricity required to run the vehicles. The chemical energy is then converted into electric energy.</p>
 
Examples of Zero Emission Electric Vehicles are <strong>Toyota Mirai, Hyundai ix35 FCEV.</strong>

## EV Challenges:
<p>One of the biggest issues with Electric Vehicles are <strong>charging times, availability of charging stations and vehicle range</strong>. Currently, the EV with the highest range is the Lucid Dream with a range north of 500 miles in a single charge. With technology improving rapidly in the EV space, very soon it will be a non-issue for people who wish to own EVs that have range anxiety.<br>
 
More than the range anxiety is the possibility of finding <strong>rapid charging stations</strong>. This is coupled with the charging times to have the battery at 80% capacity. Most EV companies are currently installing level 2 and level 3 chargers in convenient locations that will ease this issue. The charging time is also dramatically reducing with the advancement of charging technologies. There are also charging companies that are setting up charging stations all over the country to reach the saturation of gas stations in the future.</p>

## References:
1.	Morse, L. C., Schell, W. J., & Babcock, D. L. (2020). Managing Engineering and Technology. Pearson Higher 	Education, Inc. 

