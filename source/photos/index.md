---
title: 我的照片
date: 2026-06-21
type: photos
---

<style>
.photo-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 16px;
  padding: 20px 0;
}
.photo-grid img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  border-radius: 4px;
  transition: transform 0.3s ease;
  cursor: pointer;
  border: 1px solid #E4E4E7;
}
.photo-grid img:hover {
  transform: scale(1.02);
}
</style>

<div class="photo-grid">
  <img src="/-blog/photos/images/b2a6e6dc75e55c805a166dfa6e47a652.jpg" alt="照片">
</div>
