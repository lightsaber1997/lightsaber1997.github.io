---
layout: about
title: about
permalink: /
subtitle: Computer Vision &amp; Robotics Researcher · Incoming M.S. Student, <a href='https://www.gatech.edu/'>Georgia Tech</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Atlanta, GA</p>
    <p><a href="mailto:dokustar@snu.ac.kr">dokustar@snu.ac.kr</a></p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  /* Shrink the profile photo. Adjust the max-width to taste. */
  .profile {
    max-width: 150px;
  }
  .profile img {
    width: 100%;
    height: auto;
  }
</style>

Hi, I'm **GyuYeop Do**. I am an incoming M.S. student in Computer Science at **Georgia Tech**, starting in Fall 2026. I am currently completing my B.S. in Electrical and Computer Engineering at **Seoul National University**, where I expect to graduate in August 2026.

My research interests lie at the intersection of **computer vision**, **robotics**, and **3D perception**. I am especially interested in building generalist robot systems that can perceive, reason, and act reliably in the real world. My recent work has explored **vision-language-action (VLA) models**, **RGB-only grasp prediction for transparent objects**, **3D reconstruction of dynamic objects**, and **efficient open-vocabulary perception for edge devices**.

More broadly, I am interested in the core questions behind scalable robot learning: how much progress comes from scaling robot data, when architectural design matters, and whether VLA-style policies can be extended toward long-horizon planning and dexterous manipulation. During my graduate studies, I hope to explore these questions through both perception-driven and action-centered approaches.

At SNU, I have worked with [Prof. Jaesik Park](https://jaesik.info/) at the Visual & Geometric Intelligence Lab, [Prof. Jonghyun Choi](https://ppolon.github.io/) at the Machine Perception and Reasoning Lab, and Prof. Nam-Joon Kim through the COSS Program. I am currently looking for **research internship opportunities** in computer vision, robotics, and embodied AI.

## Education

<style>
  .edu-list {
    margin: 1.25rem 0;
  }
  .edu-item {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    gap: 1rem;
    padding: 0.6rem 0;
    border-bottom: 1px solid var(--global-divider-color);
  }
  .edu-item:last-child {
    border-bottom: none;
  }
  .edu-main .edu-degree {
    font-weight: 600;
  }
  .edu-main .edu-school {
    color: var(--global-text-color-light);
    font-size: 0.9rem;
  }
  .edu-main .edu-note {
    margin-top: 0.2rem;
    color: var(--global-text-color-light);
    font-size: 0.8rem;
    font-style: italic;
  }
  .edu-date {
    white-space: nowrap;
    color: var(--global-text-color-light);
    font-size: 0.85rem;
  }
</style>

<div class="edu-list">
  <div class="edu-item">
    <div class="edu-main">
      <div class="edu-degree">M.S. in Computer Science</div>
      <div class="edu-school"><a href="https://www.gatech.edu/">Georgia Institute of Technology</a> · Atlanta, GA, USA</div>
    </div>
    <div class="edu-date">Aug 2026 – Present</div>
  </div>
  <div class="edu-item">
    <div class="edu-main">
      <div class="edu-degree">B.S. in Electrical &amp; Computer Engineering</div>
      <div class="edu-school"><a href="https://en.snu.ac.kr/">Seoul National University</a> · Seoul, Republic of Korea</div>
      <div class="edu-note">Includes 1.5 years of mandatory Republic of Korea Army service as a KATUSA soldier, serving alongside the U.S. Army (1st Signal Brigade, Eighth Army)</div>
    </div>
    <div class="edu-date">Mar 2020 – Aug 2026</div>
  </div>
</div>

Some of my relevant coursework includes **3D Computer Vision**, **Linear Algebra**, **Deep Learning**, and **Random Variables**. I also enjoy building systems from the ground up; selected technical projects include an incremental structure-from-motion pipeline, a CUDA ray tracer, a debugger, and a custom memory allocator.

Outside research, I am also deeply interested in teaching. I have worked as a teaching assistant at several large private academies in South Korea, and I founded an education business that develops physics preparation books for the Korean College Scholastic Ability Test (CSAT).

Books I have authored or produced include <span style="color: var(--global-text-color-light); font-size: 0.85rem;">(click a cover to view the book)</span>:

<style>
  .book-shelf {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(110px, 1fr));
    gap: 1.25rem;
    margin: 1.5rem 0;
  }
  .book-shelf a {
    text-decoration: none;
    color: var(--global-text-color);
  }
  .book-shelf img {
    width: 100%;
    aspect-ratio: 5 / 7;
    object-fit: cover;
    border-radius: 6px;
    box-shadow: 0 4px 14px rgba(0, 0, 0, 0.18);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  .book-shelf a:hover img {
    transform: translateY(-4px);
    box-shadow: 0 8px 22px rgba(0, 0, 0, 0.28);
  }
  .book-shelf .book-title {
    margin-top: 0.5rem;
    font-size: 0.78rem;
    line-height: 1.25;
    text-align: center;
  }
</style>

<div class="book-shelf">
  <a href="https://www.yes24.com/product/goods/151778167" target="_blank" rel="noopener">
    <img src="{{ '/assets/img/book_covers/gradient-physics.jpg' | relative_url }}" alt="Gradient CSAT Physics I Prep Test" loading="lazy" />
    <div class="book-title">Gradient<br />Physics I</div>
  </a>
  <a href="https://www.yes24.com/product/goods/132399451" target="_blank" rel="noopener">
    <img src="{{ '/assets/img/book_covers/gravity-2025.jpg' | relative_url }}" alt="2025 Gravity CSAT Physics I Prep Test" loading="lazy" />
    <div class="book-title">Gravity 2025<br />Physics I</div>
  </a>
  <a href="https://www.yes24.com/product/goods/122115437" target="_blank" rel="noopener">
    <img src="{{ '/assets/img/book_covers/gravity-2024.jpg' | relative_url }}" alt="2024 Gravity CSAT Physics I Prep Test" loading="lazy" />
    <div class="book-title">Gravity 2024<br />Physics I</div>
  </a>
  <a href="https://www.yes24.com/product/goods/108668788" target="_blank" rel="noopener">
    <img src="{{ '/assets/img/book_covers/gravity-2023.jpg' | relative_url }}" alt="2023 Gravity CSAT Physics I Prep Test" loading="lazy" />
    <div class="book-title">Gravity 2023<br />Physics I</div>
  </a>
  <a href="https://www.yes24.com/product/goods/99151812" target="_blank" rel="noopener">
    <img src="{{ '/assets/img/book_covers/gravity-2022.jpg' | relative_url }}" alt="2022 Gravity CSAT Physics I Prep Test" loading="lazy" />
    <div class="book-title">Gravity 2022<br />Physics I</div>
  </a>
</div>

Feel free to reach out by [email](mailto:dokustar@snu.ac.kr). You can also find my code on [GitHub](https://github.com/lightsaber1997).
