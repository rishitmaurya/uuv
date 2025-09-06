qadruped@qadruped-HP-Z2-Tower-G9-Workstation-Desktop-PC:~$ export GZ_SIM_RESOURCE_PATH=$GZ_SIM_RESOURCE_PATH:/home/qadruped/my_uuv_gz/models


qadruped@qadruped-HP-Z2-Tower-G9-Workstation-Desktop-PC:~$ gz sim /home/qadruped/my_uuv_gz/worlds/underwater_world.sdf


qadruped@qadruped-HP-Z2-Tower-G9-Workstation-Desktop-PC:~$ ros2 run ros_gz_sim create -name uuv -file /home/qadruped/my_uuv_gz/models/uuv_model/model.sdf -x 0 -y 0 -z 0




```
my_uuv_gz
├─ README.md
├─ models
│  ├─ OceanFloorShipwreck
│  │  ├─ materials
│  │  │  ├─ scripts
│  │  │  │  └─ model.material
│  │  │  └─ textures
│  │  │     ├─ Coral02_Albedo.png
│  │  │     ├─ Coral02_Normal.png
│  │  │     ├─ Coral02_Roughness.png
│  │  │     ├─ Coral03_Albedo.png
│  │  │     ├─ Coral03_Normal.png
│  │  │     ├─ Coral03_Roughness.png
│  │  │     ├─ GroundSand_Albedo.png
│  │  │     ├─ GroundSand_Roughness.jpg
│  │  │     ├─ GroundSant_Normal.png
│  │  │     ├─ Rock_Albedo.png
│  │  │     ├─ Rock_Normal.png
│  │  │     ├─ Rock_Roughness.png
│  │  │     ├─ SunkenShip_Albedo.png
│  │  │     ├─ SunkenShip_Metalness.png
│  │  │     ├─ SunkenShip_Normal.png
│  │  │     └─ SunkenShip_Roughness.png
│  │  ├─ meshes
│  │  │  └─ underwaterworld.dae
│  │  ├─ model.config
│  │  ├─ model.sdf
│  │  └─ thumbnails
│  │     ├─ 1.png
│  │     ├─ 2.png
│  │     └─ 3.png
│  └─ uuv_model
│     ├─ meshes
│     │  ├─ capsule_back_cover.stl
│     │  ├─ capsule_cylinder.stl
│     │  ├─ capsule_front_guard.stl
│     │  ├─ capsule_glass.stl
│     │  ├─ capsule_seal.stl
│     │  ├─ frame_lower.stl
│     │  ├─ frame_upper.stl
│     │  ├─ thruster2.stl
│     │  ├─ thruster3.stl
│     │  ├─ thruster5.stl
│     │  ├─ thruster6.stl
│     │  ├─ thruster7.stl
│     │  └─ thruster8.stl
│     ├─ model.config
│     ├─ model.sdf
│     └─ trash.sdf
└─ worlds
   ├─ previous.sdf
   └─ underwater_world.sdf

```