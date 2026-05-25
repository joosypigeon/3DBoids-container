# 3DBoids-container

A containerised C/Raylib development environment for **3DBoids**, a 3D boids simulation with predator behaviour, OpenMP parallel updates, spatial hashing, lighting, and a toroidal rendering mode.

The project renders a flock of boids as 3D dart-like models. The simulation can be displayed either on a flat plane or wrapped onto the surface of a torus.

## Project structure

```text
3DBoids-container/
├── Dockerfile
├── docker-compose.yml
├── .gitignore
├── README.md
└── 3DBoids/
    ├── CMakeLists.txt
    ├── blender_dart.obj
    └── src/
        ├── main.c
        ├── boids.c
        ├── boids.h
        ├── camera.c
        ├── camera.h
        ├── normal_random.c
        ├── normal_random.h
        ├── spatial_hash.c
        ├── spatial_hash.h
        ├── torus.c
        ├── torus.h
        ├── lighting.vs
        └── lighting.fs
