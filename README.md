# 🎁 AR Photo Frame Magic

Turn a simple photo frame into a magical interactive experience using **Web-based Augmented Reality (WebAR)**.

👉 Point your camera at a photo →  
🎥 Watch videos  
🖼️ View images  
📝 Read personalized messages  

No app installation required. Works directly in the browser!

---

## 🚀 Idea

Imagine gifting someone a photo frame...  
But when they scan it, it comes alive with memories 💫

---

## 🧠 What This Project Does

This project uses **WebAR (Augmented Reality in browser)** to:

- Detect a real-world image (photo frame)
- Overlay digital content on it
- Allow user interaction via buttons

---

## 🛠️ Tech Stack
 
- HTML, CSS, JavaScript  

---

## ✨ Features

- 🎯 Image Target Detection  
- 🎥 Video overlay on scan  
- 🖼️ Image display mode  
- 📝 Text message display  
- 🎮 Interactive buttons  
- 📱 Works on mobile browsers (Android + iOS)

---

## 📂 Project Structure
project-folder/
│── index.html
│── targets.mind //file you will create on step 3 of setup
│── video.mp4 // video you want to show up
│── photo1.jpg // image you want to show up
|-- target.jpg // image you are scanning




---

## ⚙️ Setup Instructions (Step-by-Step)

### 1️⃣ Clone the repository

```bash
git clone https://github.com/pra-chauhan/AR-PhotoFrame.git

cd AR-PhotoFrame

```

### 2️⃣ Add your own media

Replace or add the following files:

- `video.mp4` → your video 
    --- [ for less hustle use the target image as first image in your video to help it ddetect easily.]
- `photo1.jpg` → your image  
- `target.jpg` → image you want to scan  

---

### 3️⃣ Generate AR Target File (.mind)

Go to:  
👉 https://hiukim.github.io/mind-ar-js-doc/tools/compile/

**Steps:**

1. Upload your `target.jpg`  
2. Click **Compile**  
3. Download `targets.mind`  
4. Place it inside your project folder  

---

### 4️⃣ Run the project

You need a local server (camera won’t work otherwise).

👉 Recommended: **Visual Studio Code + Live Server**

**Steps:**

- Open project in VS Code  
- Right-click `index.html`  
- Click **"Open with Live Server"**

---

### 5️⃣ Test on mobile

- Connect phone & laptop to same WiFi  
- Open in browser: //https...
- Allow camera access  
- Point camera at your target image  

---

## 🎮 How It Works

1. 📷 Browser opens camera  
2. 🧠 AR system scans the image  
3. 🎯 Image is detected using Computer Vision  
4. 🧩 Content is rendered on top:
   - 🎥 Video  
   - 🖼️ Image  
   - 📝 Text  
5. 🎮 User switches content using buttons  

---

## 🎁 Use Cases

- 🎂 Birthday gifts  
- 💑 Memory albums  
- 🎓 Graduation surprises  
- 💌 Personalized greeting cards  
- 📸 Interactive photo frames  

---

## ⚠️ Important Notes

- Use **high-quality target images** (clear & detailed)  
- Video should be **.mp4 (H.264)** format  
- Works best on:
  - Chrome (Android)  
  - Safari (iPhone)  
- Requires **camera permission**

---

## 🚧 Limitations

- Needs good lighting for detection  
- Large videos may load slowly  
- iOS may require user interaction to play video  

---

## 💡 Future Improvements

- Multiple image targets  
- Firebase-based dynamic content  
- Better UI/UX  
- Animations & transitions  
- Background music / audio  

---

## 🙌 Author

Made with ❤️ by **Pragya Chauhan**

---

## ⭐ Support

If you like this project, give it a ⭐ and share it!
