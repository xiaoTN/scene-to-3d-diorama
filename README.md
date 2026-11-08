# Scene to 3D Diorama

[中文](#中文) · [English](#english)

## 中文

把一张游戏截图、风景照片或插画转化成**独立的 3D 微缩沙盘效果图**。这是一个供 AI 助手读取的 skill，重点是让山峰、峡谷、河流和建筑具有真实的空间层次，而不是把原图贴在平板上。

### 效果特点

- **只输出沙盘**：默认不拼接原图；明确提出时才做前后对照。
- **地形有高低**：识别山峰、坡地和下凹的峡谷或水潭，保持水流和地貌关系。
- **底座自由设计**：可选薄地形切片、岩石底座或浅水盆，不强制使用厚托盘。
- **保留场景辨识度**：根据输入图重建角色、地貌、色彩和光线，而不照搬其他风格参考图的内容。

### 安装

将本仓库克隆到支持 Agent Skills 的助手的技能目录。下面以 `~/.agents/skills` 为例；实际目录请参考所用助手的文档。

```bash
git clone https://github.com/xiaoTN/scene-to-3d-diorama.git ~/.agents/skills/scene-to-3d-diorama
```

Windows PowerShell：

```powershell
git clone https://github.com/xiaoTN/scene-to-3d-diorama.git "$HOME\.agents\skills\scene-to-3d-diorama"
```

助手在启动时加载技能的情况下，安装后可能需要新建或重启会话。

### 使用

上传或指定一张图片，然后对支持**参考图编辑**的助手说：

> 使用 scene-to-3d-diorama，把这张风景图做成独立的 3D 微缩沙盘。山峰要突出，河谷要下凹，底座按场景设计。

也可以提出材质、视角、底座形状或画面比例等偏好。技能指导助手调用可用的图像编辑能力，本仓库不包含图片生成模型或 API 密钥；实际输出是**沙盘效果图**，不是可打印的 3D 模型文件。

### 素材与授权

请使用你有权处理的图片。生成图并不会自动获得原素材或其中人物、游戏、美术内容的商用授权。公开发布或商用前，请确认素材权利、平台 AI 标识规则和品牌方要求。仓库不包含游戏截图或此前的品牌合作素材。

## English

Create a **standalone 3D miniature diorama image** from a landscape photo, game screenshot, or illustration. This Agent Skill guides an image-capable assistant to build visible terrain relief, recessed valleys and pools, and scene-appropriate bases—rather than placing a flat picture in a tray.

### Install

Clone into your assistant's Agent Skills directory; `~/.agents/skills` is an example and the actual path depends on your assistant.

```bash
git clone https://github.com/xiaoTN/scene-to-3d-diorama.git ~/.agents/skills/scene-to-3d-diorama
```

Start a new session if your assistant loads skills at startup.

### Use

Provide a source image and ask:

> Use scene-to-3d-diorama to turn this image into a standalone miniature diorama. Emphasize the raised peaks and recessed valleys; design a base that suits the scene.

The assistant needs an image-generation tool with reference-image editing. This repository contains instructions, not a model or API key. Outputs are generated **images**, not 3D meshes.

Use only source material you have rights to process. Check permissions, platform AI-disclosure requirements, and client approval before publication or commercial use. No game screenshots or brand campaign assets are included.

## License

[MIT](LICENSE) applies to this repository's skill instructions and documentation. It does not grant rights to third-party input images or guarantee rights in generated outputs.
