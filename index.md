---
layout: post 
title: Portfolio Home 
hide: true
show_reading_time: false
---

# Welcome to My Learning Hub

Welcome to my personal GitHub Pages site! This homepage serves as a central navigation hub for my computer science journey, documenting my progress in web development, static site generation, and interactive coding.

---

## 🚀 Learning Modules & Topics

<div class="nav-grid">
  <div class="nav-card">
    <h3><a href="{{ site.baseurl }}/notebooks">🐍 Notebooks & Jokes</a></h3>
    <p>Explore JavaScript and Bash execution inside Jupyter Notebooks with interactive programming jokes and environment checks.</p>
  </div>

  <div class="nav-card">
    <h3><a href="{{ site.baseurl }}/anatomy">📁 GH Pages Anatomy</a></h3>
    <p>Understand the file architecture of a GitHub Pages project, including <code>_posts</code>, <code>_layouts</code>, <code>_data</code>, and <code>.gitignore</code>.</p>
  </div>

  <div class="nav-card">
    <h3><a href="{{ site.baseurl }}/theme">🎨 Theme Customization</a></h3>
    <p>Learn how to switch Jekyll themes using the Makefile, control layout overrides with <code>opencs.html</code>, and customize SASS/CSS styles.</p>
  </div>

  <div class="nav-card">
    <h3><a href="{{ site.baseurl }}/markdown">✍️ Markdown & HTML</a></h3>
    <p>Master Markdown shorthand and HTML fragments for clean content creation, image embedding, and hyperlink structuring.</p>
  </div>

  <div class="nav-card">
    <h3><a href="{{ site.baseurl }}/jekyll">⚙️ Jekyll & Liquid</a></h3>
    <p>Leverage Jekyll static site generation with Liquid templating constructs like variables, loops, and conditional statements.</p>
  </div>

  <div class="nav-card">
    <h3><a href="{{ site.baseurl }}/hacks">🛠️ Hacks & Challenges</a></h3>
    <p>Apply acquired web development skills, file management techniques, and custom projects into real-world code updates.</p>
  </div>
</div>

<style>
.nav-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
  gap: 16px;
  margin: 20px 0;
}

.nav-card {
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  padding: 16px;
  background-color: #fafbfc;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.nav-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
}

.nav-card h3 {
  margin-top: 0;
  margin-bottom: 8px;
  font-size: 1.15rem;
}

.nav-card a {
  text-decoration: none;
  color: #0366d6;
  font-weight: bold;
}

.nav-card a:hover {
  text-decoration: underline;
}

.nav-card p {
  margin: 0;
  color: #586069;
  font-size: 0.9rem;
  line-height: 1.4;
}
</style>
