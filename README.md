# Deploying Aether Applications

A GitOps approach can be used to deploy Kubernetes applications
on one or more Aether clusters. This includes both AMP-related
applications like the Aether Runtime Opertaional Control (ROC)
and Aether Monitoring subsystem, and connectivity applications
like SD-Core and SD-RAN.

This is currently done using Fleet, where this repository contains
Fleet bundle specifications for multiple versions of Aether
(currently 2.0 and 2.1). These specifications are designed
to be used in conjunction with
[Aether OnRamp](https://github.com/SystemsApproach/aether-onramp),
and are intended to serve as an example of how Fleet can be used
to install and configure the Aether software stack.

On GitHub, you should first create a public fork of this repo, which
you are then free to modify to specify the exact configuration you
want to deploy. Note that you will point the instantiation of Fleet
running on your target Kubernetes deployment at your forked repo,
as described
[here](https://5g.systemsapproach.org/software/overview.html).

