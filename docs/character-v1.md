# CAT-001｜角色固定形象 V1

- 状态：**APPROVED — 视觉参考已由用户确认（2026-11-09）**
- 角色类型：中华田园猫，灰棕色狸花纹（非橘猫、非三花）
- 主素材：用户上传的正面、侧面、背面三视图 `生成动物图片.png`
- 主素材 SHA-256：`92693ae4e482c04b48afaf5bfdfa5a32689b6db2645b02b7d19154ee3b134295`
- 参考原图尺寸：1344 × 1792，PNG，3,566,705 bytes
- **素材状态：原图已在 ChatGPT 工作文件中保存为 `cat-001-reference-v1.png`，目前尚未提交到 GitHub；拟存放 `assets/cat-001-reference-v1.png`。** 这份说明不能代替原图本身。

## 不可变的视觉身份

1. **毛色与纹路**：暖灰棕色底毛、深灰黑色清晰虎斑；额头连续深色纵纹，面颊两侧清晰虎斑；背部与侧面有密集条纹，不得生成成橘猫或三花。
2. **白毛分布**：下巴、口鼻下侧、胸前大片白毛延伸到腹部；四爪有白色脚尖/白袜区域。不同视角必须匹配。
3. **脸部**：略圆的真实家猫脸，直立三角耳、琥珀棕色大眼、粉色鼻头；保持面部条纹、眼间距与口鼻轮廓。
4. **身体**：自然家猫比例，中等稍结实但不肥胖；猫爪、后腿、颈肩与尾巴结构须真实，不变成人手或人形身体。
5. **尾巴**：灰棕虎斑尾巴，深色环形条纹、偏深的尾尖，长度及粗细和参考图一致。
6. **默认识别配饰**：细棕色项圈，悬挂粉色花朵饰物。可按场景更换或摘除；佩戴时保持位置和样式一致。项圈不应被视为猫的生理特征。

## 可以变化

- 衣服、眼镜、耳机、背包、帽子、道具；
- 表情、姿势、背景、室内布置、镜头、光线；
- 剧情主题：工作、游戏、动漫、股票、梗、节日与日常；
- 允许适度拟人化动作，但**始终是同一只真实比例的猫**。

## 风格边界

用户确认的三视图是**带绘制质感的身份设计参考**，不是已经完成的摄影级猫咪照片。公开视频的目标风格为**拟真、真实毛发、真实猫科肢体与自然光照**，不得沿用此前的扁平卡通示意图。

使用图生视频前，先把参考图转化成拟真的首帧，并审核纹路、白毛、鼻子、眼睛、尾巴是否保真。文字提示词不足以替代三视图参考。

### 英文角色锁定描述（与参考图一起使用）

> The same Chinese domestic short-haired cat from the approved three-view reference sheet: a warm gray-brown mackerel tabby with distinct charcoal-black stripes on the forehead, cheeks, shoulders, back, sides and legs; large white chest and lower muzzle, white front paws and white rear toes; clear amber-brown eyes, pink triangular nose, upright natural cat ears, round but realistic face, healthy medium build and natural feline proportions; a gray-brown tail with bold dark rings and a dark tip. Preserve the exact coat pattern and white markings from the reference sheet across shots. Photorealistic fur texture, natural indoor lighting, realistic feline behavior, not a cartoon. A fine brown collar with a small pink flower pendant may be worn as the default accessory.

### 禁止的偏差

> No orange fur, no calico patches, no British Shorthair appearance, no exaggerated chibi/cartoon proportions, no human hands, no extra limbs, no altered iris color, no new markings, no arbitrary changes to the white chest or paws, no inconsistent tail pattern.

## 验证状态

- [x] 用户确认原始三视图为角色外形定稿依据
- [x] 视觉锁定规则写入 GitHub
- [ ] 将原始 PNG 提交到 GitHub（尚未完成）
- [ ] 生成拟真摄影风格首帧并与参考图比对
- [ ] 在短视频中验证跨镜头纹理/面部一致性

此前 `docs/character-v0.1.md` 与 `assets/cat-001-marking-map.svg` 是**已废弃的橘白候选**，保留仅用于历史记录，不能再作为生成参考。
