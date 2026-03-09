**todo**

The Gaggimate Graphs in the shothistory tap look more complex then they realy are. The visible complexity comes from the fact, that multiple graphs get layered upon each other. But as soon as we disect the graphs and look at the single lines they get way easier to read.

![graph](./assets/ShotHistoryGraph.png)


# The Lables
First lets view at the different parts around the graph itself.

At the top there is the legend. We can clearly see what color represents what variable in the graph.

Because of the amount of variables the y-axis gets split into left and right. The left labels of the y-axis displays the temp values (°C) of the graph.

The right side labels of the y-axis are for the pressure(bar), flow(g/s) and weight(g) if a scale is connected.

Inside the Graph there are multiple vertical lines with Lables. They are the phase lables.

The x-axis is for the time dimension(s).

# The Graph

Now lets look at the graph itself and its different lines.

We have a few main values as solid lines: Temperature, Pressure, PumpFlow, PuckFlow, Weight, WeightFlow.

For some values the targets get displayed as dotted lines: Target Temp, Target Flow, Target Pressure.

# How to read a graph.

If we read a graph we move from left to right in the time dimension. This way we can see how a value changed over time.

# Excample Disecting a Shot based on the Graph 

![graph Full](./assets/ShotHistoryGraphFull.png)

Here is a shot I pulled with a Testversion of the Automatic Pro profile. 

I will first focus on the main variables of Temp, Flow, Pressure and Weight. Afterwards I will compare some to each other and see how they interact with each other.

## Temp
![graph temp](./assets/ShotHistoryGraphTemp.png)

We can see that the Temp changed a bit over the duration of the shot. The Temp was stable for the first 8 Seconds but then started to dip till the lowest point at around 22s of 87.5°C. 

## Flow
![graph flow](./assets/ShotHistoryGraphFlow.png)

This is the first time we can see a Value and its target in comparison. The dotted line shows the target/limit value. We can see that the Flow went up in Fill Headspace to around 7g/s. Afterwards it went down untill the Saturate phase. Afterwards it stayed mostly at the target value.

## Pressure
![graph pressure](./assets/ShotHistoryGraphPressure.png)
We can see, that the Pressure was over target in the Stabalize phase (Thats not optimal, I should have let out some Pressure before starting the shot). Afterwards it went down fast and then slowly climbed back up till 4 bar. and started to go down again.

## Temperature and Flow

![graph Temp and Flow](./assets/ShotHistoryGraphTempFlow.png)

This is the first time we look at two different lines and how they interact with each other.
Pump Flow means, how much water gets pumped by the pump. This Water needs to get somewhere and that place is the boiler. That incoming cold water will cool down the boiler. The PID will try to counter act this incoming temperature change and heat the water back up. If more water comes in at once, the dip will be deeper and the heater will have a harder time to work against it. 

If we now look at the Graph we can see that we had the biggest flow at around 5s ion the FillHeadspace phase. But the Temperature stayed the same. That has to do with the fact, that the Boiler has alot of thermal pass. The incoming water first has to work against this thermal mass, before the TC can messure it and the PID to react to it. The thermalmass delays the impact in the graph.

After the flow got lower and the PID had the chance to react, the Temperature started to clib again. If we had a higher flow, the temperature could have gone down further and maybe the heater couldnt have worked against it.

## Flow and Pressure

![graph Temp and Flow](./assets/ShotHistoryGraphFlowPressure.png)

Flow and Pressure are two Variables that are tightly linked. But another Variable is missing: Puckresistance.
Pressure is the combination of Flow and Puckresistance. With alot of Puckresistance little Flow is needed to build Pressure. With less Puckresistance more Flow is needed

We can kind of ignore the Fill Headspace phase for this. The Headspace is mostly air. Pushing water into the headspace has to displace the air first. Air can pass through the puck more easily and will not build much pressure. Afterwards we can see that as the Flow keeps going the Pressure keeps building slowly. This process is relatively slow, because the flow was relatively low (2g/s) and the puck did not give enough resistance for more pressure. The pressure kept increasing because water more water was pushed by the pump then the puck let through. That was true till the 25s mark. There two things happend: The Flow kept decreasing, resulting in slower pressure buildup and the puck resistance decreased. This happens because the puck degrades over time while we extract.


*Assumption based on the graph:*
One thing we can see is, that the thing that limited this extraction in the main phases was the flow. The pressure kept beeing relatively low. That means, that the Puckresistance wasnt high enough to build pressure. We could now grind finer or increase the dose to increase the puck resistance and get more pressure.

THIS IS ONLY A ASSUMPTION! Based on the graph alone we dont know how the cup tasted and if this is realy needed. I cant stress enough how important it is to taste first and only then decide if we want to change something.

This combination in the Graph leads to think that the shot was tasting to sour and wasnt great. Based on the graph alone the decision to grind finer could have been a good thing. But as I am the one who tasted the Cup I can tell you that this would have been the wrong decision in this case. It was a ligher roast where I wanted to highlight slight acidity and fruity notes. In the end the cup was perfect and I did not change anything. This is to show, that the graph can be missleasind if taste isnt used as a important factor.