GrC
===

Cerebellum Granule Neuron Model (working copy as on Modeldb)

  
After launching the model, one may insert an current clamp electrode
to see the model response as in Fig.5A in the paper.

Choosing the excitatory mossy fibers and inhibitory fibers from
control panel, it is also possible to generate synaptic patterns as
reported in Fig.10 in the paper.  See the screenshot images in the
fig10 folder for details of how to set parameters for the different
subplots in figure 10.  For example setting the parameters as in
fig10/mf0p3_300.png leads to reproducing fig 10 second from top plot:


One may also modify each synaptic terminal individually through
"Companel.hoc" file.


 
Attention: 

The GrC model was adapted to have 4 excitatory and 4 inhibitory
synapses as observed in many cerebellar granule cells of rats. To
reconfigure please follow changes in the correspoding hoc files.

The model files were tested on Fedora 10 Linux and on MS-Win platforms
both running Neuron version 7.0.

Variable time step(pref DASPK method) works without issues while on
Current clamp protocol. While during synaptic activation, it is
recommended to turn it off.
