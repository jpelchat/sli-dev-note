---
theme: default
presenter: false
download: false
contextMenu: false
title: Welcome to Slidev
info: Example
class: text-center
drawings:
  persist: false
transition: fade
mdc: true
overviewSnapshots: no
---

<div autofocus style="margin-bottom:10%" class="pt-12" >
  
  <div text-center> 
    <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer">
    <img style="margin:auto" width="200px" src="./assets/grot.gif"></span>
    Click <strong>Grot</strong> for overview. <br>
  </div>
</div>

---
transition: fade
---

<SlidevVideo autoplay controls>
  <source src="./assets/note.mp4" type="video/mp4" />
</SlidevVideo>

---
transition: fade
layout: center
---

<SlidevVideo autoplay controls>
  <source src="./assets/note_alloy.mp4" type="video/mp4" />
</SlidevVideo>


---
transition: fade
layout: center
---

<div text-center><h3>Lab overview</h3></div>

|  |  |
| --- | --- |
| <kbd>1</kbd> | 🤖 Install Alloy on a Linux host |
| <kbd>2</kbd> | 🛠️ Configure Alloy to collect metrics |
| <kbd>3</kbd> | 🔎 Explore metrics in Grafana Cloud |

<br><br><br>

---
transition: fade
layout: center
---

<p text-center> 
Click <strong>Start</strong> in the lower-right corner, once your lab is ready.
</p>