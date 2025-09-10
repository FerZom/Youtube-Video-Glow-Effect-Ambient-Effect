# Reusable Video Glow

> 💡 A project that lets you add dynamic and colorful glow effects to your videos using **HTML, CSS, and JavaScript**. Videolarınıza canlı ve renkli glow efekti ekleyebilirsiniz.

## Features / Özellikler

- Automatically applies glow effect to each area of your video.  
  - Videonuzun her bir bölgesine otomatik olarak glow efekti uygular.  
- Glow colors update based on the average pixel color of the video.  
  - Glow renkleri videodaki ortalama piksel renklerine göre güncellenir.  
- Easy to apply on different videos and reusable.  
  - Kolayca farklı videolara uygulanabilir ve tekrar kullanılabilir.  
- Customizable glow parameters like blur and opacity.  
  - Blur ve opaklık gibi glow efekt parametreleri özelleştirilebilir.  
- Responsive design adjusts automatically to screen size.  
  - Responsive tasarım, ekran boyutuna göre otomatik uyum sağlar.  

## Live Preview / Canlı Önizleme
<img width="1919" height="1030" alt="image" src="https://github.com/user-attachments/assets/548e2ffd-8d57-434c-9ceb-8ed8bb990ca2" />

> Example of the screen after applying the glow effect on the video.  
> Videoya glow efekti uygulandıktan sonra ekran görünümü örneği.

## Usage / Kullanım

1. Clone the project or download the HTML file:  
```bash
git clone https://github.com/kullaniciadi/reusable-video-glow.git
```

2. Change the video source in your HTML file:
```html
<video id="video1" autoplay loop muted>
  <source src="your-video.mp4" type="video/mp4">
</video>
```
3. Apply the glow effect using JS:
```js
applyVideoGlow("#video1", "#videoContainer1", { 
  rows: 5, 
  cols: 5, 
  blur: 0, 
  opacity: 0.7 
});
```

