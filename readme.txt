A Computational Model of Synaptic Transmission at the Calyx of Held
-------------------------------------------------------------------

This model allows the user to investigate faciliation and depression
in a complex Monte Carlo model of the calyx of Held, a giant synapse
in the mammalian auditory system.  It can be used to replicate the
results presented in the paper:

Bruce P. Graham, Adrian Y.C. Wong and Ian D. Forsythe, A computational
model of synaptic transmission at the calyx of Held, Neurcomputing
38-40: 37-42, 2001

The user is able to specify a presynaptic stimulation frequency and
duration.  The output is the postsynaptic current or voltage.

Main HOC file: run_epsc.hoc
---------------------------
Trains of EPSCs are produced that exhibit both facilitation and depression
(paper fig. 2). The relative contributions of these to the response can be
altered by changing the release probability (fig. 3).

Main HOC file: run_epsp.hoc
---------------------------
Same simulation as with "run_epsc.hoc", but fast sodium and potassium
channels are added to the soma to produce a spiking response.  Output
is now the soma voltage trace.
