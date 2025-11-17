# Liquid Gradient Effect

Custom gradient shader ile oluşturulmuş interaktif liquid efekt.

## Özellikler

- ✨ ThreeJS ile custom shader'lar
- 🌈 Dinamik gradient renkleri
- 🖱️ Mouse/touch interaktif efekt
- 🌊 Simplex noise ile liquid animasyon
- 📱 Responsive tasarım

## Kurulum

```bash
npm install
```

## Geliştirme

```bash
npm run dev
```

## Build

```bash
npm run build
```

## Özelleştirme

```javascript
// Renkleri değiştir
liquidEffect.setColors('#FF6B6B', '#4ECDC4', '#45B7D1');

// Displacement değerini değiştir
liquidEffect.setDisplacement(0.5);
```

## Kullanılan Teknolojiler

- Three.js - 3D graphics
- WebGL - GPU rendering
- GLSL - Shader programming
- Simplex Noise - Procedural animation
