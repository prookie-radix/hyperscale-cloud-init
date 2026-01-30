# Cloud-Init config to auto-setup and run a Radix Hyperscale node

---

**Cloud-Init file: [Link](https://raw.githubusercontent.com/prookie-radix/hyperscale-cloud-init/refs/heads/main/cloud-init.txt)**

---

> [!IMPORTANT]
> ### Operating system
> **Please use `Ubuntu 24.04`.** Other operating systems are not supported/tested.

> [!IMPORTANT]
> ### VM resources
> Your VM requires at least the following specs:
> * 4 **dedicated** CPU cores (if they are shared, use 8 cores!)
> * 16 GB RAM
> * 100 GB SSD
> * 100 Mbit/s network bandwidth
> 
> The node needs around 20 GB / hour disk space at high TPS.

## Confirmed usable VPS sizes for some cloud providers

### DigitalOcean
* `c-8-intel` *($0.3244 / h)*
* `gd-4vcpu-16gb-intel` *($0.23512 / h)*
* `s-4vcpu-16gb-amd` (if you can not create the others, but not recommended)

### Hetzner
* `CCX23` *(0.038 EUR / h)*
* `CPX42` *(0.031 EUR / h)*

### OVH
* `c3-16` *(0.166 EUR / h)*
* `b3-16` *(0.093 EUR / h)*

### Vultr
* `vx1-g-4c-16g-240s` *($0.153 / h)*
