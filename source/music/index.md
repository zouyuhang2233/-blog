---
title: 我的音乐
date: 2026-06-22
type: music
---

<style>
.music-intro {
  text-align: center;
  color: var(--color-muted);
  margin-bottom: 24px;
  font-size: 0.95em;
}
</style>

<div class="music-intro">共 10 首歌 · 点击播放</div>

<div id="aplayer"></div>
<script>
var ap = new APlayer({
  container: document.getElementById('aplayer'),
  fixed: false,
  autoplay: false,
  preload: 'auto',
  volume: 0.7,
  lrcType: 0,
  audio: [
        { name: "Улетали птицами гордыми (Remix)", artist: "7ouTp", url: "/-blog/audio/7ouTp%20-%20%D0%A3%D0%BB%D0%B5%D1%82%D0%B0%D0%BB%D0%B8%20%D0%BF%D1%82%D0%B8%D1%86%D0%B0%D0%BC%D0%B8%20%D0%B3%D0%BE%D1%80%D0%B4%D1%8B%D0%BC%D0%B8%20%28Remix%29.mp3" },
        { name: "Pretty Girl", artist: "Clairo", url: "/-blog/audio/Clairo%20-%20Pretty%20Girl.mp3" },
        { name: "你说抱歉时 我无法呼吸", artist: "Zy", url: "/-blog/audio/Zy%20-%20%E4%BD%A0%E8%AF%B4%E6%8A%B1%E6%AD%89%E6%97%B6%20%E6%88%91%E6%97%A0%E6%B3%95%E5%91%BC%E5%90%B8.mp3" },
        { name: "风驶过的声音是", artist: "Zy", url: "/-blog/audio/Zy%20-%20%E9%A3%8E%E9%A9%B6%E8%BF%87%E7%9A%84%E5%A3%B0%E9%9F%B3%E6%98%AF.mp3" },
        { name: "好喜欢你", artist: "刘俊骐", url: "/-blog/audio/%E5%88%98%E4%BF%8A%E9%AA%90%20-%20%E5%A5%BD%E5%96%9C%E6%AC%A2%E4%BD%A0.mp3" },
        { name: "夏の喚く (夏鸣)", artist: "小小君", url: "/-blog/audio/%E5%B0%8F%E5%B0%8F%E5%90%9B%20-%20%E5%A4%8F%E3%81%AE%E5%96%9A%E3%81%8F%20%28%E5%A4%8F%E9%B8%A3%29.mp3" },
        { name: "怎么办我想你", artist: "本兮", url: "/-blog/audio/%E6%9C%AC%E5%85%AE%20-%20%E6%80%8E%E4%B9%88%E5%8A%9E%E6%88%91%E6%83%B3%E4%BD%A0.mp3" },
        { name: "怎么办我爱你", artist: "本兮", url: "/-blog/audio/%E6%9C%AC%E5%85%AE%20-%20%E6%80%8E%E4%B9%88%E5%8A%9E%E6%88%91%E7%88%B1%E4%BD%A0.mp3" },
        { name: "我知道你 (1.2x版)", artist: "熊雨珂", url: "/-blog/audio/%E7%86%8A%E9%9B%A8%E7%8F%82%20-%20%E6%88%91%E7%9F%A5%E9%81%93%E4%BD%A0%20%281.2x%E7%89%88%29.mp3" },
        { name: "One Last Kiss", artist: "瞳りょこ", url: "/-blog/audio/%E7%9E%B3%E3%82%8A%E3%82%87%E3%81%93%20-%20One%20Last%20Kiss.mp3" },
  ]
});
</script>
