<a name="TOP"></a>
# ErcfBearingSpool
This is a bearing version of the filament spool holder of the Enraged Carrot Feeder Patch (ERCP) buffer.

The original design can be found at [ercf](https://github.com/EtteGit/EnragedRabbitProject.git).

This modification is based on the version taken on August 2023. 
It remove lots of friction compare to the original one (PTFE version).
I'm getting less failure rate with the bearing version.

It support filament spool up to 80 mm wide.

It uses two 608 bearing plus 95 mm of thread rod. That threaded rod could be M8 (metric) or 5/16" (imperial).
I provide the STL for both version.

By the way, the term "vitamin" simply mean non printer part. Apparently the origin comes from reprap [reprap](https://reprap.org/wiki/Category:Vitamin). 

Documentation generated by the OpenSCAD library [NopSCADlib](https://github.com/nophead/NopSCADlib/tree/master).

![Main Assembly](assemblies/main_assembled.png)

<span></span>

---
## Table of Contents
1. [Parts list](#Parts_list)
1. [Roll Assembly](#roll_assembly)
1. [Handle Part1 Assembly](#handle_part1_assembly)
1. [Handle Part2 Assembly](#handle_part2_assembly)
1. [Optional MainBody Assembly](#optional_mainBody_assembly)
1. [Main Assembly](#main_assembly)

<span></span>
[Top](#TOP)

---
<a name="Parts_list"></a>
## Parts list
| <span style="writing-mode: vertical-rl; text-orientation: mixed;">Roll</span> | <span style="writing-mode: vertical-rl; text-orientation: mixed;">Handle&nbsp;Part1</span> | <span style="writing-mode: vertical-rl; text-orientation: mixed;">Handle&nbsp;Part2</span> | <span style="writing-mode: vertical-rl; text-orientation: mixed;">Optional&nbsp;MainBody</span> | <span style="writing-mode: vertical-rl; text-orientation: mixed;">Main</span> | <span style="writing-mode: vertical-rl; text-orientation: mixed;">TOTALS</span> |  |
|---:|---:|---:|---:|---:|---:|:---|
|  |  |  |  |  | | **Vitamins** |
| &nbsp;&nbsp;2&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; |  &nbsp;&nbsp;2&nbsp; | &nbsp;&nbsp; Ball bearing 608-2RS 8mm x 22mm x 7mm |
| &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; |  &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp; Heatfit insert M3 x 4mm |
| &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; |  &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp; Screw M3 cap x 10mm |
| &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;1&nbsp; |  &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp; Threaded rod M8 x 88mm |
| &nbsp;&nbsp;2&nbsp; | &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;5&nbsp; | &nbsp;&nbsp;Total vitamins count |
|  |  |  |  |  | | **3D printed parts** |
| &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;1&nbsp; |  &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;bearingSH_5_16.stl |
| &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; |  &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;bearingSH_M8.stl |
| &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;.&nbsp; |  &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;mainBodyNoShoulder.stl |
| &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;1&nbsp; |  &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;nut_5_16.stl |
| &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;1&nbsp; |  &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;nut_M8.stl |
| &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; |  &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;roller.stl |
| &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;1&nbsp; |  &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;spacer1mm.stl |
| &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;1&nbsp; |  &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;spacer3mm.stl |
| &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;.&nbsp; | &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;1&nbsp; | &nbsp;&nbsp;5&nbsp; | &nbsp;&nbsp;8&nbsp; | &nbsp;&nbsp;Total 3D printed parts count |

<span></span>
[Top](#TOP)

---
<a name="roll_assembly"></a>
## Roll Assembly
### Vitamins
|Qty|Description|
|---:|:----------|
|2| Ball bearing 608-2RS 8mm x 22mm x 7mm|


### 3D Printed parts

| 1 x roller.stl |
|---|
| ![roller.stl](stls/roller.png) 



### Assembly instructions
![roll_assembly](assemblies/roll_assembly_tn.png)

1. Insert the bearing 608 at both end of the spool cylinder

![roll_assembled](assemblies/roll_assembled_tn.png)

<span></span>
[Top](#TOP)

---
<a name="handle_part1_assembly"></a>
## Handle Part1 Assembly
### Vitamins
|Qty|Description|
|---:|:----------|
|1| Heatfit insert M3 x 4mm|


### Assembly instructions
![handle_part1_assembly](assemblies/handle_part1_assembly_tn.png)

1. Install the insert on the handle.

![handle_part1_assembled](assemblies/handle_part1_assembled_tn.png)

<span></span>
[Top](#TOP)

---
<a name="handle_part2_assembly"></a>
## Handle Part2 Assembly
### Vitamins
|Qty|Description|
|---:|:----------|
|1| Screw M3 cap x 10mm|


### 3D Printed parts

| 1 x bearingSH_M8.stl |
|---|
| ![bearingSH_M8.stl](stls/bearingSH_M8.png) 



### Sub-assemblies

| 1 x handle_part1_assembly |
|---|
| ![handle_part1_assembled](assemblies/handle_part1_assembled_tn.png) 



### Assembly instructions
![handle_part2_assembly](assemblies/handle_part2_assembly_tn.png)

1. Remove the support.
2. Install the handle with a M3x10 screw ("[a]_Handle_x.stl", piece from the original design, not included here).

![handle_part2_assembled](assemblies/handle_part2_assembled_tn.png)

<span></span>
[Top](#TOP)

---
<a name="optional_mainBody_assembly"></a>
## Optional MainBody Assembly
### 3D Printed parts

| 1 x mainBodyNoShoulder.stl |
|---|
| ![mainBodyNoShoulder.stl](stls/mainBodyNoShoulder.png) 



### Assembly instructions
![optional_mainBody_assembly](assemblies/optional_mainBody_assembly_tn.png)

1. This is an optional assembly
2. If you want to be able to remove the spool from the buffer by pulling the handler you have two choices:
3. If you're are modifying an existing buffer then you have to cut the shoulder.
4. If you're building a new buffer then you can print "mainBodyNoShoulder.stl". The shoulder has been removed on the stl.

![optional_mainBody_assembled](assemblies/optional_mainBody_assembled_tn.png)

<span></span>
[Top](#TOP)

---
<a name="main_assembly"></a>
## Main Assembly
### Vitamins
|Qty|Description|
|---:|:----------|
|1| Threaded rod M8 x 88mm|


### 3D Printed parts

| 1 x bearingSH_5_16.stl | 1 x nut_5_16.stl | 1 x nut_M8.stl |
|---|---|---|
| ![bearingSH_5_16.stl](stls/bearingSH_5_16.png) | ![nut_5_16.stl](stls/nut_5_16.png) | ![nut_M8.stl](stls/nut_M8.png) 


| 1 x spacer1mm.stl | 1 x spacer3mm.stl |
|---|---|
| ![spacer1mm.stl](stls/spacer1mm.png) | ![spacer3mm.stl](stls/spacer3mm.png) 



### Sub-assemblies

| 1 x handle_part2_assembly | 1 x optional_mainBody_assembly | 1 x roll_assembly |
|---|---|---|
| ![handle_part2_assembled](assemblies/handle_part2_assembled_tn.png) | ![optional_mainBody_assembled](assemblies/optional_mainBody_assembled_tn.png) | ![roll_assembled](assemblies/roll_assembled_tn.png) 



### Assembly instructions
![main_assembly](assemblies/main_assembly.png)

1. Screw the threaded rod in the bearingSH. Don't overthight.
2. Insert a 1 mm spacer
3. Insert the roller
4. Insert a 3 mm spacer. You might need to use a thinner or a thicker spacer such that the nut end up flush with the roller.
5. Screw the nut. Don't overthight. Make sure the roller turn freely.

![main_assembled](assemblies/main_assembled.png)

<span></span>
[Top](#TOP)
