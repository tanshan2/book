# 卡琳娜谈话室：作者指定底图纯影调试样 V10

日期：2026-10-13；工具：内置 image_gen。

作者明确指定新附图为底图，要求保持该人物位置，在该图上叠加影调。此决定优先于V7—V9中重新摄影、改变人物角度或改脸的方案。

输入一：`assets/visual-references/karina-author-selected-scene-base-v1.png`，唯一的人物、构图、动作与空间依据。

输入二：`assets/visual-references/angelopoulos-interior-user-reference-v1.png`，仅用于滤镜和影调，不用于人物或空间。

不再输入其他人物肖像，不修脸、不改眼睛、不改角度。色彩要求仍为案例的灰绿老片影调，强烈区分灰绿、钢蓝、琥珀色，保持无噪点。

状态：影调试样，等待作者评价。图像生成无法保证逐像素仅调色，输出需核对人物和构图。

输出：`outputs/karina-conversation-room-selected-base-grade-v10.png`。

检查：人物尺度、头倾、侧向视线和基本五官关系、纸张动作、房间构图沿用作者底图。钢蓝桌面、灰绿墙面、琥珀灯光的色彩差别加强。生成仍存在局部材质与细节重新渲染，不宣称是确定性像素调色；待作者评价。

## 提示词

COLOR-GRADE-ONLY EDIT of IMAGE 1. Treat it as a finished photograph whose geometry must be preserved. Apply a post-production color treatment over this exact shot. Do not regenerate or rephotograph the scene.

IMAGE 1 is the user-selected base and is the SOLE authority for the woman, her exact face, eyes, head tilt, sideways gaze, hair, pose, body, hands, clothing, folded paper and all room objects. Keep its exact framing, perspective, subject size and object positions. The user's most important requirement is that her face and position must remain unchanged.

IMAGE 2 supplies ONLY the older European film COLOR RESPONSE: pervasive mineral grey-green, creamy silver window highlights, dense charcoal blacks, soft subdued middle tones, natural skin. Import no people or objects from IMAGE 2. Keep IMAGE 1's actual light-source locations and spatial modeling.

Overlay that older grey-green color response while creating STRONG, plainly visible COLOR DIFFERENCES: rich mineral/olive grey-GREEN wall and door; a distinct deep STEEL-BLUE tone in the existing metal tabletop and cool window reflections; clear warm AMBER/OCHRE in the existing lamp and its light on the right wall. These color families should stand apart much more clearly than in IMAGE 1 or IMAGE 2. Stronger color contrast, not harsher brightness contrast. Keep the soft older-film tone curve and green-grey foundation so it still belongs to the reference look. Natural pale skin remains faithful to IMAGE 1, not green, orange, yellow or retouched. Hair and cardigan remain deep neutral charcoal.

No facial edits of any kind. Do not modify eyelids, iris shape or placement, nose, lips, cheekbones, jaw, mole or expression. No pose changes, no reframing, no extra objects, no changed room design, no new light sources, no added blur. Clean photographic surfaces: ZERO visible grain, noise, dust, scratches, film damage or fog. No sepia, vignette, HDR sharpening, glossy beauty treatment, text or borders. A color-filter overlay on the exact supplied shot, with clearly stronger green/blue/amber color separation.

