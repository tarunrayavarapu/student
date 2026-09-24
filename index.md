---
layout: post 
title: Portfolio Home 
hide: true
show_reading_time: false
---

# Welcome to My Learning Hub

Welcome to my personal GitHub Pages site! This homepage serves as a central navigation hub for my computer science journey, documenting my progress in web development, static site generation, and interactive coding.

---

<div class="learning-section">
  <div class="section-header">
    <h2>🚀 Learning Modules & Topics</h2>
    <p class="section-subtitle">Explore the core concepts that power modern web development</p>
  </div>

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
</div>

<style>
.learning-section {
  background: linear-gradient(135deg, #e8f2f9 0%, #f0e8f9 100%);
  border-radius: 12px;
  padding: 32px 24px;
  margin: 24px 0;
  border: 2px solid #0366d6;
  box-shadow: 0 4px 12px rgba(3, 102, 214, 0.12);
  color: #000000 !important;
}

/* Force all text inside the section to be black */
.learning-section * {
  color: #000000 !important;
}

.section-header {
  margin-bottom: 28px;
  text-align: center;
}

.section-header h2 {
  margin: 0 0 12px 0;
  font-size: 2rem;
  color: #000000 !important;
  font-weight: 700;
}

.section-subtitle {
  margin: 0;
  font-size: 1.05rem;
  color: #000000 !important;
  font-weight: 400;
}

.nav-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 16px;
  margin: 0;
}

.nav-card {
  border: 1px solid #d1d9e0;
  border-radius: 10px;
  padding: 20px;
  background-color: #ffffff;
  box-shadow: 0 1px 4px rgba(0,0,0,0.06);
  transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
  color: #000000 !important;
}

.nav-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 16px rgba(0,0,0,0.12);
  border-color: #0366d6;
}

.nav-card h3 {
  margin-top: 0;
  margin-bottom: 10px;
  font-size: 1.2rem;
  font-weight: 600;
  color: #000000 !important;
}

.nav-card p {
  margin: 0;
  color: #000000 !important;
  font-size: 0.95rem;
  line-height: 1.5;
}

.nav-card a {
  text-decoration: none;
  color: #000000 !important;
  font-weight: 600;
  transition: color 0.2s ease;
}

.nav-card a:hover {
  color: #0256c7 !important;
  text-decoration: underline;
}

/* Yellow highlight for code words */
.nav-card code {
  background-color: #fff3a6 !important;
  border-radius: 4px;
  padding: 2px 6px;
  font-size: 0.9rem;
  color: #000000 !important;
  font-family: 'Monaco', 'Menlo', 'Ubuntu Mono', monospace;
  border: 1px solid #e6d45a;
}
</style>

---

## 📖 Learning Experience Design (LxD) Summary

This home page serves as a structured entry point for my web development workflow built on **GitHub Pages**, **Jekyll**, and **Jupyter Notebooks**:

* **Interactive Development with Notebooks**: By integrating `.ipynb` files, I can execute client-side JavaScript (like dynamic joke generators) and run Bash scripts directly in my local environment to test runtime dependencies (Python, Jupyter kernel specs).
* **Understanding Project Anatomy**: Managing files across directories such as `_posts` for blog content, `_notebooks` for raw code, `_layouts` for structural templates, and `.gitignore` to prevent tracking build artifacts is critical for maintaining an organized codebase.
* **Theme System & Design Customization**: Using Jekyll's theme architecture alongside `Makefile` tasks (`make use-minima`, `make use-dracula`), I can switch site skins while preserving local layout overrides (such as `opencs.html`) and runtime styling preferences powered by SASS (`_sass/minima/custom-styles.scss`).
* **Markdown & HTML Fragments**: Markdown provides a fast, human-readable format for writing documentation and course reflections, while embedded HTML fragments allow precise control over media elements, alignment, and interactive layouts like photo galleries and CSS grid cards.
* **Dynamic Static Generation with Jekyll & Liquid**: Jekyll transforms simple Markdown content into full HTML web pages during the build process. Utilizing **Liquid** templating tags (`assign`, `for`, `if`) allows for dynamic rendering of page posts, navigational menus, and custom metadata defined in frontmatter or `_config.yml`.

Organizing these links on my homepage provides an accessible structure for tracking my progress, reviewing core concepts, and applying hands-on hacks throughout the course.

## Learning Modules & Topics

Explore the core concepts that power modern web development

### [🐍 Notebooks & Jokes]({{ site.baseurl }}/notebooks)

Explore JavaScript and Bash execution inside Jupyter Notebooks with interactive programming jokes and environment checks.

### [📁 GH Pages Anatomy]({{ site.baseurl }}/anatomy)

Understand the file architecture of a GitHub Pages project, including `_posts`, `_layouts`, `_data`, and `.gitignore`.

### [🎨 Theme Customization]({{ site.baseurl }}/theme)

Learn how to switch Jekyll themes using the Makefile, control layout overrides with `opencs.html`, and customize SASS/CSS styles.

### [✍️ Markdown & HTML]({{ site.baseurl }}/markdown)

Master Markdown shorthand and HTML fragments for clean content creation, image embedding, and hyperlink structuring.

### [⚙️ Jekyll & Liquid]({{ site.baseurl }}/jekyll)

Leverage Jekyll static site generation with Liquid templating constructs like variables, loops, and conditional statements.

### [🛠️ Hacks & Challenges]({{ site.baseurl }}/hacks)

Apply acquired web development skills, file management techniques, and custom projects into real-wo