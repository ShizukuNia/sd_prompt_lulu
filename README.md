# ai绘画提示词

## 常用的通用tag

```prompt
masterpiece, best quality, illustration, anime, screenshot, anime screenshot, dynamic angle, 
```

## lulu形象基础prompt

**chibi是Q版形象的tag**

学生制服

```prompt
1girl, chibi, solo, blue sapphire eyes, short silver hair,
grey cardigan, white sailor_collar, black shirt, pleated skirt, black beret,
```

学生制服 夏ver.

```prompt
1girl, chibi, solo, blue sapphire eyes, short silver hair,
serafuku, white sailor_collar, white shirt, pleated skirt, white beret，
```

**裙子看细节程度可以加*plaid skirt***

偶像服

```prompt
1girl, chibi, solo, blue sapphire eyes, silver hair,  voluminous hair, straight bang, twisted braid,hemp braid, 
frills, white dress, blue_bow, choker, white beret,
```

运动服

```prompt
1girl, chibi, solo, blue sapphire eyes, silver long hair, straight bang,
wavy hair, low twintails, //双马尾
white blouse, blue jacket, white skirt,
```

粉色小裙子

```prompt
1girl, chibi, solo, blue eyes, silver long hair, wavy hair, low twintails, pink dress, bare shoulders, pink beret
```

初号机

```prompt
1girl, chibi, solo, blue eyes, silver long hair, wavy hair, low twintails,straight bang, 
serafuku, school_uniform, red bow, blue_headwear, puffy_sleeves, juliet_sleeves, dress
```

## 彩漆风格

自用的正常比例绘画风格，在final-pruned模型上效果奇佳

专用的negative prompt

```prompt
nsfw,
lowres, text, error, extra digit, low quality, jpeg artifacts, signature, blurry, normal quality, cropped, worst quality, deformity,
ui,  watermark, username, 3D, 3D games, 3D game scene, 3D character, 
bad hairs, poorly drawn hairs, fused hairs, big muscles, ugly, bad face, fused face, poorly drawn face, cloned face, big face, long face, bad eyes, fused eyes, poorly drawn eyes,
Sapphire, (braid), brush, (Ponytail)
```

下面的还没整理，随便挑一块就能用

```prompt
(Floating, paint, colorful background, high saturation, surrounded by colorful splashes, surrounded by colorful dot, colorful bubble, shining:1.3),

(Floating paint, Colorful background, high saturation, surrounded by colorful graphics, cyberpunk),
[glitch art, Pixilation, Double exposure, Chromatic Aberration, Light leaks, geometry, clear lines, squares, bright, limited palette:0.2],

(Cyberpunk, Colorful background, high saturation, surrounded by colorful geometry, pixilation, bright),

彩漆里混了点glitch
Colorful background, surrounded by colorful splashes, floating, paint, high saturation, colorful bubble, shining, bright, chromatic aberration, light leaks, geometry, clear lines, squares

(Paint, colorful background, surrounded by colorful splashes, colorful bubble, shining),
```
