# Common Proprietary Qualcomm Binaries


CPU and GPU info:

| CPU Model | CPU Name | GPU | Hexgon | Device |
| --- | --- | --- | --- | --- |
| msm8974 | Snapdragon 800 | Adreno 330 | Hexagon QDSP6 V5 | Nexus 5 |
| msm8992 | Snapdragon 808 | Adreno 418 | Hexagon V56 | Nexus 5X |
| msm8994  | Snapdragon 810 | Adreno 430 | Hexagon V56 | Nexus 6P |
| msm8996 | Snapdragon 820 | Adreno 530 | Hexagon 680 | Samsung Galaxy S7 & Galaxy S7 Edge |

for OpenCL support, find the corresponding libOpenCL.so in vendor directory, 
for example the OpenCL library of Nexus 5 is at location `msm8974/graphics/proprietary/vendor/lib/libOpenCL.so`