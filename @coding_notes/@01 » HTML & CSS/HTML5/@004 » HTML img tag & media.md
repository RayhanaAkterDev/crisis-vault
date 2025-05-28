# 📄 Topic: HTML Images & Media

- HTML lets you add images, audio, videos, and even YouTube inside a page.    
- Media makes websites look and feel more engaging.    

---

## 🔍 Key Tags & Purpose (Short Note)

- `<img>` → Shows an image on the page.    
    - `src` → image file path or link        
    - `alt` → backup text if image doesn't load        
    - `title` → shows text when hovering        
    - `width`, `height` → control image size
---
- `<audio>` → Plays sound/music.    
    - `controls` → adds play/pause buttons        
    - `autoplay` → starts playing when page loads        
---
- `<video>` → Plays video files.    
    - `controls` → adds play buttons        
    - `autoplay`, `loop`, `muted` → control playback behavior        
---
- `<iframe>` → Shows another website (like YouTube) inside your page.    
    - `src` → link to the embedded content        
    - `allowfullscreen` → allows full screen viewing        


**Practice code link**:  https://github.com/sumayaakter533/Frontend-Bootcamp/blob/58fd25c3a3ce5c0542e81713638b0e40e5564af5/html-css/html/04-images-and-media.html

```ad-todo
title: Demo code output

<img src="photo-demo.avif" alt="Local Photo" />
<audio controls>
  <source src="song.mp3" type="audio/mp3" />
</audio>
<video src="video.mp4" controls></video>
<iframe width="560" height="315" src="https://www.youtube.com/embed/CFiCdpnn-jo?si=uoUpnZQQbPIjcfGr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
```

---

> 🧠 _Tip_: Use `alt` for accessibility, and make sure your media paths are correct (relative or absolute).