# 3D_gltf_threejs
创建一个能快速加载的三维模型世界

## 为什么使用gltf

1️⃣ 更快传输

2️⃣ 更快渲染

## GLTFLoader

```js
简化版：

import {GLTFLoader} from 'three/addons/loaders/GLTFLoader.js'

{
  const gltfLoader = new GLTFLoader();
  const url = 'resources/models/cartoon_lowpoly_small_city_free_pack/scene.gltf';
  gltfLoader.load(url, (gltf) => {
    const root = gltf.scene;
    scene.add(root);
    ...
  });
```

