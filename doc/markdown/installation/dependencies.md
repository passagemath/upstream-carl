Dependencies {#dependencies}
==========

To build and use CArL, you need the following other software:
- `git` to checkout the git repository.
- `cmake` to generate the make files.
- `g++` or `clang` to compile. We use C++17 and thus need at least `g++` 7 or `clang` 5.
- `boost` for several additional libraries.
- `gmp` for calculations with large numbers.
- `Eigen3` for numerical computations.

You can install the last three by running
@code
apt-get install libboost-all-dev libgmp3-dev libeigen3-dev
@endcode

Optional dependencies
- `ccmake` to set cmake flags.
- `doxygen` and `doxygen-latex` to build the documentation.
- `gtest` to build the test cases.