# Image2.5 · Prompt Library · Leadde.ai

[![English](https://img.shields.io/badge/English-brightgreen)](README.md) [![简体中文](https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-lightgrey)](README_zh.md) [![繁體中文](https://img.shields.io/badge/%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87-lightgrey)](README_zh-TW.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-lightgrey)](README_ja-JP.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-lightgrey)](README_ko-KR.md) [![ไทย](https://img.shields.io/badge/%E0%B9%84%E0%B8%97%E0%B8%A2-lightgrey)](README_th-TH.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-lightgrey)](README_vi-VN.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-lightgrey)](README_hi-IN.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-lightgrey)](README_es-ES.md) [![Español (Latinoamérica)](https://img.shields.io/badge/Espa%C3%B1ol%20(Latinoam%C3%A9rica)-lightgrey)](README_es-419.md) [![Deutsch](https://img.shields.io/badge/Deutsch-lightgrey)](README_de-DE.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-lightgrey)](README_fr-FR.md) [![Italiano](https://img.shields.io/badge/Italiano-lightgrey)](README_it-IT.md) [![Português (Brasil)](https://img.shields.io/badge/Portugu%C3%AAs%20(Brasil)-lightgrey)](README_pt-BR.md) [![Português](https://img.shields.io/badge/Portugu%C3%AAs-lightgrey)](README_pt-PT.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-lightgrey)](README_tr-TR.md)

**Best for:** Image 2.5 prompts for commercial visuals, layouts, keyframes, and image-to-video source assets.

For PDF, PPT, SOP, training, and multilingual video workflows:
[Awesome Document-to-Video](https://github.com/LeaddeOpenLab/awesome-document-to-video)

> **High-quality prompts, curated daily**

Discover complete prompts for AI images, videos and 3D creation. Browse by style, explore multilingual editions and credit the original creators.

[Explore Leadde.ai →](https://leadde.ai/?utm_source=github&utm_medium=readme&utm_campaign=prompt-library&utm_content=image2.5)

## Meet Leadde.ai

Leadde.ai helps teams turn documents, slides and text into AI business videos for training, onboarding and marketing.

Star this repository to follow our daily prompt curation and find fresh creative ideas.

**161** Prompts · Latest addition: **2026-09-20**

<a name="catalog"></a>

## Browse by Category

[Photography](#category-photography) · [Cinematic / Film Still](#category-cinematic-film-still) · [Anime / Manga](#category-anime-manga) · [Illustration](#category-illustration) · [Sketch / Line Art](#category-sketch-line-art) · [3D Render](#category-3d-render) · [Pixel Art](#category-pixel-art) · [Watercolor](#category-watercolor) · [Ink / Chinese Style](#category-ink-chinese-style) · [Retro / Vintage](#category-retro-vintage) · [Cyberpunk / Sci-Fi](#category-cyberpunk-sci-fi) · [Minimalism](#category-minimalism) · [Other](#category-other)

<a name="all-prompts"></a>

<a name="category-photography"></a>

## Photography

<a name="prompt-2101395682712285664"></a>

### Drone aerial photography prompt shaping a luxury tropical island's coastline into a brand logo, featuring white sand beaches, turquoise lagoons, and lush palms.

Author：[@SaasJunctionHQ](https://x.com/SaasJunctionHQ) · [Source](https://x.com/SaasJunctionHQ/status/2101395682712285664)

Photography · Landscape / Nature · Published

Source：[@SaasJunctionHQ](https://x.com/SaasJunctionHQ) · [Source](https://x.com/SaasJunctionHQ/status/2090485613640446116)

**Summary:** Drone aerial photography prompt shaping a luxury tropical island's coastline into a brand logo, featuring white sand beaches, turquoise lagoons, and lush palms.

<img src="images/2101395682712285664-1.jpg" alt="Image 1" width="480" />

<img src="images/2101395682712285664-2.jpg" alt="Image 2" width="480" />

<img src="images/2101395682712285664-3.jpg" alt="Image 3" width="480" />

<img src="images/2101395682712285664-4.jpg" alt="Image 4" width="480" />

<img src="images/2101395682712285664-5.jpg" alt="Image 5" width="480" />

<img src="images/2101395682712285664-6.jpg" alt="Image 6" width="480" />

<img src="images/2101395682712285664-7.jpg" alt="Image 7" width="480" />

<img src="images/2101395682712285664-8.jpg" alt="Image 8" width="480" />

**Prompt**

```text
{
  "prompt_name": "Aerial Island Logo Shape Generator",
  "user_input_required": {
    "input_type": ["company_name (text)", "logo_image (upload)"],
    "instruction": "Provide only a company name OR upload a logo image. The system will auto-generate the rest of the scene."
  },
  "scene": {
    "subject": "A remote tropical island photographed from a direct top-down aerial drone perspective, with its coastline and landmass naturally contoured to replicate the silhouette of the provided company logo",
    "shape_source": "{{company_logo_or_name_silhouette}}",
    "shape_fidelity": "The island's outline must be instantly recognizable as the logo shape when viewed from above, while still appearing like a naturally formed landmass — no artificial or man-made geometry"
  },
  "environment": {
    "vegetation": "Dense, lush tropical palm trees and greenery covering the interior of the island",
    "shoreline": "Fine white sand beaches tracing the entire perimeter of the logo-shaped landmass",
    "water": {
      "inner_ring": "Shallow crystal-clear turquoise lagoon encircling the island",
      "outer_ring": "Deep sapphire-blue open ocean with realistic wave patterns and natural foam texture"
    }
  },
  "lighting": {
    "type": "Warm golden-hour sunlight",
    "effects": ["soft natural shadows", "cinematic highlights on water", "gentle lens glow at frame edge"]
  },
  "photography_style": {
    "genre": "High-end luxury travel and real estate aerial photography",
    "camera_angle": "Directly overhead (bird's eye / nadir view)",
    "realism": "Ultra-photorealistic, natural, organic — must not look CGI or artificially rendered",
    "resolution": "8K, hyper-detailed textures on water, sand, and foliage"
  },
  "exclusions": [
    "no visible text or watermarks",
    "no people",
    "no buildings or man-made structures",
    "no boats"
  ]
}
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100266849506316292"></a>

### A nine-grid photo in a 3x3 composition collecting a variety of amateur failed photos

Author：[@ahamme35638](https://x.com/ahamme35638) · [Source](https://x.com/ahamme35638/status/2100266849506316292)

Photography · Published

**Summary:** A nine-grid photo in a 3x3 composition collecting a variety of amateur failed photos

<img src="images/2100266849506316292-1.jpg" alt="Image 1" width="480" />

<img src="images/2100266849506316292-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
A collection of amateur failed photos, 3x3, 9:16
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100221410358735319"></a>

### Realistic 3x3 grid selfie prompt imitating a series of amateur failed photos.

Author：[@oneruofeng](https://x.com/oneruofeng) · [Source](https://x.com/oneruofeng/status/2100221410358735319)

Photography · Portrait / Selfie · Published

**Summary:** Realistic 3x3 grid selfie prompt imitating a series of amateur failed photos.

<img src="images/2100221410358735319-1.jpg" alt="Image 1" width="480" />

<img src="images/2100221410358735319-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Numerous amateur failed photos, 3x3, 9:16
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100101909634036032"></a>

### A 3x3 grid image collecting amateur everyday failed snapshot photos.

Author：[@cnyzgkc](https://x.com/cnyzgkc) · [Source](https://x.com/cnyzgkc/status/2100101909634036032)

Photography · Portrait / Selfie · Published

Source：[@KinGao476942](https://x.com/KinGao476942) · [Source](https://x.com/KinGao476942/status/2100086793995706689)

**Summary:** A 3x3 grid image collecting amateur everyday failed snapshot photos.

<img src="images/2100101909634036032-1.jpg" alt="Image 1" width="480" />

<img src="images/2100101909634036032-2.jpg" alt="Image 2" width="480" />

<img src="images/2100101909634036032-3.jpg" alt="Image 3" width="480" />

**Prompt**

```text
A collection of amateur failed photos, 3x3, 9:16
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100065803072897507"></a>

### An intimate perspective photoshoot of a girlfriend with a first-love face, featuring an adorably fierce expression and a contrasting outfit.

Author：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2100065803072897507)

Photography · Portrait / Selfie · Fashion Item · Published

Source：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2099721592582656282)

**Summary:** An intimate perspective photoshoot of a girlfriend with a first-love face, featuring an adorably fierce expression and a contrasting outfit.

<img src="images/2100065803072897507-1.jpg" alt="Image 1" width="480" />

<img src="images/2100065803072897507-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Girlfriend with a first-love face × ambiguous intimacy × unconventional experimental lens × contrasting OOTD × adorably fierce and coquettish expression
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099520724121883039"></a>

### High-end night scene fashion female portrait photography prompt from a high-angle overhead shot on an urban rooftop lounge bar.

Author：[@AIVideoHub\_](https://x.com/AIVideoHub_) · [Source](https://x.com/AIVideoHub_/status/2099520724121883039)

Photography · Portrait / Selfie · Character · Fashion Item · Cityscape / Street · Published

**Summary:** High-end night scene fashion female portrait photography prompt from a high-angle overhead shot on an urban rooftop lounge bar.

<img src="images/2099520724121883039-1.jpg" alt="Image 1" width="480" />

<img src="images/2099520724121883039-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
9:16 vertical format, urban nightscape rooftop lounge bar × high-angle overhead shot × hyperrealistic real-person fashion photography × high-end night scene editorial.

A clearly adult, beautiful East Asian woman aged 22–25, tall and slender, small head, small face, slim waist, elongated posture. Skin is exceptionally fair, delicate, translucent, presenting a clean and sophisticated cool porcelain tone, retaining authentic pores and natural skin texture.

The subject features refined, mature real-female facial features, a smooth oval face, a defined jawline, and a slightly pointed chin. Voluminous, seaweed-like long wavy black hair drapes lazily over her shoulders and back, with loose strands gently fluttering in the rooftop night breeze without obscuring her main facial features.

She is seated on a high stool at the rooftop lounge bar, body slightly turned sideways, upper body naturally leaning back, relaxed shoulders and neck, face tilted slightly upward looking up into the high-angle camera. Her gaze is cool, languid, with a touch of elusive allure, lips naturally relaxed, projecting an overall mature, restrained, and distant demeanor.

Wearing a matte mutton-fat-textured genuine leather cinched-waist long trench coat made of soft, premium leather with a delicate matte grain and natural creases. Distinctly cinched at the waist to emphasize a slender waistline; collar naturally loosened to form a low V-neckline revealing the neck, shoulders, and delicate collarbones. Styled with minimalist, sophisticated black tall boots to keep the overall look unified in dark urban fashion.

Adorned with crushed-diamond cat-eye manicured nails, dangling long crystal earrings, a slender serpentine diamond bracelet, and a V-shaped pavé diamond collarbone necklace. Fingers are slender and elongated; one hand rests naturally on the high stool or by her thigh, while the other can gently touch her long hair, collarbone necklace, or rest naturally against the edge of the bar counter. The jewelry and cat-eye nails produce subtle, sharp, and restrained glints under the city lights.

The camera is positioned at approximately 40–50° in front of and above the subject, establishing a clear high-angle overhead perspective. The subject sits lower and tilts her face slightly upward, creating a distinct visual layering of the eyes, bridge of the nose, lips, neck and shoulders, and the leather coat lapels. Avoid completely vertical top-down shots and severe wide-angle distortion.

The background is a high-rise urban rooftop lounge bar featuring glass railings, a minimalist bar counter, high-top tables and chairs, and dense city skyscrapers, neon lights, road traffic, and countless city lights in the distance. The nightscape naturally wraps around the subject, generating rich depth and layers.

Using cool white soft light as the key light for the subject, with city neon providing blue-violet, silver-gray, and subtle warm-gold ambient reflections. Key focus is placed on enhancing refined highlights along the nose bridge, eyes, lips, jawline, collarbones, jewelry, and hands, while maintaining rich shadow textures in the black matte leather without producing an oily plastic sheen.

The subject's face, eyes, fingers, cat-eye nails, pavé diamond jewelry, and leather textures remain ultra-sharp and in high definition; the background city nightscape utilizes a soft shallow depth of field to create natural neon bokeh, with the subject's outline only slightly softened.

Overall low-saturation cinematic color grading of black-gray, cool white, blue-violet, and subtle warm gold, enhanced with gentle bloom, fine film grain, and soft highlight halation. Presenting a sophisticated, languid, cool, alluring yet restrained urban nightlife fashion editorial quality.

Negative prompts: Complete vertical top-down shot, low-angle shot, severe wide-angle distortion, big head, large face, shiny plastic leather look, cheap leather, incorrect collar construction, floating jewelry, deformed manicure, fused fingers, extra hands, extra fingers, hair covering face, blurry main subject, out-of-focus face, overexposed nose bridge, plastic skin, over-smoothed skin, completely blurred background, chaotic nightscape, anime face, CG face, text, logo, watermark.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099374878910734661"></a>

### 9:16 surreal canyon landscape, colossal rotating cloud ring with long exposure time-stack effect, traveler seen from behind on the canyon floor.

Author：[@listudio](https://x.com/listudio) · [Source](https://x.com/listudio/status/2099374878910734661)

Photography · Landscape / Nature · Published

**Summary:** 9:16 surreal canyon landscape, colossal rotating cloud ring with long exposure time-stack effect, traveler seen from behind on the canyon floor.

<img src="images/2099374878910734661-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Create a 9:16 vertical, photorealistic surreal canyon time-stack photograph. In a wide, dry canyon floor, massive vertical stratified rock walls of warm brown, ochre, and charcoal black rise from the near edges, forming a dark natural frame, with rock textures and gravel maintaining crisp detail.

In the mid-to-far distance above the canyon, a colossal rotating cloud ring occupies most of the central area, with serene gray-blue sky exposed in the center of the circular opening. Utilizing a locked-off camera long exposure and multi-frame time-stacking effect: dense cumulus clouds slowly swirl in the same rotational direction, merging into continuous, smooth concentric streamlines, with the inner wall displaying hundreds of delicate curved cloud trails and soft rotational motion blur along the ring's edges; the clouds still retain realistic chiaroscuro volume and milky-white texture, not resembling a solid tunnel, free of fragmented digital noise.

From the foreground, the canyon floor stretches wide and converges into the distance; an adult traveler with their back to the camera stands at the lower center, occupying only about 2% of the frame height, remaining tack-sharp. Warm sunlight from the upper right breaks through gaps in the clouds, with continuous exposure creating a soft diffusion in the highlights, illuminating the right cloud wall and rock edges; warm rock, cool gray-blue sky, and bright milky-white clouds form a restrained three-color palette.

Subtle film grain, natural atmospheric perspective, epic silence and an overwhelming sense of scale. Motion blur affects only the clouds and a faint haze of dust; the rock walls, canyon floor, and figure remain sharp. No architecture, no dense forest, no birds, no text, no logo, no watermark, no lightning.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099375219546935317"></a>

### Surreal canyon adventure long-exposure photography, featuring a long-exposure mountain river, a tsunami wave in the sky, and a traveler's silhouette.

Author：[@listudio](https://x.com/listudio) · [Source](https://x.com/listudio/status/2099375219546935317)

Photography · Published

**Summary:** Surreal canyon adventure long-exposure photography, featuring a long-exposure mountain river, a tsunami wave in the sky, and a traveler's silhouette.

<img src="images/2099375219546935317-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Create a 9:16 vertical, photorealistic surreal canyon long-exposure adventure photograph. Wide-angle low-angle perspective, with the foreground to midground featuring a wide, icy mountain river where grey-cyan water flows around numerous dark boulders.\n\nPresented with a stable tripod long exposure: rapids merge into smooth, milky-white ribbons extending along the riverbed and continuous soft foam trails, with water carving elegant arcs around rocks while the water surface retains subtle grey-cyan gradations; all rocks remain wet, coarse, and razor-sharp. Steep, nearly barren black mountain slopes on the left and right form a V-shaped canyon mouth converging into the distance.\n\nThe distant sky is replaced by a tsunami wave of unfathomable scale, its deep cyan-grey water curling down from high on the upper left, forming a massive arched vortex wall and a dark wave barrel above the canyon. Using a long-exposure and time-stack aesthetic: water textures on the giant wave's surface stretch into continuous broad arcs along the curling direction, spray at the crest is drawn out into soft milky-white misty trails, and low clouds, mountain mist, and the wave crest transition smoothly; yet the wave's thickness, cavernous dark barrel, and water mass remain distinctly realistic, without turning into clouds.\n\nOn the lower-left riverbank, a black silhouette of an adult traveler facing away from the camera occupies approximately 4% of the frame height, remaining sharp. A pale overcast sky provides cool diffuse light from the upper right, with an overall palette of cool cyan-grey, charcoal black, and a touch of dark ochre, low saturation, high dynamic range, deep depth of field, and subtle film grain.\n\nMotion blur applies only to the river, giant wave surface, spray, and clouds/mist; the figure and topography remain sharp. No cities, no boats, no animals, no text, no logos, no watermarks, no lightning, no neon.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099375039166747111"></a>

### Surreal mountain waterfall long-exposure photography prompt, featuring layered silk water curtains, solitary peak mist, and a tiny figure in a black cloak.

Author：[@listudio](https://x.com/listudio) · [Source](https://x.com/listudio/status/2099375039166747111)

Photography · Character · Landscape / Nature · Published

**Summary:** Surreal mountain waterfall long-exposure photography prompt, featuring layered silk water curtains, solitary peak mist, and a tiny figure in a black cloak.

<img src="images/2099375039166747111-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Create a 9:16 vertical, photorealistic surreal mountain waterfall long-exposure photograph. The left foreground features a massive dark-brown layered cliff occupying nearly half the width, with coarse rock strata stacked diagonally and remaining sharp; an alpine gap on the upper left pours out an unusually wide silver-gray waterfall. Visual result of a steady tripod long exposure lasting tens of seconds to several minutes: as the waterfall plunges from high above, it merges into a heavy, smooth, continuous vertical silk water curtain, with fine parallel water threads clearly discernible; upon landing, the massive torrent is compressed by the terrain into dozens of forward-curving, spreading milky-white ribbon-like tiers, each water crest forming a smooth continuous curve, foam smoothed by time into a soft texture while retaining the depth of gray water veins, never appearing cotton-like flat dead white. The sharp, dark solitary peak on the middle-right remains clear, while mid-mountain water vapor is drawn by horizontal wind into a low-lying fog band during the long exposure, partially obscuring the distant background. Pale overcast diffuse light, cool gray, coal black, dark ochre, with the water body bright but not overexposed. At the bottom is a narrow, wet brown shore where an adult figure wearing a long black cloak stands slightly right of center with their back to the camera, occupying only about 3% of the frame height, completely sharp. Motion blur applies only to the water flow, foam, mist, and water vapor; rocks, shore, peaks, and figure remain sharp. Low saturation, subtle film grain, solemn, cold, with an authentic cataclysmic scene feel. The four corners and edges of the frame must be completely clean, free of any recognizable or unrecognizable characters, letters, numbers, signatures, seals, marks, inscriptions, logos, watermarks, dates, or decorative symbols.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099378304985989553"></a>

### Generate a 3x3 nine-grid photograph featuring fun, candid failure characteristics such as finger obstruction, out-of-focus blur, motion shake, etc.

Author：[@Jane20121221](https://x.com/Jane20121221) · [Source](https://x.com/Jane20121221/status/2099378304985989553)

Photography · Published

**Summary:** Generate a 3x3 nine-grid photograph featuring fun, candid failure characteristics such as finger obstruction, out-of-focus blur, motion shake, etc.

<img src="images/2099378304985989553-1.jpg" alt="Image 1" width="480" />

<img src="images/2099378304985989553-2.jpg" alt="Image 2" width="480" />

<img src="images/2099378304985989553-3.jpg" alt="Image 3" width="480" />

<img src="images/2099378304985989553-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
Various failed amateur photos, 3x3, 9:16
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099106601538097211"></a>

### Realistic snapshot of a young Japanese woman holding a strap handle in a deep V-neck camisole from the perspective of a seated person inside a train.

Author：[@SGRationalnvest](https://x.com/SGRationalnvest) · [Source](https://x.com/SGRationalnvest/status/2099106601538097211)

Photography · Portrait / Selfie · Character · Vehicle · Published

**Summary:** Realistic snapshot of a young Japanese woman holding a strap handle in a deep V-neck camisole from the perspective of a seated person inside a train.

<img src="images/2099106601538097211-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
24 years old, Japanese woman, train, front view, leaning forward, holding onto a high hanging strap, armpits exposed, deep V-neck camisole, looking directly forward, looking down expression, perspective from a seated person, smartphone photo, realistic texture, vertical shot
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098866288957551034"></a>

### A photorealistic blockbuster still of a woman in a charcoal riding coat leaping over a dry stone river atop a living quartz stag in hard sunlight.

Author：[@TraffAlex](https://x.com/TraffAlex) · [Source](https://x.com/TraffAlex/status/2098866288957551034)

Photography · Character · Published

**Summary:** A photorealistic blockbuster still of a woman in a charcoal riding coat leaping over a dry stone river atop a living quartz stag in hard sunlight.

<img src="images/2098866288957551034-1.jpg" alt="Image 1" width="480" />

<img src="images/2098866288957551034-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
A photorealistic blockbuster still. A woman in a charcoal riding coat clings to the neck of a stag whose body is living quartz, antlers a chandelier of points throwing shards of daylight. They are mid-leap over a dry river of white stones, hooves not yet down, her coat a flag. Hard sun, prism rainbows on her cheek. Palette: quartz, charcoal, sky-bleach, a cut of her blood-warm skin. Kinetic, no saddle gun, no violence — speed. 35mm, 2:3 aspect ratio.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098868060228927512"></a>

### Photorealistic jungle action frame of a woman in muddy khaki fleeing a floral plant monster in the rain.

Author：[@TraffAlex](https://x.com/TraffAlex) · [Source](https://x.com/TraffAlex/status/2098868060228927512)

Photography · Character · Published

**Summary:** Photorealistic jungle action frame of a woman in muddy khaki fleeing a floral plant monster in the rain.

<img src="images/2098868060228927512-1.jpg" alt="Image 1" width="480" />

<img src="images/2098868060228927512-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
A photorealistic jungle-edge action frame. A woman in mud-spattered khaki runs toward camera, eyes wide; behind her a three-story ogre built of wet heliconia, ginger and bird-of-paradise, a mouth of red bracts opening, pollen like smoke. Rain. Palette: cadmium red, jungle green, khaki, the yellow of a heliconia beak. Petals tear off in her wake. 35mm, rain on the lens. 2:3 aspect ratio.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098799449237782991"></a>

### Photography prompt for a 3x3 nine-grid depicting a woman in an ancient boudoir progressively dressing in a red-orange Tang-style costume layer by layer.

Author：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2098799449237782991)

Photography · Portrait / Selfie · Character · Fashion Item · Published

Source：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2097630845435572490)

**Summary:** Photography prompt for a 3x3 nine-grid depicting a woman in an ancient boudoir progressively dressing in a red-orange Tang-style costume layer by layer.

<img src="images/2098799449237782991-1.jpg" alt="Image 1" width="480" />

<img src="images/2098799449237782991-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
【Ancient Style Dressing Full Process | Red-robed Mu Peiling · Ancient Boudoir】

Professional high-end ancient style portrait photography; 9:16 vertical full canvas, internally strictly a 3 columns × 3 rows nine-grid (3x3 grid), with uniform grid sizes and narrow, neat gaps; each frame focuses primarily on a full-body or near-full-body composition, completely presenting the character, clothing, and dressing actions.

The same adult Eastern woman from the input reference image is the sole subject. The reference image is used exclusively to lock the character's facial features, hairstyle, body proportions, clothing design, clothing colors, patterns, textures, and final styling, without copying the reference image's white background, six-view character design sheet, front/side/back views, or avatar layouts.

The character maintains the adult Eastern female image from the reference image: long black hair, classical double bun hairstyle, gentle and delicate Eastern facial features, light and elegant makeup, and a dignified, soft feminine aura. The nine frames consistently maintain the exact same face, hair color, body proportions, and character identity.

The final outfit strictly references the complete costume design in the input image: an ancient style long dress primarily in orange-red, a red close-fitting inner layer, a light beige-brown translucent outer robe with wide sleeves, a layered skirt structure, waist ties, and exquisite metal ornaments, overall presenting the characteristics of classical Tang-style women's attire. Strictly maintain the red-orange and beige-brown color palette, clothing silhouette, sleeve shape, skirt shape, patterns, fabric transparency, and decorative details from the reference image, without transforming it into Song dynasty, Ming dynasty, modern clothing, or Xianxia fantasy costumes.

The nine grids depict the same adult woman consecutively completing the dressing process of the entire ensemble within an ancient boudoir:

Frame 1: Wearing only traditional ancient Eastern female inner garments, the upper body is a plain ancient chest wrap style, and the lower body is matching plain ancient undergarments, using ancient fabrics and traditional garment structures, simple and elegant; long black hair naturally draped down, the final double bun hairstyle not yet completed, wearing no outer garments or ornaments, standing beside a wooden clothes rack preparing to dress.

Frame 2: On the basis of the existing ancient inner garments, puts on the red-orange close-fitting inner top from the reference image, retaining all garments from Frame 1.

Frame 3: Puts on the main red-orange long skirt from the reference image, adjusting the waistband and hemline to form the complete inner costume.

Frame 4: Slips into the light beige-brown translucent outer robe, naturally slipping arms into the wide sleeves, retaining all previous garments.

Frame 5: Completes putting on the translucent outer robe, adjusting the wide sleeves, lapel, and layered skirt hem, allowing the clothing silhouette from the reference image to be fully displayed.

Frame 6: Ties the waist ribbons and metal ornaments from the reference image, adjusting the waist and lapel in front of the vanity mirror.

Frame 7: Smooths out the outer robe and skirt hem, adjusting the wide sleeves and train so that all clothing layers drape naturally, with the overall look nearing completion.

Frame 8: Sitting by the edge of the boudoir daybed putting on the ancient style shoes from the reference image, while putting on simple accessories like earrings from the reference image, and completing the double bun hairstyle.

Frame 9: Fully completes the hairstyle, clothing, and accessories, black double bun hairstyle fully styled, red-orange main skirt, beige-brown translucent outer robe, waist ornaments, footwear, and all accessories fully equipped; standing naturally before an ancient bronze mirror, presenting the complete final look from the input reference image.

Each frame strictly inherits all clothing already completed in the previous frame, only adding or completing one distinct step; the clothing state accumulates frame by frame, and must not disappear, be replaced, change color, be redesigned, or change style. Frame 1 must maintain the ancient traditional inner garment state, and Frame 9 must be highly consistent with the complete clothing in the reference image. The hairstyle also completes step-by-step, Frame 1 maintaining naturally loose hair, and Frames 8 to 9 gradually completing the double bun hairstyle from the reference image.

The background is an authentic ancient women's boudoir with a sense of ancient life; wooden lattice windows, plain sheer curtains, ancient wooden clothes rack, vanity table, bronze mirror, clothes chest, low daybed, wooden screen, a few book scrolls, and flower branches; the space is elegant, warm, and restrained, not cluttered with palace-style decorations, with no modern furniture or modern items. The overall environmental relationship is dominated by warm beige, light wood tone, and dark red-orange, harmonizing naturally with the reference costume.

Natural window light enters the interior, soft and realistic light and shadow, professional ancient style portrait photography, high-end fashion Editorial visual texture; real natural skin texture, realistic hair strands, realistic fabric folds and weight, the translucent outer robe features a natural light-transmitting effect, embroidery, fabric weave, waist metal ornaments, and clothing layers clearly visible; the whole image possesses authentic photographic quality, avoiding obvious CG character concept art effects.

The nine-grid maintains a unified photography system and spatial continuity; character's facial features, hairstyle, body type, clothing design, colors, materials, boudoir structure, and lighting direction remain highly consistent; character poses naturally vary according to real dressing behaviors, allowing standing, turning, arranging clothes, sitting on the daybed, looking in the mirror, etc., but each frame must have a distinct clothing state progression.

Bottom left signature "● DeepBlue"; "●" is a solid #0B3D91 dark blue circle, "DeepBlue" is a natural, delicate white handwritten font.

No modern bras, modern panties, modern underwear sets, modern lace underwear, modern bra strap structures, modern underwear cuts, modern clothing, modern furniture, modern objects, modern styling/makeup, different characters, different hair colors, modern hairstyles, Xianxia costumes, Song-style clothing, clothes suddenly disappearing, clothes suddenly appearing, clothing color changes, clothing style changes, hairstyle sudden changes, scene jumps, reference image six-view layouts, character design sheets, white studio backgrounds, duplicated steps, extra people, text, numbers, titles, watermarks, or brand logos.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098610123900064236"></a>

### A candid travel snapshot of an East Asian woman wearing mouse ears and posing in front of a fantasy castle.

Author：[@Aqsahere\_](https://x.com/Aqsahere_) · [Source](https://x.com/Aqsahere_/status/2098610123900064236)

Photography · Character · Published

**Summary:** A candid travel snapshot of an East Asian woman wearing mouse ears and posing in front of a fantasy castle.

<img src="images/2098610123900064236-1.jpg" alt="Image 1" width="480" />

<img src="images/2098610123900064236-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
A realistic candid travel photo of a young East Asian woman having a fun, magical day at a fairytale castle. She’s standing in front of a grand European-style fantasy castle with tall ivory towers, elegant blue rooftops, golden spires, intricate stone details, and beautiful old-world architecture. The castle takes up most of the background, giving the scene a dreamy theme-park vacation feel.\nShe has long, naturally wavy chestnut-brown hair falling loosely over her shoulders and back. She’s wearing a cute blue-and-lavender glittery mouse-ear headband and smiling naturally while looking slightly upward and to the side, as if caught in a genuine happy moment.\nShe wears a cropped cream-white textured jacket with gold buttons over a clean white collared shirt and patterned plaid tie. Her high-waisted beige, cream, and muted-blue plaid skort has soft pleats that move naturally with her pose.\nShe stretches both arms outward and leans slightly toward the camera with an excited, playful energy. The pose feels spontaneous rather than posed, like a real vacation snapshot.\nThe castle courtyard behind her has wide pale-stone steps, decorative railings, colorful banners, and detailed medieval-inspired architecture. The sky is softly overcast with pale blue-gray clouds, creating gentle, flattering daylight and natural shadows.\nUltra-photorealistic travel photography, authentic youthful appearance, realistic skin texture, natural hair strands, detailed fabric textures, believable proportions, soft depth of field, subtle natural shadows, vibrant but slightly muted colors, candid smartphone photo aesthetic, dreamy vacation atmosphere, highly detailed, vertical 3:4 composition.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098616431122559479"></a>

### iPhone candid snapshot style campus sports field female student documentary photography prompt

Author：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2098616431122559479)

Photography · Portrait / Selfie · Published

Source：[@DDJCXX](https://x.com/DDJCXX) · [Source](https://x.com/DDJCXX/status/2098240447038767437)

**Summary:** iPhone candid snapshot style campus sports field female student documentary photography prompt

<img src="images/2098616431122559479-1.jpg" alt="Image 1" width="480" />

<img src="images/2098616431122559479-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Campus daily documentary; delightfully accidental; iPhone original camera candid snapshot; narrow shoulders and extremely slim waist, exaggerated bust female student🙆🏻‍♀️
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098277829154951371"></a>

### Seaside fine art photography featuring an asymmetrical composition with a coral-pink sailboat anchored in a quiet, deserted bay, framed by a pine tree on the right.

Author：[@listudio](https://x.com/listudio) · [Source](https://x.com/listudio/status/2098277829154951371)

Photography · Vehicle · Published

**Summary:** Seaside fine art photography featuring an asymmetrical composition with a coral-pink sailboat anchored in a quiet, deserted bay, framed by a pine tree on the right.

<img src="images/2098277829154951371-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Create a 3:4 vertical seaside fine art photograph. A tranquil, deserted bay with a clear gray-blue sky occupying the upper seventy percent, and a straight deep blue horizon below. A realistic small monohull sailboat is anchored slightly to the left of the lower-middle section, its slender mast extending into the sky, its coral-pink triangular sail gently billowed with believable canvas stitching and tension, a narrow deep-blue strip at the foot of the sail, a pinkish-white cabin, pitch-black windows, a coral-red lower hull, and plausible thin rigging. The calm teal-blue water surface has fine horizontal ripples and soft, fragmented pink reflections. On the right side, a dark pine tree creates an asymmetrical frame, with its trunk rising from the lower right and its canopy reaching in from the upper right, the needles showing sparse dark reddish-pink daylight highlights while preserving a vast expanse of sky. At the very bottom is a strip of fine pinkish-white sand beach with faint tree shadows. Realistic hull, tree bark, pine needles, and seawater, crisp daylight, deep shadows, subtle film grain, understated matte print texture, surreal colors yet believable spatial depth, quiet, lingering, dreamlike, and detached. No people, text, logo, or watermark.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098277612053561383"></a>

### Surreal art photography of a pink-white salt shore and ocean transitioning from coral red to deep blue.

Author：[@listudio](https://x.com/listudio) · [Source](https://x.com/listudio/status/2098277612053561383)

Photography · Landscape / Nature · Published

**Summary:** Surreal art photography of a pink-white salt shore and ocean transitioning from coral red to deep blue.

<img src="images/2098277612053561383-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Create a 3:4 vertical surreal color art photograph. An empty coast without people, with the upper quarter featuring a uniform grayish cobalt blue sky and an extremely thin light pink distant shore traversing the high horizon. A pinkish-white saline shore bank extends from the left down to the foreground, with coarse crystalline grains, loose gravel, and naturally eroded edges clearly visible, the shoreline forming a gentle, asymmetrical arc. The shallow waters near the shore are a rich coral red, vermilion, and pink, with several slender breaking ripples advancing diagonally toward the lower right, gradually transitioning into the deep Prussian blue sea on the right; the water has realistic transparency, fine ripples, and reflections, not resembling paint or lava. Sunny side-lighting, pinkish-white highlights that retain detail, clean large color blocks contrasted with authentic microscopic textures, delicate film grain, a matte print feel, quiet, unfamiliar, blazing yet cool. Full-bleed photograph, no text, borders, logos, or watermarks.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098277688498880901"></a>

### Surreal red-coated piebald horse portrait photography against a pure blue sky background.

Author：[@listudio](https://x.com/listudio) · [Source](https://x.com/listudio/status/2098277688498880901)

Photography · Portrait / Selfie · Abstract / Background · Published

**Summary:** Surreal red-coated piebald horse portrait photography against a pure blue sky background.

<img src="images/2098277688498880901-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Create a 3:4 vertical surreal animal portrait art photograph. A low-angle shot of a robust piebald horse's head, neck, and shoulder-chest, with the body naturally cropped at the bottom and right side. The horse's head is positioned in the lower-middle, turned to the left in a three-quarter profile, with ears naturally erect, and deep black, moist eyes showing subtle reflections. The upper third is left with a cloudless, pure cobalt blue sky. The coat color features detailed surreal recoloring: primarily rich brick red and coral red, with large irregular pinkish-white patches from the bridge of the nose to the muzzle, and sparse deep blue accents between the red and white patches on the shoulder and chest. The long mane is swept to the left by a strong wind blowing from the right, with slender overlapping strands where bright red hairs interweave with deep burgundy shadows, partially cascading down the neck. Realistic details of short coat, nostrils, whiskers, and musculature. Bright natural side lighting, dense and layered shadows, sharp photography freezing a split second, subtle film grain and matte tones, evoking a wild, free, vivid fashion editorial feel. No harness, humans, text, logo, or watermark.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098277762410942530"></a>

### Red and blue contrasting surreal cactus botanical photography featuring flat coral red prickly pear pads and deep cobalt blue columnar cacti.

Author：[@listudio](https://x.com/listudio) · [Source](https://x.com/listudio/status/2098277762410942530)

Photography · Published

**Summary:** Red and blue contrasting surreal cactus botanical photography featuring flat coral red prickly pear pads and deep cobalt blue columnar cacti.

<img src="images/2098277762410942530-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Create a 3:4 vertical surreal botanical art photograph. A slightly muted, cloudless azure sky serves as the background, viewed from a low angle looking up at a cluster of real cacti growing cropped from the bottom edge. From the left to the center, three to five staggered oval flat prickly pear pads are arranged, with the tallest pad tilting slightly to the left; their skin is recolored in vibrant coral red and watermelon red, preserving the waxy matte texture, fine undulating wrinkles, and regular yet non-mechanical areoles. On the right stands a tall, deep cobalt blue columnar cactus featuring distinct vertical ribs, deep Prussian blue grooves, and vermilion star-shaped spines arranged along the rib edges. At the bottom, a few blue flat pads overlap with small red pads, forming distinct layers, leaving negative space for the sky on the upper left. Strong natural sunlight from the upper left illuminates the botanical volume and spines; vivid colors are anchored to convincing plant tissue. Sculptural, asymmetrical geometric composition, fine photographic textures, slight film grain, restrained matte finish, avoiding any plastic or 3D render look. No pots, flowers, text, logo, or watermark.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097886029692969195"></a>

### Chinese internet celebrity bedroom mirror selfie photoshoot prompt, showcasing a short hair low-cut outfit and soft indoor lighting style.

Author：[@ohmuyi](https://x.com/ohmuyi) · [Source](https://x.com/ohmuyi/status/2097886029692969195)

Photography · Portrait / Selfie · Influencer / Model · Fashion Item · Architecture / Interior · Published

**Summary:** Chinese internet celebrity bedroom mirror selfie photoshoot prompt, showcasing a short hair low-cut outfit and soft indoor lighting style.

<img src="images/2097886029692969195-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
3:4, mobile phone close-up mirror selfie, Chinese internet celebrity, cool fair skin, black short bob with light airy straight bangs, tight-fitting low-cut short-sleeved top, phone covering the right one-third of the face, bedroom with white bed and black-framed mirror, soft indoor lighting, gentle and charming
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097532595814940683"></a>

### Realistic travel portrait prompt of a young East Asian woman on the coast of Mont Saint-Michel.

Author：[@saniaspeaks\_](https://x.com/saniaspeaks_) · [Source](https://x.com/saniaspeaks_/status/2097532595814940683)

Photography · Portrait / Selfie · Character · Published

**Summary:** Realistic travel portrait prompt of a young East Asian woman on the coast of Mont Saint-Michel.

<img src="images/2097532595814940683-1.jpg" alt="Image 1" width="480" />

<img src="images/2097532595814940683-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
A photorealistic candid travel portrait of a young East Asian woman standing on a quiet sandy shoreline beside large moss-covered rocks, with a magnificent historic stone abbey and medieval castle-like architecture rising dramatically on a rocky island behind her. She has long straight dark brown hair falling naturally over one shoulder, soft youthful facial features, and a gentle warm smile while looking directly at the camera.\n\nShe is wearing a long oversized black coat with her hands casually tucked inside the pockets, layered over a light-colored outfit. A large soft cream-white scarf is wrapped warmly around her neck, hanging down the front with a small black designer-style emblem near the end. A delicate chain shoulder bag is partially visible.\n\nThe composition captures her in the foreground while the vast historic abbey dominates the background, surrounded by ancient stone walls, rocky cliffs, sandy tidal flats, and a calm coastal atmosphere. A few small distant vehicles and people add realistic scale to the scene. Soft natural evening light and a clear pale blue sky create a peaceful European travel mood.\n\nUltra-realistic photography, authentic candid travel photo, natural skin texture, realistic fabric details, soft cinematic lighting, subtle smartphone camera aesthetic, slightly dreamy color grading, natural proportions, detailed architecture, peaceful coastal atmosphere, vertical composition, 3:4 aspect ratio.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097411028510179759"></a>

### High-definition landscape photo prompt of a forest clearing with dense green foliage.

Author：[@mark\_k](https://x.com/mark_k) · [Source](https://x.com/mark_k/status/2097411028510179759)

Photography · Landscape / Nature · Published

**Summary:** High-definition landscape photo prompt of a forest clearing with dense green foliage.

<img src="images/2097411028510179759-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Photo of a clearing in the woods with lots of green foliage, highly detailed
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101617615538110920"></a>

### A realistic portrait prompt of a young woman wearing a white string bikini with her hands resting on a railing, set against a blue sea and ship deck.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2101617615538110920)

Photography · Portrait / Selfie · Character · Vehicle · Landscape / Nature · Abstract / Background · Published

**Summary:** A realistic portrait prompt of a young woman wearing a white string bikini with her hands resting on a railing, set against a blue sea and ship deck.

<img src="images/2101617615538110920-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
White Ribbons of the Blue Sea

Main Subject:
In the center of the frame, set against a bright blue sea, a young woman stands wearing a white string bikini, resting both hands on a silver ship railing. Large white ribbons on both hips and wet hair take center stage.

Person & Expression:
Slender oval face, small chin, large bright hazel eyes, thin eyebrows, a clean nasal bridge, and glossy pink lips showing a glimpse of teeth. Her head is tilted slightly to the right, smiling brightly directly at the camera. Her wet, light brown, below-the-shoulder layered hair features thin bangs and face-framing strands, flowing toward her right shoulder in the sea breeze.

Attire & Pose:
A pearl-white triangle halter-neck bikini top with thin shoulder straps and a thin underbust string, paired with matching high-leg bikini bottoms featuring long, double-tied bow ribbons on both hips. She stands with her legs slightly apart, upper body leaning forward slightly, arms extended downward, resting both hands on the silver railing behind her.

Background & Lighting:
A sparkling blue sea across the entire background, with blurred blue-gray mountain ranges and a pale sky at the top, and a silver ship railing and narrow wooden deck at the bottom of the frame. Hard direct sunlight from the upper left illuminates her hair, face, shoulders, chest, and abdomen, creating large white bokeh circles on the water's surface.

Composition & Camera:
9:16 vertical composition, straight-on camera at the subject's waist level capturing a near full-body portrait from the top of the head to mid-thigh. The subject is framed prominently in the center, the sea covers the entire background, and the white ribbons at her waist spread outward to the left and right. Arms and thighs are cropped at the bottom edge, with sharp focus on both eyes and face, while the mountain ranges are blurred with a shallow depth of field.

Texture & Style:
Photorealistic live-action photograph. High-definition rendering of natural wet skin, fine strands of hair, white swimsuit fabric, long ribbons, metallic railing, and water reflections, featuring a clean summer palette of white and vivid blue.

Negative:
Omission of white ribbons on both hips; dark sky or land-based background
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101603522584387793"></a>

### A realistic portrait photo of a woman in a black bikini lying prone on a sandy beach by a blue sea, holding out a plumeria flower.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2101603522584387793)

Photography · Portrait / Selfie · Character · Published

**Summary:** A realistic portrait photo of a woman in a black bikini lying prone on a sandy beach by a blue sea, holding out a plumeria flower.

<img src="images/2101603522584387793-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
White Flower on a Sandy Beach

Main Subject:
From the center to the left of the frame, a young woman lies prone in a black string bikini on the sand of a vibrant blue cove, extending her left hand toward the camera holding a white flower. A smiling face, sand-dusted arms, and bare feet raised and crossed behind her take center stage.

Person / Facial Expression:
A slender face with gentle contours, a small chin, large light brown eyes, thin eyebrows, a neat nose bridge, and glossy pink lips smiling brightly. Her face is turned directly forward, gazing warmly into the low-angle camera. Her dark brown hair is gathered in a messy bun on the crown of her head, with wispy bangs and strands damp with sand falling over her cheeks and shoulders.

Clothing / Pose:
A black triangle bikini top with thin shoulder straps, paired with black low-rise bikini bottoms tied with thin strings on both hips. Lying face down on the sand, her right elbow is bent with her right cheek resting on her hands, while her left arm alone extends forward toward the foreground holding a white-and-yellow plumeria. Both knees are bent backward, with her bare ankles crossed high in the air.

Background / Lighting:
Coarse, pale sand in the lower portion of the frame; white-capped waves and a transparent turquoise sea in the center; rocky reefs, a verdant island, blue sky, and white clouds in the upper area, with a slender shadow cast by tree shade at the far left edge. Harsh, direct midday sunlight from above illuminates her face, shoulders, arms, and legs, making the sand grains and the sea surface glisten intensely.

Composition / Camera:
A 3:4 vertical composition, taken from a low front-facing camera skimming the sand's surface, capturing the entire body from the foreground flower to her face, torso, and the crossed tips of her feet in the background. The white flower is placed prominently in the lower-left foreground, her face at center-left, and her raised feet in the upper half. The flower is softly blurred, focus is sharp on her face and eyes, and the distant coastline is shallowly blurred.

Texture / Style:
A photorealistic live-action photograph. High-definition rendering of natural wet skin and hair, clinging grains of sand, black swimsuit fabric, the white flower, and transparent waves, presented in dazzling tropical colors of black, sand tones, and turquoise.

Negative:
Changes to the prone pose and crossed feet; omitting the white flower
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101631708328272158"></a>

### A photorealistic three-quarter portrait prompt of a young woman smiling in the shade by a blue seaside, wearing a sheer white cover-up and a blue floral swimsuit.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2101631708328272158)

Photography · Portrait / Selfie · Character · Published

**Summary:** A photorealistic three-quarter portrait prompt of a young woman smiling in the shade by a blue seaside, wearing a sheer white cover-up and a blue floral swimsuit.

<img src="images/2101631708328272158-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Blue Flowers and White Sea Breeze

Main Subject:
In the center of the frame, in the shade by a blue seaside, a young woman leans forward, wearing a blue floral print swimsuit on a white base and a sheer white cover-up. A big smile, long wet hair, and a wooden bench and rattan bag on the left serve as focal elements.

Person / Facial Expression:
A slender oval face, small chin, light brown eyes smiling narrowly, thin eyebrows, a clean nasal bridge, and glossy reddish-pink lips widely showing white teeth. Tilting her face to the left, she beams a full smile directly at the camera. Extremely long, wet dark brown hair with thin bangs and strands crossing her face flows from her left shoulder over her chest.

Clothing / Pose:
A triangle halter swimsuit top featuring light and dark blue floral patterns on a white base, trimmed with white ruffles and a thin tie knot at the center of the bust. A sheer white short-sleeved shirt is slipped off both shoulders and worn on the arms, paired with a short white lace wrap skirt tied at the right hip. Leaning her upper body forward with both knees slightly bent, she extends both arms downward, resting one hand over the other between her knees.

Background / Lighting:
On the left of the frame are a thick wooden post, a wooden bench, a rattan bag, and blue-and-white fabric; from the center to the right are a sandy beach, white waves, a vibrant turquoise sea, a distant green island, and blue sky with white clouds above. Hard direct sunlight from above illuminates her face, hair, shoulders, and chest, creating shimmering white highlights on the water's surface.

Composition / Camera:
Vertical 3:4 composition, a three-quarter portrait capturing from the top of the head to mid-thigh taken with a front-facing camera positioned slightly lower than the subject's waist. The subject is placed prominently at center-right, the rattan bag at the lower left, and the sea and island in the upper half. Both arms and legs are cropped at the bottom edge; sharp focus on the smile and eyes, with the distant background softly blurred.

Texture / Style:
Photorealistic live-action photograph. High-definition rendering of natural wet skin and hair, blue floral patterns, sheer white fabric, lace, rattan, sand, and ocean surface, enveloped in cheerful summer light dominated by white, blue, and sand tones.

Negative:
Altering the big toothy smile; omitting the blue floral pattern and white cover-up
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101645801294360989"></a>

### A photograph-style prompt of a woman in a white swimsuit looking back on a tropical beach.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2101645801294360989)

Photography · Character · Published

**Summary:** A photograph-style prompt of a woman in a white swimsuit looking back on a tropical beach.

<img src="images/2101645801294360989-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Looking Back at the Azure Beach

Main Subject:
Captured from behind, a young woman standing on a clear tropical beach in the lower half of the frame. The white swimwear, a white shirt wrapping her waist and arms, a red puppy-style tattoo on her left buttock, and the vivid blue sky and azure sea take center stage.

Person & Expression:
A smooth oval profile, small chin, slender eyebrows, dark brown eyes with long eyelashes, a clean nose bridge, and closed reddish-pink lips. Her face is turned to the left, quietly casting her gaze toward the distant sea. Her dark brown hair is styled in a casual round bun at the back of her head, with thin bangs and long tendrils flowing along her cheeks and neck.

Attire & Pose:
A white thin-string halter bikini tied in a bow at the center of the back, and white high-cut bottoms. A sheer white long-sleeved shirt dropped off the shoulders and wrapped around both forearms and waist, back turned toward the camera with her weight on her right leg. Arms lowered in front of her body, with a small red-line floppy-eared puppy and heart tattoo on her left buttock.

Background & Lighting:
From left to center are transparent shallow waters, with a deep blue sea and a low island offshore; on the right, white sand and rugged coral rocks; covering most of the upper part are a deep blue sky and cumulus clouds, with green leafy branches at the upper right. Harsh summer sunlight from above illuminates her shoulders and back, creating fine glints of light on the water's surface.

Composition & Camera:
A 9:16 vertical composition, shot from behind close to waist height, capturing a near full-body portrait from the expansive sky overhead down to below the thighs. The subject is positioned prominently in the lower center, with her profile and back facing left, and the coastline extending toward the back right. The legs are cropped at the bottom edge, sharp focus on the subject and tattoo, with the distant island lightly blurred.

Texture & Style:
Photorealistic live-action photograph. Natural sunlit skin, fine wrinkles in the white cloth, wet sand, transparent water, and coral rocks depicted in high definition, with intense midday colors of ultramarine, turquoise, and white.

Negative:
Frontal face or long hair; omitting white outfit and puppy tattoo
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101542872772219010"></a>

### A portrait of a woman in a black ring-embellished bikini and sunglasses, looking down from a boat hatch against a blue sky.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2101542872772219010)

Photography · Portrait / Selfie · Character · Vehicle · Abstract / Background · Published

**Summary:** A portrait of a woman in a black ring-embellished bikini and sunglasses, looking down from a boat hatch against a blue sky.

<img src="images/2101542872772219010-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Black Rings of the Boat Window

Main Subject:
In the center of the frame, looking up from below through the open hatch of a boat, a young woman leans forward wearing a black ring-embellished bikini. Dark sunglasses, a vivid blue sky, and the black rim of the hatch take center stage.

Person & Expression:
A slender oval face, small chin, eyes faintly visible through large black rectangular sunglasses, thin eyebrows, a clean nasal bridge, and slightly parted pink lips. Her face is directed downward toward the camera below, casting a quiet gaze downward. Long, wet dark brown hair with thin bangs blows in the wind toward the left of the frame. Small gold hoop earrings in both ears.

Attire & Pose:
A black thin-strap bikini top features a large gold ring at the center of the chest with fine gathers, and black bikini bottoms feature gold rings on both hips, thin double straps, and a short gold chain dangling on the right side. Crouching with legs apart over the hatch, her right arm extends downward with her right hand resting on the foreground rim, while her left elbow is bent with her left hand placed on the hair at the crown of her head.

Background & Lighting:
A clear blue sky spans the entire background; metal pipes and rigging appear in the upper left, the boat's black hatch frame lines the top and bottom edges, and the underside of the hull is visible in the upper right. Harsh, direct sunlight from above illuminates her face, chest, abdomen, and arms, creating sharp reflections on the sunglasses and gold rings.

Composition & Camera:
A 3:4 vertical composition, an extreme low-angle shot looking straight up from inside the cabin, capturing a near-full-body portrait framed from the top of her head to both thighs. The subject is featured prominently in the center, with the hatch frame forming diagonal lines at the top and bottom, leaving the blue sky as broad negative space. The legs and right hand are cropped at the edges of the frame; focus is sharp on the face and upper body, while the sky remains smooth.

Texture & Style:
Photorealistic live-action photography. High-definition rendering of natural wet skin and hair, black swimwear fabric, metallic rings and chain, dark lenses, and the metal boat frame, with intense summer colors of black, gold, and vivid blue.

Negative:
Altering the low-angle perspective looking up through the boat window; omitting the gold rings
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101569548671705452"></a>

### Realistic vertical portrait photography prompt of a woman sitting on a bed in a warm-toned bedroom, pinching the ribbon of a peach satin and floral lace minidress.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2101569548671705452)

Photography · Portrait / Selfie · Character · Fashion Item · Published

**Summary:** Realistic vertical portrait photography prompt of a woman sitting on a bed in a warm-toned bedroom, pinching the ribbon of a peach satin and floral lace minidress.

<img src="images/2101569548671705452-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Theme:
Peach Lace Knot

Subject:
In the center of the frame, in a warm-toned bedroom, a young woman sits on a bed with knees spread apart, holding the central ribbon of her peach-colored satin and floral lace minidress with both hands. The three-dimensional lace at the chest and her soft smile are the focal points.

Person & Expression:
Slender oval face, small chin, large light brown eyes, thin eyebrows, neat nose bridge, glossy peach lips revealing teeth slightly. Face slightly tilted to the right, smiling gently at the camera straight ahead. Light brown hair gathered low at the back of the head, with thin bangs and long tendrils falling along both cheeks. Small silver flower-shaped pendant necklace.

Attire & Pose:
A dusty-peach thin-strapped satin minidress with triangular cups, covered all over with matching-colored three-dimensional small floral embroidered lace, a long central satin ribbon, and a short lace hem. Sitting on the bed with knees spread outward to the left and right, both elbows bent, left and right hands each pinching an end of the chest's central ribbon.

Background & Lighting:
Wrinkled off-white bedding at the bottom of the frame, a wooden side table, a glass vase with white flowers, and a fabric-shade lamp on the left side of the frame, white pillows and a peach knitted cushion on the right side of the frame, and light-colored curtains in the background. The lamp on the left of the frame and soft warm frontal light evenly illuminate her face, chest, hands, satin, and lace.

Composition & Camera:
3:4 vertical composition, frontal camera slightly higher than the seated subject's chest, capturing a three-quarter portrait from the top of the head to the spread thighs. The subject is prominent in the center, with the face in the upper half, both hands and ribbon in the center, and thighs placed at the lower left and right. Legs are cropped at the left, right, and bottom edges; sharp focus on the eyes and the chest ribbon, with the bedroom background softly blurred.

Texture & Style:
Photorealistic live-action photograph. Natural skin, soft hair, lustrous satin, three-dimensional floral lace, slender ribbon, and bedding rendered in high detail, with a gentle evening palette of peach, off-white, and amber tones.

Negative:
Omitting the chest ribbon held by both hands; red or black outfits
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101297254481223763"></a>

### Portrait prompt of a young woman in a peony-patterned kimono seated on tatami in a Japanese-style room, with realistic specifications including a folding fan and line-art thigh tattoo.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2101297254481223763)

Photography · Portrait / Selfie · Character · Published

**Summary:** Portrait prompt of a young woman in a peony-patterned kimono seated on tatami in a Japanese-style room, with realistic specifications including a folding fan and line-art thigh tattoo.

<img src="images/2101297254481223763-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Theme:
Traditional Japanese room with folding fan and peonies

Subject:
In the center of the frame, a young woman in a peony-patterned kimono sits on the tatami mats of a bright Japanese-style room, holding open a floral-patterned folding fan to the left of the frame. A large line-art tattoo of a koi fish and waves is visible on her right thigh in the foreground.

Person / Expression:
A slender oval face, small chin, large bright hazel-brown eyes, thin eyebrows, a neat nose bridge, and slightly parted glossy pink lips. Her face is tilted slightly to the right, calmly gazing directly into the camera. Her dark brown hair is styled in a high, messy updo with wispy bangs and loose strands falling along both cheeks, accented with a golden floral branch hairpin inserted at the back right of her head.

Clothing / Pose:
Wearing a one-piece-style long-sleeved kimono in unbleached ecru with large peony patterns in red, orange, and green, wrapped deeply across the chest, tied with a wide black obi featuring red-and-gold floral patterns and a thin red obijime cord. Sitting on the tatami with her legs folded under/beside her, holding the fan with her right hand and resting her left hand on the tatami to the right of the frame. Across her exposed right thigh in the foreground spreads a detailed line-art tattoo of a koi fish, waves, and flowers.

Background / Lighting:
White shoji screens on the left of the frame, a gray vase with flowering branches in the background to the right, golden fusuma sliding doors, and a low andon paper lantern. Soft daylight enters from the shoji on the left, brightly illuminating her face, kimono, and the foreground thigh, casting warm shadows toward the back right.

Composition / Camera:
2:3 vertical composition, shot from slightly above the subject seated on the tatami, capturing from the crown of the head down to her folded legs in a near-full-body close-up portrait. The face and folding fan are placed in the upper half, with the tattooed thigh positioned prominently in the lower-left foreground. The hem of the kimono is cropped at the bottom edge; sharp focus on the eyes and fan, with a soft depth of field blurring the background.

Texture / Style:
Photorealistic live-action photograph. Natural skin texture, silk luster, fine peony patterns, woven obi, Japanese washi paper of the fan, tatami weave, and fine lines of the tattoo rendered in high definition; a warm Japanese palette of ecru, vermilion, and sumi ink tones.

Negative:
Omission of the fan or the koi thigh tattoo; alteration of kimono and obi color scheme
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101282658466562299"></a>

### Realistic portrait of a young woman on a high-rise balcony with a sunset sea view, wearing an off-white openwork knit sweater with green trim and floral swimwear.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2101282658466562299)

Photography · Portrait / Selfie · Character · Landscape / Nature · Published

**Summary:** Realistic portrait of a young woman on a high-rise balcony with a sunset sea view, wearing an off-white openwork knit sweater with green trim and floral swimwear.

<img src="images/2101282658466562299-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Green-Trimmed Knit by the Sunset Sea

Main Subject:
From the center to the right of the frame, on a high-rise balcony overlooking the sun setting into the sea, a young woman sits wearing an off-white openwork knit cardigan. The green trim, chest tie, and blue ditsy floral bikini bottoms take center stage.

Person & Expression:
Slender oval profile, small chin, light brown eyes looking at the sunset on the left of the frame, thin eyebrows, clean-cut bridge of the nose, natural pink lips. Her face is turned to the left, calmly gazing at the distant horizon. Wet, extremely long wavy dark-brown hair with wispy bangs flows down her back and over her right arm.

Attire & Pose:
An off-white long-sleeved openwork knit cardigan featuring a deeply open front, dark green piping, and a green cord tied in a single knot at the chest, revealing plenty of skin. Paired with low-rise swimwear bottoms featuring scattered blue flowers and green leaves on a white background. Sitting on the edge near the window with both legs opened toward the front, arms resting down at her sides with hands placed on the seating surface.

Background & Light:
The left half of the frame shows an orange sunset, pink clouds, a blue ocean with a golden path of light, and a distant coastline at the bottom; the right side of the frame features a black window frame, indoor plants, and a wooden chair. With the low setting sun on the left as the primary light source, soft backlighting illuminates her profile, hair, shoulders, and the knit borders in gold.

Composition & Camera:
3:4 vertical composition, captured from a near-frontal camera angle positioned slightly higher than the seated subject's waist, framing a three-quarter portrait from the crown of her head to mid-thigh. The subject is framed prominently on the right half, while the sunset and horizon are arranged on the left half. Both legs are cropped at the lateral and bottom edges; focus is sharp on her profile and the green trim, with the sea moderately blurred.

Texture & Style:
Photorealistic live-action photography. High definition on wet natural skin and hair, coarse openwork knit, green piping, floral fabric, glass, and reflections on the sea surface, depicted in serene twilight tones of off-white, green, and sunset orange.

Negative:
Altering the open-front green-trimmed knit; omitting the sunset and the sea
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101239624718856403"></a>

### A live-action top-down overhead photo prompt capturing a woman in a white bikini floating on her back in an outdoor pool while resting her head on the stone edge.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2101239624718856403)

Photography · Character · Published

**Summary:** A live-action top-down overhead photo prompt capturing a woman in a white bikini floating on her back in an outdoor pool while resting her head on the stone edge.

<img src="images/2101239624718856403-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Theme:
White floating on the water surface

Main Subject:
In the center of the frame, a young woman floats straight on her back on the surface of a bright outdoor swimming pool, resting only her head on the stone edge. The white ruffled bikini, aligned long legs, and shimmering light patterns on the water surface take center stage.

Person and Expression:
A slender, inverted oval face, small chin, large brown eyes, thin eyebrows, neat nose bridge, and slightly parted reddish-pink lips. Her face is directed straight up toward the overhead camera, offering a calm gaze. Wet dark brown hair is tied in the back, with short strands spreading around her head and onto the stone edge.

Attire and Pose:
A white thin-strap triangle bikini top with delicate ruffles along the bust and edges, paired with matching low-rise bottoms with thin side ties on both hips. Lying on her back stretching her body across the water surface, legs and toes pressed together, arms opened slightly at her sides with palms submerged underwater, resting the back of her head on the stone edge in the foreground.

Background and Light:
The entire background consists of transparent pale blue pool water and platinum-gold rippling light, with a granular grayish-brown stone edge at the bottom of the frame, free of any other objects. Harsh direct sunlight from above illuminates her skin, swimsuit, and the water surface, casting shifting mesh-like caustic reflections across her whole body.

Composition and Camera:
Vertical 3:4 composition, directly overhead top-down bird's-eye camera capturing the full body from the upside-down crown of the head in the foreground to the tips of her toes in the distance. The subject is positioned prominently and vertically in the center, with her head at the lower edge and aligned legs extending into the upper half. Full body framed entirely within the shot, sharp focus on the face and chest, with crisp, clear light patterns on the water surface.

Texture and Style:
Photorealistic live-action photography. High definition detailing of natural wet skin, white ruffled fabric, transparent water, fine ripples, refracted light, and rough stone, bathed in dazzling daylight of pale light blue and white.

Negative:
Altering directly overhead bird's-eye angle and inverted head position; parting or spreading legs
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101272591956840655"></a>

### Photorealistic portrait prompt of a young woman taking a selfie wrapped in a white bath towel in a stone hot spring bathtub.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2101272591956840655)

Photography · Portrait / Selfie · Character · Published

**Summary:** Photorealistic portrait prompt of a young woman taking a selfie wrapped in a white bath towel in a stone hot spring bathtub.

<img src="images/2101272591956840655-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
White towel in hot spring lantern light

Main Subject:
Center to left of the frame, in a stone hot spring bathtub, a young woman leans close to the camera pointed at herself, wrapping a white bath towel around her chest. Wet skin and hair, blue-green hot spring water, and a water spout in the background are the main focus.

Person / Expression:
Slender oval face, small chin, large dark brown eyes, thin eyebrows, neat nose bridge, slightly parted glossy pink lips. Face tilted slightly to the right, casting a quiet gaze toward the close camera. Wet dark brownish-black hair gathered in a high messy bun, with wispy bangs and long stray strands clinging to her cheeks and neck.

Attire / Pose:
A thick, textured white bath towel wrapped strapless dress-style from her chest to her thighs, supported by her right hand gripping the right side of her chest. Sitting on the edge of the tub, her left arm extends straight toward the camera taking a selfie, and her right elbow is bent holding the towel to her body.

Background / Lighting:
On the right of the frame is a rectangular bathtub filled with blue-green hot spring water, in the background a gray-brown stone wall, a square water spout and flowing water; on the left of the frame are a wooden bucket, a small white towel, a square paper lantern, and illuminated plants above. The lantern on the left of the frame and soft warm light from above illuminate her face, shoulders, and water droplets, casting golden reflections on the water surface.

Composition / Camera:
3:4 vertical composition, a close-up bust-up selfie shot taken with an outstretched arm using a frontal camera at eye level, framing from the top of the head down to below the chest and one thigh. Face prominently placed in the upper left, towel in the lower center, and the bathtub occupying the right half. The left arm and thigh are cropped at the bottom edge; sharp focus on both eyes and face, with the water spout softly blurred.

Texture / Style:
Photorealistic live-action photograph. High-definition rendering of wet natural skin, fine stray hairs, water droplets, thick white towel, dark stone, transparent hot spring water and surface reflections, depicting a serene hot spring night scene in amber and blue-green tones.

Negative:
Changes to the white towel and the selfie left arm; dry hair
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101251955922256022"></a>

### A realistic morning light portrait of a young woman standing barefoot behind a large wooden cello.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2101251955922256022)

Photography · Portrait / Selfie · Character · Published

**Summary:** A realistic morning light portrait of a young woman standing barefoot behind a large wooden cello.

<img src="images/2101251955922256022-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Morning Light and a Large Cello

Main Subject:
In the center of the frame, in front of a white wall, a young woman stands barefoot, holding upright a wooden cello large enough to cover her body. The amber-colored body, black fingerboard, and the woman's profile and hands take center stage.

Person / Expression:
A slender profile, small chin, slightly downcast dark brown eyes, thin eyebrows, a clean nasal bridge, and natural rosy-pink lips. Her face is turned toward the lower right of the frame, quietly looking down the right side of the cello. Her long, dark brown wavy hair is half tied up at the back of her head, with wispy bangs and strands falling over her cheek, flowing over her right shoulder.

Clothing / Pose:
Clothing structures such as the type of top, dress, or shoulder straps are hidden behind the large cello body and are not presumed, revealing only bare shoulders, both arms, and below the knees. She stands barefoot with both legs together, bending her left elbow to grip the upper part of the black neck with her left hand, and extending her right arm downward to rest her right hand against the right edge of the cello.

Background / Lighting:
The background consists only of a textured white wall and a pale floor, with the cello in the center of the frame, diagonal shadows of a window frame on the left, and the endpin and the subject's bare feet at the bottom. Harsh, direct morning sunlight slants in from a window on the left side of the frame onto the wall, face, arms, and wooden body, casting soft shadows to the right.

Composition / Camera:
A 2:3 vertical composition, shot with a frontal camera at the height of the subject's waist, capturing the full body from the tip of the cello's scroll to the endpin and the tips of both feet. The cello is placed very prominently in the center, revealing only a small portion of the person's face and body from the right side. The entire instrument is contained within the frame, with focus on the wooden body and the profile, keeping the white wall flat.

Texture / Style:
Photorealistic live-action photograph. High-definition rendering of the amber wood grain, black fingerboard and strings, metal endpin, natural skin, and soft hair, creating a quiet morning scene with white walls and warm wood tones.

Negative:
Aspect ratio changes that obscure the full shape of the cello and the person; addition of a bow or chair
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101181996248805853"></a>

### A photo-style prompt of a woman wearing a red lace mini dress, crouching deeply on a living room rug, and taking a winking selfie with a smartphone.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2101181996248805853)

Photography · Portrait / Selfie · Character · Fashion Item · Published

**Summary:** A photo-style prompt of a woman wearing a red lace mini dress, crouching deeply on a living room rug, and taking a winking selfie with a smartphone.

<img src="images/2101181996248805853-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Red Lace Wink

Main Subject:
From the left to the center of the frame, in a warm evening living room, a young woman crouches deeply on a rug, taking a selfie with a white smartphone. A red ruffled lace mini dress, black slender heels, and a one-eyed wink are the centerpieces.

Person / Expression:
A slender face with rounded contours, small chin, open right eye in light brown, thin eyebrows, clean bridge of the nose, and glossy pink lips with the tip of her tongue slightly visible. Head tilted to the right, left eye closed in a wink, directing a playful gaze at the smartphone. Long, wavy light brown hair with thin bangs flowing over both shoulders, tied in a half-up style at the back of the head with a large black ribbon.

Attire / Pose:
A vibrant red thin-strap mini dress featuring shoulder ribbon ties, a delicate ribbon at the chest, tiered sheer ruffles and lace, and an asymmetrical short hemline. Wearing black thin ankle-strap open-toe heels. Crouching deeply with knees kept together, resting her left elbow on her left knee to support her left cheek in her hand, while extending her right arm forward holding the smartphone.

Background / Lighting:
On the left of the frame are a white floor lamp and an off-white sofa, in the center are light-colored walls and curtains, and on the right are a black round table, lit candles, small white flowers, and city lights outside the window, with a high-pile off-white rug at the bottom. Soft, warm light from the lamp on the left and the candles on the right envelops her face, the red lace, knees, and feet.

Composition / Camera:
3:4 vertical composition, frontal camera close to the floor capturing the entire body from the top of the head to the tips of both feet. The figure is prominently placed in the left half, with bent knees in the lower center, the smartphone in front of the chest, and the round table arranged on the right. Framing includes the shoes, sharp focus on the face and smartphone, with a soft blur on the night view and the room interior's depth.

Texture / Style:
Photorealistic live-action photograph. High-definition natural skin, long hair, sheer red lace, intricate ruffles, black leather heels, rug, and candlelight, creating intimate nighttime tones of red, black, and amber.

Negative:
Altering the one-eyed wink and deep crouch; omitting red lace
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101205651024494639"></a>

### Photo prompt of a young woman in light-colored loungewear sitting on a wooden floor holding a pink canned drink in a kitchen with the refrigerator light on late at night.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2101205651024494639)

Photography · Character · Published

**Summary:** Photo prompt of a young woman in light-colored loungewear sitting on a wooden floor holding a pink canned drink in a kitchen with the refrigerator light on late at night.

<img src="images/2101205651024494639-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Late Night by the Refrigerator Light

Main Focus:
From center to right of the frame, a young woman sits on the wooden floor in front of an open refrigerator in a dark kitchen, holding a pink canned drink in her right hand. White loungewear, the warm-toned light of the refrigerator, and travel magnets on the door are the main focal points.

Person & Expression:
A slender, oval side profile, small chin, light brown eyes looking toward the left of the frame, thin eyebrows, a neat nasal bridge, and natural pink lips. Her face is turned toward the inside of the refrigerator on the left, with a quiet, contemplative expression as she gazes inside. Light brown hair is styled in a high, messy bun, with wispy bangs and long stray strands falling over her cheeks and neck.

Clothing & Pose:
An off-white, thin-strapped ribbed camisole top featuring wide lace and a small bow at the bustline, paired with matching shorts that have a drawstring waist and lace trim at the hem. An off-white chunky knit cardigan slips off both shoulders, worn only over her arms, and she wears thick white lounge socks. She sits on the floor with both legs spread forward, her left hand resting on the floor, and her right hand holding the can upright against her right thigh.

Background & Lighting:
On the left of the frame is a white refrigerator door covered with numerous photos and travel magnets; in the center are bottles inside the open refrigerator; in the deep right of the frame are dark kitchen shelves and a small warm-toned lamp; and at the bottom is a wooden floor. Soft, warm-toned light from inside the refrigerator on the left side illuminates her face, chest, and legs from the side, casting the background into deep shadows.

Composition & Camera:
A 2:3 vertical composition, shot with a near-frontal camera positioned at eye level with the person sitting on the floor, capturing a near full-body portrait from the top of the head to the foreground legs. The person is prominently placed on the right half, the glowing refrigerator in the center-left, and the pink can at the bottom center. Both legs are cropped at the bottom edge, with sharp focus on the side profile and the can, while the deep kitchen background is blurred with a shallow depth of field.

Texture & Style:
Photorealistic live-action photograph. Natural skin texture, fine stray hairs, lace, ribbed fabric, chunky knit, metallic can, and the white surface of the refrigerator rendered in high detail, with a warm amber and deep brownish-black night aesthetic.

Negative:
Omission of open refrigerator and pink can; bright daytime scene
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101145547067506779"></a>

### A photorealistic nighttime street portrait of a smiling young East Asian woman holding a compact camera in denim-on-denim fashion.

Author：[@Aqsahere\_](https://x.com/Aqsahere_) · [Source](https://x.com/Aqsahere_/status/2101145547067506779)

Photography · Portrait / Selfie · Character · Fashion Item · Cityscape / Street · Published

**Summary:** A photorealistic nighttime street portrait of a smiling young East Asian woman holding a compact camera in denim-on-denim fashion.

<img src="images/2101145547067506779-1.jpg" alt="Image 1" width="480" />

<img src="images/2101145547067506779-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
A photorealistic nighttime street-fashion portrait of a young woman standing on a city sidewalk, holding a compact digital camera in both hands as if taking a photo. She has long dark black-brown hair styled into a neat low bun, with soft face-framing strands falling naturally on both sides of her face. A small elegant silver decorative hair clip is attached to the bun.\nShe has delicate youthful facial features, natural smooth skin, subtle rosy cheeks, soft pink lips, and a bright genuine smile. She is looking slightly downward toward the camera in her hands with a cheerful, candid expression.\nShe is wearing an oversized light-blue denim jacket with a slightly faded wash and subtle sparkling/speckled detailing, layered over a simple light-gray fitted T-shirt. She pairs it with high-waisted light-wash denim jeans for a coordinated denim-on-denim streetwear look. A thin delicate silver necklace with a tiny pendant rests around her neck. A black wrist strap is attached to the compact camera.\nShe holds a small black compact digital camera horizontally at chest level, with her left hand gripping the camera body and her right index finger pointing toward or touching the camera controls. The camera is clearly visible and detailed, with a prominent circular lens.\nThe background is a lively urban street at night, filled with softly glowing storefronts, illuminated signs, streetlights, passing cars, trees, and distant pedestrians. The background lights create beautiful circular bokeh and colorful points of light while keeping the woman sharply in focus. A tall streetlamp glows behind her, illuminating the surrounding tree canopy.\nComposition: vertical 4:5 portrait, medium-to-full body framing, subject centered slightly to the right, camera positioned around chest height, natural candid perspective, compact camera clearly visible in the foreground.\nLighting: nighttime ambient city lighting mixed with warm streetlamp illumination, soft highlights on her face and hair, gentle rim light around her silhouette, realistic shadows, colorful bokeh in the background, cinematic low-light atmosphere.\nPhotography style: ultra-realistic smartphone photography, candid Korean/Asian street-fashion aesthetic, natural skin texture, realistic hair strands, detailed denim fibers, authentic camera details, shallow depth of field, strong subject separation, subtle film grain, realistic nighttime exposure, soft cinematic color grading, high detail, 4K.\nNegative prompt: anime, cartoon, illustration, CGI, 3D render, plastic skin, excessive beauty filter, unrealistic face, distorted anatomy, malformed hands, extra fingers, missing fingers, fused fingers, distorted camera, warped clothing, artificial hair, oversaturated colors, unnatural bokeh, harsh studio lighting, blurry subject, low resolution, text, watermark, logo.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101121597423984903"></a>

### An ultra-close-up selfie photo prompt of a woman bathed in morning light, winking and slightly sticking out her tongue.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2101121597423984903)

Photography · Portrait / Selfie · Character · Published

**Summary:** An ultra-close-up selfie photo prompt of a woman bathed in morning light, winking and slightly sticking out her tongue.

<img src="images/2101121597423984903-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Morning Light Remaining in One Eye

Subject Matter:
In the center of the frame, inside a bright room with white curtains, a playful close-up of a young woman bringing her face extremely close to the lens, opening her right eye while closing her left eye, and slightly sticking out the tip of her tongue. A bent bare knee occupies a prominent area from the bottom left toward the center, and a thin, pale shoulder strap is visible in the bottom right.

Character & Expression:
Near-black dark brown hair casually gathered at the back, with fine, wet-look stray strands falling across her forehead and cheeks. A round, dark brown right eye, long eyelashes, natural eyebrows, faint blush on her cheeks, and glossy pink lips. Facing directly forward, with only her left eye closed and her mouth open, sticking out the tip of her tongue slightly toward the left in a mischievous expression.

Clothing & Pose:
A pale gray thin-strap camisole top visible only in the bottom right of the frame. One knee is bent high as if hugged up toward the chest, brought close to the bottom left of her face, while her upper body and face lean extremely close to the camera. Arms and hands are outside the frame.

Background & Lighting:
The background is a simple room where only sheer white curtains on the left and pale woodwork on the right are softly blurred. Gentle natural morning light enters from a window behind to the left, casting a warm rim light along the contours of her hair and shoulder, and creating smooth, subtle highlights across her entire face and knee.

Composition & Camera:
3:4 vertical composition, captured from an ultra-short distance just tens of centimeters in front of her face using a standard-leaning lens for a close-up that fills the frame with her forehead, both eyes, nose, mouth, chin, and knee. Hair and parts of the face are cropped boldly at the top, left, and right edges, placing the knee largely in the left foreground. Sharp focus on the open right eye and lips, with an extremely shallow depth of field across the knee and background.

Texture & Style:
Photorealistic live-action photograph. High definition in the reflections of the pupil, individual eyelashes and flyaway hairs, natural skin pores, glossy lips and tongue, and soft knee skin, maintaining an intimate selfie feel under morning window light.

Negative:
Changes to expressions with both eyes open or without sticking out the tongue; changes to a composition placed further away from the face
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101149782836150767"></a>

### A photorealistic portrait prompt of a woman in a black crop top and shorts leaning against a pillar, crouching deeply and stretching in a room bathed in morning light.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2101149782836150767)

Photography · Portrait / Selfie · Character · Architecture / Interior · Published

**Summary:** A photorealistic portrait prompt of a woman in a black crop top and shorts leaning against a pillar, crouching deeply and stretching in a room bathed in morning light.

<img src="images/2101149782836150767-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject: Black stretch beside a pillar. Main Subject: In the center of the frame, beside a thick off-white pillar in an indoor room illuminated by morning sunlight, a young woman crouches deeply and stretches both arms overhead. A black cropped top, shorts, and white high-top sneakers are the focal elements. Person / Facial Expression: Slender oval face, small chin, light brown almond-shaped eyes, thin eyebrows, clean nasal bridge, slightly parted glossy pink lips. Face tilted slightly to the left, casting a calm gaze directly at the camera. Long, dark brown wavy hair with wispy bangs cascades over both shoulders and her chest. Clothing / Pose: A black ribbed crop top with thin shoulder straps featuring a deep scoop neckline and ending above the waist; black low-rise shorts with thin double straps at both hips. Wearing off-white platform high-top sneakers. Resting her back against the pillar, she crouches deeply with both knees spread wide apart to the sides, stretching both arms overhead, supporting her right wrist with her left hand, and resting the fingers of her right hand against the pillar. Background / Lighting: A thick off-white pillar in the center of the frame; a large black-framed window and a potted plant on the left side of the frame; a wooden stool, a picture frame, and plants on the right side; a glossy parquet floor below. Harsh, direct morning sunlight from the window on the left illuminates her hair, face, abdomen, and legs, casting long shadows across the floor and pillar. Composition / Camera: Vertical 3:4 composition, frontal camera angled slightly lower than the crouching figure's chest, capturing the entire body from the overhead fingertips down to both shoes. The figure is placed prominently in the center, overlapping the vertical line of the pillar with her raised arms, while her spread knees expand across the lower half. Fingertips and shoes are kept within the frame, with sharp focus on the face and upper body, and the deeper interior softly blurred. Texture / Style: Photorealistic live-action photograph. High-definition rendering of natural skin, soft long hair, black ribbed fabric, white leather shoes, textured pillar, and glossy wooden floor, under bright morning light in tones of black, off-white, and honey. Negative: Altering the deep wide-legged crouch and overhead arms; altering the black-and-white color scheme
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100935621976191407"></a>

### Realistic portrait of a woman in denim shorts and a blue top looking back in front of a vanity mirror.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2100935621976191407)

Photography · Portrait / Selfie · Character · Published

**Summary:** Realistic portrait of a woman in denim shorts and a blue top looking back in front of a vanity mirror.

<img src="images/2100935621976191407-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Theme:
Denim Blue in Front of the Mirror

Subject:
In the center-right of the frame, in front of a large vanity mirror lined with round light bulbs, a young woman sits sideways on a white counter, twisting her upper body to look back at the camera. In the mirror, her back and the back view of her denim shorts are reflected at the same angle, with a small houseplant on the left and transparent cosmetic bottles arranged on the right.

Person & Expression:
Light brown, loosely curled hair falling below her chest, wispy bangs grazing her eyes, large brown eyes, thin eyeliner, pale pink cheeks, and slightly parted glossy lips. Her face is turned toward the camera over her right shoulder, chin tucked, gazing with a composed expression.

Outfit & Pose:
A form-fitting blue camisole crop top with thin shoulder straps, high-waisted faded denim shorts with heavy fraying, and white thin-strap heeled sandals on her feet. Sitting sideways on the counter, both hands resting on the surface, her right leg extended long forward, left knee bent, and hips turned toward the back.

Background & Lighting:
The background is a dressing room featuring the white counter in the foreground, a large mirror in the center, a light wooden wall on the left, and a row of round light bulbs on the right. Soft, warm light envelops the scene evenly from the numerous bulbs surrounding the mirror, creating smooth highlights on her hair, shoulders, legs, and the stone counter.

Composition & Camera:
A 4:5 vertical composition, captured with a standard lens at waist level, framing the full figure from the crown of the head down to near the ankle of the lowered right leg. The subject is prominently positioned center-right, leaving room for the mirror reflection on the left and the row of bulbs on the right. The tips of her toes are cropped at the bottom edge; sharp focus on her face and body, with a depth of field that allows the mirror reflection to remain clearly discernible.

Texture & Style:
Photorealistic live-action photograph. High definition on the long wavy hair, sheer blue top, frayed denim, white stone surface, round light bulbs, and mirror reflections, conveying the refined, warm sheen typical of an elegant vanity room.

Negative:
Mismatch between the pose or clothing of the mirror reflection and the real subject; changes to the sideways seated, looking-back pose
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100848799484915933"></a>

### Beige-toned street corner snapshot-style prompt featuring a woman leaning against a black lamppost holding a baked treat

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2100848799484915933)

Photography · Character · Cityscape / Street · Published

**Summary:** Beige-toned street corner snapshot-style prompt featuring a woman leaning against a black lamppost holding a baked treat

<img src="images/2100848799484915933-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject: Beige on a Street Corner. Main Subject: In the center-right of the frame, on a quiet street corner in front of a stone-faced building, a young woman leans against an ornate black lamppost, holding a small baked treat in a clear bag near her cheek. In the background, a beige stone wall, a black entrance lantern, potted greenery and red flowers, a sidewalk, and a roadway are visible. Person / Expression: Dark brown bob lightly flipping outward below the chin, bangs drifting across the forehead in the wind, large brown eyes, thin eyeliner, pale peach cheeks, and slightly parted glossy lips. Her face is tilted to the left toward the lamppost, gazing at the camera with a gentle expression. Attire / Pose: A greige strapless tube top with fine horizontal gathers across the chest, relaxed white cargo pants, a patterned scarf in golden brown and ivory tied around the waist, chunky white sneakers, and a thin black choker. Her right hand brings the baked treat near her cheek, her left hand is in her pants pocket, and her right knee is bent with her foot resting against the post. Background / Lighting: The background consists of beige stone and potted plants on the left of the frame, a black metal post on the right of the frame, and dark asphalt in the foreground, creating a tranquil street corner. With foliage in the upper left acting as the primary light source, hard daylight filtered through leaves casts dappled highlights across her hair, shoulders, and white pants, while throwing deep shadows on the post and road surface. Composition / Camera: 3:4 vertical composition, captured with a standard lens placed at waist height to prominently frame the full body from the top of the head down to the white sneakers. The subject is placed center-right, the black post creates a strong vertical line on the right, and the bent leg is positioned diagonally at the bottom. Shoes are included within the frame, focus is on the face, with a medium depth of field in the background. Texture / Style: Photorealistic live-action photograph. High-definition textures of short hair, gathered fabric, lightweight white pants, patterned scarf, transparent pastry bag, stone wall, and cast iron, creating a natural street-corner snapshot centered around beige and black tones. Negative: Changes to the posture of leaning against the post with one knee bent; omission of waist scarf and white pants.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100819355332427950"></a>

### A close-up photo prompt of a woman's profile wearing a yellow bikini and gold accessories against a backdrop of blue sky and backlighting.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2100819355332427950)

Photography · Portrait / Selfie · Character · Abstract / Background · Published

**Summary:** A close-up photo prompt of a woman's profile wearing a yellow bikini and gold accessories against a backdrop of blue sky and backlighting.

<img src="images/2100819355332427950-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
A profile glowing in midsummer

Main Subject:
On the right side of the frame, set against a vivid blue sky, a young woman's right-facing profile, shoulders, and décolletage captured from an extremely close distance and low angle. In the upper right of the frame is a brightly shining white sun, in the upper left a small white cloud, and at the bottom center a very thin strip of turquoise sea is visible.

Person / Expression:
Light ash-brown hair gathered into a round chignon low at the back of the head, with wisps of stray hair falling against the cheek. The right eye is half visible at the edge of the frame, with small studs and thin gold and silver hoops in the right ear, long eyelashes, natural eyebrows, and glossy pale pink lips. Her face is turned toward the right of the frame, showing a quiet profile gazing into the distance, with the right half cropped by the edge of the frame.

Clothing / Pose:
A mustard yellow triangle bikini top with thin shoulder and neck straps, two delicate gold necklaces of different lengths with a small transparent pendant. Her shoulders are slightly pulled forward, neck extended long as she faces right, with her arms out of frame.

Background / Lighting:
Midsummer outdoors with a background composed solely of a deep, clear blue sky and white clouds on the left side of the frame, and the distant sea at the bottom center. Hard backlighting with the sun in the upper right as the primary light source creates a white rim light along her hair and shoulders, strong highlights on her skin and yellow swimsuit, and soft reflected light wraps around the left side of her face.

Composition / Camera:
9:16 vertical composition, an ultra-close-up wide-angle perspective from below the shoulders that largely captures the right half of her face, neck, both shoulders, and décolletage. The profile is boldly cropped at the right edge of the frame, leaving ample negative space in the blue sky on the upper left. Sharp focus around the ear, hair, and lips, with a uniform, deep depth of field for the sky.

Texture / Style:
Photorealistic live-action photograph. High-definition rendering of backlit translucent stray hairs, ears and accessories, natural skin texture, stitching on the yellow swimsuit, and intense sunlight, maintaining a vivid contrast between blue and yellow.

Negative:
Changes to a frontal face or full-body composition; alterations to the low-angle perspective and right-edge cropping
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100759210703421826"></a>

### A photorealistic portrait prompt of a woman wearing a police-style uniform in an underground parking lot.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2100759210703421826)

Photography · Portrait / Selfie · Character · Published

**Summary:** A photorealistic portrait prompt of a woman wearing a police-style uniform in an underground parking lot.

<img src="images/2100759210703421826-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Underground parking lot uniform

Main Subject:
In the center of the frame, a young woman sits in the middle of a black metal bench in a concrete underground parking lot. To the right is a thick pillar with a yellow band, parked cars in the background, black ceiling pipes, white fluorescent lights, and yellow marking lines, with a polished floor reflecting the light.

Person / Expression:
Light brown curly hair reaching below the chest, thin bangs parted above the eyes, large brown eyes, black eyeliner, pale pink cheeks, and glossy coral lips. Facing forward, with a calm smile looking straight at the camera from beneath a black uniform cap.

Attire / Pose:
A black uniform cap with a gold band and a winged badge; a white short-sleeved shirt tied beneath the chest featuring black-and-gold epaulets and a "POLICE" patch on the chest; dark blue denim shorts; a thick grommet belt; black knee-high socks; and black platform patent leather loafers with gold buckles. Both hands rest on the bench beside her hips, with her legs spread wide and extending diagonally below the knees.

Background / Lighting:
An underground parking lot lined with gray concrete, a black ceiling, yellow safety lines, and dark cars. White fluorescent lights above serve as the primary light source, while a soft fill light from the front-left brightly illuminates the subject, casting hard reflections on the floor and shoes and deep shadows in the background.

Composition / Camera:
3:4 vertical composition, using a standard lens at a frontal camera angle slightly higher than the bench surface to symmetrically capture the full body from the hat down to the platform shoes. The subject is placed prominently in the center, with her spread legs forming a V-shape in the lower half. The soles of the shoes are included in the frame, with sharp focus on her face and clothing, while the cars in the background are slightly blurred.

Texture / Style:
Photorealistic live-action photograph. High-definition rendering of the curly hair, wrinkles of the white shirt, denim, black socks, patent leather shoes, metal belt, concrete, and floor reflections, emphasizing the contrast between the inorganic gray and the black and gold.

Negative:
Alterations to details of the uniform and the wide-legged sitting posture; missing hat or knee-high socks
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100454954330980559"></a>

### Realistic photo prompt of a young woman wearing a striped bra top making a double peace sign in a tropical resort lounge.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2100454954330980559)

Photography · Portrait / Selfie · Character · Published

**Summary:** Realistic photo prompt of a young woman wearing a striped bra top making a double peace sign in a tropical resort lounge.

<img src="images/2100454954330980559-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Double peace sign in the tropics

Main Subject:
In the center of the frame, in a tropical resort lounge with wooden beams and a large opening, a young woman reaches both hands toward the camera making double peace signs. In the center background, an off-white sofa with white cushions, a dark navy patterned cushion, a wooden table, and blurred palm trees and a swimming pool are visible.

Person / Expression:
Light brown hair gathered loosely in a high bun/updo, with thin bangs and loose strands framing the cheeks, large bright brown eyes, defined eyeliner, soft pink cheeks, and a radiant smile showing her teeth. Facing forward, her lively expression looks directly into the camera.

Clothing / Pose:
A bra top featuring light lavender and white fine vertical stripes, lace and buttons, and thin shoulder straps, matching wide choker wrapped around her neck, extremely short faded denim shorts, a belly button piercing, and long lavender nails. Both arms are extended wide forward, making V-signs with both hands.

Background / Lighting:
The background is an open lounge with dark wooden pillars and beams on the left and right of the frame, a white fabric sofa in the center, and tropical greenery and a water surface in the distance. Soft daytime natural light enters through the large opening at the front left as the main light source, brightly illuminating her face and body, casting strong highlights on both hands in the foreground and gentle shadows in the background.

Composition / Camera:
3:4 vertical composition, chest-height camera fitted with a wide-angle lens, framing from the top of the head to the upper thighs. The subject is placed in the center, with both hands—appearing large due to forced perspective—positioned toward the upper left and front right, keeping all fingertips within the frame. A depth of field that focuses sharply on the face while keeping the hands discernible, softly blurring the background.

Texture / Style:
Photorealistic real-life photograph. High-definition details on bright skin, individual loose hairs, stripes and lace, faded denim, long nails, and the textures of wood and fabric, captured in a breezy, vibrant resort color palette.

Negative:
Changes to the two-handed V-signs and strong perspective; changes to the color and pattern of the outfit
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100486914876850304"></a>

### Realistic photo prompt of a young woman in a black mini dress reclining on the floor of a hotel lounge with wine and a night view in the background.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2100486914876850304)

Photography · Character · Fashion Item · Abstract / Background · Published

**Summary:** Realistic photo prompt of a young woman in a black mini dress reclining on the floor of a hotel lounge with wine and a night view in the background.

<img src="images/2100486914876850304-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Theme:
The Afterglow of Night View and Wine

Subject:
In the lower right of the frame, inside a dimly lit hotel lounge overlooking a city night view, a young woman leans while sitting sideways on the carpet in front of a large patterned armchair. On a black round table on the left side of the frame, there are a bottle of red wine and a glass, a lit candle, a small black handbag, with a red chair and the light outside the window in the background.

Person and Expression:
A dark brown bob tucked inward beneath the jawline, thin bangs above the eyes, large brown eyes, delicate eyeliner, flushed cheeks, and slightly parted glossy reddish lips. Face turned to the front, with a calm gaze looking at the camera in a quiet expression.

Attire and Pose:
A black halter-neck mini dress with a thin strip of fabric wrapped around the neck and a deeply plunging neckline, paired with thin black strappy high-heeled sandals. Leaning her right shoulder and elbow against the chair, holding the neck fabric with her right hand, hips resting on the carpet, both legs extended together and stretched out toward the lower left.

Background and Lighting:
A lounge with dark wood walls, heavy curtains, a beige patterned armchair, a black marble-style table, and a pale blue night view outside the window. Soft amber light spreads from a table lamp in the center background and the candle in the foreground, illuminating her face and legs, while the surroundings sink into deep black and brown shadows.

Composition and Camera:
3:4 vertical composition, standard lens from a floor-level low angle capturing the entire body diagonally from the top of the head to the tips of the heels. Placing the figure in the lower right, leaving a still life of wine on the left, and negative space with the night view in the upper left. The toes are placed near the bottom edge, with focus on the face and upper body, and the night view featuring large circular bokeh.

Texture and Style:
Photorealistic live-action photograph. Detailed rendering of the black dress and slender shoe straps, warm skin reflections, carpet patterns, marble gloss, and glass reflections of the wine and candle, set in a cinematic low-light warm color tone.

Negative:
Alteration of leg placement while sitting sideways on the floor; absence of wine and night view
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100425761840890004"></a>

### A full-body mirror selfie of a woman wearing dusty mauve attire, reflected in a hotel's arched mirror.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2100425761840890004)

Photography · Portrait / Selfie · Character · Fashion Item · Published

**Summary:** A full-body mirror selfie of a woman wearing dusty mauve attire, reflected in a hotel's arched mirror.

<img src="images/2100425761840890004-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Theme:
Mauve in the Mirror

Subject:
In the center of the frame, a full-body selfie taken by a young woman in a hotel hallway is reflected in a large arched mirror with a black frame. Inside the mirror, a polished beige stone floor, a wooden sliding door, and a bedside table with a black lamp in the far left of the frame are visible, with the mirror frame enclosing the entire perimeter of the image.

Person / Expression:
Brown hair loosely gathered at the back of the head into an updo accented with pearl-like ornaments, wispy bangs, and loose strands along the cheeks; slender brown eyes, and pale rose cheeks and lips. Her face is turned slightly downward to the right toward her smartphone, with a calm expression as she checks the screen.

Clothing / Pose:
A dusty mauve short-sleeved crop top featuring a deep V-neckline, cascading ruffles, and thin lace-up ties in the center. Greige high-cut bottoms paired with a matching sheer knee-length pencil skirt, a black chain bag, a wide silver bangle, and delicate black thong sandals. She holds a black smartphone with her right hand while her left hand gently pulls at the waist of her skirt.

Background / Lighting:
A modern hotel guest room background featuring the encircling black mirror frame, a warm wooden wall on the right side of the frame, a beige stone floor in the foreground, and a black table lamp on the left. The overhead ceiling light serves as the primary light source, complemented by the lamp in the far left, casting soft, warm light evenly across the figure, with slender reflections stretching across the stone floor.

Composition / Camera:
A 7:10 vertical composition with a level camera positioned directly in front of the arched mirror, framing the subject from head to toe in the center with a standard field of view equivalent to a smartphone. The mirror frame is left on all four edges, with margin also left on the floor below her feet. Clear focus is maintained on the full body inside the mirror, while the bedroom in the background is softly blurred.

Texture / Style:
Photorealistic live-action photograph. A serene hotel mirror selfie exquisitely capturing the updo hair, ruffles and lace-up details, sheer mesh skirt, metallic jewelry, and reflections on the stone floor and mirror.

Negative:
Changes to the mauve outfit and its sheer texture; missing mirror frame or incomplete full body
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100394808036516139"></a>

### Portrait prompt of a young woman in a white bikini standing by a resort poolside at dusk.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2100394808036516139)

Photography · Portrait / Selfie · Character · Landscape / Nature · Published

**Summary:** Portrait prompt of a young woman in a white bikini standing by a resort poolside at dusk.

<img src="images/2100394808036516139-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Sunset Melting by the Water

Main Subject:
On the left side of the frame, a young woman stands by the water at a modern resort poolside at dusk. In the background on the right, a calm infinity pool, closed white parasols, and distant mountain ridges are visible; on the left, a bar lounge with warm lighting; at the top, white architecture and glass railings.

Person / Expression:
Wet-look light brown hair touching her shoulders, wispy bangs falling on her forehead, brown eyes and long eyelashes visible in profile, a straight nose bridge, and natural coral lips. In a three-quarter profile facing toward the upper left of the frame, with a calm, dignified expression gazing into the distance.

Attire / Pose:
A white triangle bikini swimsuit top with thin shoulder and neck straps, paired with white drawstring wide-leg pants worn low on the waist. Standing straight with both arms behind her back and shoulders pulled back, turning only her upper torso slightly to the left.

Background / Lighting:
The background consists of gray stone flooring in the foreground, a calm water surface and evening sky on the right, and white architecture with warm bar lighting on the left. The warm indoor lighting on the left acts as the primary light source illuminating the subject in soft amber, supplemented by cool diffused light from the sky on the far right, creating elongated reflections on the water surface.

Composition / Camera:
4:5 vertical composition, shot with a standard lens positioned slightly higher than waist level, framing from the top of the head to the upper thighs. The subject is placed prominently toward the left side of the frame, leaving ample negative space for the pool and evening sky on the right half. The pants are cropped at the bottom edge, with sharp focus on the face and upper body, and the distant background softly blurred.

Texture / Style:
Photorealistic live-action photograph. High detail in the wet hair, skin catching the evening light, pleats of the white swimsuit, thin pants, and reflections on the water and glass, rendered in an elegant twilight color palette blending blue and amber.

Negative:
Changes to a frontal face or smiling expression; changes to the white swimsuit and low-waisted pants
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100350516463046998"></a>

### Realistic portrait prompt of a woman relaxing on a leather sofa in a dimly lit nighttime living room.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2100350516463046998)

Photography · Portrait / Selfie · Character · Published

**Summary:** Realistic portrait prompt of a woman relaxing on a leather sofa in a dimly lit nighttime living room.

<img src="images/2100350516463046998-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Quiet night sofa

Main Subject:
In the center of the frame, a young woman leans back deeply and relaxes on a rounded brown leather sofa in a dimly lit living room. In the background on the left are horizontal blinds, a white curved desk lamp, and a cabinet; in the background on the right is a leaning picture frame; in the right foreground is a round side table and a small metallic object.

Character and Expression:
A messy black bob flaring roundly below the jawline, long piecey bangs falling over the forehead, large dark brown eyes, thin eyeliner, slightly flushed cheeks, and glossy dusty-pink lips. Facing forward with the chin slightly pulled in, she gazes into the camera with a calm, almost neutral expression.

Clothing and Pose:
A white ribbed camisole crop top with thin shoulder straps, dark navy high-waisted shorts, and short gray socks. Her right arm is bent above her head with her hand resting in her hair, her left hand rests down between her legs, her left knee is pulled up high, and her right leg is extended forward toward the viewer, creating a wide sense of depth.

Background and Light:
The background is a nighttime interior combining the central brown leather, ivory furniture and a white wall on the left, and dark woodwork on the right. Soft warm light reaches from desk lamps in the left and right background, gently illuminating her face and upper body while the surroundings sink into deep brown shadows.

Composition and Camera:
A 9:16 vertical composition, captured from a low camera position in front of the sofa with a wide-angle perspective to fit the full body from the hand above her head to her toes. The subject is positioned centrally, with the forward-extended right leg appearing large and the left knee placed on the left side. The right foot is slightly blurred in the foreground, focus is on the face, and the background has a shallow depth of field.

Texture and Style:
Photorealistic real-life photography. Render messy black hair, natural skin, white ribbed fabric, leather creases, cloth socks, and warm lamp reflections in fine detail, with a low-saturation color palette befitting a quiet night.

Negative:
Altering the black bob hair and the pose with one arm raised; weakening the perspective of the legs
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100209587974508608"></a>

### A photorealistic photography prompt of a young woman sitting on a wooden counter in a warm-lit indoor kitchen, holding up a smartphone to take a selfie.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2100209587974508608)

Photography · Portrait / Selfie · Character · Architecture / Interior · Published

**Summary:** A photorealistic photography prompt of a young woman sitting on a wooden counter in a warm-lit indoor kitchen, holding up a smartphone to take a selfie.

<img src="images/2100209587974508608-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Late-night selfie time

Main Subject:
In the center-right of the frame, inside a small studio apartment with warm lighting, a young woman sits on a wooden kitchen counter, taking a selfie with a smartphone held overhead. In the background on the left are a bed and a desk lamp; on the right are wooden hanging cabinets, plants, a small lamp, black cooking appliances, and a sink.

Person / Facial Expression:
Soft, light brown wavy hair falling below the chest, thin see-through bangs, large upturned brown eyes, long eyelashes, pale pink cheeks, and slightly parted glossy lips. Her face is tilted significantly upward toward the smartphone on the upper left, with a focused, calm expression as she gazes at the screen.

Clothing / Pose:
A short-sleeved ivory ribbed top with a deep V-neck and small front buttons, layered over a pale blue top with thin shoulder straps, a beige apron tied in front, and pale blue ties at the hips. Her right arm is extended overhead holding a smartphone in a clear case horizontally, her left hand rests on the counter behind her, and her legs are crossed.

Background / Lighting:
The background is a cozy studio apartment neatly decorated with a wood-grain counter and shelves on the right, beige drapery on the left, and a houseplant in the center background. Table lamps on both sides and an under-shelf light above serve as light sources, spreading a soft amber glow that envelops the contours of her face and body, while the deep background sinks into dark shadows.

Composition / Camera:
2:3 vertical composition, camera placed level near counter height, using a standard lens framing from the hand overhead down to the crossed thighs. The subject is prominently positioned in the center-right, her extended right arm angling diagonally toward the upper left, with feet cropped at the bottom edge. Sharp focus on her face and body, with a shallow depth of field for the bedroom in the background.

Texture / Style:
Photorealistic live-action photograph. High-definition rendering of long wavy hair, natural skin texture, ribbed fabric, thin apron, wood grain, glass, and warm lamp light, preserving a soft, low-light atmosphere characteristic of an indoor nighttime setting.

Negative:
Changes to the smartphone position and upward gaze; changing to daylight
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100121758799974473"></a>

### Realistic prompt of a woman taking a smartphone selfie in front of a hotel bathroom mirror, wearing a light yellow strapless mini dress.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2100121758799974473)

Photography · Portrait / Selfie · Character · Fashion Item · Published

**Summary:** Realistic prompt of a woman taking a smartphone selfie in front of a hotel bathroom mirror, wearing a light yellow strapless mini dress.

<img src="images/2100121758799974473-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Yellow Dress in the Mirror

Main Subject:
In the center of the frame, inside a hotel bathroom lined with large beige tiles, a young woman takes a selfie reflecting her body in a large front-facing mirror. At the bottom of the frame are a black counter and a white oval washbasin, an open wooden door on the left of the frame, and ample negative space of the ceiling and mirror visible at the top.

Person / Expression:
Dark brown loose wavy hair reaching below the chest, half-tied back, with thin bangs and loose strands at the temples, large brown eyes, thin eyeliner, soft rose cheeks, and glossy pink lips. Facing the mirror straight on, she shows a calm, gentle expression while concealing the right half of her face with a smartphone.

Attire / Pose:
A vibrant pale-yellow strapless mini dress. The neckline is straight across, with fine gathers tapering from the torso down to the waist, and a deep diagonal slit and a long hanging tail of fabric draping from the left hip. Her right hand holds a silver smartphone in front of her face, while her left hand lightly pinches the drape beside her thigh, bringing one knee inward.

Background / Lighting:
A modern bathroom composed of glossy beige tiles in the center, dark woodwork on the left of the frame, and a black stone vanity in the foreground. Soft warm light falls evenly from overhead downlights as the primary light source, creating smooth highlights on the subject's shoulders and the yellow fabric.

Composition / Camera:
3:4 vertical composition, camera placed level and directly facing the mirror, framing from the top of the head down to the thighs in the center with a standard field of view equivalent to a smartphone. Ample margins of tiled wall remain around the subject, with the washbasin cropped at the bottom edge. Sharp focus on the person in the mirror, with a deep depth of field that keeps the background distinguishable.

Texture / Style:
Photorealistic live-action photograph. A natural hotel mirror selfie rendering soft skin, wavy hair, fine wrinkles and gathers in the yellow stretch fabric, reflections on the mirror and tiles, and metal faucets with fine detail.

Negative:
Changing dress color, straps, slit; concealing the entire face with smartphone
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100088791751135719"></a>

### Realistic portrait photo prompt of a young woman leaning forward on the terrace of a seaside cafe.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2100088791751135719)

Photography · Character · Published

**Summary:** Realistic portrait photo prompt of a young woman leaning forward on the terrace of a seaside cafe.

<img src="images/2100088791751135719-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Theme:
Sunlight at a Seaside Cafe

Subject:
In the center of the frame, on the terrace of a rustic wooden cafe facing the sea, a young woman rests both hands on a foreground wooden bench, leaning her upper body closer toward the camera. In the distant left of the frame are the glittering blue sea and sandy beach, overhead is a bamboo thatched roof and rattan lighting, and in the distant right of the frame are a wooden counter and chairs.

Person / Expression:
Light brown hair reaching below her chest swept over her right shoulder, thin bangs touching her eyes, large bright brown eyes, long eyelashes, soft peach cheeks, and full, glossy pink lips. Her face is slightly tilted to the left, raising her right shoulder while looking at the camera with a soft expression.

Attire / Pose:
An ecru fine-strapped ribbed knit top with front buttons and an asymmetrical silhouette open from the left side of the chest down to the hem. Paired with short ecru drawstring shorts. Pulling her hips back while leaning her upper body forward, both arms extended straight down resting on the bench.

Background / Lighting:
The background features a seaside cafe with dark wooden furniture and white plastered walls on the right side of the frame, and tropical plants alongside the blue sea on the left side of the frame. Hard midday natural light shines in from the ocean side at the rear left as the main light source, creating bright rim light on her hair and shoulders, soft reflected light on her face, and sharp shadows on the floor.

Composition / Camera:
A 3:4 vertical composition, captured near chest height with a moderately wide-angle camera, framing a large portion of her upper body from the top of the head to the thighs. The subject is placed in the center, retaining the sea in the distant left and the cafe in the distant right along a diagonal, with both hands cropped at the bottom edge of the frame. Sharp focus on the face, with a medium depth of field for the background.

Texture / Style:
Photorealistic live-action photograph. Fine hair swaying in the sea breeze, sunlit skin, ecru rib knit, aged wood texture, and intense reflections on the sea surface are finely detailed, rendered in vibrant summer color tones combining blues and warm hues.

Negative:
Changes to an indoor setting without the sea; changes to the front-opening ecru top and forward-leaning pose
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100064633839030572"></a>

### Structured prompt for generating a portrait photograph of a black-haired woman sitting on a white chair.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2100064633839030572)

Photography · Portrait / Selfie · Character · Published

**Summary:** Structured prompt for generating a portrait photograph of a black-haired woman sitting on a white chair.

<img src="images/2100064633839030572-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject: Black Hair on a White Chair Main Subject: In the center of the frame, a young woman sits on a white wooden armchair with both knees pulled up toward her chest. A tranquil room interior with a small table covered in a lace cloth and a small potted plant on the left, and a white chest of drawers, a vase with white and light pink flowers, and a framed photo in the background to the right. Person and Expression: Glossy black bob hair ending at chin length with the tips flicking outward, heavy straight-cut bangs sitting just above the eyes, slightly elongated dark brown eyes, subtle eyeliner, pale rose cheeks, and moisturized pink lips. Her face is directed forward and tilted slightly to the right, looking at the camera with a calm, serene expression. Clothing and Pose: A gray ribbed camisole top with thin black shoulder straps and trim, small black buttons down the chest, black strappy bottoms, a white long-sleeve shirt draped loosely from shoulders to arms, and black thin-strap heels. Her knees are stacked and raised high, with her left hand resting on the top knee. Background and Light: A light-toned bedroom-like space featuring white and gray furniture, soft textiles, and flowers. Soft daytime natural light enters diagonally from a window on the left, brightly illuminating her face and legs while casting soft shadows to the right. The background flowers and furniture are softly blurred. Composition and Camera: 3:4 vertical composition, capturing the entire body along with the chair from an angle slightly higher than eye level. The subject is placed prominently in the center, with both knees forming the primary foreground shape, keeping both chair armrests and the tips of her feet within the frame. Sharp focus on the eyes and face, with a shallow depth of field in the background. Texture and Style: Photorealistic live-action photograph. Rendered in high definition depicting the sheen of black hair, natural skin texture, ribbed fabric, fine wrinkles of the white shirt, painted surface of the chair, and the cushion, set in a tranquil, muted gray color tone. Negative: Alterations to hairstyle and the knee-hugging seated pose; fully wearing the white shirt.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100027640358805923"></a>

### A realistic portrait prompt depicting a woman with a black bob sitting on a living room sofa in a pink floral minidress.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2100027640358805923)

Photography · Portrait / Selfie · Character · Fashion Item · Published

**Summary:** A realistic portrait prompt depicting a woman with a black bob sitting on a living room sofa in a pink floral minidress.

<img src="images/2100027640358805923-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Floral Patterns Blooming in the Light

Main Subject:
In the center of the frame, a young woman sits shallowly at an angle on an ivory-colored sofa in a calm living room. In the background on the far left, books and small ceramics are illuminated by warm shelf lighting, and in the center of the background, there is a sliding door with a black frame.

Figure and Expression:
A glossy black bob rounded neatly below the chin, thin piecey bangs falling lightly on her forehead, large dark brown eyes, a delicate winged eyeliner, pale pink cheeks, and glossy coral-pink lips. Facing forward with her head slightly tilted, she wears a gentle closed-mouth smile.

Attire and Pose:
A form-fitting minidress with delicate pink floral patterns on a white base, thin shoulder straps, ruffles at the neckline, and a long ribbon at the center. She leans her upper body to the left on the sofa, resting her left hand on the seat cushion, with both legs bent together toward the lower right of the frame.

Background and Lighting:
A modern interior background featuring wooden shelves on the left, an ivory sofa in the center, and gray and black sliding doors on the right. Hard sunlight from a front-right window acting as the primary light source strikes her shoulders, chest, and thighs in bands, while warm shelf lighting from the upper left and right glows gently, casting sharply defined shadows.

Composition and Camera:
9:16 vertical composition, captured from slightly above eye level, framing from the crown of the head, upper body, down to the bent thighs. The subject is placed prominently in the center of the frame, with her right leg naturally cropped by the bottom and right edges. Focus is sharp on her face and floral minidress, with the background kept clean using a shallow depth of field.

Texture and Style:
Photorealistic live-action photograph. Detailed rendering of smooth skin, reflections in black hair, sheer floral fabric and ruffles, fine embossing on the sofa, and the wood grain of the shelves, preserving the contrast between the warm indoor lighting and strong sunlight.

Negative:
Alterations to the black bob hair and floral minidress; removing shadows from direct sunlight
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099622469099217254"></a>

### Realistic portrait prompt of a woman in a white lace camisole with downcast eyes, quietly looking down at a gold-edged pearl flower brooch on her chest.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2099622469099217254)

Photography · Portrait / Selfie · Character · Published

**Summary:** Realistic portrait prompt of a woman in a white lace camisole with downcast eyes, quietly looking down at a gold-edged pearl flower brooch on her chest.

<img src="images/2099622469099217254-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Pearl flower at the chest

Main Subject:
A vertical close-up photograph of an adult woman in a white lace camisole looking down at a floral ornament on her chest in a dark gray room. The figure is centered in the frame.

Person / Expression:
Dark brown hair swept into a high updo, with thin bangs and long loose strands. Slender oval face, downcast eyes with long eyelashes, natural eyebrows, a slender bridge of the nose, and glossy peach-pink lips. A quiet, contemplative expression with her chin slightly drawn in.

Clothing / Pose:
An off-white thin-strap camisole featuring large mesh lace and frills at the neckline. Centered on the skin below the collarbone is a single brooch-like ornament made of white petals with gold edges and a round pearl at the center. White lace top. Standing with her chin slightly tucked.

Background / Lighting:
Blurred dark gray curtains. Soft window light coming from the upper left falls narrowly across her hair, downcast face, floral ornament, and chest, while the surroundings fall into deep shadow. The main light source in the background is soft light from the window side.

Composition / Camera:
2:3 vertical composition, front-facing close-up camera angle focused on the chest area. The top of the head is slightly cropped, with the downcast face in the upper half, white lace below, and the pearl flower positioned at the center. Eyelashes, lips, floral ornament, and lace are sharply in focus. The figure occupies a large portion of the frame, with the focal point on the main subject and a soft bokeh background.

Texture / Style:
Photorealistic beauty photography. High-definition depiction of natural skin texture, long eyelashes, mesh lace, gold-edged white flower, round pearl, and soft shading.

Negative:
Do not omit the gold-edged pearl flower centered below the collarbone and the downcast eyes.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099486826192842807"></a>

### A travel-photography-style prompt of a woman in a white swimsuit holding hands from a first-person perspective and looking back in a clear tropical sea.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2099486826192842807)

Photography · Character · Published

**Summary:** A travel-photography-style prompt of a woman in a white swimsuit holding hands from a first-person perspective and looking back in a clear tropical sea.

<img src="images/2099486826192842807-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Theme:
Hand Reaching toward the Blue Sea

Main Subject:
A vertical photograph in a crystal-clear tropical sea of an adult woman in a white one-piece swimsuit looking back while holding and pulling the camera's hand. The figure is positioned based around the center of the frame.

Person / Expression:
Wet, waist-length light brown hair with wispy bangs. Slender oval face contour, brown eyes looking over her shoulder, natural eyebrows, a small nose, and glossy pink lips. A subtle smile. Her face is turned over her shoulder toward the camera.

Attire / Pose:
A white sleeveless one-piece swimsuit with a deep open back and an oval cutout at the center of the lower back. Submerged in water up to her waist with her back turned, extending one arm long toward the lens. A rectangular smartwatch is on the photographer's arm in the foreground. A circular cutout hole on the back.

Background / Lighting:
Transparent turquoise-blue shallows, white sand, a lush green island in the distance on the left, and a vivid blue sky with white clouds. Strong daylight glitters across the water's surface in shimmering specks. The main lighting in the background is harsh, direct illumination from above.

Composition / Camera:
3:4 vertical composition, camera at a first-person perspective, taken from behind at a diagonal angle above the waist. The arm and hand extending from the lower left foreground connect to the subject, positioning her at center-right and spreading the sea across the entire frame. Focus on the face, the clasped hands, and the cutout on the back. Framing the subject largely with sharp focus on the protagonist, accompanied by subtle background bokeh.

Texture / Style:
Photorealistic travel photograph. Capturing wet hair, the white swimsuit, water droplets on the arm, the rectangular watch, and the transparent sea under striking, vivid natural light.

Negative:
Do not omit the first-person hand-holding and the rectangular watch in the foreground
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099370474455396482"></a>

### Photorealistic studio portrait of an elegant woman wearing a tailored black midi dress.

Author：[@MissDelulu9](https://x.com/MissDelulu9) · [Source](https://x.com/MissDelulu9/status/2099370474455396482)

Photography · Portrait / Selfie · Character · Fashion Item · Published

**Summary:** Photorealistic studio portrait of an elegant woman wearing a tailored black midi dress.

<img src="images/2099370474455396482-1.jpg" alt="Image 1" width="480" />

<img src="images/2099370474455396482-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Create a highly photorealistic full-body studio portrait of an elegant adult woman wearing a sophisticated black midi formal dress with long sleeves, a tailored waist, premium fabric, and subtle texture. Minimal jewelry, elegant pointed heels, sleek polished hair, soft natural makeup, confident gentle expression. Luxury fashion studio backdrop, soft diffused lighting, realistic skin texture, natural proportions, cinematic editorial photography, 85mm lens, ultra-detailed, 8K, no text, no watermark.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099398744529600886"></a>

### A realistic portrait photography prompt of a woman wearing dusty peach lingerie looking back over her shoulder on a bed bathed in morning light.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2099398744529600886)

Photography · Portrait / Selfie · Character · Published

**Summary:** A realistic portrait photography prompt of a woman wearing dusty peach lingerie looking back over her shoulder on a bed bathed in morning light.

<img src="images/2099398744529600886-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Dusty Peach by the Morning Window

Subject / Main Character:
A vertical photograph taken up close from the side of an adult woman in dusty peach lingerie on a white bed bathed in morning sunlight. The person is positioned centered in the frame.

Person / Expression:
Shoulder-length light ash-brown straight hair with wispy bangs. Slender oval facial contour, small chin, round brown eyes, natural thin eyebrows, slender bridge of the nose, glossy pink lips. A calm, quiet expression looking at the camera over her shoulder.

Clothing / Pose:
Dusty peach underwire bra with thin shoulder straps. Matching-color lace on the upper cups, a small bow tie at the center of the chest. Body turned sideways, back straightened, turning her face back over her shoulder. Dusty peach swimsuit.

Background / Lighting:
White sheets and pillows, light-colored wooden furniture, a large window. Strong morning sunlight from the upper right creates bright highlights and soft shadows across the cheek, nose bridge, shoulder, and hair. The main light in the background of the frame is soft light coming from the window side.

Composition / Camera:
3:4 vertical composition, camera positioned at an oblique side angle for a close-up from below the bust. Face placed in the upper right, with the shoulder and peach cups prominently placed in the lower center. Both eyes, lips, lace, and strands of hair are sharp, with the background heavily blurred. Frame the subject large, focusing on the main figure, with a gentle blur in the background.

Texture / Style:
Photorealistic beauty photography. Finely captures natural skin texture, pink lace, thin shoulder straps, ash-brown hair, and soft reflections of morning sunlight.

Negative:
Do not alter the sideways over-the-shoulder gaze and the dusty peach lace
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099367790524219462"></a>

### Photorealistic portrait prompt of a woman sitting on a wooden table by a lake.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2099367790524219462)

Photography · Portrait / Selfie · Character · Landscape / Nature · Published

**Summary:** Photorealistic portrait prompt of a woman sitting on a wooden table by a lake.

<img src="images/2099367790524219462-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Theme:
White buttons by the lakeside

Subject:
A vertical portrait of an adult woman in a white crop top sitting by a wooden table near a blue mountain lake. The subject is positioned with reference to the center of the frame.

Person and Expression:
Chest-length dark brown straight hair with an off-center parting. A slender oval face, round brown eyes, natural eyebrows, a delicate small nose, and glossy peach-pink lips. Gently smiling toward the front.

Clothing and Pose:
A white ribbed short-sleeved crop top with a deep scoop neckline and thin lace trim, with small buttons aligned below the chest. Pale blue denim shorts. Sitting on the edge of the table with both arms lowered forward.

Background and Lighting:
A blue-green lake, coniferous forest, rugged mountains with snow streaks, blue sky, and white clouds. A clear cup of iced coffee in the lower left. Strong daylight and dappled sunlight filtering through trees. The primary light source in the background of the frame is harsh, direct light coming from above.

Composition and Camera:
2:3 vertical composition, straight-on medium waist-up shot. Subject in the center, lake and mountains in the upper half, and iced coffee in the lower left. In focus on the face and the line of white buttons, with the mountains softly blurred. Capturing the subject largely, focused on the main subject with a soft bokeh background.

Texture and Style:
Photorealistic travel photography. Crisp daylight capturing the white ribbing and lace, denim, cold drink, blue lake, and mountain ridges in vivid detail.

Negative:
Do not omit the mountain lake and the iced coffee in the lower left
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099400168433152293"></a>

### Extreme close-up portrait prompt of a woman looking up at the camera with moist eyes.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2099400168433152293)

Photography · Portrait / Selfie · Character · Published

Source：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2093263569249005578)

**Summary:** Extreme close-up portrait prompt of a woman looking up at the camera with moist eyes.

<img src="images/2099400168433152293-1.jpg" alt="Image 1" width="480" />

<img src="images/2099400168433152293-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Subject:
Close-up portrait with moist eyes

Main Subject:
A vertical photograph capturing a woman in her 20s from above at close range. The subject occupies a large portion of the center of the frame, leaning her upper body forward while looking up at the camera. One hand is gently cupped right beneath her mouth, holding a small amount of clear water droplets on her palm. A dark indoor background with an intimate atmosphere unique to close-range photography.

Person / Expression:
A petite, rounded face with a soft jawline. Large brown eyes looking straight into the camera, with slightly downturned outer corners giving a gentle impression. A natural film of tears on the lower eyelids, with only a tiny tear droplet visible near the outer corner of the eye, avoiding an overly crying face. Slender brown eyebrows, pale rose blush, delicate eyelashes, and glossy pink-beige lips. Light brown long hair in loose waves, with wispy bangs and slender strands framing the face along the cheeks.

Clothing / Pose:
A pale pink, finely ribbed sleeveless top. Featuring a deep V-neck and a small ribbon at the center, paired with pale ivory-toned short bottoms underneath. A posture leaning the upper body toward the camera with shoulders slightly drawn inward. One hand is held under her face with the palm facing upward, fingers naturally curled, holding a small amount of water droplets.

Background / Lighting:
An indoor setting based on dark brown and black tones. In the left background, dark furniture and small papers appear softly blurred, while in the right background, black storage items and small white objects are blurred. Soft warm light from near the front brightly illuminates her face, hair, shoulders, and palm, with the background falling into deeper shadow. The skin has a subtle glow, with tiny reflections visible on the surface of her eyes and tears.

Composition / Camera:
Vertical 4:3. An extreme close-up portrait with the face prominently placed in the center of the upper half of the frame. A slightly wide-angle perspective looking down from a high angle, strongly bringing the face and hand into the foreground. The frame extends from the top of the head to the chest and part of the thighs, with the palm overlapping the lower-center portion of the frame. Sharp focus on the face and eyes, with the background softly blurred.

Texture / Style:
Realistic photographic expression. Smooth skin retaining natural texture, soft hair visible strand by strand, ribbed fabric, water droplets, and the transparency of tears are depicted in fine detail. Warm and soft color tones, avoiding excessive HDR or heavy skin-smoothing filters. Dimensionality characteristic of close-range photography, with the natural atmosphere of an everyday snapshot.

Negative:
Large, unnatural tears; a puffy, crying face
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099339353168441687"></a>

### Indoor fashion photography prompt of a woman wearing a black-and-white tweed mini dress sitting on a sofa.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2099339353168441687)

Photography · Portrait / Selfie · Character · Fashion Item · Architecture / Interior · Published

**Summary:** Indoor fashion photography prompt of a woman wearing a black-and-white tweed mini dress sitting on a sofa.

<img src="images/2099339353168441687-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Afternoon Black-and-White Tweed

Main Subject:
A vertical photo of an adult woman wearing a black-and-white tweed mini dress, sitting on a sofa in a bright, elegant living room. The person is positioned centered relative to the frame.

Person / Expression:
Below-shoulder light brown wavy hair with thin bangs. A slender oval face contour, horizontally elongated brown eyes, natural thin eyebrows, a petite nose, and glossy pink lips. Resting her cheek on one hand, quietly looking to the left of the frame. Her face is turned toward the left of the frame.

Attire / Pose:
An off-white fine tweed mini dress featuring thin black shoulder straps, a deep V-neck with black lace trim, black piping along the torso and hem, and small pearl-like buttons. Legs crossed, resting one elbow on her knee and the other arm on her leg. Delicate gold jewelry.

Background / Lighting:
A light beige sofa, a marble table, a vase of white roses, shelves, and a large window. Daylight from the left creates soft reflections on her hair and shoulders. The primary light in the background of the frame is soft light coming from the window side.

Composition / Camera:
2:3 vertical composition, shot from an oblique frontal angle close to a seated eye level, framing from above the knees. The subject is placed center-left, white roses in the right foreground, and the window in the back left. Focus is on the face and the black trim of the tweed. The subject is framed prominently, keeping the focus sharp on the protagonist while leaving the background with a soft bokeh.

Texture / Style:
Photorealistic indoor fashion photography. Coarse tweed, black trim, pearl-like buttons, gold jewelry, and soft skin illumination are captured in sharp detail.

Negative:
Do not change the black-and-white trim and tweed texture into plain fabric
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099309154334548142"></a>

### A photographic style prompt of a woman wearing a floral bikini and a sheer white robe beside a canopy bed at a tropical poolside.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2099309154334548142)

Photography · Portrait / Selfie · Character · Published

**Summary:** A photographic style prompt of a woman wearing a floral bikini and a sheer white robe beside a canopy bed at a tropical poolside.

<img src="images/2099309154334548142-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Floral Robe by the Water

Main Subject:
A vertical full-body photograph of an adult woman standing beside a white canopy bed by a tropical poolside, wearing a floral bikini and a long white robe. The subject is centered in the frame.

Person & Expression:
Black hair touching the shoulders gathered in a low bun, with wispy bangs. Oval face contour, elongated brown eyes, natural eyebrows, a small nose, and glossy pink lips. Facing forward with a calm, gentle gaze.

Attire & Pose:
An off-white underwire cup bikini featuring a delicate, colorful ditsy floral print, a slender tie string at the center of the bust, and matching bottoms. A translucent off-white robe with lace trim and flared short sleeves, falling below the knees. Standing with one hand resting on the daybed. Small floral print swimwear.

Background & Lighting:
A blue pool, wooden pillars, white curtains, a white daybed, palm trees, and lush dark greenery. Strong daylight shines through the sheer robe and makes the water's surface gleam blue. The key light in the background is harsh, direct overhead sunlight.

Composition & Camera:
2:3 vertical composition, straight-on front full-body shot. Subject centered, wooden pillar on the left, white curtain on the upper right, and the pool in the back left, framing from the top of the head to below the thighs. Focus on the face, floral print, and lace robe. The subject fills a large portion of the frame with sharp focus, while the background has a soft bokeh.

Texture & Style:
Photorealistic resort photography. Small floral pattern, underwire cups, sheer robe and lace, water surface, and wooden elements captured in bright, natural light.

Negative:
Do not omit the long translucent robe and the floral underwire bikini
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099262094302761246"></a>

### Resort photography-style prompt of a woman in a small floral bikini kneeling on a daybed in the shade of trees.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2099262094302761246)

Photography · Portrait / Selfie · Character · Published

**Summary:** Resort photography-style prompt of a woman in a small floral bikini kneeling on a daybed in the shade of trees.

<img src="images/2099262094302761246-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Small Floral Bikini in the Shade of Trees

Main Subject:
A vertical photograph of an adult woman kneeling on a white daybed placed in a tropical wooden pavilion, wearing a small floral bikini. The subject is positioned based around the center of the frame.

Person / Expression:
Wet dark brown hair reaching below the shoulders with thin bangs. Slender oval face contour, wide brown eyes, natural eyebrows, petite nose, and glossy pink lips. Softly smiling toward the front.

Clothing / Pose:
Triangle halter bikini with pink small floral patterns on an off-white base, thin neck ties, and matching bottoms tied at both hips. Kneeling on white bedding, both arms naturally lowered in front of the body. Small floral print swimwear. Thin shoulder straps extend from the triangle cups.

Background / Lighting:
Wooden railings, white pillows, dense tropical plants, and orange flowers. Dappled sunlight filtering through trees creates intricate chiaroscuro on the wet hair, shoulders, and fabric. The primary light in the background is soft light coming from the left side of the frame.

Composition / Camera:
3:4 vertical composition, camera facing from the front slightly below waist level. The subject is placed prominently in the center, with the white bedding surrounding the lower body and lush greenery in the background. Focus on the face and the small floral pattern. Capturing the subject prominently, focusing on the main figure, with light bokeh in the background. Upper-body shot from the waist up.

Texture / Style:
Photorealistic resort photography. Naturally and intricately captures wet hair strands, water droplets, small floral fabric, white bedding, and skin bathed in dappled sunlight.

Negative:
Do not change the small floral pattern on the off-white base and wet hair into a solid-colored dry look
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099123682249732440"></a>

### A realistic morning lifestyle photo prompt of a woman sitting on a white rug in a living room, holding out a white flower toward the camera.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2099123682249732440)

Photography · Character · Published

**Summary:** A realistic morning lifestyle photo prompt of a woman sitting on a white rug in a living room, holding out a white flower toward the camera.

<img src="images/2099123682249732440-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
A White Flower Held Out

Main Subject:
A vertical photograph of an adult woman sitting with her knees bent on a white rug in a sun-drenched living room, holding out a single white flower toward the lens. The subject is positioned relative to the center of the frame.

Person/Expression:
Light brown wavy hair falling below the shoulders with wispy bangs. Oval face shape, round brown eyes, slender eyebrows, a petite nose, and glossy coral lips. Smiling slightly at the camera with her mouth gently parted. Facing the camera straight on.

Attire/Pose:
A spaghetti-strap mini slip dress with a red ditsy floral print on white. White lace along the neckline and short hem. Sitting with one leg bent to the side, her left hand on the rug, and her right arm stretched straight toward the lens holding a white flower. A ditsy floral mini dress.

Background/Lighting:
A wooden low table with a lace cloth, bread, a vase, a stack of flower books, a large window, and a green terrace. Morning sunlight casts lattice-like shadows onto the white rug. The primary light in the background of the shot is soft light coming from the window side.

Composition/Camera:
3:4 vertical composition, camera positioned slightly high from the front capturing a near full-body shot. The white flower in the foreground is large, the face is in the center, and the bent legs and books are placed toward the bottom. Focused on the face and flower, with the background softly blurred. The subject is prominently framed, with sharp focus on the focal point and light bokeh in the background.

Texture/Style:
A photorealistic, bright lifestyle photograph. Capturing the ditsy floral pattern, white lace, flower petals, deep-pile rug, wood, and morning light in clean, fresh tones.

Negative:
Do not omit the arm extended toward the lens or the single flower in the foreground
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099093734906613857"></a>

### Fantasy photography prompt depicting a woman in a bikini bathed in a beam of light from a giant unidentified flying object \(UFO\) on a rural road at dusk.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2099093734906613857)

Photography · Character · Published

**Summary:** Fantasy photography prompt depicting a woman in a bikini bathed in a beam of light from a giant unidentified flying object \(UFO\) on a rural road at dusk.

<img src="images/2099093734906613857-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
White beam of light in an evening sky

Main subject:
A vertical fantasy photograph taken from behind of an adult woman bathed in a white beam of light from a giant disc-shaped flying object on a country road at dusk. The figure is positioned centered in the frame.

Person & Expression:
Waist-length light brown wavy hair and thin bangs. Slender oval face contour, horizontally wide brown eyes, natural eyebrows, petite nose, glossy pink lips. One hand resting atop her head, looking at the camera over her shoulder. Turning her face over her shoulder toward the camera. Calm expression.

Attire & Pose:
White thin-string triangle bikini top, short white lace skirt. Standing in the middle of the road with her back turned, twisting her upper body, bending one arm above her head.

Background & Lighting:
A narrow road lined with houses and utility poles, distant mountains, a blue-purple evening sky. A giant metallic disc covers the upper half of the frame, with a wide white conical beam of light projecting downward from its center onto the person and the road. The main background light is soft light coming from the left of the frame.

Composition & Camera:
13:18 vertical composition, camera at a low rear-diagonal angle capturing a knee-up shot. The person is positioned at the lower center, the giant disc completely filling the top edge, with the white beam of light connecting the two. Focus on the turning face and the underside of the disc. The subject is framed prominently in sharp focus, with a gentle bokeh in the background.

Texture & Style:
Photorealistic cinematic fantasy photography. Depict realistic textures in fine detail for the metallic disc, white volumetric light, evening sky, lace, and backlit hair.

Negative:
Do not omit the giant disc in the sky and the conical light beam falling upon the person
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099112358392033544"></a>

### Portrait prompt of a woman with round glasses and a bun hairstyle, wearing a floral bralette and a sheer white cardigan, smiling in a living room bathed in morning light.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2099112358392033544)

Photography · Portrait / Selfie · Character · Published

**Summary:** Portrait prompt of a woman with round glasses and a bun hairstyle, wearing a floral bralette and a sheer white cardigan, smiling in a living room bathed in morning light.

<img src="images/2099112358392033544-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Theme:
Round glasses and morning floral pattern

Subject:
A vertical close-up photograph of an adult woman sitting on the floor of a living room with flowers and morning sunlight, resting her cheek on a white sleeve. The subject is positioned based around the center of the frame.

Person/Facial Expression:
Light brown hair tied up in a high messy bun with a white scrunchie, thin bangs, and fine loose strands of hair. Round metal-framed glasses, closed eyes, long eyelashes, a petite nose, and glossy pink lips. A quiet smile. Her face is turned diagonally downward.

Attire/Pose:
A lace-trimmed bralette in off-white with blue ditsy floral print and matching short bottoms, draped with a sheer white long-sleeved cardigan slipped off the shoulders. Leaning on one elbow, supporting her cheek with a hand covered by the sleeve. Floral patterned swimwear.

Background/Lighting:
A large window, a garden, a white rug, flowers in a vase, and a clear drink with lemon in the lower right. Strong morning sunlight from the upper right edges her hair and shoulders. The main ambient light in the background is soft light coming from the window side.

Composition/Camera:
A 3:4 vertical composition, camera slightly from above, closer to below the chest. The face and round glasses are placed in the upper left, the floral pattern and white sleeves in the center, and the drink in the lower right. Focus on the face, glasses, and lace. Framing the subject largely, focusing on the main subject, with a soft blur in the background.

Texture/Style:
A photorealistic natural light photograph. Softly capturing the round glasses, sheer white fabric, ditsy floral lace, backlit hair, and the natural glow of the skin.

Negative:
Do not omit the round glasses or resting the cheek on the white sleeve; do not let hair down
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099094091179180195"></a>

### Candid street-style photo of two East Asian women conversing by a McDonald's window.

Author：[@Aqsahere\_](https://x.com/Aqsahere_) · [Source](https://x.com/Aqsahere_/status/2099094091179180195)

Photography · Cityscape / Street · Published

**Summary:** Candid street-style photo of two East Asian women conversing by a McDonald's window.

<img src="images/2099094091179180195-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Ultra-realistic candid 9:16 street photograph of two adult East Asian women in stylish short skirts, sitting casually at a window-side counter inside McDonald’s, naturally chatting together. Photographed from the sidewalk through the glass window, with realistic reflections, warm interior lighting, natural body language, authentic expressions, detailed skin and clothing textures, shallow depth of field, and an unposed smartphone photography feel.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098981813771194613"></a>

### Full-body outdoor fashion portrait of a woman in navy sequin top, flowing sheer kimono, and beige trousers walking in a garden.

Author：[@ZarnishNael](https://x.com/ZarnishNael) · [Source](https://x.com/ZarnishNael/status/2098981813771194613)

Photography · Portrait / Selfie · Character · Fashion Item · Published

**Summary:** Full-body outdoor fashion portrait of a woman in navy sequin top, flowing sheer kimono, and beige trousers walking in a garden.

<img src="images/2098981813771194613-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Create an ultra-realistic full-body outdoor fashion portrait of a young woman walking confidently along a peaceful garden pathway. She has shoulder-length voluminous wavy auburn-brown hair, neatly styled with a small delicate butterfly hair accessory, natural realistic skin texture, defined eyebrows, subtle eye makeup, soft blush, and elegant pink lipstick.\nShe is wearing a dark navy-blue sequin sleeveless top with a matching sheer, lightweight long open-front shrug/kimono flowing naturally behind her, paired with high-waisted cream/off-white straight-leg trousers and simple nude heels. A delicate long black beaded necklace completes the look.\nWarm golden-hour sunlight, lush green trees and plants, colorful small flowers, an old rustic brick wall in the background, natural bokeh, soft cinematic depth of field. The sheer outer layer moves gently with her walk, creating a graceful flowing effect.\nPhotography: ultra-realistic DSLR photography, full-body composition, eye-level camera, 50mm lens, natural proportions, realistic fabric textures, detailed hair strands, soft warm lighting, sharp subject with beautifully blurred background, premium fashion editorial aesthetic, photorealistic, high resolution, vertical 9:16.\nNegative prompt: distorted face, extra fingers, extra limbs, deformed hands, unnatural body proportions, plastic skin, oversmoothing, blurry face, duplicate person, warped clothing, artificial-looking background.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098975203866837026"></a>

### A realistic vertical-composition portrait prompt of a woman sitting cross-legged on a bed in a bedroom with a warm-toned lamp, taking a mirror selfie.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2098975203866837026)

Photography · Portrait / Selfie · Character · Published

**Summary:** A realistic vertical-composition portrait prompt of a woman sitting cross-legged on a bed in a bedroom with a warm-toned lamp, taking a mirror selfie.

<img src="images/2098975203866837026-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Theme:
Night lamp smartphone mirror

Subject:
A vertical photograph of an adult woman sitting cross-legged on a bed in a bedroom with a warm-toned lamp, taking a mirror selfie with a large smartphone. The subject is positioned centered in the frame.

Person / Expression:
Long black hair tied back, wispy bangs. The smartphone largely obscures the center of her face, with only one eye, cheek, and a portion of her glossy pink lips visible. Face directed straight ahead. A calm expression.

Clothing / Pose:
A white ribbed spaghetti-strap camisole with lace and small buttons at the bust, gray drawstring shorts, and white knee-high socks. Sitting cross-legged, holding a large copper-colored smartphone in front of her face with one hand. White top and gray shorts.

Background / Lighting:
White bedding, a wooden side table, a warm-toned table lamp, a dark window. Orange light creates soft shadows across the person and bedding. The main ambient background light is a soft light coming from the window side.

Composition / Camera:
2:3 vertical composition, camera capturing a sitting, nearly full-body view directly facing the mirror surface. The person is centered, the large smartphone is at the center of the face, and the legs in white socks are positioned downward. Focus is on the mirror reflection and clothing. Capturing the subject prominently, focused on the main figure, with a light bokeh in the background.

Texture / Style:
Photorealistic nighttime mirror selfie. Naturally captures the mirror surface, copper-colored device, white ribbing and lace, gray fabric, and warm-toned lamp.

Negative:
Do not change the composition where the smartphone largely obscures the center of the face
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098945760817479956"></a>

### A realistic natural-light portrait photo prompt of a woman in a black satin mini slip looking back on a sunlit bed.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2098945760817479956)

Photography · Character · Published

**Summary:** A realistic natural-light portrait photo prompt of a woman in a black satin mini slip looking back on a sunlit bed.

<img src="images/2098945760817479956-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Black Satin in Morning Light

Main Subject:
A vertical photograph of an adult woman sitting with her back to the camera on a white bed bathed in morning light, wearing a black satin mini slip dress. The subject is centered in the frame.

Subject and Expression:
Shoulder-length, loosely waved dark brown hair with thin bangs. A slender oval face, elongated brown eyes, natural eyebrows, a small nose, and glossy pink lips. A calm expression looking at the camera over her shoulder. Her face is turned over her shoulder toward the camera.

Attire and Pose:
A black glossy satin mini slip with thin spaghetti straps. The back is deeply open nearly to the waist, featuring multiple thin lace-up strings and small bows on both sides. She sits with her legs folded to the side, placing one hand on the bedding. A black mini dress.

Background and Lighting:
White sheets and pillows, light-colored walls, large windows. Strong morning sunlight creates thin white reflections on the black satin, warmly illuminating her back and hair. The main background light is a soft light entering from the window.

Composition and Camera:
A 4:5 vertical composition, with the camera positioned obliquely behind from the edge of the bed for an above-the-knee shot. The subject is prominently placed in the center, highlighting the open back and the side lace-up ties. Focus is on the turned face and the satin. Framing the subject prominently with focus on the main elements, and a soft background blur.

Texture and Style:
A photorealistic natural light photograph. Sharply capturing the specular gloss of the black satin, the thin lace-up strings, the white bedding, and the morning light on the hair and skin.

Negative:
Do not omit the deeply open back and the lace-up strings on both sides
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098925376554811573"></a>

### Prompt for a 4-photo realistic candid series of Japanese women cosplaying original animal-themed heroines \(Alligator, Black Panther, Frog, Sumo\) at an American comic convention.

Author：[@splash\_GL](https://x.com/splash_GL) · [Source](https://x.com/splash_GL/status/2098925376554811573)

Photography · Animal / Creature · Published

**Summary:** Prompt for a 4-photo realistic candid series of Japanese women cosplaying original animal-themed heroines \(Alligator, Black Panther, Frog, Sumo\) at an American comic convention.

<img src="images/2098925376554811573-1.jpg" alt="Image 1" width="480" />

<img src="images/2098925376554811573-2.jpg" alt="Image 2" width="480" />

<img src="images/2098925376554811573-3.jpg" alt="Image 3" width="480" />

<img src="images/2098925376554811573-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
Create a series of 4 standalone photographic portraits in a 9:16 aspect ratio.
Generate four completely separate image files, not a collage, contact sheet, split screen, or a single combined canvas. Each image must use the same event venue, the same photographer perspective setting, the same lighting mood, and the same snapshot photography style.

- COMMON LOCK
{Story}
At a weekend American-comic-style cosplay convention hall. The protagonist is an amateur photographer who came to shoot attractive cosplayers. While casually wandering through the venue, a series of slightly unpolished, reflexive candid snapshots are captured almost by chance using a neck-slung FUJIFILM X-T50. Each image features a different Japanese woman in her early 20s present at the venue. Each woman is completely immersed in embodying her favorite fictional superhero, striking serious poses and expressions. However, the mixture of the mundane hallway space, the presence of nearby attendees, the impromptu backgrounds, and the amateur photographer's candid unpredictability creates a gap between their superhero mindset and the everyday reality of the convention hall. The subject is not the figures' bodies themselves, but rather the cosplayers' energetic commitment, the humorous and spirited parody ethos born from the juxtaposition between dramatic action poses and the cluttered venue ambiance, the hallway foot traffic, the human presence, and the accidental framing. The four-image progression follows a classic narrative arc: Introduction (First encounter), Development (Finding the next subject down the hall), Twist (Encountering an even more impactful persona), and Conclusion (A final, memorable lingering impression).

{Character Portrayals}:
The subject in each image is a distinctly different, clearly adult Japanese woman in her early 20s. All possess healthy, natural, slender adult female physiques, with bell-shaped, voluminous natural busts that naturally droop with gravity. They carry an upbeat, self-motivated excitement typical of event attendees. Their facial features possess the natural individuality of real Japanese women, with subtle differences in eye shapes, profiles, jawlines, makeup intensity, and hairstyles. Each displays intense enthusiasm for "becoming their beloved hero," visible in their gaze, mouth tension, engaged shoulders, and hand positioning. The costumes are alluring and daring superhero outfits, yet maintained within the reasonable boundaries of fan-made convention costumes rather than explicit displays. They must not directly replicate actual famous characters, but instead be designed as original fictional heroines inspired by animal motifs.

{Attire}:
Each image features a different fictional American-comic-style heroine costume with a deep neckline, tailored specifically to each subject. Materials tastefully blend faux leather, stretch fabrics, mesh, and matte decorative components. Each costume possesses a realistic level of craftsmanship indicative of fan-made or convention-prepared cosplay, with theme colors, headpieces, gloves, boots, and accents like tails, ears, or capes designed along the heroine's animal motif. Costumes are bold yet structurally sound, developing natural wrinkles and tension according to movement, stance, and pose. Even where revealing, exposure stays within standard convention norms, showing no underwear or improper exposure. No brand logos, franchise logos, chest emblem text, or symbols are permitted.

{Location}:
A weekend cosplay event held inside a large commercial facility or convention exhibition hall. Broad hallways, temporary booths, partitions, makeshift photo backdrops, queue stanchions, transitions in floor materials, resting benches along the walls, and distant glimpses of attendees and other photographers are partially visible. Background elements strictly follow the venue's logistical flow, positioned where subjects would genuinely pause to pose: along walkways, beside booths, along walls, around corners, or near rest zones. The clutter remains strictly authentic to an event space, avoiding meaningless random scatter. Any posters or directional signage present must feature unreadable, illegible text.

{Lighting and Cinematography}:
Faces, expressions, skin, and hair are not overly beautified; they retain the natural asymmetry and distinctive individuality of real Japanese women, carefully rendering skin pores, mild shine, makeup textures, bangs, and flyaway hair strands. Venue lighting relies mainly on ceiling-mounted white LEDs and commercial ambient light, creating mild brightness variations across the room. Areas closer to the subject are slightly brighter, while the hall depths and wall perimeters fall into soft shadows. The frame avoids overly uniform lighting, capturing the mixed-temperature venue illumination and natural shadows. The photographer is an amateur attendee who reflexively raises a neck-worn FUJIFILM X-T50 while walking, snapping before fully framing the shot. Allow slightly delayed framing, subtle camera tilt, informal cropping, and accidental foreground obstructions or background passersby.
FUJIFILM REALA ACE-inspired rendering, soft natural skin tones.

{Consistency}:
All four images maintain the identical convention atmosphere, amateur photographer viewpoint, spontaneous FUJIFILM X-T50 snapshot aesthetic, and humorous, energetic spirit of an American comic convention. While subjects and outfits vary, each maintains natural adult female anatomical integrity, with seamless continuity in limbs, faces, attire, and backgrounds. Avoid direct replication of copyrighted franchise costumes or logos; unify the set under an original parody spirit of animal-motif heroines. Do not include text, logos, watermarks, or UI overlays.

image_1 [Introduction]:
A Japanese woman in her early 20s who is a passionate fan of "Alligator Girl." Standing near a hallway partition, she wears an assertive alligator-themed heroine costume predominantly in green and dark olive. It includes a short cropped top, textured scale-like panels, a tail-like rear accent, a headpiece featuring a stylized mini-alligator head, elbow-length gloves, and knee-high boots. With a stern, focused expression, she turns three-quarters, thrusting one arm forward while slightly flexing the other in an explosive "ready to pounce" hero stance. Her face turns toward the camera, but her piercing gaze looks slightly past it. The photographer noticed her on the move and quickly hit the shutter, slightly catching a passerby's shoulder and a blurred piece of camera gear at the frame's edge. Medium full shot, chest-to-eye level, candid slightly angled perspective.

image_2 [Development]:
A Japanese woman in her early 20s who is a passionate fan of "Black Panther Woman." In an open area just past a corridor corner, she wears a fictional feline heroine outfit styled in black and deep purple. Over a form-fitting matte bodysuit-style base, she features light armor-style plates on her shoulders and forearms, a cat-ear headpiece, a flexible tail-like accent, and fitted long boots. Dropping her center of gravity low with one leg extended forward, she poses with splayed fingers in a dedicated "stalking predator" prowl. Her expression is utterly serious—cool and dedicated to the heroine persona—with a firm mouth and a gaze cutting sharply just above the lens. In the background, other attendees waiting near a wall appear softly blurred, adding venue authenticity. Full shot, waist-height camera angle tilted slightly upward from a hasty stance.

image_3 [Twist]:
A Japanese woman in her early 20s who is a passionate fan of "Frog Woman." In an open corridor near a rest bench, she wears an amphibian-themed fictional heroine costume in vibrant lime green and black. It features a sleek bodysuit with a glossy short cape, a headpiece evoking rounded frog eyes, long boots accentuating her legs, and webbed cuff details along her wrists and forearms. Crouching deep into a wide squat, she extends one hand toward the floor and the other diagonally upward, faithfully striking an exaggerated "ready to leap" power pose. Facing the camera almost straight-on with wide eyes and a set jaw, the contrast between her theatrical intensity and the mundane venue hallway is wonderfully humorous. Snapped hastily while stopping mid-stride, the camera has a slight candid tilt, with background benches and resting participants appearing softly cluttered in blur. Medium full shot, low camera angle from knee-to-waist height.

image_4 [Conclusion]:
A Japanese woman in her early 20s who is a passionate fan of "Nippon Rikishi Girl." Wearing a completely original Japanese-style comic superhero costume in red, white, and black, she reimagines sumo design elements—kesho-mawashi apron, loincloth motifs, braided tassels, gauntlets, and boots—into an opaque, convention-safe event hero suit. Emulating an exaggerated ring-entering ritual (dohyo-iri), she stands in a deep wide squat, raising one arm forward and thrusting the other skyward in a signature finishing pose. Standing in a large exhibition hall walkway, her face points diagonally upward as if glaring at a distant nemesis, her brow furrowed in intense seriousness. Right behind her, another attendee waiting for a turn stands casually holding a beverage, accentuating the gap between her grand hero performance and reality.
Full shot. The photographer reflexively pointed the FUJIFILM X-T50 right before walking past, capturing a sliver of a booth support pillar on the right edge, shifting the subject slightly off-center to the left. Natural chest-level eye line, candid slightly oblique front angle.

Output 4 separate image files. Do not combine them into a single page.
Ensure variations (deltas) for each image are independent so each stands alone as complete instructions. If the model processes prompts individually, avoid phrases like "same as above except..." and instead place the unchanging "COMMON LOCK" settings at the start of each individual prompt.

{Output Constraints}:
Maintain consistency in hands, ears, joints, clothing, background continuity, light sources, shadows, color temperature, venue depth, and the subjects' adult maturity. Prioritize humor, energy, and the authentic, slightly cluttered festive convention atmosphere over vulgarity, avoiding explicit sexualization, excessive post-processing, CG aesthetics, and typical AI gloss. Realize each cosplay as an original animal-themed heroine, strictly omitting official designs, franchise logos, or readable text. Eliminate distortions, blur artifacts, melting, extra limbs, and excessive background clutter, prioritizing the naturalism of a real candid snapshot. Do not include text, logos, watermarks, or UI elements.

Negative prompt: collage, grid, 2x2 grid, split screen, four panel, contact sheet, multi-panel, layout, comic panel, one canvas, combined image, readable text, logo, watermark, UI, extra limbs, extra fingers, fused fingers, distorted anatomy, broken hands, deformed costume, hyper-polished studio look, official superhero logo, exact copyrighted costume.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098631695855669712"></a>

### A cozy, photorealistic shot of an East Asian woman in a warm camper van gazing at the starry Milky Way sky.

Author：[@laviniavelle](https://x.com/laviniavelle) · [Source](https://x.com/laviniavelle/status/2098631695855669712)

Photography · Character · Published

**Summary:** A cozy, photorealistic shot of an East Asian woman in a warm camper van gazing at the starry Milky Way sky.

<img src="images/2098631695855669712-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
A realistic cozy highly detailed photograph of a young East Asian woman with her hair in a soft casual bun sitting comfortably inside a warm camper van at night. She is wrapped in a thick plush floral-patterned pink quilt wearing a cozy pink fuzzy fleece sweater holding a pink ceramic mug with both hands looking out the large van window with a gentle serene smile Outside the window, a breathtaking dark night sky reveals a vivid star filled Milky Way galaxy over distant mountain silhouettes The interior of the van is filled with warm string fairy lights cozy wooden shelves with small house decor framed photos and cute plush stuffed animals a white bunny and a yellow duckling Warm, ambient lighting, cinematic, 8k resolution, photorealistic, dreamy atmosphere.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097585546973614232"></a>

### A photographic prompt of a woman in a mustard-colored top and pleated skirt looking back over a net on an orange tennis court.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2097585546973614232)

Photography · Character · Published

**Summary:** A photographic prompt of a woman in a mustard-colored top and pleated skirt looking back over a net on an orange tennis court.

<img src="images/2097585546973614232-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Looking back on an orange court

Main subject:
A vertical photograph of an adult woman standing with her back to the camera in the center of the frame on a sunny outdoor tennis court, looking back over her shoulder.

Person / Expression:
Turning only her face over her own right shoulder toward the camera, with a calm expression and closed lips. Slender oval face, small chin, horizontally elongated brown eyes, natural thin eyebrows, small nose, pale pink lips. Long, light brown wavy hair spreads across her back.

Attire / Pose:
A mustard-colored sleeveless top with a deep open back, and a white pleated short tennis skirt. Weight shifted onto one leg with a slight twist at the waist, holding a white racket lowered to her lower right with her own right hand, left arm resting naturally along her side.

Background / Lighting:
A black net crossing at waist height in the foreground, with an orange court, green fence, trees, and blue sky in the background. Harsh direct midday light from the upper left illuminates her hair and shoulders, casting a short shadow onto the court.

Composition / Camera:
4:5 vertical composition, an above-the-knee shot taken from a rear diagonal angle with the camera placed at waist height. The person is framed prominently in the center, with the net serving as a horizontal line in the foreground and the racket placed in the lower right. Focus on the face and back, background lightly blurred, with the top of the head and the hem of the skirt contained within the frame.

Texture / Style:
Photorealistic live-action photograph. Clearly captures the fine sheen of the hair, the stretch fabric of the top, the pleats of the skirt, the mesh of the net, and the dry court surface.

Negative:
Do not show facing forward; do not omit the net crossing in front of the waist and the racket in the lower right
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097534208541442338"></a>

### iPhone front-facing camera close-up headshot portrait prompt for a cool-white-skinned young East Asian woman, featuring a gray-white plush background and various face-cupping and daydreaming pose options.

Author：[@AIVideoHub\_](https://x.com/AIVideoHub_) · [Source](https://x.com/AIVideoHub_/status/2097534208541442338)

Profile / Avatar · Photography · Portrait / Selfie · Character · Abstract / Background · Published

**Summary:** iPhone front-facing camera close-up headshot portrait prompt for a cool-white-skinned young East Asian woman, featuring a gray-white plush background and various face-cupping and daydreaming pose options.

<img src="images/2097534208541442338-1.jpg" alt="Image 1" width="480" />

<img src="images/2097534208541442338-2.jpg" alt="Image 2" width="480" />

<img src="images/2097534208541442338-3.jpg" alt="Image 3" width="480" />

<img src="images/2097534208541442338-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
📱 iPhone front-facing camera casual snapshot, 9:16; 18–22 years old, clearly adult beautiful East Asian female, approximately 1.75 meters tall, delicate facial features, cold-white translucent skin, tall and slender model physique, visually natural E-cup bust. Dark, smooth, fluffy, long wavy curly hair, light-colored slim-fit deep V delicate spaghetti-strap camisole, revealing smooth neck and shoulder lines, rounded eye shape, soft flat eyebrows, jet-black clear eyes, pale pink blush and hydrated pink-toned lips, languid and quiet.

🩶 Dim indoor close-up headshot portrait, blurred background of gray-white plush fabric, cool-toned low light, low exposure, low-saturation gray-white filter, low contrast, slight sharpening, soft-focus hazy graininess, casual and relaxed, clean and high-end, with a touch of melancholy, cool, and ethereal atmosphere.

Random pose pool:

🤍 Supporting the face with one hand, palm pressed against cheek and jaw, quietly looking at the camera
🫧 Resting the side of the face on an elbow, head slightly tilted, daydreaming
🌙 Half of the face buried in the palm, gaze languid and blank
💭 Fingers gently touching the chin and side of the face, head lowered then slowly looking up
🪞 Leaning close to the camera, palm cupping the face, long curly hair falling over the front of the shoulders
☁️ Side of the face resting against the back of the hand, gaze shifting outside the frame
💤 Cupping the cheek with a hand while slightly shrugging shoulders, as if casually snapped while drowsy
✨ Supporting the face close to a plush cushion, with a faint, subtle smile at the corners of the mouth

🎲 Freely improvise around different actions regarding selfie distance, face-supporting methods, gaze, strands of hair, low light, defocus, and graininess, prioritizing the preservation of the close-up headshot, cool gray-white tone, and casual iPhone front-camera snapshot texture, pursuing an at-home dreamcore × melancholy atmosphere × high-end minimalist portrait feel.

Generate a comprehensive preview image containing different poses for me to choose from.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2096909970398941572"></a>

### Photorealistic 9:16 mirror selfie of an athletic Brazilian woman in a terracotta-orange bodysuit inside an upscale gym.

Author：[@MrDasOnX](https://x.com/MrDasOnX) · [Source](https://x.com/MrDasOnX/status/2096909970398941572)

Photography · Portrait / Selfie · Character · Published

**Summary:** Photorealistic 9:16 mirror selfie of an athletic Brazilian woman in a terracotta-orange bodysuit inside an upscale gym.

<img src="images/2096909970398941572-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Photorealistic indoor luxury fitness studio mirror selfie, vertical 9:16, a young adult Brazilian woman standing in a relaxed contrapposto pose taking a smartphone selfie. Camera captures the scene through a large floor-to-ceiling mirror using a 28–35mm equivalent phone wide-angle lens. Subject stands about 1 meter from the mirror. Full body from head to sneakers is visible. She occupies the center-left of the frame. Warm wooden flooring, black rubber mats, and rows of kettlebells and cable machines appear on the right and in the background.
Subject is a young adult Brazilian woman with a compact athletic-curvy build: moderately broad shoulders, defined but not bulky arms, full bust, cinched waist, rounded hips, and naturally thick thighs. Proportions feel grounded and real rather than model-thin or exaggerated. Warm golden-tan skin with visible pores and subtle variation. Soft natural lighting, no plastic skin.
She stands with weight on her right leg, left knee slightly bent and turned out, hips angled toward the mirror. Torso twists gently so her left shoulder is closer to the glass. Left hand rests on her hip; right hand holds a dark smartphone up near her face at cheek height. Head is turned over her left shoulder toward the phone, chin slightly down, expression calm and slightly confident with a small closed-mouth smile. Eyes look at the screen.
Hair is dark brown with warm caramel highlights, shoulder-length, worn in a loose low ponytail with face-framing strands. Face is oval with high cheekbones, full lips in a natural nude-rose tone, and dark brown almond eyes.
Outfit is a deep terracotta-orange high-neck athletic one-piece with thin straps, moderate coverage, and a high-cut but still modest leg line. Matte stretch fabric, no logos. White sneakers with clean soles.
Setting is a high-end contemporary fitness studio with large mirrors, exposed brick on one wall, warm pendant lights mixed with cool overhead LEDs, and a few other people training softly out of focus in the background. Realistic phone HDR, natural grain, accurate reflections, and believable shadows.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2096901566985068734"></a>

### Portrait snapshot prompt for a Japanese flight attendant uniform photoshoot against an airplane cabin door backdrop, featuring an integrated random action pool.

Author：[@AIVideoHub\_](https://x.com/AIVideoHub_) · [Source](https://x.com/AIVideoHub_/status/2096901566985068734)

Photography · Portrait / Selfie · Character · Abstract / Background · Published

**Summary:** Portrait snapshot prompt for a Japanese flight attendant uniform photoshoot against an airplane cabin door backdrop, featuring an integrated random action pool.

<img src="images/2096901566985068734-1.jpg" alt="Image 1" width="480" />

<img src="images/2096901566985068734-2.jpg" alt="Image 2" width="480" />

<img src="images/2096901566985068734-3.jpg" alt="Image 3" width="480" />

<img src="images/2096901566985068734-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
📱 Japanese airline casual snapshot, 3:4; 18–22 years old, clearly adult beautiful East Asian female, approximately 1.75 meters tall, delicate and sweet facial features, cool porcelain white skin, tall and slender model figure, visually natural E-cup bust. Exquisite updo hairstyle, deep V-neck white shirt × navy blue flight attendant vest × blue-and-white striped short skirt, yellow silk scarf, black mid-heels, and black pantyhose.

✈️ Airplane cabin door area, with the folding jump seat, cabin door handle, warning signs, and overhead bins naturally in frame. Cool gray low saturation, handheld smartphone tilted composition, diffused overhead lighting, slight overexposure, noise grain, and edge defocus, clear white-peach "no-makeup" makeup look, genuine amateur candid snapshot feel.

Random Action Pool:

💺 Sitting on the folding jump seat, one leg bent up, raising a hand to adjust her updo
✈️ Sitting sideways next to the cabin door, turning her head back with a sweet smile
🧣 Looking down adjusting her silk scarf, suddenly looking up at the camera
👜 Bending over rummaging through a personal carry-on pouch, capturing the mid-action moment
🙆🏻‍♀️ Leaning against the seatback stretching, natural and relaxed posture
🪞 Standing up adjusting her vest and skirt hem, turned sideways looking at the camera
💬 Sitting resting her chin on her hand daydreaming, legs naturally staggered
🚪 Holding onto the edge of the cabin door to stand up, turning back to smile

🎲 After selecting an action, freely improvise camera angles, cabin details, expressions, handheld tilt, and defocus effects, pursuing a flight attendant uniform × Japanese lifestyle portrait × accidental smartphone candid snapshot feel.

Generate a comprehensive preview image containing different actions for me to choose from.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097249218507461093"></a>

### Photorealistic close-up indoor portrait of an Asian woman in sunlight

Author：[@Aqsahere\_](https://x.com/Aqsahere_) · [Source](https://x.com/Aqsahere_/status/2097249218507461093)

Photography · Portrait / Selfie · Character · Published

**Summary:** Photorealistic close-up indoor portrait of an Asian woman in sunlight

<img src="images/2097249218507461093-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
A photorealistic close-up indoor portrait of a young woman sitting comfortably in a woven rattan chair near a bright window. She has long, naturally tousled dark brown hair with warm brown highlights, parted near the center, with loose strands softly framing and partially covering her face. She looks directly into the camera with a calm, slightly dreamy expression and natural, softly tinted lips.\nOne hand is raised gently in front of her face, with her fingertips resting delicately around her lips and cheek, creating an intimate candid pose. Her fingers are slender and naturally positioned. She is wearing a simple oversized off-white/light beige top with soft fabric texture.\nStrong warm sunlight streams through the window from the upper side, creating beautiful striped shadows and highlights across her hair, forehead, cheek, and clothing. The lighting is natural, golden, and slightly overexposed in places, giving the photograph a warm cozy atmosphere.\nBehind her is a large white woven/rattan chair with curved circular detailing. A dark green wall or window panel with elegant white botanical/leaf patterns is visible in the background, along with a simple dark vertical frame. The setting feels like a cozy modern home or café.\nComposition: vertical close-up portrait, approximately 4:5 aspect ratio, camera very close to the subject, face occupying the central-right portion of the frame, slightly low and intimate camera angle, shoulders and upper torso visible, natural framing.\nPhotography style: ultra-realistic smartphone selfie photography, soft Korean/Asian lifestyle aesthetic, natural skin texture, realistic pores, individual hair strands, subtle imperfections, warm sunlight, authentic shadows, gentle contrast, slight film grain, shallow depth of field, candid unposed feeling, high detail, 4K.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2096805553339342932"></a>

### Nighttime street portrait of a smiling young woman in a cream textured jacket and pleated skirt.

Author：[@Aqsahere\_](https://x.com/Aqsahere_) · [Source](https://x.com/Aqsahere_/status/2096805553339342932)

Photography · Portrait / Selfie · Character · Cityscape / Street · Published

**Summary:** Nighttime street portrait of a smiling young woman in a cream textured jacket and pleated skirt.

<img src="images/2096805553339342932-1.jpg" alt="Image 1" width="480" />

<img src="images/2096805553339342932-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
A photorealistic nighttime street portrait of a young woman standing on a lively city street, wearing a delicate cream-colored textured jacket with tiny floral details, decorative bows, dark trim, and pearl-like buttons, paired with a matching pleated skirt. She has long straight dark brown hair and natural soft makeup, smiling gently at the camera while making a playful hand gesture near her face. A small black handbag hangs from her arm. Warm streetlights, glowing storefronts, passing cars, and a cyclist create a vibrant urban night atmosphere in the background. Slight motion blur on the background, soft ambient lighting, candid smartphone photography, natural skin texture, shallow depth of field, cozy elegant aesthetic, realistic details, vertical composition, high resolution.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2096982628541100464"></a>

### Dual-portrait prompt creating a coordinated pair of man and woman portraits in a deep blue cosmic galaxy fantasy style.

Author：[@sha\_zdiii](https://x.com/sha_zdiii) · [Source](https://x.com/sha_zdiii/status/2096982628541100464)

Photography · Portrait / Selfie · Character · Published

**Summary:** Dual-portrait prompt creating a coordinated pair of man and woman portraits in a deep blue cosmic galaxy fantasy style.

<img src="images/2096982628541100464-1.jpg" alt="Image 1" width="480" />

<img src="images/2096982628541100464-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Create two separate ultra-detailed cinematic fantasy portraits from one prompt, both using the exact same deep blue cosmic galaxy theme and visual style. IMAGE 1 — WOMAN: Create a beautiful clearly adult woman with long flowing black hair, luminous smooth skin, glamorous blue-and-silver celestial eye makeup, glossy lips, and sparkling star-like details across her face. Add elegant crescent moon and star jewelry, subtle crystal accents, and glowing cosmic particles around her. Her expression is confident, mysterious, and attractive. Surround her with deep blue nebula clouds, glowing stars, large planets, moons, cosmic dust, and electric-blue light. The galaxy energy should naturally blend around her face, hair, shoulder, and clothing. IMAGE 2 — MAN: Create a handsome clearly adult man in the exact same blue cosmic theme. He has thick slightly messy black hair, a neat dark beard, strong facial features, intense glowing blue eyes, and a confident mysterious expression. Add subtle galaxy-like glowing patterns and tiny stars across one side of his face. His hand is near his chin in a stylish fashion pose with an elegant dark metallic ring. Surround him with the same deep blue nebula clouds, glowing planets, moons, stars, cosmic dust, and electric-blue energy. IMPORTANT: Generate the woman and man as two separate images, not together in one frame. Keep the same lighting, same blue galaxy color palette, same premium fantasy fashion style, same level of detail, and matching visual identity so both images look like a coordinated pair. Ultra-realistic, premium cinematic lighting, high contrast, glossy luxury fantasy look, sharp focus, detailed skin and hair, magical blue glow, no text, no watermark. Vertical portrait composition, 9:16 for both images.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097269715966230876"></a>

### A photographic portrait prompt of a woman standing in shallow water at dusk, draped in a wet, translucent white cloth.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2097269715966230876)

Photography · Portrait / Selfie · Character · Published

**Summary:** A photographic portrait prompt of a woman standing in shallow water at dusk, draped in a wet, translucent white cloth.

<img src="images/2097269715966230876-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject:
Translucent White Under the Evening Moon

Main Subject:
A full-body vertical photograph of an adult woman standing in the center of the frame in shallow water among coastal rocks at dusk, wrapped from chest to feet in a wet, translucent white cloth.

Person & Expression:
A quiet, near-profile expression with her head tilted toward the lower right of the frame and her gaze lowered toward the hand holding the fabric. Slender oval face contour, downcast elongated eyes, a slender nasal bridge, and softly parted pale lips. Wet, dark-brown below-the-shoulder hair is side-parted, with thin strands clinging to her cheek and neck.

Attire & Pose:
Wrapped from the chest in a long, strapless, dress-like sheer white cloth, with diagonal drapery overlapping across the torso and legs. Standing barefoot in the shallows, her own right hand is lowered by her side, her left hand pinches the cloth in front of her waist, and one leg is stepped slightly forward.

Background & Lighting:
A slender crescent moon in the blue-violet sky at the upper left of the frame, an orange sunset glow on the right horizon, and the water surface and black rocks across the lower half. Low evening sunlight from the rear right of the frame golden-rims the wet cloth and body, while soft blue twilight illuminates the front.

Composition & Camera:
A 3:4 vertical composition, full-body shot taken from a slight three-quarter front angle with the camera positioned slightly below waist height. The subject is framed prominently in the center, capturing the evening sky and crescent moon in the upper half, and the wet hem and feet at the bottom edge. Sharp focus on the subject and translucent cloth, with a gentle blur on the distant background.

Texture & Style:
Photorealistic live-action photograph. Meticulously captures the wet sheer cloth clinging to the skin, fine water droplets, reflections on the rocks and water surface, and the gradations of orange and blue-violet in the evening scene.

Negative:
Do not make the white cloth opaque; do not omit the crescent moon and the sunset glow
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2096809673378967588"></a>

### Photorealistic 9:16 portrait of a stylish woman posing in front of a black BMW.

Author：[@Lianaalane](https://x.com/Lianaalane) · [Source](https://x.com/Lianaalane/status/2096809673378967588)

Photography · Portrait / Selfie · Character · Published

**Summary:** Photorealistic 9:16 portrait of a stylish woman posing in front of a black BMW.

<img src="images/2096809673378967588-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Create a photorealistic 9:16 picture of a stylish young woman confidently posing in front of a luxurious black BMW on a modern city road. She has long, sleek, straight black hair with a clean Korean-inspired center part and soft face-framing strands. Her face should remain natural and unchanged, with fresh Korean-style makeup, dewy skin, soft blush, subtle eyeliner, and glossy nude-pink lips. She is wearing a fashionable red-and-white gingham puff-sleeve top with high-waisted white trousers for a classy modern look. Replace the black bangles with an elegant luxury wristwatch for a sophisticated touch. One hand rests naturally on the car hood while the other is placed inside her trouser pocket. The background features blurred city buildings, greenery, traffic, street barriers, and soft daylight. Keep the same confident pose, realistic proportions, cinematic depth of field, premium fashion-editorial style, ultra-realistic details, and natural photography quality.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2096601368114937969"></a>

### Ultra-realistic luxury fashion editorial featuring a blonde model in an ivory cape outfit posing with a pure white horse in a warm beige studio.

Author：[@sha\_zdiii](https://x.com/sha_zdiii) · [Source](https://x.com/sha_zdiii/status/2096601368114937969)

Photography · Fashion Item · Published

**Summary:** Ultra-realistic luxury fashion editorial featuring a blonde model in an ivory cape outfit posing with a pure white horse in a warm beige studio.

<img src="images/2096601368114937969-1.jpg" alt="Image 1" width="480" />

<img src="images/2096601368114937969-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Ultra-realistic luxury fashion editorial in a minimalist warm beige studio. A glamorous adult blonde female model with long soft wavy hair poses elegantly beside a majestic full-size pure white horse wearing a realistic black leather bridle with subtle gold hardware. The model wears a sophisticated ivory-white sleeveless tailored wide-leg outfit with a long flowing cape, elegant heels, and refined jewelry. Create a premium high-fashion campaign look with elegant model poses, sometimes standing beside the horse holding the reins and sometimes seated gracefully on geometric cream blocks while the horse stands calmly behind or beside her. Warm beige seamless background and floor, soft directional studio lighting, realistic skin texture, realistic horse anatomy and fur, natural shadows, flowing fabric, refined neutral color palette, photorealistic, luxurious editorial aesthetic, full-body composition, high detail, vertical 2:3.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2096631729410986083"></a>

### A close-up portrait of an Eastern noblewoman grooming herself in a warm, antique nighttime pavilion, featuring detailed descriptions of makeup, hair accessories, and attire.

Author：[@liyue\_ai](https://x.com/liyue_ai) · [Source](https://x.com/liyue_ai/status/2096631729410986083)

Photography · Portrait / Selfie · Character · Fashion Item · Abstract / Background · Published

Source：[@liyue\_ai](https://x.com/liyue_ai) · [Source](https://x.com/liyue_ai/status/2096269909076623535)

**Summary:** A close-up portrait of an Eastern noblewoman grooming herself in a warm, antique nighttime pavilion, featuring detailed descriptions of makeup, hair accessories, and attire.

<img src="images/2096631729410986083-1.jpg" alt="Image 1" width="480" />

<img src="images/2096631729410986083-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
9:16 vertical orientation, ancient Chinese style nocturnal beauty photography, classical Eastern noblewoman portrait, bust close-up shot, front view, the subject sitting upright in front of a dressing table, body facing the camera directly, head naturally poised and upright, gentle and affectionate gaze, looking quietly at the camera, with a subtle, soft, and restrained emotional expression, carrying a touch of hesitant, evocative nighttime sentiment. The overall aura is that of a lady from a high-born family: gentle, luxurious, exquisite, restrained, and full of classical charm, resembling a noble lady who has just paused her nocturnal grooming.

The subject is a young Eastern female with a visual age of approximately 20–28 years, clearly adult, with bright eyes and plump lips, a soft oval face, a naturally full forehead, a plump and three-dimensional midface, and a smooth, gentle jawline. Delicate and elongated eyebrows, clear and spirited eyes, naturally slender eye shape, slightly upturned outer eye corners without exaggeration, and a soft, affectionate gaze; a delicate and smooth nasal bridge, with a refined, rounded tip; soft and plump lips with a naturally distinct cupid's bow; overall facial features are exquisite and symmetrical, captivating in close-up, non-infantile, non-influencer-styled.

The makeup is a soft and vivid pomegranate style under lamplight. Translucent and delicate base makeup, fair, supple skin texture, retaining natural and fine skin details. Eye makeup features gradient blending of pomegranate red, red tea, warm brown, and a touch of warm gold shimmer, with slight deepening on the outer upper eyelid and outer corner, the under-eye aegyo sal lined with delicate warm gold pearl shimmer, fine and clean eyeliner, and distinct, curled eyelashes. The midface and apples of the cheeks have soft, natural warm rose blush, radiating a warm, healthy glow. Subtle and clear highlights are added to the nose bridge, nose tip, midface, and cupid's bow, avoiding full-face oiliness. Lip makeup is a glossy pomegranate red, fresh, lustrous, and soft, with a subtle glass-like sheen. The post-makeup demeanor is gentle, delicately glamorous, subtle, and luxurious, brimming with the emotional ambiance of a noble lady under nocturnal candlelight.

The hairstyle is a loosely gathered high bun of black hair, plump and rounded, naturally voluminous at the crown, with lustrous and silky dark strands. Adorned with pomegranate-red beaded hairpins, light gold hair chains, golden floral branch structures, small red gemstones, pearl embellishments, and multi-layered hanging tassels; the overall hair accessories are exquisite and opulent, richly layered yet not overpowering the face. Ear ornaments are pearl tassel drop earrings, matched with red jade beads and fine light-gold chains, gently swaying by the ears, enhancing the sense of luxury.

The attire is a pomegranate-red parallel-collar upper garment (duijin shangru), the fabric richly embroidered with golden thread floral patterns and dense subtle motifs, paired with a dark gold patterned long skirt and an ivory-white sheer gauze shawl. The neckline and chest feature an exquisite ancient-style tube-top underlayer (moxiong), natural and full bust, with balanced, voluptuous upper body proportions, clearly showing soft chest lines and most of the upper bust contour, yet fully covered by proper attire, overall decent, never vulgar, and non-modern-evening-gown. The color palette centers on pomegranate red, dark gold, ivory white, and warm gold, gorgeous and vivid, while preserving classical refinement.

The setting is a warm palace-lantern pavilion / pearl curtains / bronze mirror vanity / flickering candle shadows. The subject sits before an ancient vanity, with an antique bronze carved round mirror visible on the left; multi-layered pearl curtains hang in the foreground and on both sides, while the vanity holds red-and-gold jewelry boxes, pearl strands, small accessories, and candle holders. The background features warm yellow palace lanterns, a dark wood interior chamber, and softly blurred night pavilion lights in the distance; the overall space is luxurious, with a gently defocused background that never overpowers the subject.

Lighting combines warm white tending toward golden candlelight with the soft glow of palace lanterns; the subject's face has independent, soft fill light, ensuring that the eyes, eyeshadow, blush, lip makeup, hair ornaments, embroidery, and skin textures are all crystal clear. The overall frame is warm and translucent, filled with nocturnal atmosphere, yet not overly dark, not yellowish, and not murky gray. Shallow depth of field blurs the background, keeping the subject's face and makeup as the primary visual focus.

85mm portrait lens, authentic photographic texture, highly polished classical noblewoman beauty portrait, eyes precisely in focus, makeup crisp and clear, pearl ornaments and gold thread embroidery exquisitely detailed, a composition that is magnificent, softly glamorous, warm, and imbued with classical nighttime cinematic ambiance.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2096555489073279173"></a>

### Commercial food photography scene in a bright modern kitchen featuring stacked jars of pink berry smoothie, a jar of organic peanut butter, and roasted peanuts on a wooden serving board.

Author：[@DuaFatimaAi](https://x.com/DuaFatimaAi) · [Source](https://x.com/DuaFatimaAi/status/2096555489073279173)

Photography · Food / Drink · Published

**Summary:** Commercial food photography scene in a bright modern kitchen featuring stacked jars of pink berry smoothie, a jar of organic peanut butter, and roasted peanuts on a wooden serving board.

<img src="covers/2096555489073279173.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Create an ultra-realistic, high-end food photography scene in a bright, cozy modern kitchen. A vibrant thick pink berry smoothie is served in a stack of three small transparent glass jars, arranged vertically on the left side of a clean white round table. The smoothie has a rich creamy texture with subtle berry speckles and glossy highlights.

On the right, place a clear jar of organic peanut butter with a green lid, filled with golden-brown creamy peanut butter. Preserve the product packaging, label placement, colors, and proportions accurately. Scatter a few whole peanuts naturally beside the jar.

In the foreground, include a small ceramic bowl filled with mixed roasted peanuts and a beige ceramic plate holding a spoon with a generous scoop of creamy peanut butter. Add a few delicate green herb sprigs near the smoothie.

Background: clean white subway-tile kitchen wall, soft natural sunlight coming from the side, subtle shadows, warm cozy atmosphere. Place the food items on a small wooden serving board with a sheet of vintage printed paper underneath.

Add elegant handwritten-style white text in the upper-left area reading “Smoothies”, with smaller cursive text underneath reading “Tingi Kalori.

Vertical 9:16 composition, premium commercial food photography, realistic textures, natural daylight, shallow depth of field, soft bokehcrisp product details, balanced composition, warm lifestyle aesthetic, photorealistic, high resolution, no people
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097159277937115208"></a>

### Dual-element portrait of a South Asian man split with bursting water splashes on one side and glowing fire on the other.

Author：[@Aiwithamirr1](https://x.com/Aiwithamirr1) · [Source](https://x.com/Aiwithamirr1/status/2097159277937115208)

Photography · Portrait / Selfie · Character · Published

**Summary:** Dual-element portrait of a South Asian man split with bursting water splashes on one side and glowing fire on the other.

<img src="images/2097159277937115208-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Using uploaded face as reference. 
High-resolution portrait of a 23-year-old South Asian man with eyes closed and head tilted back in a serene expression, messy black hair, uploaded beard asreference. Dramatic split elemental effect: the left side of his face and body is bursting with dynamic water splashes, fluid spray, and floating water droplets; the right side is engulfed in glowing orange flames, fierce fire strands, and burning ember particles. Wearing a dark fitted t-shirt. Surreal dual-element aesthetic, cinematic lighting, high-contrast monochrome and fire color palette, studio lighting, hyper-realistic details, muted light grey background, shot on 85mm portrait lens, 8k resolution, photorealistic masterpiece.
```

[↑ Back to categories](#catalog)

---

<a name="category-cinematic-film-still"></a>

## Cinematic / Film Still

<a name="prompt-2101248200787320961"></a>

### A 30-second segmented video prompt of a young woman running through an Inception-style folding, inverted city to deliver a yellow envelope in 1940s Venice at sunset.

Author：[@oggii\_0](https://x.com/oggii_0) · [Source](https://x.com/oggii_0/status/2101248200787320961)

Cinematic / Film Still · Character · Architecture / Interior · Cityscape / Street · Published

**Summary:** A 30-second segmented video prompt of a young woman running through an Inception-style folding, inverted city to deliver a yellow envelope in 1940s Venice at sunset.

<img src="covers/2101248200787320961.jpg" alt="Image 1" width="480" />

**Prompt**

```text
[CHARACTER + STYLE]

<<<image_1>>>  is the face and identity reference. A young Korean woman in her early twenties with EXACTLY the face of <<<image_1>>> — same facial structure, same features, natural Korean skin, no glasses. Long black hair, wearing a 1940s teal-blue wool coat-dress with white collar, a brown leather satchel worn cross-body, grey knee socks, black leather shoes, holding a folded yellow envelope. Every shot of her matches <<<image_1>>> .

1940s Venice at golden hour. Amber and teal cinematic grade, anamorphic 35mm film look, shallow depth of field, volumetric god rays, fine film grain. Inception-style folding architecture — the Venetian city curls upward and hangs inverted overhead like a mirrored ceiling. The woman always stays under normal gravity while the world folds around her. Continuous camera motion, no hard cuts.

[TIMELINE PROMPT]

0–3s: Lateral tracking shot along a stone quay by the Grand Canal at sunset. The young woman in a teal coat sprints past camera, clutching a yellow envelope. Above her the entire city hangs upside down, mirrored — a man in a bowler hat walks a dachshund across the inverted street. A red umbrella drifts weightlessly between the two worlds. Pigeons scatter through the amber light.

3–6s: Camera follows behind her into a narrow Venetian alley, dry leaves swirling in her wake. At the far end the street peels upward into the sky, buildings stacking vertically like a wall of windows. Her footsteps echo between the stone walls.

6–9s: The camera slowly rolls 90 degrees. The alley wall becomes the ground beneath her feet; she keeps running, unfazed. The roll continues into a wide orbit as she races up a floating spiral stone staircase suspended in mid-air, fragments of terracotta Venetian rooftops rotating around her like a kaleidoscope.

9–12s: Extreme wide silhouette. She runs across the top of an arched stone bridge over a wide canal against the blazing setting sun. The mirrored city hangs both above and below the arch. On the inverted plane, a lone pedestrian walks the opposite direction. Birds burst across the frame in slow motion.

12–15s: Low angle looking straight up between two towering building walls, the sky a thin bright strip. She leaps across the vertical chasm, arms spread wide, coat and hair flying, satchel swinging. Camera holds on her against the sky. Wind roars.

15–18s: Handheld push-in through a crowded 1940s Rialto market street — vendors stacking crates of apples, laundry strung overhead between the buildings. She weaves between blurred foreground shoppers, running away from camera. An apple rolls loose across the cobblestones.

18–21s: Camera tilts up a grand brick bell tower — a Venetian campanile — as the surrounding city folds and curls around it. The woman appears tiny on the tower ledge, pauses against the sun, then steps off toward the rooftops. Bells begin to ring.

21–24s: Rooftop terrace garden framed by a rose-covered arbor. An elderly woman in a grey cardigan waters a bed of vivid flowers with a tin can. Behind her, Venice and the domes of St Mark's Basilica glow at sunset over the lagoon while the inverted city hangs overhead. The young woman balances along the stone balustrade, arms out, then jumps down onto the terrace.

24–27s: She holds out the yellow envelope. The old woman turns, sets down the watering can, and takes it. Both smile warmly at each other. Rose petals drift upward past them, falling toward the inverted sky.

27–30s: Camera pulls back and rises fast. The whole city folds and rotates until it becomes a top-down aerial of Venice's canals and streets curling into a sphere. The two tiny figures remain on the terrace. Slow fade to warm light.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100038053498917288"></a>

### Morning in a luxury suite, a first-person POV shot of two East Asian women in silk nightwear lounging in bed, presenting a cinematic texture and soft morning light.

Author：[@AIVideoHub\_](https://x.com/AIVideoHub_) · [Source](https://x.com/AIVideoHub_/status/2100038053498917288)

Cinematic / Film Still · Published

**Summary:** Morning in a luxury suite, a first-person POV shot of two East Asian women in silk nightwear lounging in bed, presenting a cinematic texture and soft morning light.

<img src="images/2100038053498917288-1.jpg" alt="Image 1" width="480" />

<img src="images/2100038053498917288-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
9:16 vertical orientation, wealthy young man's first-person POV × luxurious bedroom morning × two adult women × hyper-realistic live-action photography × high-end cinematic Editorial.

The scene is early morning just waking up in a top-tier luxury hotel suite / private penthouse bedroom. The camera adopts a male first-person point of view: the owner of the lens has already gotten out of bed, standing beside the bed or about 1–2 meters away from it, looking back at the large bed behind him. The lens owner himself does not appear fully in the frame; only through the standing eye level, bedside position, and first-person composition is the feeling of "a wealthy young man who just got out of bed and looks back" conveyed.

A massive, high-end double bed sits in the center of the frame, layered with slightly disheveled cream-white, ivory-white premium bedsheets, a duvet, and fluffy pillows. Lazily lounging on the bed are two beautiful East Asian women aged 23–27, explicitly adult; their facial features, hairstyles, and temperaments must be distinctly different, avoiding duplicate faces or a twin-like appearance.

The woman on the left has jet-black long wavy hair, a delicate oval face, and cool, refined features. She lies on her side on a pillow as if having just awakened, one hand resting naturally on the edge of the duvet, looking at the camera with a sleepy gaze and a faint smile.

The woman on the right has long dark-brown hair styled in a relaxed low updo or messy bed hair, a delicate heart-shaped face, and a gentle, radiant, glamorous vibe. She is half-reclining against the headboard or amidst soft pillows, tilting her face slightly up toward the first-person camera, looking languid, relaxed, with a playful just-woken-up smile.

The two are dressed in different designs of high-end silk loungewear/pajamas: one wears an ivory-white pure silk camisole slip dress, and the other wears a light champagne silk robe. The garments are soft, relaxed, featuring authentic silk drape and delicate pearlescent sheen, maintaining full coverage without wardrobe malfunctions or exposure of sensitive areas.

The subjects' hair is slightly tousled, and the sheets and duvet retain natural post-sleep wrinkles, giving the scene lived-in traces of "staying in a luxury suite last night, having just awakened in the morning." Their poses must not be identical—one on her side, one half-reclining—creating a natural, spontaneous feel.

The bedroom is exceptionally spacious and opulent, showing dark wood headboard elements, cream upholstered walls, floor-to-ceiling windows, heavy drapes, high-end sofas, a glass coffee table, nightstands, and a few refined everyday items. By the bed, subtle details such as a men's suit jacket, a wristwatch, a smartphone, or a hotel breakfast tray can naturally appear, reinforcing the lived-in ambiance of a young wealthy heir's private suite, while keeping the environment tidy, sophisticated, and free of cluttered luxury brand logos.

Outside the expansive floor-to-ceiling windows is an early morning high-rise city view, with a pale blue sky and soft golden morning light illuminating distant buildings. Some curtains are already drawn open; the first morning rays enter the bedroom from the side, casting soft, warm golden rim lights and highlights on the rumpled white bedding, the women's hair strands, the silk nightwear, and the edges of their skin.

The camera height is at the natural eye level of a standing adult, using an approximately 35–50mm first-person photographic perspective, looking slightly downward at the bed. The composition must clearly convey the spatial relationship: "I have gotten out of bed and am standing beside it → looking back at the bed → two women still lazily lounging on the bed looking back at me."

The subjects' faces, eyes, hair strands, silk pajamas, and bedding textures remain sharp and high-definition; the background is softly blurred yet the structure of the luxurious bedroom remains discernible. 4K–8K ultra-high definition, authentic skin texture, natural morning light, high dynamic range, subtle bloom, and fine cinematic grain.

Overall atmosphere: wealthy young man's early morning first-person POV, just got out of bed, luxurious private suite, two beautiful adult women still lounging in bed, disheveled premium bedding, morning sunlight, languid and joyful, opulent and relaxed, lived-in feel reminiscent of a movie opening shot.

Negative prompts: sexual acts, exposed sensitive areas, full nudity, slipping clothes, underage subjects, childish faces, three people crammed in bed, male fully in frame, third woman, duplicate faces, twin faces, both with identical hairstyles, both with identical sleepwear, unconscious subjects, passed out drunk, fearful expressions, forced situations, excessively messy bedding, cheap hotel, exaggerated brand logos, disproportionate head, oversized face, abnormal body proportions, extra limbs, extra hands or feet, plastic skin, severe overexposure, heavy blur, anime face, CG face, text, logo, watermark.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098362443042803749"></a>

### Cinematic action sequence of an assassin fighting Templar knights in 15th-century Granada fortress.

Author：[@yourPlugAI](https://x.com/yourPlugAI) · [Source](https://x.com/yourPlugAI/status/2098362443042803749)

Cinematic / Film Still · Published

Source：[@yourPlugAI](https://x.com/yourPlugAI) · [Source](https://x.com/yourPlugAI/status/2097579893017989538)

**Summary:** Cinematic action sequence of an assassin fighting Templar knights in 15th-century Granada fortress.

<img src="covers/2098362443042803749.jpg" alt="Image 1" width="480" />

**Prompt**

```text
In 15th-century Granada, a solo assassin battles through dozens of elite Templar knights within the walls of a sprawling fortress. Relying on lightning-fast Taijutsu, burst-acceleration, and precise sword deflections, he turns every enemy strike into a devastating counter. A high-octane 30-second AAA blockbuster action sequence driven by raw kinetic energy, continuous IMAX camera tracking, and relentless combat momentum.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097716825668702388"></a>

### Turn the two reference images into one breathtaking, ultra-realistic cinematic travel landscape with a seamless sunset animation loop combining Istanbul and alpine European lake village elements.

Author：[@KrishnaBio1](https://x.com/KrishnaBio1) · [Source](https://x.com/KrishnaBio1/status/2097716825668702388)

Cinematic / Film Still · Landscape / Nature · Published

**Summary:** Turn the two reference images into one breathtaking, ultra-realistic cinematic travel landscape with a seamless sunset animation loop combining Istanbul and alpine European lake village elements.

<img src="images/2097716825668702388-1.jpg" alt="Image 1" width="480" />

<img src="images/2097716825668702388-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Turn the two reference images into one breathtaking, ultra-realistic cinematic travel landscape with a seamless sunset animation loop.

SCENE
Combine the key elements from both images into one natural-looking destination. Include the grand Ottoman-style mosque with multiple minarets and domes, Istanbul-style waterfront and boats from the first image, together with the peaceful alpine lake, colorful European village, dramatic snow-capped mountains and beautiful hilltop stone castle from the second image.

Create a wide scenic waterfront view with historic architecture on one side and the castle and mountains on the other. Add colorful flowers, green trees, Mediterranean plants, a vintage lantern and an elegant terrace with a small café table in the foreground.

SUNSET & LIGHTING
Beautiful golden-hour sunset with pastel blue, pink, peach and orange clouds. Warm sunlight illuminates the mosque, castle, village, mountains and boats. The lake reflects the sunset, buildings and mountains with realistic gentle ripples and golden reflections.

ANIMATION
Create 16 consecutive frames of a smooth seamless loop. Animate only subtle environmental movement: slowly drifting clouds, gentle water ripples, boats moving slightly, birds flying in the distance, flowers and tree leaves softly moving in the breeze, and subtle candle/lantern flickering.

Keep the camera completely fixed. Keep the mosque, castle, mountains, houses and all major objects perfectly consistent across every frame. Frame 16 must smoothly transition back into Frame 1.

STYLE
Ultra-realistic cinematic travel photography, luxury tourism advertisement, breathtaking golden-hour atmosphere, realistic architecture, detailed mountains, natural vegetation, beautiful water reflections, atmospheric depth, high dynamic range, rich but natural colors, professional photography, photorealistic 8K quality.

CAMERA
Wide cinematic landscape view, 24mm lens, stable locked camera, natural perspective, realistic depth of field, consistent framing and lighting across all frames.

ANIMATION SETTINGS
16 frames, approximately 2.2-second complete loop, smooth continuous GIF animation, no camera movement, no flickering.

NEGATIVE PROMPT
cartoon, anime, painting, CGI, 3D render, low quality, distorted buildings, warped mosque, crooked minarets, malformed castle, distorted mountains, duplicated boats, floating objects, unrealistic reflections, fake water, excessive fog, oversaturated colors, extreme HDR, blurry image, motion blur, camera shake, zoom, flickering, morphing buildings, changing architecture, disappearing objects, duplicated birds, unnatural clouds, image seams, visible collage, text, logo, watermark, border, black bars, artifacts.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100839251294446037"></a>

### Cinematic portrait of a purple-bob female character tying her shoes in ruins surrounded by orange smoke.

Author：[@Wareenaa](https://x.com/Wareenaa) · [Source](https://x.com/Wareenaa/status/2100839251294446037)

Cinematic / Film Still · Portrait / Selfie · Character · Fashion Item · Published

**Summary:** Cinematic portrait of a purple-bob female character tying her shoes in ruins surrounded by orange smoke.

<img src="images/2100839251294446037-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Create a hyper-realistic full-body cinematic portrait of the same young adult female character from the reference image, preserving her signature appearance: vivid violet-purple chin-length straight bob haircut with soft bangs, fair porcelain skin, natural freckles across her nose and cheeks, hazel/light-brown almond-shaped eyes, small straight nose, delicate facial features, glossy natural lips, and slim physique.\n\nShe is seated on a rustic wooden chair, one knee pulled up toward her chest while she holds and adjusts the shoelace of her raised foot. She leans slightly forward with her head tilted toward the camera and a calm relaxed expression. She wears an oversized loose olive-green short-sleeved T-shirt, light-blue denim jeans with rolled-up cuffs, dark canvas Converse-style sneakers with white soles, black round-framed glasses, and a small beige crossbody/waist bag.\n\nSet the scene outdoors among weathered stone and brick ruins, with an old stone archway framing the composition, dry plants and foliage in the foreground, and the wooden chair resting on earthy dirt ground. Fill the background with thick light-orange and peach-colored smoke creating a dreamy dramatic haze.\n\nUse soft moody natural lighting with warm pastel smoke tones, realistic shadows, cinematic depth of field, detailed skin and hair, authentic denim and fabric textures, atmospheric haze, photorealistic quality, ultra-detailed 8K, premium editorial photography, dreamy rustic aesthetic.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097676144141312095"></a>

### Dark cinematic portrait prompt in a psychological horror game aesthetic, depicting a woman with mysterious runes on her face, marked by dust and scratches.

Author：[@her19845](https://x.com/her19845) · [Source](https://x.com/her19845/status/2097676144141312095)

Cinematic / Film Still · Portrait / Selfie · Character · Published

**Summary:** Dark cinematic portrait prompt in a psychological horror game aesthetic, depicting a woman with mysterious runes on her face, marked by dust and scratches.

<img src="images/2097676144141312095-1.jpg" alt="Image 1" width="480" />

<img src="images/2097676144141312095-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
**Style:** Dark and dramatic cinematic photography with a high-end psychological horror video game aesthetic.\n\n**Subject:** The model included in the image extension. Her skin displays detailed textures of dirt, dust, and subtle scratches. Fine etched marks or mysterious vertical runes are visible on her cheek.\n\n**Lighting and Color:** A monochromatic and somber color palette dominated by dark emerald green, olive, and deep shadows. Side lighting sculpts the face, leaving half the scene in darkness.\n\n**Textures:** Pronounced analog film grain, detailed pores, a dusty, eerie, and claustrophobic atmosphere.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097222942438649948"></a>

### Prompt template for a hand-held travel card showcasing a miniature 3D destination landscape.

Author：[@Goodmanprotocol](https://x.com/Goodmanprotocol) · [Source](https://x.com/Goodmanprotocol/status/2097222942438649948)

Cinematic / Film Still · 3D Render · Landscape / Nature · Published

**Summary:** Prompt template for a hand-held travel card showcasing a miniature 3D destination landscape.

<img src="images/2097222942438649948-1.jpg" alt="Image 1" width="480" />

<img src="images/2097222942438649948-2.jpg" alt="Image 2" width="480" />

<img src="images/2097222942438649948-3.jpg" alt="Image 3" width="480" />

<img src="images/2097222942438649948-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
Create an ultra-realistic cinematic 4:5 vertical travel photograph of a sleek, minimalist travel card held naturally in one hand against an expansive sky.\n\nUse [COUNTRY NAME] as the creative focus. Transform the card into a living window into the destination, with a breathtaking miniature aerial world seamlessly emerging from its surface. Feature the country’s most iconic landmark, surrounded by authentic landscapes, architecture, atmosphere, and subtle details unique to the destination.\n\nMake the transition between the physical card and miniature world seamless, magical, and physically believable, as if the entire destination exists inside the card.\n\nIntegrate [COUNTRY NAME] in elegant, bold uppercase typography as part of the card design.\n\nUse cinematic natural light, realistic textures, atmospheric depth, subtle reflections, dramatic perspective, soft lens falloff, and premium editorial travel-photography aesthetics.\n\nUltra-photorealistic, 8K detail, cinematic color grading, realistic skin and materials, physically accurate lighting, luxurious, emotional, aspirational, universally beautiful. No cartoon, no illustration, no artificial CGI appearance.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2096808538534514913"></a>

### Cinematic portrait of a man in a beige sweater with warm golden rim lighting against a moody background.

Author：[@iamsofiaijaz](https://x.com/iamsofiaijaz) · [Source](https://x.com/iamsofiaijaz/status/2096808538534514913)

Cinematic / Film Still · Portrait / Selfie · Character · Abstract / Background · Published

**Summary:** Cinematic portrait of a man in a beige sweater with warm golden rim lighting against a moody background.

<img src="images/2096808538534514913-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Photorealistic cinematic portrait of a handsome adult man with tousled medium-length brown hair and a neatly trimmed beard, wearing a soft beige knitted crewneck sweater. He faces the camera with a calm, confident, slightly contemplative expression. Warm golden rim lighting creates a glowing halo around his hair and shoulders, with a strong soft key light illuminating his face. Dark, moody background with subtle amber haze and atmospheric smoke, dramatic high-contrast lighting, natural skin texture, sharp eyes, realistic facial details, shallow depth of field, professional studio photography, 85mm portrait lens, f/1.8, creamy bokeh, warm cinematic color grading, luxury editorial aesthetic, ultra-detailed, photorealistic, 8K.
```

[↑ Back to categories](#catalog)

---

<a name="category-anime-manga"></a>

## Anime / Manga

<a name="prompt-2097834253748949105"></a>

### A prompt to draw Chiikawa and Usagi in a JoJo-inspired dramatic gekiga style.

Author：[@namatorihamu](https://x.com/namatorihamu) · [Source](https://x.com/namatorihamu/status/2097834253748949105)

Anime / Manga · Illustration · Published

**Summary:** A prompt to draw Chiikawa and Usagi in a JoJo-inspired dramatic gekiga style.

<img src="images/2097834253748949105-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Try depicting Chiikawa and Usagi in a JoJo style
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099334317306761376"></a>

### Prompt instructs generation of a mixed-media portrait combining a realistic person and an exaggerated manga doodle shadow mirroring their pose.

Author：[@itxsarmadd](https://x.com/itxsarmadd) · [Source](https://x.com/itxsarmadd/status/2099334317306761376)

Anime / Manga · Portrait / Selfie · Character · Published

**Summary:** Prompt instructs generation of a mixed-media portrait combining a realistic person and an exaggerated manga doodle shadow mirroring their pose.

<img src="images/2099334317306761376-1.jpg" alt="Image 1" width="480" />

<img src="images/2099334317306761376-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Use the uploaded reference image as the strict identity and outfit reference. Preserve the face, facial features, skin tone, hairstyle, hair colour, accessories, outfit, and overall vibe exactly as shown. Create a high-quality vertical (4:5 or 9:16) mixed-media portrait featuring: A realistic full-body version of the person. A black hand-drawn doodle-shadow of the same person on the wall beside them. The real person should look cute, slightly embarrassed, playful, and naturally copying a new random mischievous pose each generation. The doodle-shadow should perform the same pose idea in a much more exaggerated, chaotic, cartoonish way, with manga motion lines, stars, hearts, and sparkles. Use a clean white/cream studio wall, minimal background, soft natural lighting, and keep both figures fully visible. The doodle should clearly resemble the real person through hairstyle, accessories, outfit silhouette, and pose. Negative Prompt: outfit changes, identity changes, realistic second person, normal shadow, horror, anime human, cluttered background, repeated pointing or finger-gun poses, stiff pose, extra limbs/fingers, distorted body, text, watermark, logo, AI artifacts.
```

[↑ Back to categories](#catalog)

---

<a name="category-illustration"></a>

## Illustration

<a name="prompt-2097713691433070629"></a>

### Asking ChatGPT to draw a self-portrait with a nameplate indicating its version number.

Author：[@Tz\_2022](https://x.com/Tz_2022) · [Source](https://x.com/Tz_2022/status/2097713691433070629)

Illustration · Portrait / Selfie · Published

**Summary:** Asking ChatGPT to draw a self-portrait with a nameplate indicating its version number.

<img src="images/2097713691433070629-1.jpg" alt="Image 1" width="480" />

<img src="images/2097713691433070629-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Draw a self-portrait of yourself, with a nameplate that has your version number on it
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097521286436065680"></a>

### Generate an illustrated exam paper formatted like an English CET-4 test, with question contents combining civil service exam questions.

Author：[@Tz\_2022](https://x.com/Tz_2022) · [Source](https://x.com/Tz_2022/status/2097521286436065680)

Illustration · Text / Typography · Published

Source：[@Lonely\_\_MH](https://x.com/Lonely__MH) · [Source](https://x.com/Lonely__MH/status/2097494755752202574)

**Summary:** Generate an illustrated exam paper formatted like an English CET-4 test, with question contents combining civil service exam questions.

<img src="images/2097521286436065680-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Create a CET-4 (College English Test Band 4) exam paper, but all the questions inside are civil service examination questions, richly illustrated with both pictures and text.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2101196922715250752"></a>

### Contemporary editorial illustration of a Japanese girl featuring simplified forms and negative space.

Author：[@miyajin333](https://x.com/miyajin333) · [Source](https://x.com/miyajin333/status/2101196922715250752)

Illustration · Character · Published

**Summary:** Contemporary editorial illustration of a Japanese girl featuring simplified forms and negative space.

<img src="images/2101196922715250752-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Subject: Japanese girl\nStyle: Contemporary editorial illustration, conceptual and simplified forms, expressive proportions, sophisticated limited color palette, bold negative space, subtle textures, slightly distorted geometric shapes, intellectual visual simplicity, modern magazine-style illustration, analog color scheme, 3:4 aspect ratio.
```

[↑ Back to categories](#catalog)

---

<a name="category-sketch-line-art"></a>

## Sketch / Line Art

<a name="prompt-2101315631237021853"></a>

### A prompt template for creating vintage minimalist architectural sketch posters featuring landmarks with geometric accents and typography.

Author：[@Naiknelofar788](https://x.com/Naiknelofar788) · [Source](https://x.com/Naiknelofar788/status/2101315631237021853)

Poster / Flyer · Sketch / Line Art · Retro / Vintage · Minimalism · Architecture / Interior · Text / Typography · Published

**Summary:** A prompt template for creating vintage minimalist architectural sketch posters featuring landmarks with geometric accents and typography.

<img src="images/2101315631237021853-1.jpg" alt="Image 1" width="480" />

<img src="images/2101315631237021853-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
A sophisticated minimalist architectural art poster featuring [LANDMARK / STRUCTURE] as the central subject, illustrated in a refined hand-drawn architectural sketch style. Preserve the landmark’s recognizable silhouette, proportions, and defining architectural details, while transforming it into an elegant artistic composition.\n\nUse a limited monochromatic color palette inspired by the location, with soft vintage tones on a warm ivory/off-white paper background. Combine delicate ink lines, fine architectural hatching, subtle halftone texture, and lightly distressed print details.\n\nSurround the structure with a few abstract geometric shapes, soft translucent circles, subtle atmospheric elements, birds, or tiny contextual details that complement the landmark without overpowering it. Add a subtle sense of depth through overlapping layers and faded linework.\n\nInclude small minimalist typography on one side: [CITY / COUNTRY], [LANDMARK NAME], and optional coordinates or a short location descriptor, arranged like a premium travel-art print.\n\nClean negative space, editorial graphic design, museum-quality travel poster aesthetic, elegant composition, understated luxury, vintage screen-print texture, artistic architectural illustration, no people, no photorealistic background, no unnecessary objects, 4:5 vertical composition.\n\n[LANDMARK] reimagined as a collectible minimalist travel-art poster, combining architectural sketching, vintage printmaking, geometric abstract shapes, delicate linework, halftone texture, muted location-inspired colors, and elegant negative space. The landmark remains instantly recognizable but feels like a hand-crafted piece of modern graphic art. Add tiny birds, subtle environmental elements, coordinates, and minimal location typography. Premium editorial aesthetic, artistic, sophisticated, highly shareable, 4:5 vertical.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097284686448046135"></a>

### Prompt for generating minimal hand-drawn architectural travel-journal sketches on ivory paper.

Author：[@Naiknelofar788](https://x.com/Naiknelofar788) · [Source](https://x.com/Naiknelofar788/status/2097284686448046135)

Sketch / Line Art · Architecture / Interior · Published

**Summary:** Prompt for generating minimal hand-drawn architectural travel-journal sketches on ivory paper.

<img src="images/2097284686448046135-1.jpg" alt="Image 1" width="480" />

<img src="images/2097284686448046135-2.jpg" alt="Image 2" width="480" />

<img src="images/2097284686448046135-3.jpg" alt="Image 3" width="480" />

<img src="images/2097284686448046135-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
Create a minimal hand-drawn architectural artwork of [STRUCTURE] on warm ivory paper. Show the structure as a simple, elegant ink sketch with clean imperfect lines, subtle pencil shading, tiny handwritten annotations, and a few delicate architectural details. Keep the composition airy with plenty of blank space, muted earthy tones, soft paper texture, and an authentic handmade travel-journal feel. No photorealism, no heavy details, no clutter — simple, artistic, and refined.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2096902953110299096"></a>

### Prompt transforms a reference photo into a 50/50 vertical poster, pairing original photo on top with colored-pencil watercolor sketch below.

Author：[@MissDelulu9](https://x.com/MissDelulu9) · [Source](https://x.com/MissDelulu9/status/2096902953110299096)

Poster / Flyer · Sketch / Line Art · Watercolor · Published

**Summary:** Prompt transforms a reference photo into a 50/50 vertical poster, pairing original photo on top with colored-pencil watercolor sketch below.

<img src="images/2096902953110299096-1.jpg" alt="Image 1" width="480" />

<img src="images/2096902953110299096-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Create a premium vertical travel-journal poster in an exact 50/50 split.

Top 50%: Keep the original reference photo completely real and unchanged same composition, architecture, people, colors, lighting, perspective, and details.

Bottom 50%: Transform the same photo into a delicate hand-drawn colored-pencil + watercolor sketch on warm cream paper, with visible pencil strokes, soft washes, subtle paper grain, imperfect outlines, and gentle cross-hatching. Keep every subject recognizable.

Add elegant handwritten text: “A Beautiful Day” above and “Memories to Keep” below. Minimal, nostalgic, sophisticated travel-magazine aesthetic. No extra objects, no photorealism in the bottom half, exact 50/50 layout.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097176979497791899"></a>

### Prompt transforms photos into an editorial art poster with mixed-media sketch styling and minimal layout.

Author：[@saniaspeaks\_](https://x.com/saniaspeaks_) · [Source](https://x.com/saniaspeaks_/status/2097176979497791899)

Poster / Flyer · Sketch / Line Art · Published

**Summary:** Prompt transforms photos into an editorial art poster with mixed-media sketch styling and minimal layout.

<img src="images/2097176979497791899-1.jpg" alt="Image 1" width="480" />

<img src="images/2097176979497791899-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Create a premium editorial art poster for every uploaded photograph, treating each image as its own independent composition and never merging multiple photos together. Use a strict 3:4 vertical format with the canvas split into two perfectly equal horizontal halves: the upper half should remain a faithful, photorealistic presentation of the original image, preserving the subject’s exact identity, facial features, proportions, pose, clothing, objects, composition, lighting, shadows, mood, and natural colors, enhanced only with sophisticated editorial color grading and seamless environmental extension where necessary; the lower half should transform the visual story into an entirely different artistic interpretation—a tiny, carefully composed handmade mixed-media artwork centered within expansive warm ivory negative space, occupying no more than 10–20% of the lower section, using expressive ink sketching, layered gouache-like color fields, subtle collage textures, torn-paper edges, imperfect brushwork, visible fibers, soft pigment variations, and charming human imperfections while retaining the most recognizable silhouette, gesture, objects, and emotional narrative from the original photo. Extract up to four dominant harmonious colors from each photograph and reinterpret them in a muted, sophisticated palette. Add only occasional understated editorial typography when it genuinely enhances the composition, such as a poetic title, place, date, or single word. The overall result should feel like a collectible contemporary art publication cover—minimal, poetic, tactile, elegant, emotionally quiet, visually distinctive, and unmistakably connected to its original photograph.
```

[↑ Back to categories](#catalog)

---

<a name="category-3d-render"></a>

## 3D Render

<a name="prompt-2100051568154538130"></a>

### A nanoscale East Asian woman navigating DRAM and 3D NAND memory cell skyscraper chip cities from a microscopic electron microscope perspective.

Author：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2100051568154538130)

Photography · 3D Render · Character · Cityscape / Street · Published

Source：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2099508984541769771)

**Summary:** A nanoscale East Asian woman navigating DRAM and 3D NAND memory cell skyscraper chip cities from a microscopic electron microscope perspective.

<img src="images/2100051568154538130-1.jpg" alt="Image 1" width="480" />

<img src="images/2100051568154538130-2.jpg" alt="Image 2" width="480" />

<img src="images/2100051568154538130-3.jpg" alt="Image 3" width="480" />

<img src="images/2100051568154538130-4.jpg" alt="Image 4" width="480" />

<img src="images/2100051568154538130-5.jpg" alt="Image 5" width="480" />

**Prompt**

```text
Realistic East Asian woman × nanoscale real person × weaving between gigantic memory cells × DRAM memory city × nano skyscrapers × dense transistor array × electron microscope perspective snapshot × microscopic black background\n\nImage 2\n\nRealistic East Asian woman × nanoscale real person × weaving between gigantic memory structures × cute and playful expression × holding onto a massive memory structure with both hands, peeking out and looking around × 3D NAND memory city × nano skyscrapers × infinitely stacked memory cells × electron microscope perspective snapshot × microscopic black background
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097646788258021837"></a>

### Handcrafted miniature 3D travel diorama prompt featuring iconic city landmarks on textured paper.

Author：[@Naiknelofar788](https://x.com/Naiknelofar788) · [Source](https://x.com/Naiknelofar788/status/2097646788258021837)

3D Render · Published

**Summary:** Handcrafted miniature 3D travel diorama prompt featuring iconic city landmarks on textured paper.

<img src="images/2097646788258021837-1.jpg" alt="Image 1" width="480" />

<img src="images/2097646788258021837-2.jpg" alt="Image 2" width="480" />

<img src="images/2097646788258021837-3.jpg" alt="Image 3" width="480" />

<img src="images/2097646788258021837-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
Create a charming handcrafted miniature travel scene featuring [ICONIC STRUCTURE] as the main focal point.\nShow the landmark as a beautifully sculpted tiny 3D model, with soft rounded details, handmade textures, delicate imperfections, and a whimsical storybook feeling. Surround it with a few subtle elements that represent its location—such as tiny trees, flowers, streets, boats, mountains, clouds, or local objects—without making the scene crowded.\n\nPlace everything on a clean warm-white textured paper background, with plenty of elegant negative space. Add a small tasteful wooden or paper travel plaque containing:\n\n[STRUCTURE NAME]\n[CITY, COUNTRY]\nFamous for: [SHORT UNIQUE FACT]\n\nUse soft natural lighting, gentle shadows, pastel yet realistic colors, miniature diorama depth, handcrafted clay/paper textures, and a premium cute travel-journal aesthetic. Centered composition, highly detailed landmark, adorable but sophisticated, clean and collectible travel-card design, no photorealistic people, no clutter.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097580884098764800"></a>

### Create a premium cute miniature 3D diorama of a landmark with souvenir plaque text.

Author：[@Naiknelofar788](https://x.com/Naiknelofar788) · [Source](https://x.com/Naiknelofar788/status/2097580884098764800)

3D Render · Architecture / Interior · Published

**Summary:** Create a premium cute miniature 3D diorama of a landmark with souvenir plaque text.

<img src="images/2097580884098764800-1.jpg" alt="Image 1" width="480" />

<img src="images/2097580884098764800-2.jpg" alt="Image 2" width="480" />

<img src="images/2097580884098764800-3.jpg" alt="Image 3" width="480" />

<img src="images/2097580884098764800-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
Create a premium cute miniature 3D diorama of [STRUCTURE NAME], [CITY, COUNTRY]. Keep the landmark recognizable, elegant, and charming, with clean composition, soft pastel tones, subtle handcrafted details, gentle natural lighting, and a refined travel-souvenir aesthetic.

Include minimal, tasteful text:
[STRUCTURE NAME]
[CITY, COUNTRY]
Famous for: [SHORT DESCRIPTION]
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097587863139537262"></a>

### Fictional 3D romance RPG beach first-person game screenshot, featuring Morrigan Aensland and a complete game HUD interactive UI.

Author：[@underwoodxie96](https://x.com/underwoodxie96) · [Source](https://x.com/underwoodxie96/status/2097587863139537262)

App / Web Design · 3D Render · Character · Published

Source：[@underwoodxie96](https://x.com/underwoodxie96) · [Source](https://x.com/underwoodxie96/status/2097554154554314891)

**Summary:** Fictional 3D romance RPG beach first-person game screenshot, featuring Morrigan Aensland and a complete game HUD interactive UI.

<img src="covers/2097587863139537262.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Please capture a realistic screenshot from a fictional next-generation 3D open-world romance RPG, presented from the male protagonist’s first-person perspective. On the beach, Morrigan Aensland from Darkstalkers invites the protagonist to help her apply sunscreen. The overall visual style must feature high-quality cartoon-rendered 3D characters combined with Unreal Engine 5-level graphics, achieving AAA-quality visual fidelity. It should include ultra-detailed character modeling, realistic skin shading, cinematic lighting, PBR materials, high-precision clothing textures, and finely rendered classroom environments. The final image must look like an actual playable game screenshot, including a complete game user interface: minimap, quest display, character status bars, interaction prompts, dialogue subtitles, HUD elements, and more.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097704623952035841"></a>

### Prompt template for generating 3D miniature collectible souvenir maps of countries highlighting specific cities and landmarks.

Author：[@Naiknelofar788](https://x.com/Naiknelofar788) · [Source](https://x.com/Naiknelofar788/status/2097704623952035841)

3D Render · Published

**Summary:** Prompt template for generating 3D miniature collectible souvenir maps of countries highlighting specific cities and landmarks.

<img src="images/2097704623952035841-1.jpg" alt="Image 1" width="480" />

<img src="images/2097704623952035841-2.jpg" alt="Image 2" width="480" />

<img src="images/2097704623952035841-3.jpg" alt="Image 3" width="480" />

**Prompt**

```text
Create a charming 3D miniature map of [COUNTRY] with the national borders clearly outlined and accurately shaped. Place a large elegant location pin exactly on [CITY], with [ICONIC LANDMARK] rising from the map at the pin location. Add tiny roads, mountains, rivers, buildings, trees, and subtle cultural details within the country. Make the map slightly raised and sculptural, with layered terrain, soft shadows, rounded edges, and handcrafted miniature textures. Use a refined palette inspired by [COUNTRY], warm ivory background, soft studio lighting, clean premium composition. Add elegant text: “[CITY]” and beneath it “[COUNTRY] • [FAMOUS FOR]”. Cute, sophisticated, highly recognizable, collectible 3D travel souvenir aesthetic.
```

[↑ Back to categories](#catalog)

---

<a name="category-pixel-art"></a>

## Pixel Art

<a name="prompt-2100265645103612367"></a>

### A prompt to generate the broad bean monster \\&quot;Soramameman\\&quot; as a 4x4, 16-frame 2D pixel art action sprite sheet.

Author：[@nostalGGames](https://x.com/nostalGGames) · [Source](https://x.com/nostalGGames/status/2100265645103612367)

Pixel Art · Published

**Summary:** A prompt to generate the broad bean monster \\&quot;Soramameman\\&quot; as a 4x4, 16-frame 2D pixel art action sprite sheet.

<img src="images/2100265645103612367-1.png" alt="Image 1" width="480" />

<img src="images/2100265645103612367-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
- A monster materialized from the spirit of a broad bean\n- Has two eyes\n- Soramameman turned into 2D pixel art\n- Made into an action character atlas\n- Output sprites as 16 action frames in a 4x4 grid
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097863751471157498"></a>

### Generate a 16-frame continuous action 2D pixel sprite sheet arranged in a square 4×4 grid based on the reference image, maintaining consistent character proportions and baseline, with instructions for a seamless looping action including idle, charging, release, and recovery.

Author：[@derek\_wall90176](https://x.com/derek_wall90176) · [Source](https://x.com/derek_wall90176/status/2097863751471157498)

Game Asset · Pixel Art · Character · Published

**Summary:** Generate a 16-frame continuous action 2D pixel sprite sheet arranged in a square 4×4 grid based on the reference image, maintaining consistent character proportions and baseline, with instructions for a seamless looping action including idle, charging, release, and recovery.

<img src="covers/2097863751471157498.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Upload Image 1 as the sole reference for character identity and costume. Convert the character in Image 1 into a high-quality 2D pixel game character, generating a square, 4×4 evenly divided, 16-frame continuous action Sprite Sheet. Each cell is identical in size. The frames play in sequence from left to right, top to bottom. Strictly preserve the character's face shape, hairstyle, body type, costume color scheme, signature accessories, and weapon structure. All 16 frames must use the same pixel scale, character size, facing direction, and color palette. The character completes a single [sword swing attack / jump / roll / spell casting / pounce] action. Frames 1 to 3 are idle and charging; Frames 4 to 7 are center of gravity shift and action unfolding; Frames 8 to 10 execute the main attack and power release; Frames 11 to 13 display inertia and follow-through; Frames 14 to 16 return to the idle state. Frame 16 seamlessly connects back to Frame 1. Adjacent frames only change the joints, silhouette, hemline, hair, and weapon position necessary to complete the action. Action direction, force dynamics, and motion trajectory remain continuous. All cells maintain the same camera angle, character scaling, ground baseline, and frame center. The character is completely displayed, with no cropping of the head, weapon, tail, or special effects. Background preferentially uses a transparent channel. When a transparent background is unstable, switch to a uniform solid color background for easy subsequent cutout. Do not generate scenes, ground textures, grid lines, numbering, or text. Adopt clear hard-edged pixels, a limited color palette, and uniform pixel density. Blurred edges, anti-aliasing, semi-realistic rendering, duplicate frames, skipped frames, character deformation, costume variations, weapon additions or removals, perspective shifts, and recomposition per cell are forbidden.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097574111518375970"></a>

### A prompt to generate a pixel art sprite sheet depicting four actions \(running, jumping, spinning attack, and falling down\) with four frames each, based on the attached character.

Author：[@npaka123](https://x.com/npaka123) · [Source](https://x.com/npaka123/status/2097574111518375970)

Pixel Art · Character · Published

**Summary:** A prompt to generate a pixel art sprite sheet depicting four actions \(running, jumping, spinning attack, and falling down\) with four frames each, based on the attached character.

<img src="covers/2097574111518375970.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Keep the attached character's face, hairstyle, outfit, color scheme, and physique consistent, and generate four types of game-ready pixel art motions on a single sprite sheet image, each with up to 4 frames. The size of each frame is 256x256px.
・Running: Lean the body forward and move arms and legs alternately in large motions.
・Jumping: Crouch → Leap up → Spread arms and legs in mid-air → Land.
・Spin Attack: Front → Side → Back → Opposite side, rotating the entire body full circle.
・Falling Down: Stumble → Tilt sideways → Lie down → Close eyes and become motionless.
Arrange one action per row horizontally, aligning the size, ground level, center, and scale across all cells. The background must be a completely solid flat color, with no shadows, text, borders, numbers, UI, blur, semi-transparency, gradients, or anti-aliasing. Ensure looping actions seamlessly connect from the end back to the start.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097573967955730524"></a>

### Instructions to generate a sprite sheet arranging 4 types of in-game pixel art actions \(running, jumping, spin attack, and falling\) with 4 frames each, based on the reference image.

Author：[@npaka123](https://x.com/npaka123) · [Source](https://x.com/npaka123/status/2097573967955730524)

Pixel Art · Character · Published

**Summary:** Instructions to generate a sprite sheet arranging 4 types of in-game pixel art actions \(running, jumping, spin attack, and falling\) with 4 frames each, based on the reference image.

<img src="covers/2097573967955730524.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Maintain consistency with the attached character's face, hairstyle, outfit, color palette, and physique, and generate a single sprite sheet image featuring 4 types of pixel art motions that look great in a game, with up to 4 frames each. Each frame size is 256x256px.\n- Run: Lean the body forward, moving limbs alternately with wide motions.\n- Jump: Crouch → Leap up → Spread limbs in mid-air → Land.\n- Spin Attack: Front → Side-facing → Back-facing → Opposite side-facing, completing a full-body 360-degree rotation.\n- Fall: Stumble → Tilt sideways → Lie down → Close eyes and become motionless.\nArrange one action per row horizontally in a single line, keeping the cell dimensions, ground level, center alignment, and scale uniform across all cells. The background must be a completely solid single color, with no shadows, text, borders, numbers, UI, blur, semi-transparency, gradients, or anti-aliasing. Ensure looping animations transition seamlessly between the first and last frames.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097559943075533257"></a>

### Instruction to generate a 16-frame sprite sheet animation loop of a pixel art male goblin drawing a bow and shooting an arrow.

Author：[@Fomsky\_Wei](https://x.com/Fomsky_Wei) · [Source](https://x.com/Fomsky_Wei/status/2097559943075533257)

Pixel Art · Published

**Summary:** Instruction to generate a 16-frame sprite sheet animation loop of a pixel art male goblin drawing a bow and shooting an arrow.

<img src="covers/2097559943075533257.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Do not use skills, create a sprite sheet.
This sheet contains the process of a pixel art male goblin drawing a bow and arrow and shooting.
A total of 16 frames.
Then slice this image and make it into a perpetual looping gif
```

[↑ Back to categories](#catalog)

---

<a name="category-watercolor"></a>

## Watercolor

<a name="prompt-2097637962137895058"></a>

### Prompt for transforming a photo into a retro colored pencil and watercolor hand-drawn travel journal illustration style

Author：[@tataemugc](https://x.com/tataemugc) · [Source](https://x.com/tataemugc/status/2097637962137895058)

Illustration · Watercolor · Retro / Vintage · Published

Source：[@Crypto\_QianXun](https://x.com/Crypto_QianXun) · [Source](https://x.com/Crypto_QianXun/status/2097174853707284785)

**Summary:** Prompt for transforming a photo into a retro colored pencil and watercolor hand-drawn travel journal illustration style

<img src="images/2097637962137895058-1.jpg" alt="Image 1" width="480" />

<img src="images/2097637962137895058-2.jpg" alt="Image 2" width="480" />

<img src="images/2097637962137895058-3.jpg" alt="Image 3" width="480" />

<img src="images/2097637962137895058-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
Transform the photo into a hand-drawn travel journal style using colored pencil and watercolor. Keep the original composition, buildings, people, trees, grass, road, and perspective intact. Use warm beige aged paper to convey a hand-drawn feel showing pen strokes and watercolor bleeding. Simplify the buildings into expressive shapes, adding loose outlines, fine cross-hatching, and slightly imperfect edges. Maintain the clear summer day atmosphere, soft blue sky, warm beige buildings, green grass, and scattered leisurely figures and benches. Use faded vintage travel sketch tones. Place the illustration in the lower half of the page, leaving a wide beige margin at the top. Write '맑은 날씨' in handwriting at the top, and '— 소중한 순간 —' at the bottom. Render in a nostalgic art travel magazine style, evoking personal sketchbook memories, with no photographic feel.
```

[↑ Back to categories](#catalog)

---

<a name="category-ink-chinese-style"></a>

## Ink / Chinese Style

<a name="prompt-2100241141967081911"></a>

### An extreme close-up photography prompt for Chinese-style nail art centered on Song Dynasty aesthetics, emphasizing locking the focus on the exquisite nail art visuals.

Author：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2100241141967081911)

Photography · Ink / Chinese Style · Published

Source：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2100101510634037441)

**Summary:** An extreme close-up photography prompt for Chinese-style nail art centered on Song Dynasty aesthetics, emphasizing locking the focus on the exquisite nail art visuals.

<img src="images/2100241141967081911-1.jpg" alt="Image 1" width="480" />

<img src="images/2100241141967081911-2.jpg" alt="Image 2" width="480" />

<img src="images/2100241141967081911-3.jpg" alt="Image 3" width="480" />

<img src="images/2100241141967081911-4.jpg" alt="Image 4" width="480" />

<img src="images/2100241141967081911-5.jpg" alt="Image 5" width="480" />

**Prompt**

```text
Song Dynasty aesthetics × Song-style nail art extreme close-up × Nail art as primary visual focus-locked
```

[↑ Back to categories](#catalog)

---

<a name="category-retro-vintage"></a>

## Retro / Vintage

<a name="prompt-2100099718605135962"></a>

### Vintage Japanese streetwear travel poster prompt featuring a tactical fashion model against an urban collage with aged paper typography.

Author：[@harboriis](https://x.com/harboriis) · [Source](https://x.com/harboriis/status/2100099718605135962)

Poster / Flyer · Retro / Vintage · Influencer / Model · Fashion Item · Cityscape / Street · Text / Typography · Published

**Summary:** Vintage Japanese streetwear travel poster prompt featuring a tactical fashion model against an urban collage with aged paper typography.

<img src="images/2100099718605135962-1.jpg" alt="Image 1" width="480" />

<img src="images/2100099718605135962-2.jpg" alt="Image 2" width="480" />

<img src="images/2100099718605135962-3.jpg" alt="Image 3" width="480" />

<img src="images/2100099718605135962-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
Create a vertical 4:5 ultra-realistic editorial travel fashion poster inspired by a vintage Japanese street magazine cover.

A young woman stands prominently in the center foreground, photographed from a slightly low angle. She has dark hair tied into a messy high bun with loose strands framing her face, wearing narrow futuristic black wraparound sunglasses and looking slightly toward the camera with a confident, calm expression. She wears an oversized black technical utility jacket covered with realistic straps, buckles, zippers, pockets, printed patches, labels and subtle reflective details, paired with dark tactical-style clothing and a large black utility bag. Preserve realistic fabric texture and natural proportions.

The background is a Tokyo night street collage, featuring rain-soaked neon streets, Japanese shop signs, narrow urban alleys, Tokyo Tower glowing at night, and a Tokyo train arriving at a station. Arrange several rectangular photographs around the central subject at different slight angles, creating a handmade editorial scrapbook layout. Use off-white aged paper as the main background with subtle paper grain, worn edges, folds, stains and vintage print texture.

At the top, add huge bold black typography reading:

TOKYO

Under it, smaller elegant italic serif text:

FUTURE IS NOW

Add small editorial text blocks such as:

“Where tradition meets technology, and every street tells a story of tomorrow.”

Include minimalist globe symbols, technical graphic lines, barcode elements, coordinates, small labels and futuristic editorial markings.

Use Japanese-inspired red and black graphic panels throughout the composition. Add a vertical red panel on the right with Japanese typography, a red graphic card on the lower left containing large Japanese characters, and another red photographic panel in the lower right showing a dark silhouette of the woman.

Include small typography such as:

35.6895° N
139.6917° E

and:

SHIBUYA • SHINJUKU • HARAJUKU • AKIHABARA

Overall aesthetic: high-end Japanese streetwear magazine, cyberpunk Tokyo, vintage travel poster, contemporary fashion editorial, analog print collage. Muted black, charcoal, cream, dark gray and deep red color palette. Strong photographic realism, cinematic night lighting, subtle film grain, slightly faded ink, authentic paper texture, imperfect print registration, sophisticated magazine typography, balanced negative space.

Composition: central full-body subject, oversized “TOKYO” headline occupying the upper section, layered Tokyo photographs surrounding her, red graphic accents, vintage paper border, premium editorial layout.

Photorealistic, highly detailed, cinematic, 8K, realistic skin, realistic clothing textures, professional fashion photography, authentic vintage print finish, no modern digital UI elements.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100123233630519438"></a>

### A style transformation prompt that extracts image features and reconstructs them into a lighthearted, retro hand-drawn editorial illustration inspired by modernism, Bauhaus, and picture books.

Author：[@bantya\_otime](https://x.com/bantya_otime) · [Source](https://x.com/bantya_otime/status/2100123233630519438)

Illustration · Retro / Vintage · Published

Source：[@huku\_ken\_ai](https://x.com/huku_ken_ai) · [Source](https://x.com/huku_ken_ai/status/2100054565727113316)

**Summary:** A style transformation prompt that extracts image features and reconstructs them into a lighthearted, retro hand-drawn editorial illustration inspired by modernism, Bauhaus, and picture books.

<img src="images/2100123233630519438-1.jpg" alt="Image 1" width="480" />

<img src="images/2100123233630519438-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Extract the most distinctive subjects, contours, poses, and narrative relationships from the image, and reconstruct them into a lighthearted, naive, retro hand-drawn editorial illustration. Avoiding mechanical replication of details, the illustration is reinterpreted through generalized shapes, moderately exaggerated proportions, iconic features, and humorous visual metaphors, while maintaining the original's characteristic expression. These illustrations blend modernist editorial illustration, Bauhaus graphic design, children's picture books, naive art, and trendy sketching techniques. The forms are concise, the outlines give a slightly ambiguous impression reflecting the unique imperfections of hand-drawing, and specific elements are appropriately enlarged to create a narrative, stylish, and playful image.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098314775344394279"></a>

### Traditional Chinese style CCD direct flash Eight Beauties of Qinhuai group photo prompt

Author：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2098314775344394279)

Photography · Retro / Vintage · Portrait / Selfie · Character · Group / Couple · Published

Source：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2097135361046839783)

**Summary:** Traditional Chinese style CCD direct flash Eight Beauties of Qinhuai group photo prompt

<img src="images/2098314775344394279-1.jpg" alt="Image 1" width="480" />

<img src="images/2098314775344394279-2.jpg" alt="Image 2" width="480" />

<img src="images/2098314775344394279-3.jpg" alt="Image 3" width="480" />

<img src="images/2098314775344394279-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
Rouged fragrance and splendid beauty; misty moonlight over the Qinhuai River; glances brimming with springtime charm; each with distinct grace and demeanor; CCD direct flash; group photo of the Eight Beauties of Qinhuai: Liu Rushi, Chen Yuanyuan, Li Xiangjun, Dong Xiaowan, Gu Hengbo, Bian Yujing, Kou Baimen, and Ma Xianglan
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097954772586557873"></a>

### 1980s retro portrait prompt using reference identity with 35mm analog film aesthetic, vintage fashion, and neon ambient glow.

Author：[@Goodmanprotocol](https://x.com/Goodmanprotocol) · [Source](https://x.com/Goodmanprotocol/status/2097954772586557873)

Photography · Retro / Vintage · Portrait / Selfie · Fashion Item · Published

**Summary:** 1980s retro portrait prompt using reference identity with 35mm analog film aesthetic, vintage fashion, and neon ambient glow.

<img src="images/2097954772586557873-1.jpg" alt="Image 1" width="480" />

<img src="images/2097954772586557873-2.jpg" alt="Image 2" width="480" />

<img src="images/2097954772586557873-3.jpg" alt="Image 3" width="480" />

<img src="images/2097954772586557873-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
Create an authentic 1980s retro-vintage portrait in a 4:5 vertical aspect ratio, using the provided person as the exact facial reference. Preserve their identity, facial structure, recognizable features, skin tone, and natural expression with high accuracy—do not alter or beautify the face.\n\nGive the subject a classic 1980s hairstyle and stylish period-accurate fashion with bold silhouettes, authentic textures, and effortless vintage attitude. Compose the portrait naturally with a strong editorial feel, keeping the subject as the clear focal point.\n\nCapture the image as if shot on a 35mm analog film camera, with realistic film grain, subtle dust and texture, gentle softness, natural skin detail, slight color fading, and authentic analog imperfections. Use warm nostalgic color grading, soft neon highlights, subtle ambient glow, and direct on-camera flash to create the distinctive look of an iconic 1980s photograph.\n\nKeep the lighting cinematic yet believable, with soft shadows, realistic highlights, natural contrast, and a slightly imperfect film exposure. The final image should feel genuinely photographed in the 1980s—not digitally recreated, with a timeless, nostalgic, fashionable, and effortlessly cool atmosphere.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097628670143954978"></a>

### Create a two-panel travel diary poster: realistic street scene on top, vintage illustration style with the same composition on the bottom, with typography layout.

Author：[@Alina\_with\_Ai](https://x.com/Alina_with_Ai) · [Source](https://x.com/Alina_with_Ai/status/2097628670143954978)

Poster / Flyer · Photography · Illustration · Retro / Vintage · Cityscape / Street · Text / Typography · Published

**Summary:** Create a two-panel travel diary poster: realistic street scene on top, vintage illustration style with the same composition on the bottom, with typography layout.

<img src="images/2097628670143954978-1.jpg" alt="Image 1" width="480" />

<img src="images/2097628670143954978-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Create a realistic two-panel editorial travel diary poster using the first image as the exact composition/reference and the second uploaded image as the facial reference.

Replace the woman in the original poster with the woman from my reference photo. Preserve my facial identity and recognizable facial features accurately—face shape, eyes, eyebrows, nose, lips, skin tone, and natural proportions. Do not beautify, alter, or redesign my face.

TOP PANEL

Recreate the original street scene exactly:

European-style narrow cobblestone street

Historic cream-colored buildings

Café signs, windows, balconies, street lamps and bollards

Same camera angle, framing, perspective and composition

Same seated/leaning pose and body position

Same black textured sweater/coat

Natural long dark hair

Soft cinematic daylight

Photorealistic skin texture and realistic lighting

Integrate my face naturally with the original pose, head angle and lighting

BOTTOM PANEL

Create the matching hand-drawn/printed illustration version of the same scene.

Keep the same pose, clothing, hairstyle and facial identity

Convert the photograph into a textured vintage editorial illustration

Blue, cream and muted warm-orange ink palette

Visible paper grain and imperfect ink texture

Keep my facial features recognizable while matching the illustrated style

Preserve the street, buildings, plants, cars and perspective from the original

TYPOGRAPHY & LAYOUT

Keep the original poster layout and typography style:

Large handwritten title: “By the Street”

Small English diary text

Chinese text in the upper-left

Date: 2026.08.29

Small diary number/details

Right-side phrase: “GOOD THINGS ALWAYS HAPPEN IN QUIET MOMENTS.”

Most important: My face should be the only facial identity used. Do not copy the original woman's face. Keep the overall poster composition, pose, clothing, background and artistic style as close to the reference as possible. High-quality, natural, seamless face integration, photorealistic top panel and authentic printed illustration bottom panel.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097185580224491672"></a>

### 90s vintage streetwear editorial portrait of a man leaning against a classic American car with a weathered Oakland urban wall in the background.

Author：[@harboriis](https://x.com/harboriis) · [Source](https://x.com/harboriis/status/2097185580224491672)

Photography · Retro / Vintage · Portrait / Selfie · Character · Fashion Item · Vehicle · Cityscape / Street · Abstract / Background · Published

**Summary:** 90s vintage streetwear editorial portrait of a man leaning against a classic American car with a weathered Oakland urban wall in the background.

<img src="images/2097185580224491672-1.jpg" alt="Image 1" width="480" />

<img src="images/2097185580224491672-2.jpg" alt="Image 2" width="480" />

<img src="images/2097185580224491672-3.jpg" alt="Image 3" width="480" />

<img src="images/2097185580224491672-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
Create an ultra realistic vertical 9:16 editorial streetwear photograph of a young man with thick curly dark hair, wearing black sunglasses, a cream and black oversized polo shirt with bold “OAKLAND” collegiate lettering and smaller athletic text underneath, loose black cargo-style pants, white sneakers, and a classic metal wristwatch. He is casually leaning against the front of a vintage American car with his hands in his pockets and one leg crossed over the other. Set the scene on a gritty urban street with an old weathered building behind him. Add large faded wall typography reading “OAKLAND”, with “CALIFORNIA” and “EST. 1852” underneath. Warm late-afternoon sunlight, muted brown and beige color palette, subtle film grain, soft shadows, nostalgic 1990s street-fashion aesthetic, realistic skin texture, natural pose, cinematic depth of field, detailed vintage car, authentic editorial photography. Full body composition, low eye-level camera, 35mm lens, warm cinematic lighting, photorealistic, high detail, 4K.
```

[↑ Back to categories](#catalog)

---

<a name="category-cyberpunk-sci-fi"></a>

## Cyberpunk / Sci-Fi

<a name="prompt-2097880604872438019"></a>

### A grand, realistic sci-fi landscape featuring ochre-red hills, a tiny solitary rear silhouette, and a colossal fractured stone planetary ring in the distance.

Author：[@listudio](https://x.com/listudio) · [Source](https://x.com/listudio/status/2097880604872438019)

Photography · Illustration · Cyberpunk / Sci-Fi · Landscape / Nature · Published

**Summary:** A grand, realistic sci-fi landscape featuring ochre-red hills, a tiny solitary rear silhouette, and a colossal fractured stone planetary ring in the distance.

<img src="images/2097880604872438019-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Generate a 2:3 vertical grand sci-fi landscape image featuring photorealistic natural textures, fine film grain, and restrained vintage cinematic color grading. In the foreground are softly rolling ochre-red dried-grass hills, with a solitary adult standing near the bottom center slightly to the left, back facing the camera, wearing a dark long coat; the figure's height occupies only 2.5% of the frame, quietly gazing into the distance. Across the vast middle-ground plain, countless tiny, low-rise off-white settlements are scattered, with a silver-cyan river winding in a gentle S-curve through the towns and reddish-brown earth. Towering behind the horizon is a planetary-scale, slightly tilted ancient fractured stone mega-ring: the ring body is extremely massive, its colossal left arc entity dominating the upper-left of the frame, with its top and left edges cropped by the frame; the curved fractured segment on the right extends into the sky, with an irregular fracture misaligned with the main ring; the center encloses an arcing sky void expanding toward the upper-right, not two straight parallel walls. The surface features rough stratification resembling deep cyan-black basalt, macro fractures, and slowly weathered longitudinal furrows, definitely not a smooth metallic ring. Warm golden low-angle sunlight skims from the right side of the frame across the curved inner rim and the fracture, while the vast bulk of the structure sinks into layered dark-green shadows, its base obscured by massive yet serene milky-white-golden cumulus clouds and dust mist, resembling clouds accumulating at the foot of the behemoth rather than an explosion. The right sky is deep grey-cyan-blue, the dried grass is coppery red and dark ochre, and the river reflects only restrained natural light. Use the tiny rear view, miniature towns, cloud layer at the foot of the titan, and the ring extending off-frame to emphasize the insignificance of humanity. Quiet, distant, heavy, incomprehensible grandeur, crisp depth layers, realistic natural light, no text, no logos, no watermarks, no lasers or lens flares.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098901467956461671"></a>

### A cyberpunk-style portrait prompt of a woman in a black outfit on all fours on the floor in a gaming room glowing with pink and blue neon lights.

Author：[@CyberTotal2026](https://x.com/CyberTotal2026) · [Source](https://x.com/CyberTotal2026/status/2098901467956461671)

Photography · Cyberpunk / Sci-Fi · Portrait / Selfie · Character · Published

**Summary:** A cyberpunk-style portrait prompt of a woman in a black outfit on all fours on the floor in a gaming room glowing with pink and blue neon lights.

<img src="images/2098901467956461671-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Theme:
Black outfit under blue and pink neon

Subject:
A vertical photograph of an adult woman in a black outfit on all fours on the floor in a gaming room illuminated by pink and blue neon lights. The person is positioned centered in the frame.

Person / Expression:
Dark brown hair styled in braided pigtails on both sides, thin bangs, round glasses. Slender oval face contour, horizontally long brown eyes, thin eyebrows, small nose, pink lips. Her face is raised, looking seriously into the camera.

Attire / Pose:
A black corset-style strap top, black short shorts, a thin harness around the neck, black long gloves reaching above the elbows. With both hands and both knees on the floor, she arches her back and raises her face.

Background / Lighting:
Illuminated gaming equipment, monitors, pink and blue LED strips, neon text reading "GAME OVER" in the upper right. The colored light casts rims of both colors onto the black outfit and skin. The key light in the background of the frame is soft light coming from the neon light sources on the left and right.

Composition / Camera:
3:4 vertical composition, camera positioned near the floor, front-diagonal full-body close perspective. Hands placed in the lower foreground, face in the center, lettering in the upper right. Focus on the face, glasses, and black harness, background features neon bokeh. The person is framed prominently, with the subject in focus and a light blur in the background.

Texture / Style:
Photorealistic cyberpunk indoor photography. Highly contrasted and finely detailed depiction of black leather-like fabric, long gloves, glasses, pink and blue neon, and reflections on the skin.

Negative:
Do not omit the hands-and-knees posture and round glasses; do not make it a bright daytime room
```

[↑ Back to categories](#catalog)

---

<a name="category-minimalism"></a>

## Minimalism

<a name="prompt-2097628383362597075"></a>

### Generate an off-white, minimalist magazine-style palmistry reading guide infographic.

Author：[@hahazwei](https://x.com/hahazwei) · [Source](https://x.com/hahazwei/status/2097628383362597075)

Infographic / Edu Visual · Minimalism · Published

**Summary:** Generate an off-white, minimalist magazine-style palmistry reading guide infographic.

<img src="images/2097628383362597075-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Use this image to generate a complete palmistry reading guide infographic. Pay attention to the lines on the palm, label key palm lines, conduct a detailed palmistry analysis, and present the interpretation against an off-white background, overall adopting a clean, minimalist, and luxurious magazine editorial style. Use slender fine lines, rounded cards, and deliberate negative space to create an expensive, sophisticated aesthetic. Keep the primary focus on the palmistry reading itself.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097622528340668736"></a>

### Realistic high-angle portrait of a young East Asian woman in a pink bikini in front of a minimalist gray background.

Author：[@catgirlcozy](https://x.com/catgirlcozy) · [Source](https://x.com/catgirlcozy/status/2097622528340668736)

Minimalism · Portrait / Selfie · Character · Abstract / Background · Published

**Summary:** Realistic high-angle portrait of a young East Asian woman in a pink bikini in front of a minimalist gray background.

<img src="images/2097622528340668736-1.jpg" alt="Image 1" width="480" />

<img src="images/2097622528340668736-2.jpg" alt="Image 2" width="480" />

<img src="images/2097622528340668736-3.jpg" alt="Image 3" width="480" />

**Prompt**

```text
Top-down 35-degree high-angle shot, a young realistic East Asian woman with reddish-brown hair facing the camera, with both hands behind her head, elbows spread wide, showing a bright, genuine, toothy smile, hands clasped behind her head. She is wearing a pink string bikini and a delicate gold necklace, standing barefoot in front of a minimalist gray concrete background. Soft indoor natural light, realistic-textured lifestyle portrait snapshot style
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097204639863287913"></a>

### Oriental Zen New Chinese-Style Woman Lattice Window Poster Wallpaper Prompt, featuring a color palette of jade cyan, rose red, and warm white.

Author：[@liyue\_ai](https://x.com/liyue_ai) · [Source](https://x.com/liyue_ai/status/2097204639863287913)

Poster / Flyer · Minimalism · Character · Abstract / Background · Published

Source：[@liyue\_ai](https://x.com/liyue_ai) · [Source](https://x.com/liyue_ai/status/2096838519918596234)

**Summary:** Oriental Zen New Chinese-Style Woman Lattice Window Poster Wallpaper Prompt, featuring a color palette of jade cyan, rose red, and warm white.

<img src="images/2097204639863287913-1.jpg" alt="Image 1" width="480" />

<img src="images/2097204639863287913-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Theme Direction: Oriental Zen minimalist cover poster
Style Branch: Feminine aesthetic New Chinese style
Subject Content: A classical-style woman standing in front of a lattice window, with a quiet and reserved posture
Emotional Motif: Elegant, gentle, sense of light luxury
Scene and Imagery: Jade-cyan lattice window, rose-red flower shadows, warm white wall, woman, minimal light gold details
Composition and Space: 9:16 vertical composition, lattice window in the upper-middle section, figure in the lower-middle section, with a clean title area preserved at the top
Color Control: Warm white as a bright base, jade-cyan used for the lattice window and minimal background structures, rose-red for flower shadows and localized accents, light gold only for a tiny amount of accessory highlights, character clothing in pearl white or pale pink-white; avoid the entire image being jade-cyan or rose-red
Light and Texture: Soft natural light, vivid and translucent colors, clean graphic poster feel
Aspect Ratio: 9:16
Supplementary Requirements: Overall, it must convey a high-aesthetic New Chinese cover feel, exquisite without being over-decorated
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2096807576168169628"></a>

### Generate a 3:4 split-screen editorial poster based on the uploaded photo: top half preserves original photo faithfully, bottom half transforms into a small minimalist hand-drawn illustration.

Author：[@Sairah\_0](https://x.com/Sairah_0) · [Source](https://x.com/Sairah_0/status/2096807576168169628)

Poster / Flyer · Illustration · Minimalism · Published

**Summary:** Generate a 3:4 split-screen editorial poster based on the uploaded photo: top half preserves original photo faithfully, bottom half transforms into a small minimalist hand-drawn illustration.

<img src="images/2096807576168169628-1.jpg" alt="Image 1" width="480" />

<img src="images/2096807576168169628-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Create ONE independent high-end editorial poster for EACH uploaded photo. Never combine photos. Each photo must become a separate poster.\n\nFORMAT\nStrict 3:4 vertical. Divide the canvas into two exactly equal 50% horizontal sections.\n\nTOP 50% — ORIGINAL PHOTO\nPreserve the photo faithfully: identity, face, body proportions, pose, clothing, objects, composition, lighting, shadows, atmosphere, and colors. Keep it photorealistic with subtle premium editorial color grading. Seamlessly extend the background if needed; never distort or alter the subject.\n\nBOTTOM 50% — MINIMAL ILLUSTRATION\nReinterpret the most recognizable elements as a small, centered, hand-drawn paper illustration occupying only 10–20% of the bottom half. Preserve the key subject, silhouette, pose, objects, and narrative.\n\nUse delicate imperfect lines, bold flat acrylic-style shapes, rough paper grain, handmade brush marks, and organic edges. Keep the background warm white/off-white with generous negative space.\n\nCOLOR\nExtract dominant colors from the original photo and reduce them to a maximum of 4 restrained, harmonious colors.\n\nTYPOGRAPHY\nOptional minimal editorial text such as a short title, location, year, or keyword. Do not force text if unnecessary.\n\nSTYLE\nQuiet, poetic, refined, minimal, innocent, artistic, thoughtful, premium, and highly recognizable — like a contemporary art book or independent editorial cover.
```

[↑ Back to categories](#catalog)

---

<a name="category-other"></a>

## Other

<a name="prompt-2101538802946715870"></a>

### Top-down motorsport editorial poster of a white GT race car against a split black/white graphic background with giant typography.

Author：[@harboriis](https://x.com/harboriis) · [Source](https://x.com/harboriis/status/2101538802946715870)

Poster / Flyer · Vehicle · Text / Typography · Abstract / Background · Published

**Summary:** Top-down motorsport editorial poster of a white GT race car against a split black/white graphic background with giant typography.

<img src="images/2101538802946715870-1.jpg" alt="Image 1" width="480" />

<img src="images/2101538802946715870-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Create a hyper-realistic premium motorsport editorial poster featuring a white GT race car photographed from a dramatic high-angle top-down perspective.

FORMAT:
Vertical 9:16 composition, ultra-high resolution, clean commercial automotive photography, sharp details, realistic reflections and materials.

MAIN SUBJECT:
A white professional GT racing car viewed almost perfectly from directly above, positioned vertically along the left and center of the frame.

The entire car should be visible from front to rear. The car is oriented vertically, with the front toward the top of the image and the rear toward the bottom.

The vehicle has an aggressive wide-body racing design with:

- White aerodynamic bodywork
- Black aerodynamic vents and openings
- Exposed racing wheels
- Large slick racing tires
- Detailed metallic multi-spoke wheels
- Red accent lines around the body
- Large rear aerodynamic wing
- Racing splitter and diffuser
- Complex aerodynamic panels
- Visible windshield and cockpit
- Realistic panel seams, screws, vents and carbon-fiber components

The car should look like a professional endurance or GT race car, with authentic motorsport proportions and extremely detailed aerodynamic bodywork.

CAR DETAILS:
The tires are black racing slicks with realistic white sidewall lettering.

The wheels should be highly detailed metallic dark gunmetal alloy wheels with visible brake components behind the spokes.

Add subtle red motorsport branding and graphics on the white bodywork. Include a large red circular abstract racing logo or graphic on the central side panel.

Use small realistic sponsor-style decals and technical markings throughout the car.

PERSPECTIVE:
Extreme top-down automotive photography.

The camera is positioned almost directly above the vehicle, creating a flat graphic composition while maintaining realistic three-dimensional depth.

The car occupies approximately 65 to 70 percent of the image width and extends almost the full height of the composition.

BACKGROUND:
Pure minimalist black and white graphic background.

The entire background is divided vertically:

- Left side: clean bright white background
- Right side: deep solid black background

Create a sharp vertical transition between the white and black areas.

Behind the car, place enormous bold white geometric typography extending vertically through the black background.

The typography should be extremely large, thick, modern and condensed, functioning primarily as a graphic design element rather than normal readable text.

The letters should be partially hidden behind the race car.

Use oversized white block letters with rounded corners and strong geometric construction. Some letters should extend beyond the edges of the composition.

The typography should create a dramatic black-and-white contrast around the vehicle.

LAYOUT:
The white race car sits directly over the boundary between the white and black background.

The left side of the car blends visually into the white area while the right side overlaps the giant white typography on the black background.

The oversized letters must remain behind the car and should never cover the vehicle.

Create strong negative space around the car while maintaining the bold graphic appearance.

LIGHTING:
Bright studio lighting from above, producing soft realistic shadows beneath the car.

Use clean high-key illumination on the white bodywork.

The black background should remain deep and pure without unnecessary gradients.

Add subtle realistic reflections across the glossy white paint, windshield, metallic wheels and carbon-fiber components.

The vehicle should have a premium studio-rendered appearance while remaining photorealistic.

MATERIALS:
Extremely realistic glossy white automotive paint.
Realistic carbon fiber texture.
Brushed and polished metal wheels.
Transparent windshield glass.
Rubber racing tires with detailed texture.
Small red painted accents.
Sharp aerodynamic edges.

GRAPHIC STYLE:
Minimalist luxury motorsport advertising campaign.

Combine:

- Premium automotive photography
- Brutalist graphic design
- Motorsport editorial design
- High-contrast black and white composition
- Oversized geometric typography
- Clean modern advertising aesthetic

COLOR PALETTE:
Pure white
Deep black
Dark charcoal
Metallic gunmetal
Small amounts of vivid racing red

No unnecessary colors.

FINAL IMAGE:
Photorealistic professional automotive campaign poster, extremely detailed race car, realistic proportions, dramatic overhead perspective, crisp edges, high contrast, clean studio lighting, premium motorsport advertising, minimalist composition, bold oversized typography, sophisticated editorial art direction, ultra-detailed 8K quality.

IMPORTANT:
Keep the exact overall composition of the reference: vertically oriented white race car positioned across the white and black background boundary, giant white geometric letters behind the car on the black side, minimal color palette, strong top-down perspective, red racing accents, and a clean premium motorsport poster aesthetic.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100545582972751933"></a>

### A collection of direct CCD flash POV realistic photo prompts featuring Genshin Impact characters Ningguang and Ganyu in service settings such as foot massage, KTV, and billiard rooms.

Author：[@0xkyne](https://x.com/0xkyne) · [Source](https://x.com/0xkyne/status/2100545582972751933)

Character · Published

**Summary:** A collection of direct CCD flash POV realistic photo prompts featuring Genshin Impact characters Ningguang and Ganyu in service settings such as foot massage, KTV, and billiard rooms.

<img src="images/2100545582972751933-1.jpg" alt="Image 1" width="480" />

<img src="images/2100545582972751933-2.jpg" alt="Image 2" width="480" />

<img src="images/2100545582972751933-3.jpg" alt="Image 3" width="480" />

<img src="images/2100545582972751933-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
👠 Ningguang cosplayer, foot massage technician, private room, cheongsam, in service, direct CCD flash, client POV perspective\n\n🎤 Ningguang cosplayer + Ganyu cosplayer, commercial KTV companions, KTV private room, character-colored minimalist dresses, joyfully interacting with guests, direct CCD flash + smartphone shot\n\n🎱 Young maiden Ningguang cosplayer, pool assistant instructor, billiard hall, puffy mini skirt + white silk stockings, playing billiards, direct CCD flash + client POV perspective
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100498666763030990"></a>

### Create a 3:4 comparison poster based on the uploaded photo, with the upper part featuring the snapshot texture of the original image, and the lower part simulating an 85mm F1.2 full-frame large-aperture creamy bokeh effect.

Author：[@lovimg\_com](https://x.com/lovimg_com) · [Source](https://x.com/lovimg_com/status/2100498666763030990)

Poster / Flyer · Portrait / Selfie · Published

**Summary:** Create a 3:4 comparison poster based on the uploaded photo, with the upper part featuring the snapshot texture of the original image, and the lower part simulating an 85mm F1.2 full-frame large-aperture creamy bokeh effect.

<img src="images/2100498666763030990-1.jpg" alt="Image 1" width="480" />

<img src="images/2100498666763030990-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Please create a standalone 3:4 vertical "Bokeh Isolation Twin" visual poster based on my uploaded photo.

The frame is strictly divided into upper and lower regions, with a 1:1 height ratio, each occupying 50%.

The top and bottom must maintain:

The exact same subject, the same face, the same action, the same posture, the same gaze direction, the same subject position, the same scene, the same shooting angle, and the same compositional relationship.

Do not redesign the person.

Do not change the background.

Do not alter the photo's content.

Upper Half | REAL

Completely preserve the original uploaded photo.

Maintain the original mobile phone photography, digital camera, or candid snapshot texture.

Fully retain the person, background, and environmental details.

Slight exposure and color adjustments are allowed, but do not change the depth of field relationships.

Allow the viewer to clearly see the original, authentic state of the photo.

Lower Half | 85MM F/1.2

Strictly simulate a professional full-frame large-aperture portrait photograph based on the exact same frame as the upper half.

Simulate:

An 85mm full-frame prime lens, f/1.2 aperture.

The subject's eyes, face, and primary contours remain high-definition and sharp.

Recalculate depth of field based on real spatial distance.

The focal plane where the subject is located remains sharp.

The environment in front of and behind the subject enters a defocused state progressively according to distance.

The near background retains a small amount of structural definition.

The mid-distance background begins to soften.

The distant background is completely transformed into a natural, creamy bokeh.

In the background:

Streetlights, car lights, display windows, leaf reflections, metal glints, and sunlight highlights

Naturally transform into realistic optical bokeh of varying sizes and degrees of blur.

The out-of-focus areas must exhibit authentic lens characteristics:

Soft circular light spots, slight cat-eye deformation at the edges, highlight gradients, foreground/background depth-of-field layering, and realistic spatial compression.

The subject's hair, shoulders, and clothing edges must not have an artificial cutout look.

A natural transition between hair strands and the bokeh is required.

Preserve subtle lens breathing, chromatic aberration, grain, exposure imperfections, and authentic photographic flaws.

The final result must look like:

The same photographer did not move positions, but simply switched from an ordinary smartphone to an 85mm F1.2 professional lens and shot it again.

Prohibited:

Gaussian blurring the entire background.

Prohibited: The background turning into a flat blob of color without spatial depth.

Prohibited: Cutting out the person and pasting them onto a blurred background.

Prohibited: Face swapping.

Prohibited: Changing the subject's pose or action.

Prohibited: Adding nonexistent buildings or scenery.

Prohibited: Illustrative or painterly look.

Prohibited: Excessive skin smoothing.

Prohibited: Plastic skin.

Prohibited: AI studio-shot look.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100405863123173606"></a>

### Creative video prompt starting with a Mac desktop: A black-clad female warrior in the wallpaper fumbles a thrown dagger, shattering the screen glass, and in a panic opens the Control Center to dim the screen and conceal the cracks.

Author：[@TanLuAI](https://x.com/TanLuAI) · [Source](https://x.com/TanLuAI/status/2100405863123173606)

Abstract / Background · Published

**Summary:** Creative video prompt starting with a Mac desktop: A black-clad female warrior in the wallpaper fumbles a thrown dagger, shattering the screen glass, and in a panic opens the Control Center to dim the screen and conceal the cracks.

<img src="covers/2100405863123173606.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Using the provided Apple desktop image as the first frame, 16:9, 15 seconds, fixed camera, continuous one-shot. Maintain consistency in the woman's facial features, black martial artist outfit, hairstyle, and blue misty background; preserve desktop icons, menu bar, and the Dock.
0–4 seconds: The woman in the desktop wallpaper suddenly comes to life with a calm expression, tossing and catching the same short dagger twice consecutively into the air; the blade spins in mid-air with natural movement, and strands of her hair gently drift.
4–6 seconds: On the third toss, she fumbles, and the short dagger slips from her hand; the blade tip flies toward the audience and strikes the screen glass. Accompanied by a crisp sound of shattering glass, web-like cracks instantly radiate from the impact point, overlaying in front of the character and desktop UI, accompanied by a brief screen shake.
6–9 seconds: The woman freezes at first, then widens her eyes and furrows her brows, showing an overtly flustered and panicked expression of someone who just caused trouble. She looks at the cracks, then looks at the audience, hurriedly trying to cover the cracks with her hands only to find it impossible.
9–14 seconds: She suddenly gets an idea, reaches out to click the Control Center in the top-right corner, opens the screen brightness slider with the sun icon, and frantically drags the brightness slider to the left to lower it. Each adjustment synchronizes with the entire screen dimming, causing the character, background, icons, and cracks to gradually fade into darkness together; as she adjusts it, she glances guiltily toward the audience, finally pulling the brightness to the absolute lowest.
14–15 seconds: The screen turns completely pitch black and holds for one second, without any text or logo appearing.
Audio: Begins with brisk martial arts instrumental music and the whooshing sound of the spinning dagger cutting through the air; the music cuts out abruptly upon impact, emphasizing the sound of shattering glass; followed by sounds of flustered fabric rustling and UI clicking, ending in complete silence.
Constraints: No camera cuts, no character changes, no background changes, no additional characters or flying daggers, no physical computer frame or keyboard. Cracks must remain permanently fixed on the screen glass plane. The final darkening must be triggered by the woman operating the brightness slider, not by a sudden cut to black.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100255511228932598"></a>

### Vertical four-grid candid fail shots, lotus root harvesting scene in a lotus pond and character

Author：[@ahamme35638](https://x.com/ahamme35638) · [Source](https://x.com/ahamme35638/status/2100255511228932598)

Character · Published

**Summary:** Vertical four-grid candid fail shots, lotus root harvesting scene in a lotus pond and character

<img src="images/2100255511228932598-1.jpg" alt="Image 1" width="480" />

<img src="images/2100255511228932598-2.jpg" alt="Image 2" width="480" />

<img src="images/2100255511228932598-3.jpg" alt="Image 3" width="480" />

**Prompt**

```text
Vertical 2×2 failed photos, scene of harvesting lotus roots in a lotus pond + character
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2100102387323076955"></a>

### Generate a 3x3 nine-grid collection of amateur candid failed photos

Author：[@AI\_jacksaku](https://x.com/AI_jacksaku) · [Source](https://x.com/AI_jacksaku/status/2100102387323076955)

Other · Published

Source：[@AI\_jacksaku](https://x.com/AI_jacksaku) · [Source](https://x.com/AI_jacksaku/status/2097878193013199231)

**Summary:** Generate a 3x3 nine-grid collection of amateur candid failed photos

<img src="images/2100102387323076955-1.jpg" alt="Image 1" width="480" />

<img src="images/2100102387323076955-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
A series of amateur failed photos, 3x3, 9:16
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099213523947864179"></a>

### Geometric abstract character poster prompt template based on Constructivism, Suprematism, and Futurism.

Author：[@VoxcatAI](https://x.com/VoxcatAI) · [Source](https://x.com/VoxcatAI/status/2099213523947864179)

Poster / Flyer · Character · Abstract / Background · Published

Source：[@VoxcatAI](https://x.com/VoxcatAI) · [Source](https://x.com/VoxcatAI/status/2054455196298932406)

**Summary:** Geometric abstract character poster prompt template based on Constructivism, Suprematism, and Futurism.

<img src="images/2099213523947864179-1.jpg" alt="Image 1" width="480" />

<img src="images/2099213523947864179-2.jpg" alt="Image 2" width="480" />

<img src="images/2099213523947864179-3.jpg" alt="Image 3" width="480" />

<img src="images/2099213523947864179-4.jpg" alt="Image 4" width="480" />

<img src="images/2099213523947864179-5.jpg" alt="Image 5" width="480" />

<img src="images/2099213523947864179-6.jpg" alt="Image 6" width="480" />

<img src="images/2099213523947864179-7.jpg" alt="Image 7" width="480" />

<img src="images/2099213523947864179-8.jpg" alt="Image 8" width="480" />

**Prompt**

```text
{Subject / Character / Concept}, Constructivism × Suprematism × Futurism × Swiss International Style graphic design × Geometric Neo-Modernism.

Deconstruct and translate the subject into a highly graphic geometric visual system, eschewing traditional realistic modeling in favor of distilling the subject's core silhouettes, identifying traits, signature colors, structural relationships, and directional dynamics, then reconstructing them into geometric color blocks, diagonal axes, circles, rectangles, triangles, directional vectors, modules, and negative space. Humans, animals, architecture, machinery, objects, or abstract concepts are all uniformly integrated into this geometric compositional logic while retaining sufficient recognizability.

The overall design employs Path-based Shape Construction, centering on Geometric Blocking, Hard-edge Abstraction, Modular Repetition, and Directional Cutting. Generous use of 15°, 30°, and 45° diagonal axes establishes dynamic momentum, imparting the subject with a distinct sense of forward motion, rotation, collision, slicing, or expansion.

The composition utilizes Constructivist Cropping and Asymmetrical Balance. The subject may partially extend beyond the edges of the frame, bisected or occluded by large diagonally cut color planes; localized structures can be scaled up, repeated, rotated, or mirrored to forge a powerful visual rhythm. The image maintains a clear visual focal point while avoiding a conventional, static, centered portrait layout.

Media execution employs Vector Graphics × Screen Print × Risograph Simulation × Digital Collage. The subject is composed of crisp vector edges and expansive solid-color planes, with localized simulations of silkscreen ink layering, risograph misregistration/color trapping shifts, paper fiber texture, subtle halftone dots, and slight edge misalignment, granting the visual both digital design precision and physical print tactility.

Lighting de-emphasizes naturalistic illumination, adopting a Flat Tonal Structure × Graphic Contrast × Optical Depth. Spatial depth is established primarily through value contrast across color blocks, geometric occlusion, scale variations, translucent overlaps, and foreground-background relationships, rather than relying on complex gradient rendering. Subtle glowing geometric accents or highlighted edges can be incorporated locally to create a Luminous Graphic Field, while prioritizing planar composition throughout.

The color scheme utilizes a highly recognizable, limited palette centered on black, white, red, cobalt blue, ultramarine, bright yellow, orange, cool gray, and off-white/cream, with 2–4 dominant colors automatically selected based on the subject. The colors maintain high contrast, rigid order, and distinct surface area proportions, avoiding chaotic gradients and excessive secondary mixtures. Subtle third-color overlays produced by localized screen-print overprinting are permitted.

The overall aesthetic references El Lissitzky's Proun Composition spatial geometry, Alexander Rodchenko's Constructivist posters and radical cropping, Kazimir Malevich's Suprematist basic forms, László Moholy-Nagy's Bauhaus optical geometry, and Josef Müller-Brockmann's Swiss Grid System order, while ultimately preserving an original visual structure.

Incorporate VOXCAT elements: Integrate a minimalist geometric stylized “V” + cat logo into the upper-left corner, seamlessly blended into the Constructivist typography/layout; add a small “voxCAT” signature in the lower-right corner. Cat ear silhouettes, cat eyes, V-shaped bevels, and cat tail curves may be further translated into circles, triangles, diagonal lines, or modular geometric glyphs, serving as recurring VOXCAT visual motifs throughout the composition.

Overall requirements: clear structure, strong geometric relationships, sharp edges, intact color blocks, stable typography and layout, distinct sense of velocity, ample negative space, low noise, no particles, no complex realistic backgrounds, high degree of finish. Aside from the VOXCAT logo and the voxCAT signature, no other text, numbers, UI elements, watermarks, or extraneous logos should appear.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099141066784215478"></a>

### Chinese dreamlike courtyard and modern empty swimming pool, CCD soft focus texture

Author：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2099141066784215478)

Other · Published

Source：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2099065219259761109)

**Summary:** Chinese dreamlike courtyard and modern empty swimming pool, CCD soft focus texture

<img src="images/2099141066784215478-1.jpg" alt="Image 1" width="480" />

<img src="images/2099141066784215478-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Chinese dreamlike aesthetic × CCD direct flash soft focus × empty swimming pool
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098980048703467897"></a>

### A 30-second gameplay video prompt for an authentic AAA-style racing game featuring grandmas on mobility scooters set in rural Japan.

Author：[@SSSS\_CRYPTOMAN](https://x.com/SSSS_CRYPTOMAN) · [Source](https://x.com/SSSS_CRYPTOMAN/status/2098980048703467897)

Other · Published

**Summary:** A 30-second gameplay video prompt for an authentic AAA-style racing game featuring grandmas on mobility scooters set in rural Japan.

<img src="covers/2098980048703467897.jpg" alt="Image 1" width="480" />

**Prompt**

```text
A 30-second continuous video sequence. Gameplay footage in the style of an authentic racing game featuring battles exclusively with senior mobility scooters. Rendered not as a live-action film, but as high-definition real-time 3DCG of a cutting-edge AAA racing game. People, mobility scooters, roads, mountains, rice paddies, residential houses, utility poles, guardrails, sky, lighting, shadows, reflections, dust clouds, and the sense of speed are all unified with realistic yet distinctly game-CG textures. The highest priority is presenting it as an in-game screen, consistently maintaining authentic racing game UI and camerawork throughout.

0–3 seconds: Title sequence. Opening from a black background, delivering brief, stylish close-ups of mobility scooter tires, motor, handlebars, battery, and shopping basket just like a serious racing game. Emphasize metallic sheen, plastic textures, minute scratches, and light reflections. Afterwards, the title logo from the reference image is displayed prominently in the center of the screen. The logo display exudes high quality and weight, resembling the title screen of a genuine racing simulator.

3–6 seconds: Starting grid. Set in rural Japan. Broad rice paddies, farm roads, weathered houses, mini kei-trucks, irrigation ditches, and a clear morning atmosphere framed by mountain ridges. Six mobility scooters are lined up side-by-side. All drivers are grandmothers in their 70s to 90s. Dressed in typical countryside attire—straw hats, floral jackets, arm covers, and monpe-style baggy trousers—yet every single one wears an unnervingly dead-serious expression. The protagonist is positioned near the front. The red start signal lights illuminate sequentially and shut off for a simultaneous start.

6–10 seconds: Immediately after race start. Initially rolling out slowly around 6 km/h like authentic mobility scooters. The HUD displays position, lap, speed, remaining battery, mini-map, and a tachometer-style motor output gauge. Top of the screen shows "1/3 LAP", top left displays position "3/6", bottom right shows speedometer at "6 km/h". The camera alternates naturally between authentic racing chase cam, low tracking cam, onboard-style corner entry cam, and side overtaking cam, all flowing seamlessly as gameplay footage.

10–15 seconds: The protagonist presses a red button beside the handlebars, and a large "SPORT+" UI appears on screen. An absurd, uncharacteristic surge of acceleration erupts from the scooter. The speedometer rockets from 6 → 18 → 35 → 52 → 68 → 80 km/h. The motor whine rises sharply, the chassis vibrates, and the green onions and grocery bags in the front basket flutter violently. Blazing down the narrow agricultural road at 80 km/h, overtaking other mobility scooters one by one. "OVERTAKE" text may appear on the screen.

15–21 seconds: Ultra-high-speed rural road racing. The track spans narrow paved paths between rice fields, treacherous straights beside irrigation ditches, and tight alleys weaving between houses. A fierce, side-by-side battle against two rival mobility scooters. Tiny wheels bounce over bumps, shaking the chassis unstably, yet they charge forward at nearly 80 km/h. Red racing lines, braking points, split times, and position shifts appear on screen. The protagonist overtakes a kei-truck by mere hairbreadth, kicking up dust clouds while diving onto a dirt farm track. Top priority is an authentic racing game sensation of speed.

21–26 seconds: The climax showcase. A sharp right turn looms ahead, bordered on the outside by an irrigation canal. A "BRAKE" guide flashes on screen. The protagonist maintains 80 km/h until the last split second, executing heavy braking. Speedometer plunges 80 → 54 → 41 km/h. Tires screech, the body rolls heavily, and one wheel nearly lifts off the ground, barely maintaining grip. The camera drops lower behind the vehicle, amplifying tension. Accelerating cleanly the moment the corner is cleared, triggering a "PERFECT CORNER" UI pop-up.

26–30 seconds: Final straight. The protagonist and a rival grandma race neck-and-neck. Both deadpan and expressionless. Speed reaches 76–82 km/h. Battery level is nearly depleted. "FINAL LAP" and "BOOST" flashes on screen. The protagonist unleashes one final burst of acceleration, edging ahead by a hair. Crossing the finish line just tens of centimeters ahead. "1st PLACE" is splashed across the screen. The mobility scooter comes to a halt, heat haze rising faintly from the motor. Battery displays 1%. The grandmother stares blankly at the meter and mutters a single line: "How'm I gonna get home now?" ("帰り、どうすんべ。"). Concludes like a race results screen, showing mobility scooters parked along the country path alongside the protagonist's victory banner.

Throughout the entire piece, humor stems solely from the absurdity of the premise, while the footage itself is portrayed completely as a serious, authentic racing game. The critical elements are rural mobility scooters impossibly accelerating from 6 to 80 km/h to aggressively attack farm roads and canal banks, accompanied by full UI, dynamic camera angles, standings, speedometer, racing line, and braking prompts, unmistakable to any viewer as "authentic racing game gameplay footage."
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098960216792682600"></a>

### Mandala Gothic style costume design prompt detailing a translucent tunic and accessories.

Author：[@AI\_GIRL\_DESIGN](https://x.com/AI_GIRL_DESIGN) · [Source](https://x.com/AI_GIRL_DESIGN/status/2098960216792682600)

Portrait / Selfie · Fashion Item · Published

**Summary:** Mandala Gothic style costume design prompt detailing a translucent tunic and accessories.

<img src="images/2098960216792682600-1.jpg" alt="Image 1" width="480" />

<img src="images/2098960216792682600-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
A gray short-sleeved tunic with an enormous boxy silhouette that covers from above the waist down to the hips. It is made of a special material that looks like layers of thick translucent organza, coarse mesh, and a thin resin film, featuring wide sleeves that project broadly sideways from the shoulders to the cuffs. At the neckline is a small black shirt collar and a black ribbon tie. Thick black cords are sewn across the entire tunic as abstract embroidery, meandering like a continuous, random one-stroke line, with small vermilion to coral-colored butterflies, knots, and petal-shaped appliqués scattered at intersections and edges. The insides of the cuffs are black. The fabric features realistic creases, folds, seam allowances, raised threads, and subtle translucency. Black knee-high socks. Red mules. On the back right of the head is an enormous matte-black bow-shaped chignon. Long, slender chain earrings of red and black beads hang down from both ears to near the chest.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098634675057238254"></a>

### A prompt to generate professional-quality live concert promotional flyers in a 2x2 grid with different costumes, genres, and typography while maintaining the character and art style.

Author：[@hAru\_mAki\_ch](https://x.com/hAru_mAki_ch) · [Source](https://x.com/hAru_mAki_ch/status/2098634675057238254)

Poster / Flyer · Character · Fashion Item · Text / Typography · Published

Source：[@hAru\_mAki\_ch](https://x.com/hAru_mAki_ch) · [Source](https://x.com/hAru_mAki_ch/status/2098616421190435145)

**Summary:** A prompt to generate professional-quality live concert promotional flyers in a 2x2 grid with different costumes, genres, and typography while maintaining the character and art style.

<img src="images/2098634675057238254-1.jpg" alt="Image 1" width="480" />

<img src="images/2098634675057238254-2.jpg" alt="Image 2" width="480" />

<img src="images/2098634675057238254-3.jpg" alt="Image 3" width="480" />

**Prompt**

```text
Maintain this character and art style, and present live concert promotional flyers in a 2x2 grid of four panels featuring various live costumes and poses, as if created by a professional designer.\n\nFreely conceptualize the costumes, poses, music genres, backgrounds, lighting, and flyer designs, giving each of the four panels a distinct appeal and unexpected flair. Incorporate visuals and striking typography that convey the excitement and worldview of the live performance, and include fictional announcement information such as concert titles, dates, times, and venues to achieve a professional-grade finish.\n\nMaintain the exact same character and the same art style across all four panels. The overall aspect ratio should be 4:3.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098559982035951785"></a>

### An aesthetic portrait described through classical poetry depicting a woman draped in sheer gauze and reclining on a couch after bathing.

Author：[@listudio](https://x.com/listudio) · [Source](https://x.com/listudio/status/2098559982035951785)

Portrait / Selfie · Character · Published

**Summary:** An aesthetic portrait described through classical poetry depicting a woman draped in sheer gauze and reclining on a couch after bathing.

<img src="images/2098559982035951785-1.jpg" alt="Image 1" width="480" />

<img src="images/2098559982035951785-2.jpg" alt="Image 2" width="480" />

<img src="images/2098559982035951785-3.jpg" alt="Image 3" width="480" />

<img src="images/2098559982035951785-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
Fresh from the fragrant orchid bath, draped in sheer gossamer,
Her tender body reclines gracefully on a soft couch.
Where layers of translucent silk overlap, her alabaster skin shines through,
Eyes closed gently, harboring a lingering springtime tenderness.
Warm mist hazily twines around her jade-like frame,
A wisp of remaining warmth softly dissolves into the rosy glow.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098400287262470292"></a>

### 10-second high-end wireless earbuds commercial storyboard prompt, showing a modern urban career woman wearing and using the product in an office setting.

Author：[@Adam38363368936](https://x.com/Adam38363368936) · [Source](https://x.com/Adam38363368936/status/2098400287262470292)

Comic / Storyboard · Product Marketing · Character · Product · Cityscape / Street · Published

Source：[@Adam38363368936](https://x.com/Adam38363368936) · [Source](https://x.com/Adam38363368936/status/2098318586859377102)

**Summary:** 10-second high-end wireless earbuds commercial storyboard prompt, showing a modern urban career woman wearing and using the product in an office setting.

<img src="covers/2098400287262470292.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Using the AEROX ONE wireless Bluetooth earbuds and charging case from the reference image as the sole product reference, strictly maintain the earbud shape, proportions, silver-gray metal and matte white materials, the rounded contour of the charging case, brand typography, aperture positions, and structural relationships consistent; do not redesign, do not deform, and do not introduce extra products.

Produce a 10-second high-end consumer electronics brand commercial, featuring a young Asian woman as the urban lifestyle female protagonist. The protagonist has a clean, neat, and restrained temperament, wearing a simple white shirt or a light gray blazer, with natural makeup and realistic skin texture, embodying the overall vibe of a modern urban professional woman. The character only serves to express lifestyle and atmosphere; the product is always the visual centerpiece.

0-2 seconds:
Early morning modern office space, with natural light entering through floor-to-ceiling windows. The female protagonist walks to the desk and sets down her phone and leather bag. The camera cuts swiftly to the AEROX ONE charging case on the desk; the lid opens crisply, and both earbuds clearly appear. The camera pacing is crisp and sharp, with the product appearing in the very first second.

2-4 seconds:
The female protagonist picks up one earbud and places it in her ear with a natural, elegant, non-exaggerated motion. Cut to a close-up of the earbud, with cool white highlights gleaming along the metallic edge, fitting naturally in the ear, highlighting the sophisticated aesthetic of the product when worn. Blurred office environment in the background.

4-6 seconds:
The female protagonist walks through a modern office area or coffee shop aisle wearing the earbuds, captured with a smooth lateral tracking shot. Her demeanor is focused, relaxed, and in control. The earbuds must remain clearly visible in the frame and cannot be fully obscured by hair. The overall tone emphasizes urban commute, efficiency, and a lifestyle aesthetic.

6-8 seconds:
Cut to her sitting by the window using a laptop, one hand lightly tapping the earbud as if switching modes or answering a call. Slight camera push-in, blurred city in the background, creating a premium lifestyle commercial mood blending product and character.

8-10 seconds:
Quick cut back to a pure product hero shot. The AEROX ONE earbuds and charging case rest on a minimalist silver-gray tabletop, with a soft blurred background and the protagonist out of focus in the far distance providing environmental ambiance. The camera gradually decelerates and comes to a stop, leaving the earbuds and charging case as the sole sharp subject in the frame, creating the finale of a high-end consumer electronics brand commercial.

Overall Style:
High-end, modern, technological, urban, restrained, realistic, like an international consumer electronics brand campaign.
The imagery must feature genuine commercial photography texture, real optical lenses, precise perspective, sharp product edges, and authentic, natural silver-gray metal and matte white materials.
The pacing must have distinct variations; avoid using slow motion throughout.
Human movements must be natural, avoiding a posed look, excessive smiling, and exaggerated facial expressions.

Key Requirements:
Maintain consistent product appearance.
Earbuds must have normal anatomy and realistic proportions when worn in the character's ear.
The protagonist's hair must not cover the earbuds.
Do not add a second set of earbuds.
No product deformation.
No excessive sci-fi visual effects.
No neon cyberpunk.
No large blocks of subtitles.
No deformed hands.
The character must not overshadow the product as the main subject.
No watermarks.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098363788928143624"></a>

### Structured prompt for an exploded view product poster of a sparkling oolong tea beverage can.

Author：[@luo24853969](https://x.com/luo24853969) · [Source](https://x.com/luo24853969/status/2098363788928143624)

Product Marketing · Poster / Flyer · Product · Published

**Summary:** Structured prompt for an exploded view product poster of a sparkling oolong tea beverage can.

<img src="images/2098363788928143624-1.jpg" alt="Image 1" width="480" />

<img src="images/2098363788928143624-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
{
  "type": "Exploded view product poster",
  "subject": "Sparkling tea beverage can",
  "style": "Clean high-tech 3D render, studio lighting, subtle glowing details",
  "background": "Soft pastel orange and light beige gradient",
  "header": {
    "logo": "PUBBLE",
    "subtitle": "REFRESH YOUR MOMENT WITH PUBBLE!"
  },
  "layout": {
    "centerpiece": "Vertically stacked exploded view, fully displaying the 9 structural layers of the sparkling oolong tea can: outer aluminum can body, top lid pull tab, printed label layer, inner wall lining, sparkling liquid core, bottom concave structure, sugar-free formula core, delicate fragrance oolong tea essence layer, bottom anti-slip design.",
    "callout_labels": {
      "count": 8,
      "left_side": [
        "Sugar-Free Formula\nZero-burden refreshing taste, making every sip light and effortless.",
        "Sparkling Carbonation Structure\nFine, dense bubbles delivering crisp, exhilarating textural layers.",
        "Delicate Fragrance Oolong Tea Essence\nCarefully selected oolong tea leaves, preserving natural tea aroma and sweet aftertaste."
      ],
      "right_side": [
        "High-Quality Aluminum Can Body\nLightweight and durable, perfectly locking in fresh flavor.",
        "Top Lid Pull Tab Design\nEasy to open, enhancing the user experience.",
        "Gradient Visual Label\nSoft pastel orange to off-white color scheme, creating a fresh atmosphere.",
        "330ml Optimal Capacity\nJust right to carry around, refreshing wonderful moments anytime.",
        "Bottom Stable Structure\nAnti-slip design for secure placement."
      ]
    },
    "footer": {
      "left_text_block": {
        "headline": "Freshness, starting from the structure.",
        "body": "Every layer of structure is meticulously designed; from the sugar-free formula to the delicate fragrance oolong tea essence, PUBBLE brings a pure and refreshing experience through refined craftsmanship and natural flavor."
      },
      "right_logo": "PUBBLE"
    }
  }
}
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098256551425319223"></a>

### A fantasy incantation-style prompt summoning a double-edged sword imbued with the power of dragon scales and flashes of light.

Author：[@0Narasan](https://x.com/0Narasan) · [Source](https://x.com/0Narasan/status/2098256551425319223)

Animal / Creature · Published

**Summary:** A fantasy incantation-style prompt summoning a double-edged sword imbued with the power of dragon scales and flashes of light.

<img src="images/2098256551425319223-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
"Hear the pulse of the sleeping dragon at the edge of the void. Horn that pierces the heavens, fountainhead of magic that scorches all creation.\nBy the seal of the covenant, I command.\nGather upon my right arm, one-handed yet double-edged, the free and absolute condemner.\nHarbor the protection of dragon scales upon your blade, and turn the roar of ruin into a flash of light. Come forth and pass judgment——"
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098277846250922232"></a>

### Boyfriend-perspective iPhone tennis daily snapshots, young girl in simple tennis wear

Author：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2098277846250922232)

Portrait / Selfie · Character · Published

Source：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2096132813120807024)

**Summary:** Boyfriend-perspective iPhone tennis daily snapshots, young girl in simple tennis wear

<img src="images/2098277846250922232-1.jpg" alt="Image 1" width="480" />

<img src="images/2098277846250922232-2.jpg" alt="Image 2" width="480" />

<img src="images/2098277846250922232-3.jpg" alt="Image 3" width="480" />

<img src="images/2098277846250922232-4.jpg" alt="Image 4" width="480" />

<img src="images/2098277846250922232-5.jpg" alt="Image 5" width="480" />

**Prompt**

```text
Like a casual tennis daily photo taken by a boyfriend on an iPhone: a young adult girl wearing a simple tennis outfit and sneakers; randomly capturing her different movements, spontaneous in-the-moment happenings, and varying shooting distances each time, like an authentic, candid photo casually taken while spending time together.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097797456117539136"></a>

### Template prompt for generating a 4×4 \(16-frame\) 2D game sprite sheet from a reference character.

Author：[@SSSS\_CRYPTOMAN](https://x.com/SSSS_CRYPTOMAN) · [Source](https://x.com/SSSS_CRYPTOMAN/status/2097797456117539136)

Character · Published

**Summary:** Template prompt for generating a 4×4 \(16-frame\) 2D game sprite sheet from a reference character.

<img src="covers/2097797456117539136.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Reference this character to create a 2D animation sprite sheet for a game.
The action is "🔴 Enter action here".

Express one continuous action across a total of 16 frames in 4 columns × 4 rows.

[Sprite Sheet Specifications]
・Square canvas
・4 columns × 4 rows, 16 frames in total
・All 16 cells must be exactly the same size
・Ensure a minimum margin of 10px on the top, bottom, left, and right of each cell
・No borders, grid lines, numbers, letters, symbols, or UI elements whatsoever
・Background must be a unified solid white across all frames
・Arrange frames in chronological order from top-left to right, and from top row to bottom row

[Most Important: Fixed Size and Position]
・Keep the character's display scale consistent across all 16 frames
・Camera zoom-in and zoom-out are prohibited
・Fix the ground contact baseline beneath the feet at the exact same height
・Ensure the character's center position does not shift drastically between frames; change poses only as necessary for the movement

[Most Important: Stay Completely Within the Cell]
・Keep everything, including hair, clothing, limbs, weapons, accessories, effects, afterglow, and particles, strictly inside each cell
・Do not overflow into adjacent cells
・Do not breach the 10px margin safe zone
・Even if the action becomes large, do not scale down the character to compensate
・If necessary, tone down effects or the swing range of arms to keep everything inside the cell

[Drawing Guidelines]
・Clear, legible silhouette readable as a 2D game sprite
・Natural movement connecting smoothly between frames
・Prioritize flawless continuity as animation assets rather than standalone illustrations
・Unify detail density, line work, coloring, and shading across every frame
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097784050660376617"></a>

### A translucent, glowing maple leaf hovers above calm water, with pink flowers blooming inside and its stem gently touching the surface to create concentric ripples.

Author：[@churvikv](https://x.com/churvikv) · [Source](https://x.com/churvikv/status/2097784050660376617)

Other · Published

**Summary:** A translucent, glowing maple leaf hovers above calm water, with pink flowers blooming inside and its stem gently touching the surface to create concentric ripples.

<img src="images/2097784050660376617-1.jpg" alt="Image 1" width="480" />

<img src="images/2097784050660376617-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Prompt 1:
An enchanting and surreal digital art piece featuring a translucent, golden maple leaf hovering magically above the surface of calm, dark water. The leaf glows from within with a warm, ethereal light, its delicate veins clearly visible. Inside the translucent structure of the leaf, tiny, vibrant pink flowers and closed buds are embedded, appearing to bloom within its very veins. The tips of the leaf are edged with a sparkling, golden glitter that drifts into the air like magic dust. The leaf's stem extends downward, just touching the water's surface, creating concentric ripples that spread outward. Below the water, a reflection of the glowing leaf and stem is faintly visible. The background is a dreamy twilight forest with silhouetted pine trees against a soft, gradient sky of purple, orange, and blue. Several pink water lilies float on the dark water, adding to the serene and magical atmosphere.

Prompt 2:
A majestic, ethereal maple leaf made of translucent, crystalline material floats delicately above a serene dark pond. The leaf is intricately detailed with glowing veins and is embedded with small, soft pink cherry blossom flowers and buds that seem to grow directly from its structure. Golden, shimmering magical dust particles swirl around the leaf, casting a warm, radiant glow. The tip of the leaf stem gently touches the water surface, creating perfect concentric ripples that reflect the light. The background features a dreamy, out-of-focus forest landscape at dusk, with hints of silhouetted trees and a soft gradient sky ranging from deep twilight blues to pale pinks. Floating pink lotus flowers rest on the calm water surface in the foreground and mid-ground. The lighting is soft, cinematic, and magical, highlighting the glassy textures and bioluminescent quality of the scene. The composition is centered, vertical, and symmetrical, evoking a sense of tranquility, mystical nature, and fairy-tale beauty, rendered with hyper-realistic digital art precision.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097780695414530375"></a>

### Generate a webpage interface with a Chrome frame showing a ChatGPT conversation that generates a livestreamer screenshot.

Author：[@XChatScout](https://x.com/XChatScout) · [Source](https://x.com/XChatScout/status/2097780695414530375)

App / Web Design · Published

**Summary:** Generate a webpage interface with a Chrome frame showing a ChatGPT conversation that generates a livestreamer screenshot.

<img src="images/2097780695414530375-1.jpg" alt="Image 1" width="480" />

<img src="images/2097780695414530375-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Create a webpage screenshot that includes a Chrome browser frame, showing a user conversing on ChatGPT and using GPT-Image-2.5 to generate a screenshot of a female livestreamer streaming.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097715653981667777"></a>

### Prompt for a portrait of a shy traditional beauty half-hidden behind a curtain.

Author：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2097715653981667777)

Portrait / Selfie · Published

Source：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2097367159085420949)

**Summary:** Prompt for a portrait of a shy traditional beauty half-hidden behind a curtain.

<img src="images/2097715653981667777-1.jpg" alt="Image 1" width="480" />

<img src="images/2097715653981667777-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Refined and tenderly affectionate; hazy shadows of flowers; half-concealed by curtain shadows; hesitant to speak, holding back words; a bashful beauty; breathtaking grace breaking the mold
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097672457582985315"></a>

### Generate a text-to-image prompt for a 5-day travel itinerary guide map of Rizhao, Qingdao, and Yantai.

Author：[@MrGafish](https://x.com/MrGafish) · [Source](https://x.com/MrGafish/status/2097672457582985315)

Infographic / Edu Visual · Published

**Summary:** Generate a text-to-image prompt for a 5-day travel itinerary guide map of Rizhao, Qingdao, and Yantai.

<img src="images/2097672457582985315-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Traveling to Rizhao, Qingdao, and Yantai for 5 days this month, generate a travel itinerary guide infographic
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097710368542146635"></a>

### Generate a Qingming solar term themed poster.

Author：[@shitunote](https://x.com/shitunote) · [Source](https://x.com/shitunote/status/2097710368542146635)

Poster / Flyer · Published

Source：[@shitunote](https://x.com/shitunote) · [Source](https://x.com/shitunote/status/2096740511612797206)

**Summary:** Generate a Qingming solar term themed poster.

<img src="covers/2097710368542146635.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Generate a Qingming solar term poster
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097665256424349855"></a>

### Generate an illustrated long infographic image of five thousand years of Chinese history

Author：[@cnyzgkc](https://x.com/cnyzgkc) · [Source](https://x.com/cnyzgkc/status/2097665256424349855)

Infographic / Edu Visual · Diagram / Chart · Published

**Summary:** Generate an illustrated long infographic image of five thousand years of Chinese history

<img src="images/2097665256424349855-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Generate an image that tells the story of five thousand years of history
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097611216139235779"></a>

### Generate a 3x3 nine-grid of Chinese and English multi-expression meme stickers based on a character reference image.

Author：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2097611216139235779)

Character · Published

Source：[@DeepBlueX0](https://x.com/DeepBlueX0) · [Source](https://x.com/DeepBlueX0/status/2097258933928796451)

**Summary:** Generate a 3x3 nine-grid of Chinese and English multi-expression meme stickers based on a character reference image.

<img src="images/2097611216139235779-1.jpg" alt="Image 1" width="480" />

<img src="images/2097611216139235779-2.jpg" alt="Image 2" width="480" />

<img src="images/2097611216139235779-3.jpg" alt="Image 3" width="480" />

<img src="images/2097611216139235779-4.jpg" alt="Image 4" width="480" />

<img src="images/2097611216139235779-5.jpg" alt="Image 5" width="480" />

<img src="images/2097611216139235779-6.jpg" alt="Image 6" width="480" />

<img src="images/2097611216139235779-7.jpg" alt="Image 7" width="480" />

<img src="images/2097611216139235779-8.jpg" alt="Image 8" width="480" />

**Prompt**

```text
Reference the character in the image, generate a 3*3 grid with a total of 9 different emoji/sticker expressions, Chinese and English can appear, light gradient background
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097631043004273061"></a>

### Cristiano Ronaldo eating shawarma animation.

Author：[@royalpinto007](https://x.com/royalpinto007) · [Source](https://x.com/royalpinto007/status/2097631043004273061)

Other · Published

Source：[@gabrielchua](https://x.com/gabrielchua) · [Source](https://x.com/gabrielchua/status/2097546354373603554)

**Summary:** Cristiano Ronaldo eating shawarma animation.

<img src="covers/2097631043004273061.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Cristiano Ronaldo eating shawarma
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097558679956664521"></a>

### Cybernetic horror portrait featuring a gaunt humanoid with a cracked porcelain mask, head cables, and high-contrast monochrome lighting.

Author：[@meng\_dagg695](https://x.com/meng_dagg695) · [Source](https://x.com/meng_dagg695/status/2097558679956664521)

Portrait / Selfie · Published

**Summary:** Cybernetic horror portrait featuring a gaunt humanoid with a cracked porcelain mask, head cables, and high-contrast monochrome lighting.

<img src="images/2097558679956664521-1.jpg" alt="Image 1" width="480" />

<img src="images/2097558679956664521-2.jpg" alt="Image 2" width="480" />

<img src="images/2097558679956664521-3.jpg" alt="Image 3" width="480" />

**Prompt**

```text
Cybernetic horror portrait, gaunt humanoid figure with cracked porcelain-white skull-like mask, mismatched hollow eye sockets (one sunken void, one recessed metallic ring), jagged exposed teeth, surrounded by a chaotic tangle of thick black cables and industrial bobbin/coil attachments wired into the head, tattered dark fabric top, dramatic low-key lighting, deep black background, high contrast monochrome, horror photography, cinematic, hyperdetailed texture, 85mm lens, shallow depth.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097519422407872858"></a>

### Turntable studio video of a carved wooden chess knight smoothly rotating 360 degrees.

Author：[@higgsfield](https://x.com/higgsfield) · [Source](https://x.com/higgsfield/status/2097519422407872858)

Product · Published

**Summary:** Turntable studio video of a carved wooden chess knight smoothly rotating 360 degrees.

<img src="covers/2097519422407872858.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Create a photorealistic studio turntable video of a polished wooden chess knight.

The knight has a minimalist carved horse silhouette: broad flat sides, a rounded elongated muzzle, a tiny dark eye, an angular ear, and a gently curved neck. A smooth, dark brown insert follows the mane along the back. The figure stands on a wide circular wooden base with several concentric stepped rings.

Use warm brown wood with clearly visible vertical grain, softly rounded edges, and a glossy lacquer finish. Preserve the exact shape, proportions, wood grain, and dark mane insert throughout the video.

The entire chess piece, including its base, rotates smoothly through one complete 360-degree turn around its vertical axis at a constant speed. It stays perfectly centered and firmly on the surface. The first and last frames match for a seamless loop.

Keep the camera completely stationary, looking slightly downward at the piece. Show the entire object with a small margin above and below. Use a seamless light-gray studio background and floor, soft diffused lighting, gentle highlights on the lacquer, and a subtle contact shadow beneath the base.

Duration: 3 seconds. Frame rate: 30 fps. Square 1:1 composition.

No camera movement, zoom, cuts, wobbling, floating, deformation, changing proportions, sliding wood textures, flickering, additional objects, text, or logos.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097513469172129825"></a>

### High-angle portrait of a slender woman wearing a floral qipao with dreamy soft lighting and delicate makeup.

Author：[@BubbleBrain](https://x.com/BubbleBrain) · [Source](https://x.com/BubbleBrain/status/2097513469172129825)

Portrait / Selfie · Character · Published

**Summary:** High-angle portrait of a slender woman wearing a floral qipao with dreamy soft lighting and delicate makeup.

<img src="images/2097513469172129825-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
9:16, wearing a qipao, soft light bloom, dreamy blur, high-angle shot looking down, tall slender model figure, refined makeup, fox-like beauty face
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097486896750338125"></a>

### An image-to-image prompt template for redesigning character themes while maintaining lighting, texture, and composition based on a reference image.

Author：[@nanyuan0412](https://x.com/nanyuan0412) · [Source](https://x.com/nanyuan0412/status/2097486896750338125)

Character · Published

**Summary:** An image-to-image prompt template for redesigning character themes while maintaining lighting, texture, and composition based on a reference image.

<img src="images/2097486896750338125-1.jpg" alt="Image 1" width="480" />

<img src="images/2097486896750338125-2.jpg" alt="Image 2" width="480" />

<img src="images/2097486896750338125-3.jpg" alt="Image 3" width="480" />

<img src="images/2097486896750338125-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
Use the attached image as a photography reference. Preserve its exposure balance, lighting direction, fabric textures, and compositional rhythm; redesign the character and the theme's color palette. The character is an adult, do not replicate the face of the reference figure. After generation, check against the original image: Did you arbitrarily alter the lighting setup, thicken the clothing, or make the skin overly airbrushed/smooth?
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2099184782538395709"></a>

### 10-second vertical skincare commercial storyboard video prompt, featuring unboxing, picking up the bottle, hero display, lotion application texture, and a rotating closing shot.

Author：[@Andy4aicreate](https://x.com/Andy4aicreate) · [Source](https://x.com/Andy4aicreate/status/2099184782538395709)

Comic / Storyboard · Published

**Summary:** 10-second vertical skincare commercial storyboard video prompt, featuring unboxing, picking up the bottle, hero display, lotion application texture, and a rotating closing shot.

<img src="covers/2099184782538395709.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Create a high-quality photorealistic 10-second vertical 9:16 skincare commercial using the uploaded image as the exact visual reference. Preserve the fictional “澄光 / CHENG GUANG Cocoa Soft Glow” bottle design, label, colors, packaging, and overall composition accurately. Do not copy real-world Vaseline trademarks.

Scene 1 (0–2s): Smooth cinematic camera push-in toward the open gift box. The Cheng Guang Cocoa Soft Glow bottle is beautifully revealed among soft pink wrapping paper and decorative elements. Warm cozy lighting, subtle sparkles.

Scene 2 (2–4s): A woman's hands gently pick up the Cheng Guang bottle from the box. Slow natural hand movement, realistic skin texture, soft warm lighting, premium unboxing feeling.

Scene 3 (4–6s): Hero product shot. The bottle stands upright surrounded by cocoa beans, cocoa butter and fresh green leaves. Camera slowly moves from left to right with elegant cinematic depth of field.

Scene 4 (6–7s): Extreme close-up of a smooth lotion texture being spread gently across skin. Show the creamy, lightweight texture and glossy moisturizing finish in realistic macro detail.

Scene 5 (7–9s): The bottle is held elegantly in one hand and slowly rotated toward the camera. Highlight the Cocoa Butter and Serum-in-Lotion concept with premium beauty-commercial lighting.

Scene 6 (9–10s): Final hero shot of the Cheng Guang Cocoa Soft Glow bottle surrounded by cocoa beans and leaves. Camera slowly pushes in, subtle sparkling effects, luxurious warm background, clean product-focused composition.

Style: photorealistic, premium beauty advertisement, cinematic lighting, realistic hand movements, smooth camera transitions, shallow depth of field, soft bokeh, warm golden tones, 4K, highly detailed, natural motion, no distortion, no extra products, no change to bottle label or branding.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2098369223244628234"></a>

### A sequential generation prompt depicting a Japanese woman executing a sequence of actions from receiving a pass to finishing a dunk in a poolside resort 3x3 basketball game across a 4-part narrative structure \(introduction, development, climax, conclusion\).

Author：[@splash\_GL](https://x.com/splash_GL) · [Source](https://x.com/splash_GL/status/2098369223244628234)

Character · Published

**Summary:** A sequential generation prompt depicting a Japanese woman executing a sequence of actions from receiving a pass to finishing a dunk in a poolside resort 3x3 basketball game across a 4-part narrative structure \(introduction, development, climax, conclusion\).

<img src="images/2098369223244628234-1.jpg" alt="Image 1" width="480" />

<img src="images/2098369223244628234-2.jpg" alt="Image 2" width="480" />

<img src="images/2098369223244628234-3.jpg" alt="Image 3" width="480" />

<img src="images/2098369223244628234-4.jpg" alt="Image 4" width="480" />

**Prompt**

```text
[Output]
Create a series of 4 independent photo portraits in [9:16] aspect ratio.
Generate completely separate, individual image files rather than a collage, contact sheet, split screen, or merged single canvas. Each image must feature the identical adult woman, the exact same outfit, accessories, court, lighting conditions, and photographic style.

• Common Settings (COMMON LOCK)
{Story}
Morning, on a poolside 3x3 basketball court at a resort hotel. A distinctly adult Japanese gyaru woman in her early 20s participates in an intense game as part of a 3-person team. Depicting a 4-part progression (Introduction, Development, Twist/Climax, Conclusion): receiving a pass from a teammate, finding space, maneuvering past a defender, accelerating into the paint area, stepping into a powerful takeoff, and finishing with a one-handed dunk shot. The primary focus is not merely the subject's appearance, but the continuous physical movement—rapidly shifting court distances unique to a narrow 3x3 half-court, ball trajectory, footwork, weight shifting, the sense of rising ascent in the jump, cloth and hair inertia, through to the landing.
{Subject Appearance}:
The central figure is an unmistakably adult Japanese gyaru woman in her early 20s. A tall, hourglass-shaped slim build. Long legs, a slender waist, wide pelvis characteristic of an adult female, and slender limbs, contrasted with bell-shaped, extremely voluminous breasts where weight gathers at the bottom, naturally drooping significantly with gravity, each appearing far larger than a basketball. This extreme body proportion must be strictly locked as the highest priority and must not be normalized, reduced in size, or rendered unnaturally spherical during athletic movement. Maintain an anatomically natural connection to the rib cage, shoulders, back, and waist.
The facial features are distinct, authentic Japanese characteristics leaning below average rather than idealized beauty. Small monolid to shallow double-eyelid eyes, slightly spaced eye stance, a low nasal bridge, a petite nose tip, a wide mouth, and a naturally asymmetrical facial outline. Healthy light-beige skin. Gyaru-style makeup using thin eyeliner, understated mascara, beige-tone lipstick, and natural blush. Platinum-silver short straight hair, blunt heavy bangs cut horizontally near the eyebrows, with short ends extending from below the ears to the nape of the neck. Only the tips of the hair move with a slight delay relative to the body due to running, taking off, and jumping.
{Outfit}:
Pink-based resort swimwear. Fabric designed with sufficient front-panel width and three-dimensional tailoring to comfortably cover the exceptionally large bust, visibly protruding forward over the chest. The neckline, armholes, sides, and high-cut leg openings are fully opaque, ensuring neither breasts nor undergarments are exposed even during vigorous motion. Black-and-white high-grip basketball shoes. Small silver hoop earrings only. Bags, smartphones, and unnecessary accessories are kept off-court and omitted from the frame.
{Location}:
An outdoor 3x3 half-court adjacent to a resort hotel poolside. Blue-gray elastic court surfacing, white 3-point lines and paint area, transparent backboard, orange rim, black support pole, and a resort swimming pool with swimming guests in the distance. The hotel's exterior wall is visible in the background, with only required teammates and opponents partially visible at the edges of the frame. The court surface shows only faint scuff marks from shoes during play. No stray basketballs, drinks, bags, or decorative items. Realistic scale proportions are maintained between the rim height, backboard, court lines, and the subject's height.
{Lighting & Photography}:
Low natural morning sunlight casts from the side of the court, stretching long shadows of the players and the basket pole across the ground surface. Weak reflected light from the hotel's exterior walls fills the shadow side. The face and attire are not flatly or evenly lit; the contrast between highlights and shadows is naturally preserved.
The photographer is a friend shooting from outside the sideline. Following the sequence toward the baseline alongside the dunk movement, tracking from an angle that does not obstruct the player's path. In jumping scenes, the camera is positioned low to capture both the rim and the subject's upward ascent within the same frame. Dynamic perspective without excessive wide-angle distortion.
FUJIFILM CLASSIC Neg.-inspired rendering, soft natural skin tones, gently saturated colors.
{Consistency}:
Strictly maintain the identical face, hair, skin, specified body shape, outfit, shoes, and accessories across all 4 images. Prioritizing the specified body proportions above all else, while naturally aligning gravity, inertia, fabric tension, and anatomical structures.

image_1 [Introduction]:
Right after catching a fast pass from a teammate near the right wing. The subject is positioned slightly right of center, body angled toward the hoop, stepping forward with her left foot, securing the ball with both hands held below chest level. Her face is turned toward the rim, checking the defender and the open lane with small, focused eyes. Her right elbow is naturally bent, and her left hand supports the side of the ball. Her upper body maintains posture, centering her gravity to transition instantly into acceleration. The front panel of the swimwear projects forward over her chest; one defender stands roughly 1.5m in front, and one teammate moves along the opposite perimeter. Medium-full shot. The camera is stationed outside the sideline, slightly angled upward from waist height, leaving the path toward the hoop visible in the deep background.

image_2 [Development]:
The moment of powerful acceleration into the paint area after driving past the outside of the defender. The subject takes a single, heavy dribble with her right hand, pushing off the floor with her right foot while extending her left leg forward. Her face faces the rim, eyes locked on the forward path. Her left arm swings diagonally backward for running balance. The ball is in transit back up toward her right hand from the floor, aligning precisely with the body's forward direction. Natural inertia and delay from acceleration affect her chest and hair. The defender begins falling behind her back. Full-body shot. The camera is positioned at the photographer's knee-to-waist height after shifting toward the baseline, capturing a low diagonal front angle that frames the foot kicking the floor, the ball, and the hoop all in the same shot.

image_3 [Twist/Climax]:
The instant of taking off on the final step right before the basket, rising high into the air toward a one-handed dunk. The subject kicks off strongly from the floor with her left leg, driving her right knee forward and upward, holding the basketball high overhead with her right arm. Her left arm extends outward to the side to stabilize her aerial posture. Her face is directed at the rim, her gaze fixed onto the center of the rim. Her body is completely off the floor, clearly showing her long legs and upward jump trajectory. Her bust exhibits lag due to gravity and inertia relative to the rising torso. Dynamic full-body shot. The camera angles sharply upward from knee height outside the baseline, visually chaining the ball, extended arm, rim, and transparent backboard vertically, highlighting the jump height and upward path.

image_4 [Conclusion]:
Immediately after the dunk is executed, forcefully hammering the ball through from directly above the rim with her right hand. The ball begins passing downward through the net as her right hand pulls away from the rim. The subject transitions into descent, naturally flexing her knees to prepare for landing. Her left arm is spread to the side of her body, and her gaze begins turning downward to locate her landing spot on the court. Residual inertia from the shift between ascent and descent remains in her hair and chest, with the fabric hem beginning to fall a beat behind. In the background, a teammate already turns to run back on defense, while an opponent under the basket tracks the ball. Full-body shot. Shot from a low, diagonal side angle outside the baseline, presenting the ball passing through the net, the descending body, and the court landing spot in a continuous flow.

Output 4 individual image files. Do not combine them into a single page.
Ensure the changes (deltas) for each image are independent and function as complete, standalone instructions. Even when the model processes prompts individually, do not abbreviate with phrases like "same as above" or "likewise"; fully apply the COMMON LOCK subject identity, body proportions, clothing, court, and shooting conditions to each image.

{Output Constraints}:
Lock the specified body shape across all 4 images, expressing dynamic athletic motion through posture, gravity, inertia, and fabric tension rather than altering the body proportions themselves. Ensure continuity in rim height, jump trajectory, takeoff position, and relative ball position. Always feature exactly one basketball of standard official regulation size. Avoid deformities in fingers, wrists, elbows, knees, ankles, ears, garments, net, rim, backboard, or court lines. Prioritize dynamic fluidity linking acceleration, takeoff, ascent, dunk, and descent. Eliminate distortions, blurring, extra limbs, duplicate balls, melting, excessive post-processing, artificial CG aesthetics, and AI-typical ornamentation. Do not include text, jersey numbers, team names, brand logos, watermarks, or UI elements.
Negative prompt: collage, grid, 2x2 grid, split screen, four panel, contact sheet, multi-panel, layout, comic panel, one canvas, combined image, duplicate basketball, extra ball, extra limbs, extra fingers, fused fingers, malformed hands, distorted anatomy, floating limbs, rigid pose, static pose, artificial spherical breasts, reduced bust size, inconsistent body proportions, detached anatomy, exposed underwear, transparent clothing, readable text, logo, watermark, UI.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097765578161418569"></a>

### Generation prompt for a body swap scene between a high school boy and girl.

Author：[@irekawarimaniax](https://x.com/irekawarimaniax) · [Source](https://x.com/irekawarimaniax/status/2097765578161418569)

Character · Published

**Summary:** Generation prompt for a body swap scene between a high school boy and girl.

<img src="images/2097765578161418569-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Draw a single panel depicting a body swap between a high school boy and girl
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097533103376081383"></a>

### Fashion portrait of a stylish young man in sunglasses and denim jacket gesturing 'shh' against a grunge wall.

Author：[@Aiwithamirr1](https://x.com/Aiwithamirr1) · [Source](https://x.com/Aiwithamirr1/status/2097533103376081383)

Portrait / Selfie · Character · Fashion Item · Published

**Summary:** Fashion portrait of a stylish young man in sunglasses and denim jacket gesturing 'shh' against a grunge wall.

<img src="images/2097533103376081383-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
Create a cinematic, ultra-realistic fashion portrait of a stylish young man with thick, voluminous dark hair and a neatly trimmed beard, wearing red-framed black sunglasses, a black T-shirt, distressed black denim jacket, and a metal dog-tag necklace. He is holding one finger vertically against his lips in a confident “shh” gesture. Dramatic warm studio lighting, sharp facial details, strong contrast, rugged streetwear aesthetic. Background features a distressed vintage wall with bold teal, cream, and red vertical paint sections, heavy grunge texture, paint splatters and black dripping paint. Centered composition, waist-up portrait, editorial fashion photography, high detail, realistic skin texture, shallow depth of field, 4K, moody and stylish, poster-quality.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097543193651007508"></a>

### A detailed prompt for creating a professional 9:16 Korean beauty-magazine style 'Makeup Analysis Guide' infographic based on a reference portrait, featuring close-up facial analysis, color swatches, and structured makeup steps.

Author：[@ayzalnooor24521](https://x.com/ayzalnooor24521) · [Source](https://x.com/ayzalnooor24521/status/2097543193651007508)

Infographic / Edu Visual · Portrait / Selfie · Published

**Summary:** A detailed prompt for creating a professional 9:16 Korean beauty-magazine style 'Makeup Analysis Guide' infographic based on a reference portrait, featuring close-up facial analysis, color swatches, and structured makeup steps.

<img src="images/2097543193651007508-1.jpg" alt="Image 1" width="480" />

<img src="images/2097543193651007508-2.jpg" alt="Image 2" width="480" />

**Prompt**

```text
Beautiful Korean girl with soft natural features, wearing a black outfit and clear glasses, styled in a clean modern beauty-editorial look. Create a professional “MAKEUP ANALYSIS GUIDE” infographic using the uploaded portrait as the main visual reference. Preserve the original facial features, hairstyle, skin texture, glasses, and natural recognizability without excessive retouching. Highlight the eyes, brows, nose, cheeks, and glossy pink lips with elegant close-up detail panels and subtle callout lines. Add a refined warm-neutral, rosy-pink, and soft-brown makeup color palette with small beauty swatches. Include concise sections for Makeup Steps, Best Makeup Looks, Key Products, and Quick Tips with minimal readable text. Use a premium Korean beauty-magazine aesthetic with clean typography, soft beige accents, dark editorial background, and balanced spacing. Make the final composition polished, sophisticated, photorealistic, and 9:16 vertical format, with the overall feeling of “Same You, Just More Polished.”
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2096914920915001598"></a>

### Candid smartphone photo of a young East Asian woman in a grey sweatshirt and jeans sitting on a sunny garden balcony terrace.

Author：[@Aqsahere\_](https://x.com/Aqsahere_) · [Source](https://x.com/Aqsahere_/status/2096914920915001598)

Character · Published

**Summary:** Candid smartphone photo of a young East Asian woman in a grey sweatshirt and jeans sitting on a sunny garden balcony terrace.

<img src="images/2096914920915001598-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
A completely natural, photorealistic candid smartphone photo of a young East Asian woman sitting comfortably cross-legged on a balcony garden terrace. She has long, naturally wavy dark brown hair falling loosely over her shoulders and down the front of her body, with soft individual strands moving naturally. Her features are delicate and realistic, with subtle natural makeup and authentic skin texture. She is wearing an oversized cozy light-gray sweatshirt with relaxed-fit light-blue jeans. Sitting casually and naturally, she gently rests one hand against her cheek while looking upward and slightly off to the side. Her expression feels genuinely cute and thoughtful, with a subtle slightly pouty look, as if the photo was captured during a quiet unposed moment. She sits on a light-colored outdoor terrace surface surrounded by lush green plants, leafy potted foliage, and small blooming pink flowers. A simple black metal balcony railing runs behind her, with dense trees and natural greenery filling the background. The setting feels peaceful, private, and like a real everyday garden balcony. Soft warm natural daylight falls gently across her face and clothing, creating realistic subtle shadows. Natural skin pores, authentic hair texture, realistic sweatshirt fabric, and believable denim details are clearly visible. Nothing looks overly polished or artificially posed. Shot as an authentic casual smartphone photograph with a natural eye-level perspective. Full-body seated composition, vertical framing, with the subject positioned slightly toward the lower-middle of the frame. The background has gentle natural depth of field—softly blurred while remaining clearly recognizable. Ultra-realistic photography, natural proportions, candid everyday moment, Korean-inspired casual fashion aesthetic, muted soft colors, subtle film grain, realistic lighting, slightly imperfect smartphone-camera details, 4K realism, no beauty-filter effect, no excessive retouching. Negative prompt: cartoon, anime, illustration, CGI, artificial-looking skin, plastic skin, excessive makeup, distorted facial features, extra fingers, malformed hands, extra limbs, incorrect anatomy, unnatural body proportions, stiff pose, oversaturated colors, dramatic studio lighting, blurry face, low resolution, watermark, text, logo.
```

[↑ Back to categories](#catalog)

---

<a name="prompt-2097157373936935051"></a>

### A Korean woman and a young girl in a hijab enjoy coffee at an outdoor café during golden hour, decorated with hand-drawn doodles.

Author：[@Lianaalane](https://x.com/Lianaalane) · [Source](https://x.com/Lianaalane/status/2097157373936935051)

Portrait / Selfie · Character · Food / Drink · Published

**Summary:** A Korean woman and a young girl in a hijab enjoy coffee at an outdoor café during golden hour, decorated with hand-drawn doodles.

<img src="images/2097157373936935051-1.jpg" alt="Image 1" width="480" />

**Prompt**

```text
A Korean girl with long, soft, dark brown hair is sitting at a cozy outdoor café during warm golden hour, gently holding a ceramic cup of coffee near her lips. She is wearing an elegant cream-colored ribbed cardigan with a fitted square neckline and matching high-waisted cream trousers, creating a soft and classy look. A small cream shoulder bag hangs naturally from her shoulder while she sits comfortably on a beautiful woven rattan chair. Beside her sits a cute little girl wearing a beige hijab, a modest cream blouse with delicate lace details, and a flowing brown skirt. The little girl is also holding a warm cup and looking happily toward the Korean girl. In front of them is a round marble café table with a cup of coffee, a freshly baked pastry, and a small glass vase filled with delicate white flowers. The background features lush green trees, a charming café exterior, warm sunlight, and beautiful cinematic bokeh. Add subtle white hand-drawn hearts, sparkles, and a smiling sun around them for a cute dreamy atmosphere, with highly detailed faces, natural expressions, soft lighting, photorealistic quality, and a cozy aesthetic.
```

[↑ Back to categories](#catalog)

---

[Explore Leadde.ai →](https://leadde.ai/?utm_source=github&utm_medium=readme&utm_campaign=prompt-library&utm_content=image2.5)
