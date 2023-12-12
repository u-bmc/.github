# Makes **Waves** in your Datacenter

u-bmc is a linux OS distribution that is fully open-source, and tailer made for
Baseboard Management Controllers (BMCs). The repository is structed as follows:

* u-bmc/u-bmc

This is the main u-bmc repository. This should be your starting point.
* u-bmc/operator

The 'operator' is the core u-bmc compontant that manages all microservices and
the complete lifecycle of the BMC.

Here's a short sneak-peek of features for the upcoming dev release:
- New userspace architecture using a monolithic approach
- TUF updates
- Sigstore provenance
- New boards supported
- A more flexible build system using Task+Dagger
- Compatibility with Redfish via gRPC and HTTP(S)
- Many more, so stay tuned!
