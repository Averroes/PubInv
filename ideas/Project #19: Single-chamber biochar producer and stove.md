# Motivation

Biochar is normally produced in two-chamber systems.  Such systems separate the fuel for the heat of pyrolysis from
the payload to be converted to biochar.  This makes it simple to prevent combustion in the feedstock chamber by limiting
oxygen there.

However, such systems necessarily have a certain complexity in that the feedstock and the fuel must be treated separately.

# Idea

We can use a single chamber and provide a way to control oxygen to the chamber. This would given the stove operator
the option of producing biochar, or to combust the biochar for additional heat.

This idea also has a potential advantage in sanitation and waste elimination if we attempt to use the feedstock as the
fuel.

# Design

(I need to add a drawing here.)

The basic idea is similar to designs for produing charcoal that I have seen.  The main chamber has a high output pipe
that is ducted to a burner beneath the chamber.  Once pyrolisys begins, this provides enough heat to continue the 
process until no more pyrolysis occurs. Such systems often put fuel below the main chamber to start the process, and 
rely on self ignition of they syngas when pyrolysis begins.

Instead, we could light the main chamber, and allow oxygen in (at the bottom, presumably.)  This would have a valve
that could be closed.  In the simplest operation, the operator observes that pyrolysis has begun, shuts the valve to
stop combustion of the syngas, then lights the syngas jets.  Such a system thus has a symbolic "going exothermal" point.

The operator could choose to open the valve, which would allow oxygen in, beginning combustion.  This biochar
present would thus be consumed, perhaps adding to the cooking value.

A possibly different embodiment would be to take to use a sensors to dermine that the inner chamber had reached 
the temperator of pyrolyis and automatically shut off combustion in the chamber and light the syngas jets.
Posssibly the dying combustion could be used to ignite the syngas---this is somewhat uncertain.  Any lighting 
is likely to be unreliable.

Note that if we are constructing a control mechanism, we also want to limit temperature (or raise temperature) to produce either more biochar (low temperature) or more energy (high temperature.)  For my initial application, limiting temperature seems more reasonable.

I don't know how to do this.  We do NOT want to limit oxygen to the syngas, nor do we want to release syngas unburned, nor do I want to try to collect syngas, although obviously that could be valuable in a large scale operation.  I suppose we could control a valve that allowed a fraction of the syngas to be diverted and flared off.



<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">PIFAH Project #19: Virtual Single-chamber biochar producer and stove</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/PIFAH/PIFAH" property="cc:attributionName" rel="cc:attributionURL">Robert L. Read</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/PIFAH/PIFAH" rel="dct:source">https://github.com/PIFAH/PIFAH</a>.
