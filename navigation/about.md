---
layout: post
title: About
permalink: /about/
comments: true
---

# About Me

## As a Conversation Starter
Here are places connected to my heritage and life.

<div id="grid_container"></div>
<script>
var outputElement = document.getElementById("grid_container");
outputElement.innerHTML = '';

// Data Array for Flags
const living_in_the_world = [
  {
    flag: "https://upload.wikimedia.org/wikipedia/commons/4/41/Flag_of_India.svg",
    greeting: "Namaste",
    description: "India - Cultural Heritage"
  },
  {
    flag: "https://upload.wikimedia.org/wikipedia/commons/0/01/Flag_of_California.svg",
    greeting: "Hey",
    description: "California - Golden State"
  },
  {
    flag: "https://upload.wikimedia.org/wikipedia/commons/a/a4/Flag_of_the_United_States.svg",
    greeting: "Hello",
    description: "United States - Home"
  }
];

// Create grid container
const container = document.createElement('div');
container.id = 'grid_container_inner';
container.style.display = 'grid';
container.style.gridTemplateColumns = 'repeat(auto-fill, minmax(180px, 1fr))';
container.style.gap = '15px';
container.style.padding = '10px 0';

// Loop through flag data
for (const location of living_in_the_world) {
  const item = document.createElement('div');
  item.style.border = '1px solid #ccc';
  item.style.borderRadius = '8px';
  item.style.padding = '12px';
  item.style.textAlign = 'center';
  item.style.boxShadow = '0 2px 5px rgba(0,0,0,0.1)';

  const img = document.createElement('img');
  img.src = location.flag;
  img.alt = location.description;
  img.style.width = '100%';
  img.style.height = '100px';
  img.style.objectFit = 'cover';
  img.style.borderRadius = '4px';

  const desc = document.createElement('p');
  desc.textContent = location.description;
  desc.style.fontWeight = 'bold';
  desc.style.margin = '8px 0 4px 0';

  const greet = document.createElement('p');
  greet.textContent = location.greeting;
  greet.style.margin = '0';
  greet.style.color = '#555';

  item.appendChild(img);
  item.appendChild(desc);
  item.appendChild(greet);
  container.appendChild(item);
}

outputElement.appendChild(container);
</script>

### Journey through Life

A lifelong learner and tech pioneer, I've been fortunate to work across multiple decades of computing evolution:

- 🏫 **Elementary Schools** - Tucson, Honolulu, LA, and Glendale (CA) - built my foundation
- 🏫 **High School** - Hoover High in Glendale, graduated '77 - discovered technology
- 🎓 **Early Tech Education** - Glendale Community College & LA Wilshire Computer Tech School ('77-'79) - dBase era
- ⛪ **England** - LDS Missionary in London ('79-'81) - served and learned resilience
- 💼 **Ashton-Tate** - Culver City/Glendale founder - built dBase 2 & 3 for original PCs ('82-'87)
- 🎓 **University of Oregon** - CompSci degree ('89-'91) - Go Ducks! 
- 💼 **Microniche & Point Control** - Eugene, Oregon - CAD CAM developer and founder ('88-'96)
- 🏢 **Qualcomm** - San Diego, CA - Satellite Communications & 1st Mobile OS (BREW) ('96-'19) - 23 incredible years
- 👨‍🏫 **Del Norte High School** - San Diego, CA - Computer Science Teacher ('19-present) - giving back to the next generation

### Culture, Family, and Faith

Everything for me revolves around family and faith—the two pillars that make life meaningful.

**Heritage & Family:**
- My mother shared that I have Danish, English, and Irish roots. I've researched and documented my [family tree]({{site.baseurl}}/images/about/familytree.png)
- I've been blessed with a beautiful, large family. I was married twice—my first wife passed away. Together we had 5 children (4 adopted by me, 1 biological), and I've been blessed with three grandchildren
- My grandchildren call me "Abuilito" (a term of endearment in Spanish)

**Memories Through Photos:**
Gallery of cherished moments—scroll to see family, adventures, faith, and culture memories:

<comment>
Gallery of Pics, scroll to the right for more ...
</comment>
<div class="image-gallery">
  <img src="{{site.baseurl}}/images/about/missionary.jpg" alt="Image 1">
  <img src="{{site.baseurl}}/images/about/john_tamara.jpg" alt="Image 2">
  <img src="{{site.baseurl}}/images/about/tamara_fam.jpg" alt="Image 3">
  <img src="{{site.baseurl}}/images/about/surf.jpg" alt="Image 4">
  <img src="{{site.baseurl}}/images/about/john_lora.jpg" alt="Image 5">
  <img src="{{site.baseurl}}/images/about/lora_fam.jpg" alt="Image 6">
  <img src="{{site.baseurl}}/images/about/lora_fam2.jpg" alt="Image 7">
  <img src="{{site.baseurl}}/images/about/pj_party.jpg" alt="Image 8">
  <img src="{{site.baseurl}}/images/about/trent_family.png" alt="Image 9">
  <img src="{{site.baseurl}}/images/about/claire.jpg" alt="Image 10">
  <img src="{{site.baseurl}}/images/about/grandkids.jpg" alt="Image 11">
  <img src="{{site.baseurl}}/images/about/farm.jpg" alt="Image 12">
</div>
