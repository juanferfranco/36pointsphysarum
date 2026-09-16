# physarum-36p — Visual Studio 2026 Project

This repository provides a **Visual Studio 2026 project setup** for the openFrameworks implementation of *physarum-36p* by [Bleuje](https://github.com/Bleuje/physarum-36p).

The simulation code is derived from the original repository:

* **physarum-36p** by Bleuje
  https://github.com/Bleuje/physarum-36p

This repository does not claim authorship of the Physarum simulation implementation. Its purpose is only to provide the project configuration required to build and run the code using **Visual Studio 2026**.

## Installation

This project is configured for **openFrameworks 0.12.1**.

Clone the repository inside the `apps/myApps` directory of your openFrameworks installation:

```text
of_v0.12.1_vs_64_release/
└── apps/
    └── myApps/
        └── physarum-36p/
```

For example:

```bash
cd of_v0.12.1_vs_64_release/apps/myApps
git clone <repository-url>
```

The repository should therefore be located at:

```text
of_v0.12.1_vs_64_release\apps\myApps\<repository-folder>
```

This location is important because the Visual Studio project uses the standard relative directory structure expected by openFrameworks.

Once cloned, open the Visual Studio solution and build the project using **Visual Studio 2026**.

## Attribution

The implementation used here comes from **Bleuje's `physarum-36p` project**, a simplified openFrameworks implementation inspired by **36 Points** by Sage Jenson (mxsage).

Original work:

**36 Points — Sage Jenson**
https://www.sagejenson.com/36points/

Derived implementation:

**physarum-36p — Bleuje**
https://github.com/Bleuje/physarum-36p

As stated in the original repository, Bleuje's implementation differs from *36 Points* by using counters on pixels while reusing and adapting parameter sets from the original work.

## License

The derived Physarum code is distributed under the:

**Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License (CC BY-NC-SA 3.0)**

https://creativecommons.org/licenses/by-nc-sa/3.0/

Accordingly, material derived from the original project must:

* give appropriate attribution,
* not be used for commercial purposes, and
* be distributed under the same or a compatible license when modified or redistributed.

The Visual Studio project configuration provided by this repository is intended solely to make the original code easier to build and explore with Visual Studio 2026.
