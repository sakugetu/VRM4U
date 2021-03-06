# VRM4U
Runtime VRM loader for UnrealEngine4

**For packaging, please download from UnrealEngine_VRM4UPlugin repository.**

## Description
VRM4U is importer for VRM.
Also it can load models on runtime.

https://github.com/ruyo/VRM4U/wiki/VRM4U

## Features
|||
|----|----|
|![2](https://github.com/ruyo/VRM4U/wiki/images/shot/03.png)|![2](https://github.com/ruyo/VRM4U/wiki/images/shot/04.png)|
|![2](https://github.com/ruyo/VRM4U/wiki/images/shot/01.png)|![2](https://github.com/ruyo/VRM4U/wiki/images/shot/02.png)|

- Import VRM file
- Animation
    - Generate bone, blendshape, swing bone, collision and humanoid rig.
    - Switch swing bone type PhysicsAsset/VRMSpringBone.
- Material
    - MToon simulated material. No postprocess.
- Mobile
    - Vanilla UE4Editor can use VRM on mobile by using BoneMap reduction.
    - Available on Forward/Deferred.

## Requirement
 - UE4.20.3, UE4.21, UE4.22, UE4.23
 - **For packaging, please download from UnrealEngine_VRM4UPlugin repository.**

## SampleMap
- VRM4UContent/Maps/VRM4U_sample.umap
![3](https://raw.githubusercontent.com/wiki/ruyo/VRM4U/images/samplemap.png)

## Usage
 - Drag and drop VRM file.

||
|----|
|![2](https://github.com/ruyo/VRM4U/wiki/images/overview.gif)|
|[![](https://img.youtube.com/vi/Qlz0bUSLjss/0.jpg)](https://www.youtube.com/watch?v=Qlz0bUSLjss) https://www.youtube.com/watch?v=Qlz0bUSLjss|


## Author
[@ruyo_h](https://twitter.com/ruyo_h)

## License
MIT(VRM4U)

3-clause BSD-License(assimp)

### Source
https://github.com/ruyo/UnrealEngine_VRM4UPlugin ([Connecting Epic, GitHub Accounts](https://www.unrealengine.com/en-US/blog/updated-authentication-process-for-connecting-epic-github-accounts))

https://github.com/ruyo/assimp

Thanks.
