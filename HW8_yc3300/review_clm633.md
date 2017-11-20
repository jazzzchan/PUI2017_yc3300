![raw canonical github image link](https://github.com/cmoscardi/PUI2017_yc3300/blob/master/HW8_yc3300/311_trafficcomplaint_plot.PNG?raw=true)


#### CLARITY: is the plot easy to read? is it clear or confusing, are the quantities being visualized ambiguous?
I think this plot is very clear! Darker red indicates "more traffic complaints", and lighter red indicates "fewer traffic complaints".

There is some ambiguity in the specific choice of metric - this appears to be overall number of calls. But what timeframe of data was being looked at? Then, should this somehow be normalized (by road area or something like this)?


#### ESTHETIC: beautiful is a subjective judgment: you should not judge the plot on the basis of whether you think it is "beautiful", but you should judge whether its esthetic is functional to what it is meant to communicate. Are the colors chosen appropriately? Are the graphical elements used appropriate to represent the quantities being visualized? Are the graphical choices allowing you to focus on the right elements or are they distracting you?
I think the gradient is chosen appropriately for something like traffic, which is bad (so darker red => more bad makes sense). The map is nice. 

Three improvements I personally would make: 

1. The legend blocks a corner of NYC and there's a lot of blank space in the top left of the map, so I would consider moving the legend to the top left corner so it's out of the way.
2. The axes have ticks - they're probably the X and Y coordinates, right? - I would remove those, since they aren't communicating anything but could confuse a viewer.
3. I'm less sure about this one, but the title and caption are the same? I would make the title at the top convey different information from the "Fig. 1" thing at the bottom.

#### HONESTY: is the plot honestly reproducing the data or is it deforming it, perhaps to emphasize a point?
The only point I'd make here would be about the specific choice of metric for traffic, which I mentioned under "Clarity." Basically, I'd hope for some justification of the choice of "overall number of calls" as the way to measure traffic complaints... maybe in the "process" section or in the caption below?
