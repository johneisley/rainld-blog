---
title: 音乐
date: 2026-08-16 12:00:00
type: "music"
---

欢迎来到我的专属音乐空间，这里收集了我最喜欢的本地音乐。

<!-- 1. 手动强制引入 APlayer 的核心 CSS 和 JS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/aplayer@1.10.1/dist/APlayer.min.css">
<script src="https://cdn.jsdelivr.net/npm/aplayer@1.10.1/dist/APlayer.min.js"></script>

<!-- 2. 播放器的 HTML 骨架容器 -->
<div id="my-aplayer" style="margin-top: 20px;"></div>

<!-- 3. 初始化播放器并放入你的歌曲 -->
<script>
document.addEventListener("DOMContentLoaded", function() {
    const ap = new APlayer({
        container: document.getElementById('my-aplayer'),
        theme: '#F28500', // <--- 已经在这里为你修改成了活力橙
        listMaxHeight: '400px',
        audio: [
            { name: '搁浅', artist: '周杰伦', url: '/music/周杰伦-搁浅.mp3', cover: '/music/音乐.png' },
            { name: '春娇与志明', artist: '街道办GDC、欧阳耀莹', url: '/music/街道办GDC、欧阳耀莹-春娇与志明.mp3', cover: '/music/音乐.png' },
            { name: '烟花易冷', artist: '周杰伦', url: '/music/周杰伦-烟花易冷.mp3', cover: '/music/音乐.png' },
            { name: '一路向北', artist: '周杰伦', url: '/music/周杰伦-一路向北.mp3', cover: '/music/音乐.png' }
        ]
    });
});
</script>