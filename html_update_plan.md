# HTML Update Plan

## Objectives
- Insert images into corresponding HTML files based on the image allocation plan
- Keep existing HTML content unchanged (only add images)
- Prepare for GitHub Pages deployment with iframe usage

## Task List

### 1. Check HTML File Structure
- Review current content and structure of all 5 HTML files
- Identify appropriate locations for image insertion

### 2. Update page1_home_text_en_only.html
- Insert 首页.jpg as main banner/background
- Insert 宫崎骏.jpg or 宫崎骏1.jpg for Miyazaki's portrait
- Add English alt attributes

### 3. Update page2_about.html
- Insert 宫崎骏.jpg or 宫崎骏1.jpg in biography section
- Add English alt attribute: "Hayao Miyazaki"

### 4. Update page3_films.html
- Insert 8 movie images:
  - 千与千寻.jpg - alt: "Spirited Away"
  - 哈尔的移动城堡1.jpg - alt: "Howl's Moving Castle"
  - 天空之城.jpg - alt: "Castle in the Sky"
  - 幽灵公主.jpg - alt: "Princess Mononoke"
  - 悬崖上的金鱼姬.jpg - alt: "Ponyo"
  - 起风了.jpg - alt: "The Wind Rises"
  - 魔女宅急便.jpg - alt: "Kiki's Delivery Service"
  - 龙猫.jpg - alt: "My Neighbor Totoro"

### 5. Update page4_analysis.html
- Insert 7 analysis images:
  - spirited_away_wordcloud.png
  - character_network.png
  - character_frequency.png
  - sentiment_analysis.png
  - sentiment_timeline.png
  - code.png
  - parsing_code_sample.png

### 6. Update page5_project.html
- Add appropriate images (Miyazaki photos or overview images)

## Important Notes
- Use relative paths for all images
- Maintain all English content
- Do not modify existing HTML structure
- Only add new content where necessary
- Ensure compatibility for iframe deployment
- All images should have descriptive English alt attributes

## Deployment Info
Files will be deployed to GitHub Pages and accessed via:
```html
<iframe 
  src="https://eva-039.github.io/home/page1_home_text_en_only.html" 
  width="100%" 
  height="800px" 
  style="border:none;">
</iframe>
```