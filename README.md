<div class="custom-github-banner-wrapper">
  <style>
    /* 1. Base Wrapper for the entire banner area */
    .custom-github-banner-wrapper {
      --github-dark-bg: #0d1117; /* Replicates GitHub's native dark mode background */
      width: 100%;
      min-height: 250px;
      margin: 0;
      padding: 0;
      border-radius: 6px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      background-color: var(--github-dark-bg);
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Noto Sans", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
    }

    /* 2. Content Overlay (Text and Header) - Ensures text merges into the BG */
    .custom-github-banner-content {
      padding: 24px;
      color: #c9d1d9; /* White-ish text for dark mode */
      position: relative;
      z-index: 10;
      pointer-events: none; /* Allows interactions with underlying animations */
    }

    .custom-github-banner-content h1 {
      margin-top: 0;
      font-size: 32px;
      color: #f0f6fc;
      border-bottom: 1px solid rgba(139, 148, 158, 0.4);
      padding-bottom: 10px;
    }

    .custom-github-banner-content p {
      margin: 4px 0;
      font-size: 16px;
    }

    /* 3. Live Animated Scene Container */
    .custom-github-scene {
      width: 100%;
      height: 180px; /* Scene height, distinct from text area */
      position: relative;
      overflow: hidden;
      margin-bottom: 24px;
    }

    /* 4. Layer 1: Pixelated Bamboo Forest Background */
    .custom-github-scene-bamboo-forest {
      position: absolute;
      top: 0;
      left: 0;
      width: 200%; /* Wider than container for tiling */
      height: 100%;
      /* REPLACEME: Link to your tileable pixelated bamboo forest image */
      background-image: url("REPLACEME_TILEABLE_BAMBOO_URL");
      background-size: repeat-x;
      background-repeat: repeat-x;
      animation: custom-scrolling-bamboo 60s linear infinite;
      z-index: 1;
      image-rendering: pixelated; /* Essential for crisp pixel art */
    }

    @keyframes custom-scrolling-bamboo {
      0% { background-position: 0 0; }
      100% { background-position: -100% 0; }
    }

    /* 5. Layer 2: Hanging Panda Sprite */
    .custom-github-scene-panda {
      position: absolute;
      /* REPLACEME: Link to your pixelated hanging panda image */
      background-image: url("REPLACEME_PANDA_SPRITE_URL");
      background-size: cover;
      width: 80px; /* Adjust based on your asset size */
      height: 120px; /* Adjust based on your asset size */
      image-rendering: pixelated;
      z-index: 5;
      /* Position panda initially off-screen right */
      right: -100px;
      top: 20%;
      animation: custom-hanging-panda 30s linear infinite;
    }

    @keyframes custom-hanging-panda {
      0% { transform: translateX(120%) translateY(0); }
      15% { transform: translateX(80%) translateY(0); }
      /* Simulates slight swaying while hanging */
      20% { transform: translateX(70%) translateY(-2px); }
      25% { transform: translateX(60%) translateY(2px); }
      30% { transform: translateX(50%) translateY(0); }
      70% { transform: translateX(-50%) translateY(0); }
      100% { transform: translateX(-150%) translateY(0); }
    }
  </style>

  <div class="custom-github-banner-content">
    <h1>About Me:</h1>
    <p>Hey there, It's Avishek</p>
    <p>Aspiring AI&ML Engineer</p>
    <p>OUTR CSE(AI&ML)'29</p>
  </div>

  <div class="custom-github-scene">
    <div class="custom-github-scene-bamboo-forest"></div>
    <div class="custom-github-scene-panda"></div>
  </div>
</div>

## 🌐 Socials:
[![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:avishekkk402@gmail.com) 

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=Avishekkk-Mohanty&theme=shadow_blue&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=Avishekkk-Mohanty&theme=shadow_blue&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Avishekkk-Mohanty&theme=shadow_blue&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=Avishekkk-Mohanty&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
