### Hi there! 👋
Here are some ideas to get you started:

- 🔭 I’m currently working at **Advance Intelligence Group**
- 🌱 I’m currently learning about **Cloud, Software, and AI**
- 👯 I’m looking to collaborate on **Innovative AI and App Projects**
- 💬 Ask me about **API Development, Cloud, AI, and System Design**
- 📫 How to reach me: [linkedin.com/in/vn-phamviethung](https://www.linkedin.com/in/vn-phamviethung)
- 😄 Pronouns: **He/Him**
- ⚡ Fun fact: **No Fun**

<!-- Placeholder divs for stats and top languages -->
<div id="stats"></div>
<div id="top-langs"></div>

<!-- JavaScript to load GitHub stats based on color scheme -->
<script>
  const isDarkMode = window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches;

  const statsDiv = document.getElementById('stats');
  const topLangsDiv = document.getElementById('top-langs');

  const statsImage = document.createElement('img');
  const topLangsImage = document.createElement('img');

  if (isDarkMode) {
    statsImage.src = 'https://github-readme-stats.vercel.app/api?username=pham0084&theme=vue-dark&show_icons=true';
    topLangsImage.src = 'https://github-readme-stats.vercel.app/api/top-langs/?username=pham0084&hide_progress=true&theme=vue-dark';
  } else {
    statsImage.src = 'https://github-readme-stats.vercel.app/api?username=pham0084&theme=vue&show_icons=true';
    topLangsImage.src = 'https://github-readme-stats.vercel.app/api/top-langs/?username=pham0084&hide_progress=true&theme=vue';
  }

  statsDiv.appendChild(statsImage);
  topLangsDiv.appendChild(topLangsImage);
</script>
