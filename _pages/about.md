---
layout: about
title: About
permalink: /
subtitle: M.Sc. Student in Power Engineering.

profile:
  align: right
  image: Jida_Wang.jpg
  image_circular: false 
  more_info: >
    <div style="text-align: center !important; width: 100%;">
      <p style="margin-bottom: 0px; font-weight: bold;">Jida Wang</p>
      <p style="font-size: 0.9rem; margin-top: 2px;">(王骥达, Everett Somerville)</p>
    </div>

news: false 
latest_posts: false
selected_papers: flase
social: false 

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---
<!-- 安全的全局样式覆盖：深蓝色主题与 Times New Roman 字体 -->
<style>
  /* 强制替换网页主题色为深蓝色 */
  :root, html[data-theme="dark"] {
    --global-theme-color: #4169E1 !important;
    --global-hover-color: #4169E1 !important;
    --global-hover-icon-color: #4169E1 !important;
  }
  
  /* 强制替换主页所有元素的字体为 Times New Roman */
  body, p, a, div, span, li, td, th, h1, h2, h3, h4, h5, h6, strong, em {
    font-family: "Times New Roman", Times, serif !important;
  }
</style>
<style>
  p {
    text-align: justify !important;
  }
</style>
<div class="social" style="text-align: left !important; margin-top: -10px !important; margin-bottom: 20px !important;">
  <div class="contact-icons" style="font-size: 0.5rem !important;">
    
    <a href="mailto:JWANG115@e.ntu.edu.sg" target="_blank" title="JWANG115@e.ntu.edu.sg" style="font-size: 0.85rem !important; margin-right: 12px !important; text-decoration: none !important; display: inline-flex !important; align-items: center !important; gap: 4px !important;">
      <i class="fas fa-envelope" style="font-size: 0.85rem !important;"></i> JWANG115@e.ntu.edu.sg
    </a>
    
    <a href="https://scholar.google.com/citations?hl=en&user=qsJbwesAAAAJ" target="_blank" title="Google Scholar" style="font-size: 0.85rem !important; margin-right: 12px !important; text-decoration: none !important; display: inline-flex !important; align-items: center !important; gap: 4px !important;">
      <i class="ai ai-google-scholar" style="font-size: 0.85rem !important;"></i> Google Scholar
    </a>

    <a href="https://github.com/Karphlorth" target="_blank" title="GitHub" style="font-size: 0.85rem !important; margin-right: 12px !important; text-decoration: none !important; display: inline-flex !important; align-items: center !important; gap: 4px !important;">
      <i class="fab fa-github" style="font-size: 0.85rem !important;"></i> GitHub
    </a>

    <a href="https://www.linkedin.com/in/jida-wang-6a9137391/" target="_blank" title="LinkedIn" style="font-size: 0.85rem !important; margin-right: 12px !important; text-decoration: none !important; display: inline-flex !important; align-items: center !important; gap: 4px !important;">
      <i class="fab fa-linkedin" style="font-size: 0.85rem !important;"></i> LinkedIn
    </a>
    
    <a href="{{ '/assets/pdf/Jida_Wang_s_CV.pdf' | relative_url }}" target="_blank" title="Curriculum Vitae" style="font-size: 0.85rem !important; text-decoration: none !important; display: inline-flex !important; align-items: center !important; gap: 4px !important;">
      <i class="ai ai-cv" style="font-size: 0.85rem !important;"></i> Curriculum Vitae
    </a>
    
  </div>
</div>


Greetings!

I am an M.Sc. student in Power Engineering at [Nanyang Technological University, Singapore](https://www.ntu.edu.sg/)(NTU). Previously, I obtained my B.Sc. in Electrical Engineering and Automation from [Beijing Institute of Technology](https://www.bit.edu.cn/)(BIT). Also, I am a researcher in Electrical Engineering, with a strong focus on smart grid, renewable energy systems, and advanced control, optimisation, AI/digitalisation of sustainable power grids.
 
Currently, I am conducting research on the Vulnerability Analysis of Renewable-Integrated Power Grids under False Data Injection Attacks (FDIA) and Resilience Enhancement in Sustainable Power Grids via Mamba-Driven Anomaly Detection at NTU, Singapore under the supervision of [Dr. Yan Xu](https://eexuyan.github.io/soda/index.html) and [Dr. Ziming Yan](https://zm-learn.github.io/home/). In the meantime, I am working as an Energy Analytics, Digital Operations and Electricity Market Trading Intern at [Crystal Clear Environmental Pte Ltd](https://www.crystalclear.com.sg/), Singapore.

---

<!-- 把这行代码放在你想要跳转的“简历/教育”部分的开头 -->
<h2>Research Interests</h2>
(i) modelling, optimisation, AI/digitalisation of renewable-energy power systems

(ii) stability and control of renewable-energy power systems

(iii) data-analytics for smart grid applications and electricity market

---
<!-- 把这行代码放在“项目”部分的开头 -->
<h2 id="projects">Projects</h2>
(这里是你的项目内容...)

---
<!-- 把这行代码放在“发表文章”部分的开头 -->
<h2 id="publications">Publications</h2>


<!-- 绕过底层限制，使用 JS 强行接管并重构导航栏 -->
<script>
  document.addEventListener("DOMContentLoaded", function() {
    // 找到网页顶部的导航栏菜单容器
    var navUl = document.querySelector('#navbarNav ul.navbar-nav');
    if (!navUl) return;
    
    // 把右上角的 太阳/月亮 主题切换按钮先备份存起来
    var themeToggle = navUl.querySelector('.toggle-container');
    
    // 霸道清空系统自动生成的死板导航栏
    navUl.innerHTML = '';
    
    // 定义我们专属的“一页流”锚点菜单
    var menuItems = [
      { name: 'About', link: '{{ "/" | relative_url }}' },
      { name: 'CV', link: '{{ "/" | relative_url }}#cv' },
      { name: 'Projects', link: '{{ "/" | relative_url }}#projects' },
      { name: 'Publications', link: '{{ "/" | relative_url }}#publications' }
    ];

    // 按顺序把我们的菜单重新生成并塞进去
    menuItems.forEach(function(item) {
      var li = document.createElement('li');
      li.className = 'nav-item';
      var a = document.createElement('a');
      a.className = 'nav-link';
      a.href = item.link;
      a.innerText = item.name;
      li.appendChild(a);
      navUl.appendChild(li);
    });

    // 最后把主题切换按钮放回最右边，保证夜间模式功能正常
    if (themeToggle) {
      navUl.appendChild(themeToggle);
    }
  });
</script>

<style>
  html { scroll-behavior: smooth !important; }
  h2[id] { scroll-margin-top: 80px; }
</style>

