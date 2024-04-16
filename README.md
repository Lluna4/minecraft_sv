# Jelly
A simple 1.20.4 minecraft server made in c++20 thats in development!
## Build
To build the project you have to simply enter the build directory `cd build` configure cmake `cmake ..` and then build the project `cmake --build .`, the project has dependencies with [crashoz/uuid_v4](https://github.com/crashoz/uuid_v4) and [nlohmann/json](https://github.com/nlohmann/json) so please install uuidv4 and put nlohmann_json in the same directory as the project, also for now it only works for AVX2 enabled cpus, i plan on doing an uuid lib myself (probably using md5) to make it more portable
## Features
This project aims to be a simple minecraft server for me to learn but also to be as inclusive as possible, for now it has pronouns built in that can be changed with `/pronouns <pronouns>` but i also plan to provide support for plural systems in the future
## Dependencies
I'm really glad that some amazing people created awesome c++ libraries for uuids and json, without them this project would be impossible \
Thank you crashoz for making [crashoz/uuid_v4](https://github.com/crashoz/uuid_v4) <3 \
And also thank you nlohmann for making [nlohmann/json](https://github.com/nlohmann/json) <3 
