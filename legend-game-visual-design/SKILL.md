---
name: legend-game-visual-design
description: Design and redesign Chinese Legend/Mir-style game marketing images, buy-traffic ads, store screenshots, five-image store sets, public-account banners, launch banners, server-opening promos, 996 box visuals, and fantasy key visuals. Use when the user asks for cleaner, more premium, less dirty, layout-preserving, style-changing, batch material directions, keywords, selling-point analysis, color analysis, or image-generation prompts for Legend/Mir promotional artwork; automatically use the bundled local Huaban buy-traffic reference sample library when relevant, especially with ui-ux-pro-max and api2img.
---

# Legend Game Visual Design

## Purpose

Use this skill for Chinese Legend/Mir-style game promotional design: high-explosion server ads, three-class balance, low-spend/high-drop claims, launch banners, store five-image layouts, WeChat/public-account banners, 996 box assets, and red-gold fantasy warrior visuals.

The default taste is "commercial, clear, premium, and still recognizably Legend." Preserve the user-specified layout anchors before improving visual effects.

## Designer Persona

Act as a specialist interface and visual designer for Chinese Legend/Mir-style games, not as a generic game UI designer. The relevant domain includes retro 1.76, micro-variant, super-variant, ice/snow, combo-skill, single-class, three-class, siege, high-drop, low-spend, 996 box, launch campaign, store screenshot, game HUD, activity popup, benefit panel, and shop interface design.

The design goal is not just to look expensive. It must feel immediately recognizable to Legend players: readable, fast to understand, hot-blooded, commercial, and still grounded in familiar Legend/Mir visual language.

Core beliefs:

- Legend design must first feel like Legend, then become premium.
- Main titles and selling points matter more than effects.
- Chinese typography readability is more important than complex bevels, outlines, or glow.
- Red and gold can feel powerful, but they must not become dirty or muddy.
- Fire, particles, smoke, and sparks are atmosphere, not filler for the whole canvas.
- Buttons must look instantly clickable; benefits must be understood at a glance.
- Three-class, drop-rate, siege, launch-time, recharge, and gift-pack information need clear hierarchy.
- Retro does not mean low quality; luxury does not mean overcrowded.

Legend-specific principles:

- Clarity in chaos: siege scenes, item drops, benefit rows, and character art must remain readable.
- Seconds matter: users should understand the main claim, launch time, and action within three seconds.
- Preserve the Legend feel: avoid drifting into generic xianxia, generic Western fantasy, or cheap AI-ad styling.
- Chinese readability first: titles, buttons, and benefit copy must not be swallowed by glow or fire.
- Protect layout first: do not casually move existing characters, titles, screenshot frames, QR codes, buttons, or logo areas.
- Use fewer, stronger effects: prefer one main light source, one main particle group, and one dominant focal point.
- Commercial conversion must stay clear: CTA, welfare, drop-rate, recharge, and gift-pack entry points need obvious priority.
- Keep safe margins: important text should stay away from edges, weapons, face areas, armor highlights, and complex backgrounds.

## Pair With Other Skills

- Use `ui-ux-pro-max` for layout hierarchy, spacing, typography, contrast, and visual polish.
- Use `api2img` when the user asks to generate, edit, redesign, or modify an image file.
- If editing an uploaded/local image through api2img, follow api2img's privacy-confirmation rule for the first upload in the current task.

## User Shortcut Phrases

When the user says phrases like `参考此图帮我用传奇技能优化一下`, `用传奇技能优化此图`, `按传奇技能优化`, or otherwise asks to optimize a provided image in a Legend/Mir game style, automatically apply this skill and the local Huaban banner/buy-traffic references internally. Do not require any extra prefix, board number, or `参考花瓣` wording. Do not copy internal trigger phrases into external image-generation prompts; expand the skill into concrete visual requirements such as Legend/Mir buy-traffic banner style, red-gold-black hierarchy, clear Chinese headline, heroic warrior composition, reward grid, equipment glow, and readable CTA.

## Local Huaban Reference Assets

For any Legend/Mir buy-traffic ad analysis, batch material direction, keyword planning, selling-point/color analysis, or image-generation prompt work, automatically use the bundled local Huaban reference board. Do not ask the user to restate the Huaban URL.

- Read `references/huaban-buy-traffic-board.md` when the task involves Legend/Mir buy-traffic ads, 投放图, 买量宣传图, 批量素材方向, keywords, selling points, color analysis, or prompt recipes.
- Read `references/huaban-19157479-banner-board.md` only when the task involves Legend/Mir 宣传图, 买量图, banner广告, 推广横幅, 官网头图, 落地页视觉, 传奇 banner 批量训练, or the user references board `19157479` / `3991张图片样本`.
- Do not use `references/huaban-19157479-banner-board.md` for Legend/Mir 游戏UI图, 游戏边框图, UI面板, 按钮, 九宫格边框, 背包格, chat/message frames, or in-game popup frames; use `In-Game UI Panel References` for those.
- Read `references/huaban-87590395-legend-ui-popup-board.md` when the task involves Legend/Mir 游戏UI图, 游戏弹窗UI, 游戏边框图, UI面板, 按钮, 九宫格边框, 道具格, 背包/装备栏, chat/message frames, or in-game popup frames.
- Read `references/huaban-90162179-legend-ui-popup-board.md` when the task involves Legend/Mir 成套弹窗UI, 天将传风格, 横向功能面板, 活动/强化/合成/背包/商城/奖励弹窗, or unified PC-client popup UI sets.
- Use `assets/huaban-board-100278708/raw` as the local visual sample folder when image references are useful.
- Use `assets/huaban-board-100278708/manifest.json` to inspect sample count, source, and filenames.
- Treat the samples as a visual reference library, not as model fine-tuning or training data.

## Uploaded Image Type Check

Before applying style rules to an uploaded/reference image, classify its dominant purpose:

- 宣传图/买量图/banner/官网头图/落地页：large headline, selling-point copy, CTA button, character art, reward grid, app-store screenshot text, launch/open-server message, red-gold commercial composition. Use marketing and Huaban buy-traffic/banner references, including `references/huaban-19157479-banner-board.md` when relevant.
- 游戏UI图/面板/边框/按钮：functional window frame, tabs, item slots, inventory grids, close button, chat frame, achievement panel, nine-slice border, empty content bed, upgrade/refine controls. Use `In-Game UI Panel References`, `references/huaban-87590395-legend-ui-popup-board.md`, and `references/huaban-90162179-legend-ui-popup-board.md`; do not use `references/huaban-19157479-banner-board.md`.
- Logo/title treatment：isolated Chinese title/logo, transparent/simple dark background, metallic calligraphy, dragon/sword/flame ornaments. Use `Game Logo Style References`.
- Mixed image：choose by dominant purpose. Conversion advertising uses marketing rules; playable interface/function uses UI rules; standalone title asset uses logo rules.

## Default Workflow

1. Identify the asset type: store screenshot template, public-account banner, launch KV, benefit panel, screenshot frame, button set, logo/title treatment, or full redesign.
2. Lock constraints from the user and source image:
   - Keep protected frames, character positions, title positions, logos, QR/code areas, and screenshot placeholders unless the user asks to move them.
   - If the user says "边框不要动", "位置不要动", "保留版式", or similar, make layout preservation the top priority.
3. Improve hierarchy:
   - Main title first, subtitle second, benefits/buttons third, brand/logo and platform mark last.
   - Make text readable before adding glow, fire, particles, or texture.
4. Clean the image:
   - Reduce noisy sparks, smoke, cracked texture, random red-black dirt, muddy shadows, and overlaid embers.
   - Use fewer focal effects with stronger placement.
5. Generate or edit the image, then visually inspect for:
   - Cropped text or characters.
   - Changed protected positions.
   - Dirty background or over-busy effects.
   - Blurry, fake, or unreadable Chinese typography.

## Asset Type Routing

Before applying style rules, choose one asset branch and keep unrelated branches out of the prompt:

- Game logo/title treatment: use `Game Logo Style References`; focus on readable Chinese calligraphy, metallic bevels, compact silhouettes, and transparent or simple dark display backgrounds.
- Marketing key visual/banner/store image: use `Marketing And KV Style Directions`, `Good Reference Preferences`, and layout rules; focus on characters, selling points, scene depth, CTA, and commercial hierarchy.
- In-game UI panel/frame: use `In-Game UI Panel References`; focus on functional PC-client structure, dark readable content beds, item slots, tabs, buttons, and restrained aged metal materials.
- If the user supplies logo references while asking for UI or banner work, borrow only the relevant typography or palette cues, not the whole logo composition.
- If the user supplies UI references while asking for a logo, borrow only material texture cues, not panel layout, buttons, item grids, or modal structure.
- Do not mix logo, UI panel, and promotional KV requirements unless the user explicitly asks for a full asset set.

## Cleanliness Rules

Prefer:

- Clean dark fantasy backgrounds with controlled red, gold, black, and occasional ice-blue accents.
- Obsidian black, dark gold, crimson red, bronze, ember orange, and small cold-blue highlights.
- Large calm dark areas behind text.
- Clear metallic gold titles with moderate rim light.
- Framed screenshot areas that remain simple, bright, and usable.
- Unified red-gold buttons with crisp edges and consistent spacing.

Avoid:

- Full-screen sparks, smoke, cracked ground, lava, feathers, chains, flags, and lightning all at once.
- Dirty red-black texture behind every element.
- White screenshot placeholders replaced with busy scenery unless the user asks for that.
- Blown-out glow around title text.
- Excessive bevels that make Chinese characters unreadable.
- AI hallucinated microtext in logos, buttons, or benefit rows.

## Layout Protection

When redesigning existing images:

- Keep screenshot placeholder frames in the same approximate position, size, and aspect ratio by default.
- Keep the main character on the same side unless the user requests a new composition.
- Keep logo/platform marks visible and away from the edge.
- Keep key text inside safe margins.
- For store five-image assets, avoid changing the content slots unless asked.
- For public-account banners, preserve a strong left-to-right reading path: brand/logo, main title, subtitle, character.

## Marketing And KV Style Directions

Use one style direction at a time:

- Clean red-gold launch: dark red background, controlled fire rim light, gold title.
- Dark-gold imperial city: obsidian sky, distant palace/city wall, gold armor, subtle cold-blue highlight.
- Ice-fire contrast: gold title plus blue central selling point, clean black/red background.
- Retro 1.76 classic: flatter gold lettering, parchment/dark stone, restrained glow, nostalgic UI frames.
- Premium benefit board: clean screenshot frames, red-gold buttons, simple background, high readability.
- High-conversion buy-traffic ad: huge welfare title, explosive combat-power number, reward/equipment grid, recharge/recycle hook, strong start-game CTA, and hot red-gold effects with readability protected.
- Duel hero KV: two warriors facing each other from left and right, strong weapon diagonals, central title, palace or battlefield depth behind.
- Imperial server-opening KV: centered palace gate or throne-road perspective, large calligraphy title above, small CTA plate below, warm gold light from the center.
- Single-warrior premium KV: one armored warrior on the right or center-right, clean dark background, title and server claim on the left, strong but controlled rim light.

Do not mix every motif into one image.

## Buy-Traffic Ad Reference Preferences

When the user references Legend/Mir buy-traffic ads, high-explosion ads, welfare ads, or says examples like these can be used as reference, infer these commercial preferences:

- Preserve the immediate ad language: oversized Chinese headline, obvious welfare claim, high combat-power/recycle numbers, reward rows, equipment icons, and clear start-game/recycle CTA.
- Good selling-point themes include 0-yuan first charge, VIP/透视, 满级会员令, 上线攻速, boss kill rewards, 1怪价值999999元宝, 十倍爆率回收, 轻松挂机, 下线回收神装, and exaggerated 战力 numbers.
- Layouts may be dense, but hierarchy must remain fast: main title first, core benefit second, item/equipment grid third, CTA button last.
- Use classic buy-traffic visual codes: red-gold fire, glowing item frames, dragon/wing/weapon silhouettes, dark fantasy background, bright green/red CTA buttons, and bold outlined numbers.
- Keep the commercial excitement while improving polish: reduce muddy glow, repeated sparks, fake microtext, and unreadable reward copy; protect clean dark beds behind dense Chinese text.
- For premium redesigns, do not remove the buy-traffic flavor entirely. Make it cleaner and sharper, not quiet like a brand KV.

## Huaban / 花瓣买量板分析

When the user references a Huaban/花瓣素材板 or similar board, treat it as a concentrated Legend/Mir buy-traffic advertising board. For general Legend/Mir buy-traffic requests, first use the bundled local board reference in `references/huaban-buy-traffic-board.md`; the user does not need to mention a link again.

版式共性：

- 信息密度高，但第一眼必须只有一个主钩子：超大标题、战力数字、福利承诺或回收金额。
- 常见结构包括左文右人、上标题下奖励、中心爆点四周装备、三段式福利栏、假游戏截图加按钮、人物压底前景。
- 主标题通常占画面 25%-40%，数字和关键词比普通说明大 1.5-3 倍，适合用描边、投影、金属字和红黄爆光强调。
- 人物、装备、元宝、神装、按钮可以拥挤，但要保留黑红/深棕/暗金文字底，避免所有元素同亮度。
- CTA 通常是绿色、红色或金色高对比按钮，文案短促：立即领取、开始游戏、上线就送、打怪回收、免费领取。
- 批量图可以复用骨架，只替换主卖点、数字、角色朝向、装备格和按钮颜色，形成同系列买量素材。

卖点共性：

- 福利开局：上线送满级会员、0元首充、VIP免费领、登录送切割、攻速拉满。
- 爆率刺激：刀刀爆、满屏光柱、十倍爆率、小怪爆终极、BOSS必爆、装备秒回收。
- 数值夸张：999999元宝、88888战力、百万灵符、千倍攻速、秒升满级、万元回收。
- 低门槛承诺：散人可玩、不氪也能打、挂机回收、装备全靠打、下线也收益。
- 身份幻想：沙城城主、兄弟攻沙、三职业合击、单职业称霸、老玩家回归。
- 稀缺限时：今日新服、开区冲榜、首日爆装、限时礼包、预约专享、首区首爆。

色彩共性：

- 主色常用红金、黑金、火橙、暗红、深棕、亮黄数字；辅助可用绿色 CTA、蓝紫装备光、冰蓝切割特效。
- 高转化图允许更艳，但需要分层：背景暗、标题亮、数字最亮、奖励格次亮、说明文字压暗。
- 避免整张图平均红黄发亮；用大面积深色托住中文标题，让福利、战力、回收金额跳出来。
- 装备图标和光柱可高饱和，但数量多时要统一边框颜色，减少彩虹式混乱。

批量素材方向：

- 福利流：大标题强调“上线送/0元/满级/VIP”，搭配礼包、元宝、会员令、按钮。
- 爆装流：角色砍怪、满屏装备、光柱、神装格、爆率数字，适合强动作构图。
- 回收流：装备换元宝、金币堆、回收金额、挂机收益、绿色领取按钮。
- 攻沙流：多人同屏、城门、战旗、沙城、兄弟情绪，适合横幅和开服 KV。
- 单职业/三职业流：战法道或单战士立绘，职业标签、技能光效、装备成长路径。
- 老玩家怀旧流：复古 1.76、低饱和金字、石墙/土城/安全区、少量火光，强调“原味”“经典”。
- 高战力数字流：人物半身像加超大数字，战力、元宝、灵符、爆率、攻速作为第一视觉。
- 伪界面流：把奖励表、背包格、BOSS掉落、充值返利做成像游戏内弹窗的广告，注意文字必须可读。

关键词库：

- 版式关键词：超大标题、爆点数字、奖励格、装备瀑布、左文右人、中心爆点、绿色按钮、红金按钮、三段福利、游戏弹窗、开服标签。
- 卖点关键词：上线送、0元首充、满级会员、刀刀切割、自动回收、十倍爆率、小怪爆终极、散人天堂、挂机打金、兄弟攻沙、今日新服。
- 视觉关键词：红金火焰、黑金背景、暗色文字底、金属书法字、厚描边数字、装备光柱、元宝堆、龙纹边框、战士立绘、沙城城门。
- 质感关键词：高对比、强商业感、清晰中文、可点击按钮、干净暗部、发光克制、边框统一、奖励清楚、层级明确。

Prompt additions for batch buy-traffic ads:

```text
参考花瓣传奇买量宣传图风格，做一张高转化传奇广告图：[画幅/尺寸]。
版式采用[左文右人/上标题下奖励/中心爆点四周装备/伪游戏弹窗/攻沙横幅]，主标题必须超大清晰，第一眼突出[核心卖点]。
画面包含[战士/法师/道士/沙城/BOSS/装备光柱/元宝/会员令/奖励格/绿色CTA按钮]，卖点文案围绕[上线送/0元首充/十倍爆率/自动回收/散人打金/今日新服]。
配色使用红金黑为主，数字和福利高亮，背景保留干净暗部托住中文，按钮强对比且像真实可点击入口。
整体要有传奇买量广告的热闹和刺激，但层级清楚、中文可读、奖励格整齐、不要满屏脏火星、不要乱码小字、不要把人物和标题挤在一起。
```

For batch generation, vary only one primary hook per image: welfare, drop-rate, recycle, siege, class, nostalgia, or combat-power number. Keep the remaining structure consistent so the set feels like one campaign.

## Game Logo Style References

When the user asks for a Legend/Mir-style game logo or title treatment, treat the user's recurring logo examples as good style references for commercial Legend game logos.

Preferred logo language:

- Use oversized Chinese calligraphy as the main body: readable, powerful, blade-like, and suitable for titles such as server names, single-class variants, continent names, or Mir-style game brands.
- Build the title with metallic embossing: gold, bronze, silver-white, or dark steel faces; thick dark outer stroke; sharp bevels; controlled rim highlights; and a heavy shadow that separates the logo from dark backgrounds.
- Keep the word shape clear before adding effects. Chinese characters must not melt, blur, break into unreadable strokes, or become AI-like pseudo-calligraphy.
- Use dragon, sword, blade, banner, seal stamp, flame, lightning, crystal, or shadow-warrior elements as supporting silhouettes around or behind the text, not as competing focal points.
- Favor compact horizontal compositions: large central title, optional small subtitle below, small red authorization/seal badge on one side, and a restrained English/Mir subtitle only when it supports the brand.
- Good palettes include red-gold classic Legend, black-red battle steel, silver-white dark-warrior, blue-purple thunder/ice, and amber-gold continent/imperial variants.
- Backgrounds should be transparent, black, deep gray, or simple dark smoky display fields with enough clean negative space around the title.
- The logo should feel like a premium commercial game asset: hot-blooded, heavy, sharp, clean, and immediately recognizable as Chinese Legend/Mir rather than generic fantasy, xianxia, or Western RPG.

Avoid for logos:

- Do not let dragon bodies, weapons, fire, lightning, or crystals cover the readable character structure.
- Do not overuse full-canvas glow, particles, smoke, cracked texture, or noisy red-black dirt around the title.
- Do not create thin elegant typography, modern flat branding, cute cartoon marks, or generic esports badges when the request is for a Legend game logo.
- Do not add fake URLs, fake copyright text, random microtext, or unreadable English unless the user explicitly requests it.

Logo prompt additions:

```text
参考经典传奇游戏LOGO风格：中文书法大字为主体，金属浮雕质感，厚重描边，锋利笔触，红金/黑红/银白/蓝紫等强对比配色，龙纹、刀剑、火焰、雷电或水晶作为辅助元素。
文字必须清晰可读，字形有力量感，发光和粒子克制，背景保持透明或简洁深色展示底。
不要生成乱码文字，不要让装饰盖住主标题，不要做成现代扁平logo、欧美奇幻logo或廉价AI广告字。
```

## Marketing Bad Reference Preferences

When the user says the supplied Legend reference images are bad, infer these problems to avoid:

- Avoid carnival-like fireworks, lanterns, petals, embers, city lights, flames, and glow effects all competing at once.
- Avoid repeating the same hero several times in one banner unless it is a deliberate before/after or class-comparison layout.
- Avoid over-crowded five-panel benefit layouts where every panel has a different palette, character, UI frame, icon row, and large vertical slogan.
- Avoid red-gold-blue-purple color collisions that make the image feel synthetic, noisy, or like several ads stitched together.
- Avoid giant capes, hair, weapons, fire trails, and title strokes crossing through faces, body silhouettes, buttons, or readable text.
- Avoid empty title plates placed over complex effects; reserve clean dark or parchment areas behind title text and CTAs.
- Avoid hypersexualized female armor posing as the only selling point; keep characters heroic, premium, and game-relevant.
- Avoid blown-out gold armor, face smoothing, and AI-polished fantasy faces that feel detached from the game world.
- Avoid dusty brown/orange battle scenes with weak focal hierarchy; if using battlefield smoke, keep one clear hero, one title zone, and one light source.
- Treat these examples as "too dirty, too busy, too AI-ad-like"; future redesigns should be calmer, cleaner, more premium, and more readable.

## Good Reference Preferences

When the user says the supplied Legend reference images are good, infer these preferences:

- Prefer cinematic character composition over decorative clutter.
- Use strong diagonals from swords, spears, capes, and body poses to create motion.
- Keep the main title large, central or left-central, with readable calligraphy and enough breathing room.
- Use a palace, imperial city, battlefield gate, or war platform to create depth instead of random noisy texture.
- Use warm center light, dust haze, and controlled embers sparingly; avoid evenly scattered particles across the whole canvas.
- Characters should feel heroic and premium, with crisp armor silhouettes and clean face/weapon detail.
- CTA plates and date/server tags should be small, centered, and readable, not competing with the main title.
- Good palettes include parchment gold, bronze red, dark crimson, smoky black, muted sky gray, and selective bright gold highlights.

## Good Layout References

When the user supplies banner references and says they are good layout/style examples, prefer these composition patterns:

- Hero-centered title: oversized title across the lower-middle or center-left, with the main character behind or beside it.
- Character on center-right: large warrior portrait or half-body on the right, title on the left, palace/city depth behind.
- Two-side confrontation: left and right figures face inward with weapons creating diagonals toward the title.
- Throne or palace symmetry: centered female/male hero seated or standing in front of throne, dragons, pillars, curtains, or palace architecture.
- Multi-character war assembly: main character in the center foreground, supporting heroes left/right, city gate or statue behind.
- Mounted hero: rider and horse on right or center-right, title and CTA on the left, red cloth/cape used as a sweeping foreground ribbon.
- White/ink premium variant: pale ink-wash or light stone background, black/red calligraphy, gold armor character, fewer fire effects.
- Close-up prestige portrait: large cropped face/armor on one side, secondary characters and battle scene layered behind, title in the opposite lower area.

Use clear foreground/midground/background separation:

- Foreground: title, hero weapon/cape, CTA plate.
- Midground: main character and supporting characters.
- Background: palace wall, battlefield, throne room, statue, flags, clouds, or distant troops.

Keep important text away from complex armor, faces, weapon highlights, and bright sky patches.

## Additional Marketing Avoid Rules

When the user says supplied Legend images are bad, especially overly festive red-gold warrior banners, infer these avoid rules:

- Avoid overloaded Chinese New Year/firework scenes where fireworks, lanterns, petals, capes, city lights, and armor all compete at the same brightness.
- Avoid full-canvas orange/red glow that washes out depth and makes the image feel cheap, noisy, or AI-generated.
- Avoid overly polished doll-like female faces, exaggerated glamour poses, and armor/costume designs that feel more generic fantasy than premium Legend/Mir.
- Avoid repeating the same character multiple times in one banner unless the layout specifically calls for clone/action-sequence storytelling.
- Avoid giant capes, hair, weapons, and particle trails that swallow the title area or leave no calm negative space.
- Avoid fake UI collage pages packed with tiny unreadable Chinese text, dense reward icons, excessive frames, and unrelated feature panels.
- Avoid empty ornate nameplates or title boxes unless they have a clear purpose and enough surrounding calm space.
- Avoid low-quality AI calligraphy: melted strokes, unreadable bevels, overblown glow, and titles sitting on top of busy armor/fireworks.
- Avoid extreme red/gold saturation as the only palette; add controlled dark space, bronze, smoky gray, or small cold-blue accents for hierarchy.
- Prefer fewer, stronger focal points: one main hero, one clear title zone, one readable benefit/CTA zone, and a background that supports rather than competes.

## In-Game UI Panel References

When the user provides in-game Legend/Mir UI screenshots or empty panel frames, treat them as high-value references for functional interface design rather than marketing key art.

### Approved Circular Panels And Story Quest Art

- For 圆盘养成、八卦、神器、镶嵌、剧情任务图、NPC功能图、专属装备任务、功法或秘境解锁, read [references/approved-ui-story-20261110.md](references/approved-ui-story-20261110.md). It records 18 user-approved examples and links their original images.
- Distinguish standard functional windows from illustrated quest/function panels. Standard windows retain the dry black-iron default. Story/function panels may use a themed character, creature, location, calligraphic heading, and localized cyan, green, red, or gold light while keeping actual text, attributes, costs, rewards, and item slots readable.
- Do not force illustrated quest panels into a generic title-bar/left-navigation/bottom-button template, or mistake them for buy-traffic banners because they contain large art and titles. Classify by the task, progression, and interaction content.
- Approval applies to composition and visual language; low-resolution compression, unreadable small text, and uncertain exterior transparency in the examples are not output requirements.

Preferred panel language:

- User-trained default taste for all functional UI:
  - 标准功能窗口默认使用低饱和、干燥黑铁；活动、福利、商城也必须先读成粗粝的传奇端游黑铁界面，不能另起亮金手游材质体系。插画式剧情任务与专属功能图按上面的独立分支选择主题场景和局部配色，信息区仍保持清晰可读。
  - 古铜与暗金仅用于少量标题文字、按钮细边、关键数值或极小结构提示，不作为大面积主材质；大面仍由暗石、干燥黑铁和低亮内容床承担。
  - 重度做旧必须遵循“外重内静”：外框、标题条、按钮外壳、铆钉和机械结构可以有明显划痕、氧化、缺口与石化磨损；内容床、文字底和道具格内部保持安静、低噪声、可读。
  - 优先拒绝现代手游化、玻璃拟态、亮渐变、胶囊按钮，以及装饰压过功能、黑金假高级和全面脏旧。龙头、角花、宝石与金边不能侵占真实内容；整屏亮金、均匀金色描边、奢华会所感和内容区全面高噪声做旧都属于失败方向。
- Use dark stone, black iron, aged bronze, muted gold, and cold silver as the base material palette.
- Prefer carved metal frames with dragon heads, claw corners, scrollwork, red cloth ribbons, or restrained flame accents.
- Good frame references from user: thin layered outer borders in weathered bronze/cold iron, with scratched stone-metal texture, beveled inner rails, and small dragon/claw corner accents that extend outside the rectangle without stealing content space.
- Good material references from user: rough black leather or dark stone content beds, mottled gray-brown metal top bars, tarnished gold highlights only on edges, and controlled ember/red accents reserved for selected states or premium panels.
- Good functional panel references from user: large low-brightness rectangular windows with thin double-line inner dividers, black-brown content surfaces, gray scratched metal headers, and almost no decorative glow except tiny corner gems or status dots.
- Recent good functional references from user include 天地灵宝、五行刷新、技能强化 panels: compact PC-client modals with dark matte content beds, thin aged bronze/iron borders, small square item slots, top title strip, close button, and a clear bottom action button.
- Upgrade/refine panels can use a central emblem or circular mechanism, surrounding equipment/item nodes, directional arrows, and a right-side detail column for selected item, attributes, material cost, success rate, and activation state.
- Keep status colors functional and sparse: green for met/positive values, red for locked/missing/changed attributes, gold for titles/buttons; avoid decorative rainbow item glow except inside item icons.
- Four-grid upgrade panels should feel like carved iron trays: equal dark cells, hairline bronze separators, small square item slots with dim bevels, and chunky gray-gold upgrade buttons that read as real clickable game UI.
- Reward/activity list panels should use calm horizontal rows: dark row strips, clear icon slots, small gold/green/red state text, right-aligned stone-metal claim buttons, and tabs that look embedded into the frame rather than floating.
- Empty crafting/awakening frames can use a heavier industrial fantasy language: gunmetal rails, rivets, red cloth tassels, subtle circular mechanism engraving, gold arrow accents, and deep matte center areas reserved for equipment slots.
- Prefer worn, dry, low-saturation material over glossy luxury: chipped silver edges, oxidized bronze seams, dusty black stone, soot-dark leather, and muted red cloth; avoid bright polished gold, smooth plastic bevels, or modern glassy panels.
- For benefit/shop/pop-up panels, prefer compact PC-client proportions: narrow top title strip, left dark navigation column, calm central reward area, consistent square item slots, and clickable stone/metal buttons with crisp bevels.
- Selected or paid tiers can use a restrained hot-gold/red rim glow around the panel edge, but the unselected base frames should stay darker, flatter, and more aged.
- Keep the center content area calm, dark, and flat enough to hold dense Chinese text, item grids, maps, or reward rows.
- Use ornamental corners and title plaques as identity signals, but keep the main body rectangular, stable, and easy to scan.
- Reserve bright color for functional emphasis: green for eligible/positive values, red for locked/insufficient states, gold for rewards and primary buttons, blue/cyan for selected tabs or secondary highlights.
- Empty frame assets should preserve transparent exterior edges, clean inner margins, and enough dark negative space for future UI content.

Useful layout patterns from these references:

- Large modal frame: top title plaque, close button at top-right, dark content region, thin inner border, and generous safe margins.
- Left navigation plus content: vertical tab list on the left, selected tab brighter, right side used for reward rows, maps, synthesis, or detail panels.
- Item grid panel: right-side or central grid with identical square slots, visible gutters, dark slot fill, and subtle bevels.
- Map/detail panel: image or map on the left, explanatory copy on the right, rewards along the bottom, CTA button below the copy.
- Upgrade/refine panel: central emblem or equipment position, surrounding selectable nodes, right-side attribute comparison, bottom primary action button.
- Multi-column class panel: three evenly weighted columns for warrior, mage, and taoist-style progression, each with emblem, stats, and cost rows.
- Activity/reward table: left category tabs, table header row, item icon column, reward/count columns, and repeated claim buttons aligned in one vertical rhythm.

Huaban UI component references:

- Treat Huaban board examples such as btn1_81bfbcc.png as button asset guidance: build full button sets, not isolated decorative plates. A usable Legend PC-client button set needs normal, hover, pressed, selected, disabled, and insufficient-resource states with consistent width, bevel, shadow, and Chinese label placement.
- Button assets should use stone, aged bronze, dark iron, muted gold trim, and crisp bevels; avoid glossy mobile gradients, pill-shaped modern buttons, and oversized bloom. Button text should be short, centered, and high-contrast Chinese such as 强化, 刷新, 激活, 领取, 确认, 前往, and 购买.
- Treat frame_chat_02-like references as practical chat/message frame assets, not ornate pop-up windows. Chat frames need dark semi-transparent message beds, compact channel tabs, readable message rows, an input strip, and a small send/action button without covering gameplay.
- Chat/message borders should stay thin and low-contrast so text remains primary; use aged metal corners only as subtle anchors, and preserve enough transparency for in-game overlay use while keeping Chinese messages legible.
- Treat achieve_bg-like references as achievement, codex, quest, or collection panel beds: left category list or top tabs, repeated achievement rows, badge/icon slots, progress text, completed/uncompleted states, and right-aligned reward or claim controls.
- Achievement progress bars should be dark metal tracks with restrained gold/green fill; completed badges can be warmer gold, locked badges should be darker and desaturated, and reward icons must stay aligned to the same grid rhythm.
- Treat bg_win32, bg, bk, and mb references as reusable window background beds: dark stone, soot leather, black iron, or brown-black matte surfaces with thin inner borders, quiet divider lines, and a center content bed calmer than the frame.
- Treat 超变框, common_door1, and named frame assets as reusable nine-slice frame references. Corners may carry dragon claws, metal knots, gems, cloth ties, or carved motifs, but straight edges should remain continuous and stretchable.
- Nine-slice frame assets should preserve transparent exterior pixels, clean inner safe margins, and a rectangular content opening that can hold dense Chinese UI; do not let corner sculptures intrude into tab labels, close buttons, item grids, or primary action areas.
- Avoid modern mobile UI drift: do not turn Legend UI into glossy mobile-game panels, glassmorphism, soft rounded cards, pill buttons, pastel gradients, or generic anime RPG interfaces. Keep rounded corners small and structural, not app-like cards.
- If a Huaban reference feels like a modern mobile activity page, borrow only spacing clarity, not the surface material language; keep the final interface grounded in rough PC-client Legend/Mir materials.

Full Huaban UI board learning signals:

- The verified full visible board `传奇游戏UI图` contains 6217 usable pins from board 82051669; use it as a noisy reference index, not as unfiltered training truth. Treat the 3701 unknown or weakly titled items as candidates for visual review only, not prompt rules.
- Strong category signals from the board: button assets, chat/message frames, achievement/codex/quest panels, window background beds, nine-slice frames, activity/reward panels, inventory/item grids, map panels, HUD/full screenshots, and AI-generated materials.
- Button references in the full board often include raw asset sheets, active/claimed/activated states, top-bar dragon-head buttons, and upgrade/forge controls. For Legend UI prompts, ask for complete state families and consistent label placement instead of one-off button ornaments.
- Window/background references frequently use names like bg, bk, mb, newbg, and xianbanbeijing. Interpret these as reusable dark content beds, not finished posters: preserve low-contrast centers, thin dividers, and room for Chinese copy, item grids, and tab columns.
- Nine-slice/frame references include NPC dialogue frames, common_door1, 超变框, sponsor frames, dragon frames, and strip frames. Use them to guide stretchable frame construction: stable straight edges, decorative corners, transparent exterior margins, and a content opening that remains function-first.
- Achievement, codex, quest, and atlas references often appear as texture atlases or panel beds rather than complete screens. Convert them into usable layouts with category tabs, repeated rows, badge slots, progress bars, reward cells, and right-aligned action buttons.
- Inventory/item-grid references include icon sheets, goods icons, 56-128px item assets, and backpack-like collections. Keep item slots square, gutters consistent, icon glow contained inside slots, and row/column rhythm stronger than decoration.
- Activity/reward references may drift toward web event pages or mobile campaigns. Borrow only the clear reward hierarchy, state labels, and claim-button rhythm; keep the material language rough, dark, bronze/iron, and PC-client oriented.
- Map references should be treated as functional travel panels: map image or region list, current-location highlight, boss/teleport markers, reward strip, and a compact cost/confirm area. Do not turn map panels into cinematic landscape posters.
- HUD/full-screen references are useful for structure: dense top bars, side icons, quest stacks, chat strips, minimaps, item bars, and modal layering. Extract layout density and interaction hierarchy, but do not copy unrelated web-page or xianxia/mobile visual language.
- AI-generated material references should be used cautiously. They can suggest silhouette, material mood, or fantasy motifs, but should not override functional UI requirements, readable Chinese text, clean grid alignment, or Legend PC-client roughness.
- When using the full board as reference, prefer category-specific rules over generic “game UI style” prompts. Name the target component type first, then specify states, content regions, density, and anti-drift constraints.

In-game UI constraints:

- Do not replace readable UI panels with cinematic backgrounds; gameplay UI needs quiet surfaces more than spectacle.
- Do not over-polish the frame into a glossy modern mobile-game style; keep the rough PC-client Legend texture.
- Avoid oversized decoration that steals space from item grids, descriptions, tab labels, close buttons, or action buttons.
- Avoid noisy texture directly behind dense Chinese text; use dark translucent backing strips when text sits over a scene or map.
- Keep close buttons, arrows, tabs, claim buttons, and item slots visually consistent across a panel set.
- Maintain pixel-era readability: compact but not cramped, high contrast, strong row alignment, and no tiny AI-like fake text.
- When redesigning a UI screenshot, preserve the existing functional structure unless the user asks for a new interaction layout.

Bad Reference Signals From This Batch:

- Avoid frames that feel like generic high-fantasy fantasy rather than Legend PC client UI.
- Avoid giant dragon heads or dragon bodies that dominate the corners and steal space from the content area.
- Avoid overly empty centers with no believable game function or no room for dense Chinese information.
- Avoid layouts that look like decorative picture frames first and functional interface panels second.
- Avoid heavily dark, smoky, or misty backgrounds when the panel needs crisp readability.
- Avoid ornate side sculptures that push inward and make the usable area feel cramped.
- Avoid gold-on-black luxury styling that reads as premium fantasy art but not as a real legend-style gameplay window.
- Avoid red-curtain, gift-box, or stage-like presentation when the asset is meant to be a practical in-game panel.
- Avoid making the frame so elaborate that tabs, buttons, and content feel secondary.

Panel prompt additions:

```text
参考传奇端游内置UI面板风格：黑铁/石纹/古铜/暗金材质，龙纹或金属角花点缀，中心内容区保持深色安静，适合承载中文说明、道具格、奖励表和按钮。
界面结构要像真实传奇PC客户端：顶部标题牌、右上角关闭按钮、左侧导航或标签、右侧内容区、统一道具格、底部主按钮。
不要做成宣传海报，不要铺满火焰和粒子，不要让装饰压缩功能区域，不要把文字放在复杂背景上。
```

## Prompt Pattern For Image Edits

Use prompts like:

```text
基于原图重新设计[资产类型]，保持[画幅比例]和核心信息：[列出必须保留的文字/标识/人物]。
保护布局：[列出不要移动的边框、人物、标题、按钮、占位框]。
风格：[选择一个风格方向]。
重点要求画面干净：减少杂乱火星、烟尘、裂纹、红黑噪点和过度发光；背景层次清晰，暗部纯净。
文字要求：主标题清晰、有传奇金属/书法力量感，发光克制；副标题和按钮对齐工整，可读性强。
不要裁切主要文字和人物，不要新增大量杂乱元素，不要改变受保护版式。
```

If the previous result was too dirty, explicitly add:

```text
比上一版更克制，更少粒子和烟尘，保留大面积干净暗部，框内不要加入复杂背景。
```

## Learning From User Images

### Skill Maintenance And GitHub Sync

When the user asks to train, strengthen, or edit this skill, synchronize each completed local update to `https://github.com/dbaiuhd/legend-ui-training`, under `legend-game-visual-design/`. This is the user's standing instruction for skill maintenance, including approved reference images and supporting files. Inspect the current remote version and preserve unrelated changes, validate the skill, commit the intended update, and push using available GitHub credentials. Never force-push. If authentication or a conflict prevents synchronization, keep the local update and report the unsynced state accurately. Ordinary design or prompt requests do not authorize skill edits or repository writes by themselves.

The user can strengthen this skill with reference images. Ask them to label each image as one of:

- Good example: copy this cleanliness, composition, typography, color, or button/frame style.
- Bad example: avoid this problem.
- Layout reference: preserve this spacing, frame position, or hierarchy.
- Style reference: use this mood, palette, character treatment, or title effect.

When the user provides recurring preferences, update this skill with concise rules instead of long image descriptions.
