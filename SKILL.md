---
name: oil-collage-avatar
description: 将人物照片或原创角色制作成怪趣、俏皮、抽象的油彩拼贴海报头像，融合不对称平面动画造型、浓烈撞色和撕纸叠层。适用于有个性的艺术头像；默认不做精致美化、写实肖像或花卉装饰。
---

# 怪趣油彩拼贴头像

生成有辨识度、有幽默感的艺术头像。默认方向是 **怪趣、俏皮、抽象、强烈个人风格**，结合油彩笔触、平面动画角色与手工拼贴。不要把照片自动变成精致漂亮的通用插画脸。用户后续指定的风格和元素优先。

## 视觉判断

- **有性格的变形**：保留人物少数标志性线索，同时大胆重构比例。可用不对称眼睛、偏斜的三角鼻子、小而歪的嘴、单边挑眉、大头小肩膀、几何化发型。选择少数有节奏的变形，不机械地在每张脸上叠满所有效果。怪得有趣、表情灵动，不要恐怖化或丑化羞辱。
- **油彩与平面动画**：脸和头发用简单大色块塑造，有厚颜料刮痕、粗笔触、干刷断点；不靠真实光影雕琢皮肤。避免通用动漫大眼、精致唇形、柔美时尚插画和光滑 3D。
- **真实可见的拼贴**：不同形状的手绘纸片组合成画面，边缘有剪切、撕裂纤维、纸张叠压和少量投影。可以有错位的五官纸片，不只是给完整插画加颗粒滤镜。
- **浓烈但有秩序的配色**：用两三种主色控制大块面积，再加强调色与少量奶白、黑色。钴蓝、番茄红、酸黄、翡翠绿、玫红、淡紫均可。丰富来自色块关系与冷暖碰撞，不是遍布彩虹渐变。
- **装饰简洁古怪**：优先考虑棋盘格、歪条纹、涂鸦、螺旋、不规则星形、印刷碎片等抽象剪贴语言。留出呼吸空间，不堆满所有元素。默认不用花朵、叶片或植物花框；只有用户明确要时再加入。
- **头像构图**：默认正方形、无文字，脸与发型轮廓是焦点，核心表情处于中央圆形裁切安全区。允许局部不对称，但小图仍要清楚。

## 照片与风格参考

查看照片并识别实际朝向；横倒照片默认转正，保留自然头部倾斜。提取脸型、眼形、发型、眼镜、表情等少数可见特征，不推断身份或性格。

用户照片是唯一的 **identity source / edit target**；其他示例只能是 **style reference**。参考示例的画法与拼贴逻辑，不复制示例人物长相。大胆变形也要留下属于本人的线索，例如独特的发型轮廓或微笑方式，而非换成随机卡通人物。

如果用户要求“更像本人”，减少比例变形并强化标志性线索；如果说“太漂亮、没特色”，改变造型比例、表情和构图，而不只是增加颜色或颗粒。如果说“更抽象”，减少面部细节并增强几何化；如果说“更俏皮”，优先改表情、姿态和错位节奏。

## 生成方式

优先使用可用的内置图像生成／编辑工具。照片任务真实传入照片；对本地图片先查看，再按工具要求传入路径。可以遵循当前 imagegen 技能的操作规范。不用代码滤镜、SVG 或文字描述替代用户要的成图。

已有失败版本是需要避免的问题样本，不要自动把它作为风格参考重新传入，防止继承精致脸、花卉或写实构图。已确认的参考图才作为视觉锚点。没有照片但只需示意时直接创建原创角色；明确要求本人头像却缺照片时才索要照片。

按实际输入改写以下提示词骨架，不能原样遗留变量：

> Create a weird, playful, abstract oil-painted paper-collage avatar. The personal photo is the only identity source. Preserve [distinctive visible cues] while boldly reinterpreting the person as an eccentric flat 2D animation character. Use [a few deliberate proportional distortions] and [playful expression]. Simple chunky facial planes, opaque oil pigments, blunt brushwork and dry-brush skips. Assemble visibly separate cut-paper shapes with torn edges, small overlaps and shallow paper shadows. Use [dominant colors] plus [accent colors], clear hierarchy and some breathing room. Optional [selected geometric collage accents]. Keep the expression readable in a circular crop. No generic beauty illustration, no glamorous anime eyes, no realistic skin, no smooth 3D shading, no flowers or botanical framing, no unsolicited text or watermark. Offbeat and mischievous, not frightening.

## 检查与交付

查看结果：是否真正怪趣而非漂亮模板脸？是否有油彩的平面角色与可见拼贴层次？配色是否强烈但有主次？是否仍有照片里本人的辨识线索？是否误加了花卉？针对最关键的问题修正，避免无目的重复生成。

直接展示图像并简短说明变化。保存最终图与可复用提示词，保留原照片，后续版本用新文件名。创建或上传技能包只包含通用说明；用户原照片和个人头像不自动加入公开或私有仓库，发布个人素材需单独明确请求。
