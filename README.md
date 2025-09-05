# NFT Preview Card

A responsive NFT preview card component with hover states for the image, title, and creator link.

## 🔗 Live
- **Demo:** <https://yaminqabaha7.github.io/-NFT-Preview-Card/>
- **Repo:** <https://github.com/Yaminqabaha7/-NFT-Preview-Card>

## 📸 Screenshot
![NFT Card Screenshot](./images/Screenshot%202025-09-05%20092251.png)

## 🧱 Built With
- Semantic HTML5
- CSS3 (Flexbox, responsive)
- Google Fonts — Outfit

## ✨ Features
- Image hover overlay with view icon  
- Cyan-highlighted price and subtle time meta  
- Divider line using `border-top`  
- Accessible markup and focusable links

## 📂 Structure
```
.
├── index.html
├── styles.css
└── images/
    ├── image-equilibrium.jpg
    ├── image-avatar.png
    ├── icon-view.svg
    ├── icon-ethereum.svg
    └── icon-clock.svg
```

## ⚙️ Getting Started
1. Clone the repo  
2. Open `index.html` in a browser  
   _or_ run a local server (e.g. VS Code Live Server or `npx serve .`)

## 🧩 Notes
- Overlay built with `position: relative/absolute` and `overflow: hidden`.  
- HSL color values to match the style guide.  
- Divider implemented via border:  
  ```css
  
  ```

## 🚀 Improvements
- Add fade/scale animation to the overlay  
- RTL (right-to-left) layout support  
- Better accessibility (focus states, ARIA)

## 🙏 Acknowledgments
Challenge inspired by [Frontend Mentor](https://www.frontendmentor.io/) — NFT preview card.
