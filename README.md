# OpenXDR KVM Installer Documentation

Operator-focused documentation for deploying and operating Stellar Cyber OpenXDR components on KVM.

- **Live documentation:** https://kvm.xdr.ooo/
- **한국어 문서:** https://kvm.xdr.ooo/ko
- **Installer source:** https://github.com/xdr-labs/OpenXDR-KVM-Installer

## Start here

| Goal | Korean documentation |
| --- | --- |
| Choose the correct installer | [설치 프로그램 선택](https://kvm.xdr.ooo/ko/getting-started/choose-installer) |
| Check host and BIOS requirements | [요구사항](https://kvm.xdr.ooo/ko/getting-started/requirements) |
| Install Ubuntu Server 24.04 | [Ubuntu Server 24.04 LTS 설치 가이드](https://kvm.xdr.ooo/ko/getting-started/installing-ubuntu-24-04) |
| Choose a topology / network model | [배포 방식 선택 가이드](https://kvm.xdr.ooo/ko/getting-started/deployment-guide) |
| Run a first deployment | [빠른 시작](https://kvm.xdr.ooo/ko/getting-started/quickstart) |
| Troubleshoot a failed step | [Troubleshooting](https://kvm.xdr.ooo/ko/operations/troubleshooting) |

## Installer guides

- [DP KVM Installer](https://kvm.xdr.ooo/ko/installers/dp) — DL-master / DA-master Data Processor deployment
- [Standard Sensor](https://kvm.xdr.ooo/ko/installers/sensor) — NAT/Bridge and PCI/Bridge SPAN deployment
- [High-performance Sensor](https://kvm.xdr.ooo/ko/installers/high-performance-sensor) — dual-VM / NUMA / PCI passthrough deployment
- [AIO + Sensor](https://kvm.xdr.ooo/ko/installers/aio-sensor) — integrated AIO and Sensor deployment
- [Stellar Appliance CLI](https://kvm.xdr.ooo/ko/operations/appliance-cli) — post-deployment host operations

## Documentation scope

This repository documents:

- KVM/libvirt host preparation
- DP, Sensor, High-performance Sensor, and AIO + Sensor deployment
- networking, storage, SR-IOV, PCI passthrough, NUMA and CPU placement
- DRY_RUN and full configuration validation
- persistent state, logging, reboot and resume
- post-deployment operations and troubleshooting

## Source of truth

Operational behavior should be checked against the current implementation in:

- https://github.com/xdr-labs/OpenXDR-KVM-Installer

The Korean installation walkthroughs are written primarily for **Ubuntu Server 24.04 LTS**. The installer source may retain compatibility paths for older Ubuntu/OpenXDR releases; legacy deployments should verify the current source and the target release support matrix rather than assuming the 24.04 procedure applies unchanged.

Repository-specific credentials, private image URLs, and environment-specific secrets are intentionally excluded.
