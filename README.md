# prompt-covers

缪斯画布提示词库封面图镜像：把散落在各图床/仓库的 1,742 条提示词封面图收拢到自己的仓库，防原源下架。

- `covers/` 每张图一个文件，文件名 = 提示词 id 的清洗版。
- `manifest.json` 是对照表：id → 原始地址、文件名、大小、SHA-256。

- `prompts/muse-video-prompts.json` 提示词正文（2026-11-24 收录）：apimodels/muse-video-prompts 的 205 条全文，含原帖链接（仅作出处标注）；封面图本体见 `covers/mv001.jpg` … `covers/mv205.jpg`（有封面的 110 条），对照关系见 `manifest.json`。
