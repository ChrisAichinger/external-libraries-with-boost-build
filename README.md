# Build External Libraries With Boost Build (Example)

An example project that shows how to include external libraries that require
other build systems, e.g. `make` or `cmake`, in Boost Build projects.
The magic happens in `libsquare/Jamfile`, adapt that to your needs.

To build this project, run `bjam` (or `bb2`) in the root folder.

See [the accompanying blog post](https://greek0.net/blog/2016/06/18/building_external_libraries_with_boost_build/) for more information.
