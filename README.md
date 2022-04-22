# inekf_vendor
This is a CMake wrapper around [inekf](https://github.com/mayataka/inekf), a state estimator of legged robots.

# Requirements
- [Eigen3](http://eigen.tuxfamily.org/index.php?title=Main_Page)
- [Pinocchio](https://github.com/stack-of-tasks/pinocchio)

# Usage
```
find_package(inekf_vendor REQUIRED)

ament_target_dependencies(my_target inekf_vendor)
```
