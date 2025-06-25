<!-- 使用 HTML 定义容器 -->
<div style="display: flex; gap: 20px;">
  <!-- 左侧部分：头像和基本信息 -->
  <div style="flex: 1;">
    <img src="[https://example.com/your-profile-picture.jpg](https://github.com/HanlardResearch/HanlardResearch.github.io/blob/main/tx.jpg)"  alt="Your Profile Picture" width="200" height="200" style="border-radius: 50%;">

    <!-- 基本信息 -->
    <h3>Xiaoteng Ma</h3>
    <p>Tsinghua University</p>
    <p>PostDoc at Tsinghua University. Focusing on Reinforcement Learning.</p>

    <!-- 联系方式 -->
    <ul style="list-style-type: none; padding: 0;">
      <li><i class="fas fa-map-marker-alt"></i> Beijing, China</li>
      <li><i class="fas fa-envelope"></i> <a href="mailto:xiaoteng.ma@example.com">Email</a></li>
      <li><i class="fas fa-researchgate"></i> <a href="https://www.researchgate.net/profile/Xiaoteng_Ma">ResearchGate</a></li> 
      <li><i class="fas fa-database"></i> <a href="https://dblp.org/pid/m/XiaotengMa.html">DBLP</a></li> 
      <li><i class="fab fa-github"></i> <a href="https://github.com/xiaotengma">Github</a></li> 
      <li><i class="fab fa-google-scholar"></i> <a href="https://scholar.google.com/citations?user=example">Google Scholar</a></li>
      <li><i class="fas fa-id-card"></i> <a href="https://orcid.org/0000-0000-0000-0000">ORCID</a></li>
      <li><i class="fas fa-book-open"></i> <a href="https://zhuanlan.zhihu.com/xiaotengma">知乎</a></li>
    </ul>
  </div>

  <!-- 右侧部分：自我介绍和论文列表 -->
  <div style="flex: 2;">

  {% include_relative intro.md %}
  
  {% include_relative pub.md %}
  
  {% include_relative coauthor.md %}
  
  {% include_relative other.md %}
