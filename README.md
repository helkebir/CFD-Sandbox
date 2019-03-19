# CFD-Sandbox
Sandbox for CFD experiments, mainly relating to rocket aerodynamic performance simulations.

## Models

3D Models of the rocket bodies are found in the `models` folder. They are formatted as ASCII Stereolithography (STL) files, and split into three parts (fins and nozzles are to be added):

**RocketBody**
* NoseCone
* BodyTube
* BottomCap

Note that the exist both in meter and millimeter format. The files in meters are marked by the `_m` suffix. Note that the RocketBody files combines all three consituents as one solid, and not as separate solids as is normally the case. Such a file structure is adhered to in the `_cc`-suffixed files, which contain solids `nc` (nosecone), `bt` (bodytube) and `bc` (bottomcap).