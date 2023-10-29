# RT-Less：A RGB Dataset for 6D Pose Estimation of **R**eflective **T**exture-**L**ess Object

----

[Xinyue Zhao,](https://person.zju.edu.cn/0012074)[Yue Chao,](https://github.com/transcend-lzy/RTL-toolbox)[Quanzhi Li,]()[Quanyou Wang,]()[Zaixing He*](https://person.zju.edu.cn/zaixinghe)

- A Multi-Scene Image Dataset for Pose Estimation
- **Large public unique dataset:** RTL contains 258K real and synthetic images of reflective texture-less metal parts.
- **Multiple scenes:** The scene setup contains many variables to simulate real scene and provide varying levels.
- **Industrial multi-view acquisition:** Camera placement uses the eye-in-hand method to simulate a real industrial view.
- **Ground truth pose & bounding-boxes:** Accurate annotations for each object are provided.
- **Various CAD models:** Three types of formats of CAD models were provided to assist training.

## **OBJECTS**

![img](https://cdn.jsdelivr.net/gh/lqz123/ImageBucket/images/obj.png)

38 reflective texture-less machined parts with typical industrial features.

## **SCENES**

![scene](https://cdn.jsdelivr.net/gh/lqz123/ImageBucket/images/scene.png)

32 scenes simulate real scenes in terms of parts placement, parts types and shape, lighting, background, etc.

## USAGE

Training modes

- Use CAD models only without real images for training.
- Use real images for training (CAD models are optional).

Testing modes

- Use object detection simulation module to test the pose estimation method only.
- Use build-in real object detection module to test the object detection and pose estimation methods as a whole.

Scene groups

- Few occlusions and clutters scenes: 1, 3, 7, 11, 13, 15, 16, 20, 24, 28, 29, 31, 32
- Slight occlusion and few clutters scenes: 6, 5, 12, 15, 17, 22, 24, 25, 26, 27
- Severe occlusion and clutter scenes: 2, 4, 8, 9, 10, 14, 18, 19, 21, 23, 27, 30

Toolbox

[Some python scripts to help you understand and use RTL](https://github.com/transcend-lzy/RT-Less-toolbox)

## DOWNLOAD

CAD Models

| [Sldprt models](https://1drv.ms/u/s!AiwRMXEmaB9whzonwjXK0uDWjaYM) | [Ply models](https://1drv.ms/u/s!AiwRMXEmaB9whzonwjXK0uDWjaYM) | [Stl models](https://1drv.ms/u/s!AiwRMXEmaB9whzonwjXK0uDWjaYM) | [models BOP format](https://1drv.ms/u/s!AiwRMXEmaB9whzonwjXK0uDWjaYM) |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |

Infos

| [obj_infos](https://1drv.ms/u/s!AiwRMXEmaB9whzUnwjXK0uDWjaYM) | [scene_infos](https://1drv.ms/u/s!AiwRMXEmaB9whzYnwjXK0uDWjaYM) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

Objects

| [Objects Real(512×512)](https://1drv.ms/f/s!AiwRMXEmaB9wh2onwjXK0uDWjaYM) | [Objects Render(512×512)](https://1drv.ms/f/s!AiwRMXEmaB9whzwnwjXK0uDWjaYM) | [Objects Real(2448×2048)](https://1drv.ms/f/s!AiwRMXEmaB9wiEInwjXK0uDWjaYM) |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |

Scenes

| [Scenes Real(512×512)](https://1drv.ms/f/s!AiwRMXEmaB9wiAMnwjXK0uDWjaYM) | [Scenes Real(2448×2048)](https://1drv.ms/f/s!AiwRMXEmaB9wiCwnwjXK0uDWjaYM) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |