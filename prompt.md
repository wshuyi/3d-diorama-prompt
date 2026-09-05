# 3D卡通展示 v5.0

将任意图片转换为精美的3D卡通微缩场景风格。

---

## 核心方法：原图直接风格化

> [!IMPORTANT]
> **跳过文字描述，直接基于视觉信息转换**
> 避免AI根据文字产生幻觉，确保角色特征100%忠于原图

---

## 执行流程

### Step 1: 获取原图

搜索并获取一张包含目标内容的图片：

**选图标准**：

- ✅ 包含多个主角（更有故事性）
- ✅ 角色清晰可辨
- ✅ 有动态感的场景
- ❌ 不需要高清，只要内容清晰即可

**获取方式**：

- Google图片搜索 → 点击预览 → 截图
- 或直接使用已有的参考图

### Step 2: 直接风格化

使用图像生成工具，传入原图，**只描述风格，不描述内容**：

```text
Transform this into a 3D cartoon diorama.
Cinema 4D style, miniature scene on wooden display base,
45-degree isometric view, smooth rounded 3D modeling,
PBR materials, soft lighting, contact shadows,
warm cozy atmosphere.

Keep all characters exactly as they appear -
same colors, same features, same poses.
Only change the rendering style to 3D cartoon diorama.

Title "{标题}" at top center.
```

### Step 3: 验证

对比生成结果与原图，确认关键特征保留。

---

## 风格规格

| 项目 | 规格 |
| ------ | ------ |
| 渲染风格 | Cinema 4D / Blender |
| 场景类型 | 微缩立体透视模型 (Diorama) |
| 视角 | 45° 等距俯视 |
| 建模 | 圆润平滑，柔和倒角 |
| 材质 | PBR（哑光/光泽/金属/织物） |
| 灯光 | 柔和顶侧光 + 温暖环境光 |
| 阴影 | 柔软接触阴影 |
| 底座 | 圆形/方形木质展示底座 |
| 氛围 | 温馨、治愈、童话 |

---

## 红线规则

❌ **禁止文字描述角色内容** — 不要在prompt中描述"棕色野猪"、"粉色小猪"等
❌ **禁止望文生义** — 让AI看图，不是让AI读文字

✅ **必须传入原图** — 把原图作为输入
✅ **只描述风格** — prompt只写3D渲染风格要求
✅ **保持原样** — 明确要求保持原图中的所有特征
