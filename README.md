# OpenXDR KVM Installer Documentation

Mintlify documentation for the OpenXDR KVM Installer.

This site turns the OpenXDR KVM Installer product overview and the current installer implementation into an operator-focused deployment guide for Stellar Cyber OpenXDR components on KVM.

## Documentation scope

- DP-Installer.sh — Data Processor host preparation and DL/DA deployment
- Sensor-Installer.sh — standard modular Sensor deployment
- 6000-Sensor-Installer.sh — high-performance dual-VM Sensor deployment
- AIO-Sensor-Installer.sh — integrated AIO + Sensor deployment
- Hardware, KVM/libvirt, networking, storage, images, VM deployment, SR-IOV / PCI passthrough where applicable
- DRY_RUN, full configuration validation, persistent state, logging, reboot and resume
- English and Korean navigation

## Source of truth

The operational behavior documented here is based on the current implementation in:

- https://github.com/xdr-labs/OpenXDR-KVM-Installer
- https://xdr.ooo/products/openxdr-kvm-installer

The intended documentation URL is:

- https://kvm.xdr.ooo/

Repository-specific credentials, private image URLs, and environment-specific secrets are intentionally excluded.
