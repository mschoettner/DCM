# DCM

Here I will be trying to build a python implementation of dynamic causal modeling (DCM).

The package will be developed using a dataset from openfmri.org ([data](https://www.openfmri.org/dataset/ds000117/ "The dataset used")).

### Approach

Instead of trying to build DCM from scratch, I will follow [Peer's](https://github.com/PeerHerholz) advice and instead create a Nipype interface similar to how the [other SPM functions](https://nipype.readthedocs.io/en/latest/interfaces/generated/interfaces.spm.html) are implemented in [Nipype](https://nipype.readthedocs.io/en/latest/). The corresponding [part of the Nipype tutorial](https://miykael.github.io/nipype_tutorial/notebooks/advanced_create_interfaces.html) on how to make interfaces will serve as a starting point.
