# 01 - Introduction
Welcome to this tutorial where I will teach you how to create a virtual machine for Arch Linux ARM.
This tutorial will use the UTM hypervisor, but replacing it should be straightforward.

## Why ARM?
Macs with an Apple chip use the aarch64 instruction set, x86_64 Arch Linux needs to be emulated in this machines, which slows down the experience.
Using Arch Linux ARM allows the guest to avoid heavy translation layers, therefore improving performance.

## Requirements
* [UTM Hypervisor](https://mac.getutm.app/)
* [Alpine Linux Standard aarch64 Image](https://alpinelinux.org/downloads/)
* Internet Connection
* A Mac with Apple chip
* Some experience with Linux (recommended)

---

By the end of this tutorial you will have a fast and completely functional Arch Linux system running in your Mac.
