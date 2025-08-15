# Make **Waves** in your Data Center

u-bmc is an open-source Linux platform purpose-built for Baseboard Management
Controllers. Everything lives in a single monorepo
([u-bmc/u-bmc](https://github.com/u-bmc/u-bmc)), forming what we call a _neo-monolith_: a tightly integrated
systems-building library you can embed in a standalone Linux system or, in the near future, drop
into an existing OpenBMC stack to migrate gradually.

## Why you might like it:

* Limited IPMI and Redfish support, plus a modern gRPC interface exposed through [ConnectRPC](https://connectrpc.com).
* Core services, board support, update logic, and test harnesses are all here, ready to ship with sane defaults.
* Our build and CI pipelines run entirely on [Dagger](https://dagger.io)—no Makefile spaghetti.

Pull the [u-bmc/u-bmc](https://github.com/u-bmc/u-bmc) repo, run the Dagger workflow, and make some waves!
