<!-- SPDX-FileCopyrightText: 2025 Contributors to the Media eXchange Layer project. -->
<!-- SPDX-License-Identifier: CC-BY-4.0 -->

# MXL : Media eXchange Layer

[![Build Pipeline](https://github.com/dmf-mxl/mxl/actions/workflows/build.yml/badge.svg)](https://github.com/dmf-mxl/mxl/actions/workflows/build.yml)
[![GitHub release](https://img.shields.io/github/v/release/dmf-mxl/mxl)](https://github.com/dmf-mxl/mxl/releases)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE.txt)
[![Issues](https://img.shields.io/github/issues/dmf-mxl/mxl)](https://github.com/dmf-mxl/mxl/issues)

[Go straight to documentation](#governance)

# What is MXL?

- MXL is an open-source SDK designed for high-performance and container-friendly shared media exchange across on‑premise or cloud environments.
- It provides an open and non-proprietary exchange layer, helping to promote interoperability by avoiding the need for conversion between vendors. Such a layer is required by the [EBU Dynamic Media Facility Reference Architecture](https://tech.ebu.ch/dmf/ra).
- This repository contains an open-source SDK that specifies MXL through implementation, including how video, audio and data payloads are represented in shared memory, and the timing of those payloads.

## Key Characteristics

MXL: 

- is implemented in C++, exposed via a C API with Rust bindings available
- supports for V210 video, Float32 audio and ANC data
- implements zero-copy media sharing or low-copy media movement
- is asynchronous by design
- is a thin library with minimal external dependencies
- can be deployed on local (on-premise) or cloud compute
- is suitable for use in containerised environments

# Getting Started

See [Getting Started](Getting%20Started.md) for more information about how to get started with MXL.

# MXL Governance

Information about the governance of the MXL project, including the project governance principles and technical charter, can be found [here](GOVERNANCE/README.md).

# Technical Documentation

- [MXL Architecture](Architecture.md)
- [SDK Usage](Usage.md)
- [Building options](Building.md)
- [Tools](Tools.md)

# License

This code is covered by the [Apache v2 license](./LICENSE.txt)
