<h1 align="center">  
    FLATSAT PLATFORM 2.0
    <br>
</h1>

<h4 align="center">FlatSat platform designed and developed by SpaceLab.</h4>

<p align="center">
    <a href="https://github.com/spacelab-ufsc/spacelab#versioning">
        <img src="https://img.shields.io/badge/status-in%20development-red?style=for-the-badge">
    </a>
    <a href="https://github.com/spacelab-ufsc/flatsat-platform2/releases">
        <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/spacelab-ufsc/flatsat-platform2?style=for-the-badge">
    </a>
    <a href="https://github.com/spacelab-ufsc/flatsat-platform2/releases">
        <img alt="GitHub commits since latest release (by date)" src="https://img.shields.io/github/commits-since/spacelab-ufsc/flatsat-platform2/latest?style=for-the-badge">
    </a>
    <a href="https://github.com/spacelab-ufsc/flatsat-platform2/commits/master">
        <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/flatsat-platform2?style=for-the-badge">
    </a>
    <a href="https://github.com/spacelab-ufsc/flatsat-platform2/issues">
        <img alt="GitHub issues" src="https://img.shields.io/github/issues/spacelab-ufsc/ttc?style=for-the-badge">
    </a>
    <a href="https://github.com/spacelab-ufsc/flatsat-platform2/graphs/contributors">
        <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/spacelab-ufsc/flatsat-platform2?color=yellow&style=for-the-badge">
    </a>
</p>

<p align="center">
  	<a href="#overview">Overview</a> •
  	<a href="#repository-organization">Repository Organizarion</a> •
  	<a href="#license">License</a> •
  	<a href="#releases">Releases</a> •
  	<a href="#notes">Notes</a>
</p>

<p align="center">
    <img src="https://github.com/spacelab-ufsc/flatsat-platform2/blob/documentation/doc/figures/flatsat_perspective_image.png">
</p>

## Overview

The FlatSat Platform 2.0 is a testbench for testing the main SpaceLab's subsystems (but can be adapted for other CubeSat missions). A FlatSat is an electrical model of the satellite with the subsystems assembled side by side over a workbench that can be mounted during the V&V [[1]](#1). They offer an easier, faster and safer way for testing subsystems before assembly into the final structure of a CubeSat. It can be used in combination with the hardware-in-the-loop (HIL) technique, which justifies the usage of a built-in MicroZed and sensors. It supports up to 6 modules.

## Repository Organization
	- doc: Technical FlatSat's documentation.
	- firmware: FlatSat's firmware project (sources and configs)
	- hardware: Flatsat's hardware project (sources and outputs).

## License

This project is open-source under three different licenses: CERN Open Hardware License v2.0 for hardware, GNU General Public License v3.0 for firmware, and CC BY-SA 4.0 for the documentation.

## Releases

The FlatSat Platform hardware releases are synchronized in order to garantee compatibility. Then, using diferent versions might lead to unpredictable behavior. Refer to the [documentation](https://github.com/spacelab-ufsc/flatsat-platform2/tree/master/doc) for compatibility notes.

## Notes

More info about the SpaceLab: [GitHub](https://github.com/spacelab-ufsc/spacelab) and [Website](https://spacelab.ufsc.br/en/home/).

## References
<a id="1">[1]</a> 
J. C. E. Barcellos, A. W. Spengler, L. O. Seman, R. D. C. e. Silva, H. P. Roldán and E. A. Bezerra, "FlatSat Platforms for Small Satellites: A Systematic Mapping and Classification," in IEEE Journal on Miniaturization for Air and Space Systems, vol. 4, no. 2, pp. 186-198, June 2023, doi: 10.1109/JMASS.2023.3249044.
