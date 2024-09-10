# WidowX 250 S Robot Description (URDF)

The robot model here is based on the real2sim project: https://github.com/simpler-env/SimplerEnv


## Changes Made:

- Added a .srdf file for SAPIEN to parse to avoid self collisions for better/faster simulation
- Removed some collision meshes that were unnecessary (e.g. inside another collision mesh)
- Removed mimic joint tags as they are not used and are modelled by the ManiSkill defined controllers