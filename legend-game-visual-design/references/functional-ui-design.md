## In-Game UI Panel References

When the user provides in-game Legend/Mir UI screenshots or empty panel frames, treat them as high-value references for functional interface design rather than marketing key art.

### Approved Circular Panels And Story Quest Art

- For 圆盘养成、八卦、神器、镶嵌、剧情任务图、NPC功能图、专属装备任务、功法或秘境解锁, read [approved-ui-story-20261110.md](approved-ui-story-20261110.md). It records 18 user-approved examples and links their original images.
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
按实际功能选择顶部标题牌、关闭按钮、导航或标签、内容区、道具格和操作按钮；保留原图已有结构，不机械补齐所有控件。
不要做成宣传海报，不要铺满火焰和粒子，不要让装饰压缩功能区域，不要把文字放在复杂背景上。
```

