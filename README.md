
# StarterLibrcsc

[![License: LGPL v3](https://img.shields.io/badge/License-LGPL_v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)

librcsc is a basic library to develop a simulated soccer team and related tools for the RoboCup Soccer Simulation.
All programs can work with rcssserver-18.
starter librcsc is a simplified version of librcsc to help junior student to participate in RoboCuo Soccer Simulation League.

- IranOpen RoboCup Soccer Simulator: https://rcss.ir/
- IranOpen RoboCup Soccer Simulator GitHub: https://github.com/RCSS-IR/
- The RoboCup Soccer Simulator: https://rcsoccersim.github.io/
- RoboCup Official Homepage: https://www.robocup.org/

## Quick Start

The latest librcsc depends on the following libraries:
 - C++17
 - Boost 1.41 or later https://www.boost.org/

In the case of Ubuntu 20.04 or later, execute the following commands for installing a basic development environment:
```
sudo apt update
sudo apt install build-essential libboost-all-dev cmake libtool
```

To build the library, execute commands from the root of source directory:
```
mkdir build
cd build
cmake ..
make
```

Once successfully built, you can install the library file and header files to the default installation directory (``~/local/starter``):
```
make install
```

## References

- Hidehisa Akiyama, Tomoharu Nakashima, HELIOS Base: An Open Source Package for the RoboCup Soccer 2D Simulation, In Sven Behnke, Manuela Veloso, Arnoud Visser, and Rong Xiong editors, RoboCup2013: Robot World XVII, Lecture Notes in Artificial Intelligence, Springer Verlag, Berlin, 2014. http://dx.doi.org/10.1007/978-3-662-44468-9_46
- Hidehisa Akiyama, Itsuki Noda, Multi-Agent Positioning Mechanism in the Dynamic Environment, In Ubbo Visser, Fernando Ribeiro, Takeshi Ohashi, and Frank Dellaert, editors, RoboCup 2007: Robot Soccer World Cup XI Lecture Notes in Artificial Intelligence, vol. 5001, Springer, pp.377-384, July 2008. https://doi.org/10.1007/978-3-540-68847-1_38
