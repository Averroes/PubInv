# Motivation

Biochar is normally produced in two-chamber systems.  Such systems separate the fuel for the heat of pyrolysis from
the payload to be converted to biochar.  This makes it simple to prevent combustion in the feedstock chamber by limiting
oxygen there.

However, such systems necessarily have a certain complexity in that the feedstock and the fuel must be treated separately.

# Idea

We can use a single chamber and provide a way to control oxygen to the chamber. This would given the stove operator
the option of producing biochar, or to combust the biochar for additional heat.

This idea also has a potential advantage in sanitation and waste elimination if we attempt to use the feedstock as the fuel.

# Relation to other designs

I think:

* Gassifying stoves depend on a secondary air which is heated first then added to the stream of gases produced by the fire chamber, thus more fully combusting all of the gas products.  I haven't seen any design that actually switches over to using purely syngas by cutting off oxygen in the fire chamber.
* Rocket stoves use a forced updraft in a J-shape to provide a great deal of oxygen to produce a fast, clean comubustion.
* Retort -- This is the basic biochar producing feature.  A great practical example using a tempperatures sensor is here: http://www.biochar.info/biochar.CarbonZero-Experimental-Biochar-Kiln.cfml  where it gives practical advice on the temperature.  Again, this design is lighting second fire under the retort rather than using the fuel in the retort and then cutting of oxygen as I am suggesting.  This is a wonderful reasource as it gives practical advice on monitoring the temperature (i.e., pyrolisys begins at 320C, goal temperature is 360C to 420C.) It also suggests using thermocouple wire for measuring temperature. It also shows that it is possible for the fire to get too hot (up to 1000C), which will tend to destroy the stove parts, is dangerous, and decreases the amount of biochar produced.
* Afterburner -- My current design does not have an afterburner.  I may have to add that to my design based on the excellent exposition by CarbonZero above.

The CarbonZero article above is for a much large scale than I imagine but the problems they had of things getting red-hot and/or too-hot seems to suggest something like the "movable firebed" idea below could be extremely valuable as a temperature control.

# Design

![biochar-producing syngas stove 002](https://cloud.githubusercontent.com/assets/5296671/7164458/ee607f8e-e365-11e4-8bfa-ff690d4ae29e.jpg)


The basic idea is similar to designs for produing charcoal that I have seen.  The main chamber has a high output pipe
that is ducted to a burner beneath the chamber.  Once pyrolisys begins, this provides enough heat to continue the 
process until no more pyrolysis occurs. Such systems often put fuel below the main chamber to start the process, and 
rely on self ignition of they syngas when pyrolysis begins.

Instead, we could light the main chamber, and allow oxygen in (at the bottom, presumably.)  This would have a valve
that could be closed.  In the simplest operation, the operator observes that pyrolysis has begun, shuts the valve/access door to
stop combustion of the syngas, then lights the syngas jets.  Such a system thus has a symbolic "going exothermal" point.

The operator could choose to open the valve, which would allow oxygen in, beginning combustion.  This biochar
present would thus be consumed, perhaps adding to the cooking value.

A possibly different embodiment would be to take to use a sensors to dermine that the inner chamber had reached 
the temperator of pyrolyis and automatically shut off combustion in the chamber and light the syngas jets.
Posssibly the dying combustion could be used to ignite the syngas---this is somewhat uncertain.  Any lighting 
is likely to be unreliable.

Note that if we are constructing a control mechanism, we also want to limit temperature (or raise temperature) to produce either more biochar (low temperature) or more energy (high temperature.)  For my initial application, limiting temperature seems more reasonable.

I don't know how to do this.  We do NOT want to limit oxygen to the syngas, nor do we want to release syngas unburned, nor do I want to try to collect syngas, although obviously that could be valuable in a large scale operation.  I suppose we could control a valve that allowed a fraction of the syngas to be diverted and flared off.

# Solving the Positive Feedback Problem

One of the problems of any syngas retort is the that it is subject to positive feedback.  That is, the hotter it
gets, the more syngas it produces, which makes it get hotter, which makes it produce more syngas, etc.

This has several problems:
* It's dangerous.
* It degrades the materials faster.
* It tends to produce more "biofuel", that is, heavier hydrocarbons in the form of alkanes, which means less biochar is produced.

If we begin from the assumption that we have some form of active control in response to temperature, we limit this 
positive feedback. It would be very dangeous to allow pressure to build up in the syngas. I am not prepared to contemplate piping the syngas off for storage (although in other circumstance it is a valuabe product and that would
be the best thing to do.

I believe there should always be two flames: the heating flame, which heats the retort, and the "afterburner" which does not heat the retort, but burns excess syngas.  If we can adjust the proportion of produced syngas going to these two flames, we can limit the amount of heating.  It is even reasonable to assume that the afterburner can be arragned so that it burn draw more air across the outside of the retort, thus cooling it.

It would seem that any practical use by non-experts would have to have either passive or active control of the proportion of the syngas going to these two flames.

# Alternate Embodiments

## Camp Stove

One valuable idea would be to make a biochar-producing camp stove for the Western audience.  This would be appealing,
because it would help the environment.  If parks would allow it, the burying or scattering of the cooled and wetted
biochar could be a significant improvement in both soil quality and carbon sequestration.  A challenge for this
application would be to build a stove that would accept a standard length firewood log, which seems to be 16".  We would have to make a firebox 18" in at least one dimension.

(P.S. written after reading a stupid article in Fast Company about using a polymer to extract CO2 from the air -- I actually think if we could make a stove that would fit in people's fire place, sent the smoke up the existing flue, and produce biochar, at least some Americans would want to use it.  This would mean the 18" firebox would have to be vertical rather than horizontal. I believe this would do far more to sequester carbon than any idea of pulling CO2 from the air and retaining it as CO2.  Until you reduce it to elemental carbon and elemental oxygen, you aren't making progress.)

## Fireplace Stove

What if we build a stove that would fit into the average American fireplace?  We could direct the exhaust up the 
flue. If we build a one-log system that could reduce a single log to biochar, then people could safely make biochar
at home, get heat and get rid of waste wood all at the same time.  No pretty dancing flames, however.  But you could 
roast marshmallows.  You will have to provide your own bearskin rug.

## Movable Firebox

A fascinating idea is to have a movable firebox, perhaps made into separate partitions.  This would allow you 
to remove biochar from one box partition while still cooking with the other.  It is a step toward a 
continuous process.

Note that moving toward a continuous process is actually very important for any treatment of human waste, for example.


<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">PIFAH Project #19: Virtual Single-chamber biochar producer and stove</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/PIFAH/PIFAH" property="cc:attributionName" rel="cc:attributionURL">Robert L. Read</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/PIFAH/PIFAH" rel="dct:source">https://github.com/PIFAH/PIFAH</a>.
