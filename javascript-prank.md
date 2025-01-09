
### **1. Flip the Entire Webpage Upside Down**  
```javascript
document.body.style.transform = 'rotate(180deg)';
```  
🎉 **Result:** The webpage flips upside down. Watch your friends panic!  

---

### **2. Make All Links Rickrolls**  
```javascript
document.querySelectorAll('a').forEach(link => {
  link.href = 'https://www.youtube.com/watch?v=dQw4w9WgXcQ';
});
```  
🎉 **Result:** Every link leads to the infamous Rick Astley video.  

---

### **3. Shrink All Images**  
```javascript
document.querySelectorAll('img').forEach(img => {
  img.style.width = '10px';
  img.style.height = '10px';
});
```  
🎉 **Result:** All images on the page shrink to tiny thumbnails.  

---

### **4. Add Random Emoji to Every Paragraph**  
```javascript
document.querySelectorAll('p').forEach(p => {
  p.innerHTML += ' 😂🤣🤔';
});
```  
🎉 **Result:** Every paragraph now has random emojis at the end.  

---

### **5. Play a Random Sound on Click**  
```javascript
document.body.addEventListener('click', () => {
  const audio = new Audio('https://www.soundjay.com/button/sounds/beep-07.mp3');
  audio.play();
});
```  
🎉 **Result:** Every time they click anywhere, a beep sound plays.  

---

### **6. Replace All Buttons with a Troll Face**  
```javascript
document.querySelectorAll('button').forEach(btn => {
  btn.innerHTML = '<img src="https://i.imgflip.com/1ur9b0.jpg" alt="Troll Face" style="width: 50px;">';
});
```  
🎉 **Result:** All buttons are now troll faces.  

---

### **7. Add a Random Confetti Effect**  
```javascript
setInterval(() => {
  const confetti = document.createElement('div');
  confetti.textContent = '✨';
  confetti.style.position = 'absolute';
  confetti.style.left = Math.random() * window.innerWidth + 'px';
  confetti.style.top = Math.random() * window.innerHeight + 'px';
  confetti.style.fontSize = '24px';
  document.body.appendChild(confetti);
}, 100);
```  
🎉 **Result:** Sparkling confetti appears randomly all over the screen.  

---

### **8. Bounce All Images Around**  
```javascript
document.querySelectorAll('img').forEach(img => {
  setInterval(() => {
    img.style.position = 'absolute';
    img.style.top = Math.random() * window.innerHeight + 'px';
    img.style.left = Math.random() * window.innerWidth + 'px';
  }, 500);
});
```  
🎉 **Result:** All images start bouncing around the screen.  

---

### **9. Replace All Text With ‘Hahaha’**  
```javascript
document.body.innerHTML = document.body.innerHTML.replace(/\w+/g, 'hahaha');
```  
🎉 **Result:** Every word on the page turns into *"hahaha."*  

---

### **10. Invert All Colors**  
```javascript
document.body.style.filter = 'invert(1)';
```  
🎉 **Result:** The entire page's colors are inverted, like a photo negative.  

---

**Bonus:** Combine multiple pranks for chaos! Just be sure your friend can easily restore the page by refreshing it. 😄
