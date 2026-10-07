# NOVAMÓVIL - Código Completo del Proyecto Modificado

**Número de WhatsApp / Contacto Oficial:** `62644245` (Enlace directo: `https://wa.me/59162644245`)

## 📱 Catálogo de los 7 Modelos Seleccionados:
1. **Redmi Note 17** — 128 GB — 6+6 RAM (12 GB Total) | 108 MP & AMOLED 120Hz
2. **X5D** — 256 GB — 4+4 RAM (8 GB Total) | Batería 5200 mAh 2 Días
3. **Play 10** — 64 GB — 3+3 RAM (6 GB Total) | Pantalla fluida 90Hz
4. **Spark Go3** — 64 GB — 4+4 RAM (8 GB Total) | Audio DTS al 300% & 120Hz
5. **Magic 8 Lite** — 256 GB — 8+8 RAM (16 GB Total) | Récord Guinness Anticaídas 360° & Curva 1.5K
6. **Smart 20** — 64 GB — 4+4 RAM (8 GB Total) | Magic Ring Interactivo & Audio 200%
7. **Redmi A7 Pro** — 64 GB — 4+4 RAM (8 GB Total) | Cámara 50 MP, Cristal Mate & HyperOS

---

## 1. Archivo `data/phones.json`
```json
[
  {
    "id": "redmi-note-17",
    "name": "Redmi Note 17",
    "brand": "Xiaomi",
    "price": 1980,
    "originalPrice": 2190,
    "discount": "10% OFF",
    "image": "assets/images/redmi-note-17.jpg",
    "colors": ["Midnight Black", "Ocean Blue", "Aurora Green"],
    "isFeatured": true,
    "badge": "📸 108 MP & AMOLED 120Hz",
    "tagline": "Fotografía ultra nítida y pantalla AMOLED fluida",
    "specs": {
      "pantalla": "6.67\" AMOLED FHD+ (2400x1080) 120Hz con brillo de 1800 nits",
      "camara": "108 MP Cámara Principal con zoom 3x sin pérdida + 8 MP Ultra Gran Angular + 2 MP Macro | Frontal 16 MP",
      "procesador": "Qualcomm Snapdragon 685 (6 nm) Octa-Core",
      "ram": "6 GB + 6 GB RAM Virtual (12 GB Total)",
      "memoria": "128 GB de almacenamiento interno",
      "bateria": "5000 mAh con Carga Rápida de 33W",
      "ip": "IP54 (Protección contra polvo y salpicaduras de agua)",
      "caracteristicaUnica": "📸 Espectacular cámara de 108 MP con sensor de gran tamaño y zoom óptico 3x sin pérdida de calidad, combinada con pantalla AMOLED de 120Hz con brillo de 1800 nits y sonido Dolby Atmos."
    },
    "description": "El superventas definitivo de Xiaomi. Con 128 GB de memoria y 6+6 GB de RAM, pantalla AMOLED de 120Hz y cámara de 108 MP para fotos de calidad profesional."
  },
  {
    "id": "honor-x5d",
    "name": "X5D",
    "brand": "Honor",
    "price": 1550,
    "originalPrice": 1690,
    "discount": "8% OFF",
    "image": "assets/images/honor-x5d.jpg",
    "colors": ["Midnight Black", "Emerald Green", "Cyan Lake"],
    "isFeatured": false,
    "badge": "💾 256 GB Memoria Masiva",
    "tagline": "Máximo almacenamiento y batería de 2 días de duración",
    "specs": {
      "pantalla": "6.56\" HD+ (1612x720) 90Hz, Dynamic Dimming con protección visual certificada TÜV",
      "camara": "50 MP Ultra-Clear Principal + Sensor de Profundidad | Frontal 8 MP",
      "procesador": "MediaTek Helio G36 Octa-Core (hasta 2.2 GHz)",
      "ram": "4 GB + 4 GB HONOR RAM Turbo (8 GB Total)",
      "memoria": "256 GB de almacenamiento interno (ampliable hasta 1 TB)",
      "bateria": "5200 mAh con optimización IA (hasta 2 días enteros de uso continuo)",
      "ip": "IP52 (Resistencia a salpicaduras accidentales de agua y polvo)",
      "caracteristicaUnica": "💾 Enorme capacidad de almacenamiento de 256 GB para guardar miles de fotos, videos y aplicaciones a precio accesible, respaldada por batería de 5200 mAh para más de 40 horas de uso."
    },
    "description": "Espacio infinito para todo lo que necesitas. 256 GB de memoria interna con 4+4 GB de RAM Turbo y batería inagotable de 5200 mAh."
  },
  {
    "id": "honor-play-10",
    "name": "Play 10",
    "brand": "Honor",
    "price": 950,
    "originalPrice": 1050,
    "discount": "9% OFF",
    "image": "assets/images/honor-play-10.jpg",
    "colors": ["Midnight Black", "Sky Blue"],
    "isFeatured": false,
    "badge": "⚡ Económico & Eficiente",
    "tagline": "Rendimiento confiable y pantalla fluida de 90Hz",
    "specs": {
      "pantalla": "6.56\" HD+ 90Hz con protección ocular",
      "camara": "13 MP Principal con Inteligencia Artificial | Frontal 5 MP",
      "procesador": "MediaTek Helio Octa-Core eficiente",
      "ram": "3 GB + 3 GB RAM Virtual (6 GB Total)",
      "memoria": "64 GB de almacenamiento interno",
      "bateria": "5000 mAh de larga duración con puerto USB Tipo-C",
      "ip": "IP52 (Protección contra salpicaduras de líquidos)",
      "caracteristicaUnica": "⚡ Smartphone ligero y ágil de excelente autonomía con batería de 5000 mAh y pantalla fluida de 90Hz para navegar con total suavidad en tus redes sociales favoritas."
    },
    "description": "La opción más accesible y confiable de Honor. Con 64 GB de memoria y 3+3 GB de RAM, ideal para llamadas, WhatsApp, redes sociales y multimedia."
  },
  {
    "id": "tecno-spark-go-3",
    "name": "Spark Go3",
    "brand": "Tecno",
    "price": 1150,
    "originalPrice": 1250,
    "discount": "8% OFF",
    "image": "assets/images/tecno-spark-go-3.jpg",
    "colors": ["Startrail Black", "Glittery White", "Magic Skin Green"],
    "isFeatured": false,
    "badge": "🔊 Audio DTS 300% & 120Hz",
    "tagline": "Pantalla ultra fluida de 120Hz con sonido estéreo potente",
    "specs": {
      "pantalla": "6.67\" HD+ ultra fluida a 120Hz con notch interactivo 'Dynamic Port'",
      "camara": "13 MP HDR con Inteligencia Artificial y flash dual | Frontal 8 MP con flash frontal",
      "procesador": "Unisoc T615 Octa-Core de buen desempeño",
      "ram": "4 GB + 4 GB Memoria Fusión (8 GB Total)",
      "memoria": "64 GB de almacenamiento interno",
      "bateria": "5000 mAh con conector USB Tipo-C",
      "ip": "IP54 (Resistencia a gotas de lluvia y polvo)",
      "caracteristicaUnica": "🔊 Altavoces estéreo duales con amplificación de volumen de hasta 300% con certificación DTS, pantalla de 120Hz ultra suave y certificación de resistencia a salpicaduras IP54."
    },
    "description": "Potencia de sonido y fluidez insuperables en su categoría. Pantalla de 120Hz y parlantes estéreo con potencia aumentada al 300% para escuchar videos y música con máxima claridad."
  },
  {
    "id": "honor-magic-8-lite",
    "name": "Magic 8 Lite",
    "brand": "Honor",
    "price": 2250,
    "originalPrice": 2499,
    "discount": "10% OFF",
    "image": "assets/images/honor-magic-8-lite.jpg",
    "colors": ["Titanium Gold", "Midnight Black", "Emerald Green"],
    "isFeatured": true,
    "badge": "🏆 Récord Guinness Anticaídas 360°",
    "tagline": "La pantalla curva ultra resistente que desafía la gravedad",
    "specs": {
      "pantalla": "6.78\" AMOLED Curva 1.5K, 120Hz, 1200 nits, Protección 360° Anticaídas",
      "camara": "108 MP Ultra-Clear + 5 MP Gran Angular + 2 MP Macro | Frontal 16 MP",
      "procesador": "Qualcomm Snapdragon 6 Gen 1 (4 nm) Octa-Core",
      "ram": "8 GB + 8 GB HONOR RAM Turbo (16 GB Total)",
      "memoria": "256 GB UFS 3.1",
      "bateria": "5800 mAh con SuperCharge 35W (Duración hasta 3 días)",
      "ip": "IP53 (Resistencia a salpicaduras de agua y polvo en 360°)",
      "caracteristicaUnica": "🏆 Poseedor del Récord Mundial Guinness por resistencia extrema a caídas continuas desde 1.5 metros. Estructura con tecnología de amortiguación HONOR Ultra-Bounce certificada con 5 estrellas por SGS y pantalla curva 1.5K."
    },
    "description": "El teléfono indestructible con diseño curvo premium ultradelgado de 7.98mm. Incorpora 256 GB de memoria, 8+8 GB de RAM Turbo y pantalla HONOR Ultra-Bounce 360° con batería colosal de 5800 mAh."
  },
  {
    "id": "infinix-smart-20",
    "name": "Smart 20",
    "brand": "Infinix",
    "price": 1090,
    "originalPrice": 1200,
    "discount": "9% OFF",
    "image": "assets/images/infinix-smart-20.jpg",
    "colors": ["Timber Black", "Shiny Gold", "Crystal Green", "Galaxy White"],
    "isFeatured": false,
    "badge": "🔮 Magic Ring Interactivo & 200% Audio",
    "tagline": "Estilo moderno, animaciones dinámicas y volumen ultra potente",
    "specs": {
      "pantalla": "6.6\" HD+ 90Hz fluida con barra interactiva animada 'Magic Ring'",
      "camara": "13 MP Cámara Principal con IA y Doble Flash LED | Frontal 8 MP con Flash Frontal para selfies",
      "procesador": "Unisoc T606 Octa-Core de buen desempeño",
      "ram": "4 GB + 4 GB RAM Extendida (8 GB Total)",
      "memoria": "64 GB de almacenamiento interno",
      "bateria": "5000 mAh de larga duración con puerto USB Tipo-C",
      "ip": "IP53 (Resistencia contra polvo y salpicaduras)",
      "caracteristicaUnica": "🔮 Barra interactiva 'Magic Ring' que muestra animaciones de llamadas, batería y desbloqueo estilo Dynamic Island, con altavoces potenciados al 200% de volumen y flash frontal para fotos nocturnas."
    },
    "description": "El teléfono más económico y completo para el día a día. Diseño moderno, animaciones mágicas en pantalla y un potente sistema de audio para disfrutar de tu música favorita en cualquier lugar."
  },
  {
    "id": "xiaomi-redmi-a7-pro",
    "name": "Redmi A7 Pro",
    "brand": "Xiaomi",
    "price": 1180,
    "originalPrice": 1290,
    "discount": "8% OFF",
    "image": "assets/images/xiaomi-redmi-a7-pro.jpg",
    "colors": ["Midnight Black", "Forest Green", "Star Blue"],
    "isFeatured": false,
    "badge": "⚡ Xiaomi HyperOS & 50 MP",
    "tagline": "Elegancia con acabado en cristal mate y cámara de 50 MP",
    "specs": {
      "pantalla": "6.71\" HD+ Dot Drop 90Hz protegida por Corning Gorilla Glass",
      "camara": "50 MP Cámara Dual con IA y HDR | Frontal 5 MP con modo belleza",
      "procesador": "MediaTek Helio G36 Octa-Core",
      "ram": "4 GB + 4 GB RAM Virtual (8 GB Total)",
      "memoria": "64 GB de almacenamiento interno",
      "bateria": "5000 mAh con carga de 15W",
      "ip": "IP52 (Protección contra salpicaduras de líquidos)",
      "caracteristicaUnica": "💎 Tapa trasera con textura de cristal mate antihuellas dactilares, lector de huellas lateral de alta velocidad y el nuevo sistema operativo fluido Xiaomi HyperOS."
    },
    "description": "El smartphone de entrada más vendido de Xiaomi. Ofrece una cámara de 50 MP de alta definición, 64 GB de almacenamiento, 4+4 GB de RAM y la suavidad del nuevo sistema HyperOS."
  }
]
```
