<!-- 使用 HTML 定义容器 -->
<div style="display: flex; gap: 20px;">
  <!-- 左侧部分：头像和基本信息 -->
  <div style="flex: 1;">
    <img src="https://github.com/HanlardResearch/HanlardResearch.github.io/blob/main/tx.jpg"  alt="Your Profile Picture" width="200" height="200" style="border-radius: 50%;">

    <!-- 基本信息 -->
    <h3>张 晗</h3>
    <p>鹏城国家实验室</p>
    <p>哈尔滨工业大学</p>

    <!-- 联系方式 -->
    <ul style="list-style-type: none; padding: 0;">
      <li><i class="fas fa-map-marker-alt"></i> 深圳, 中国</li>
      <li><i class="fas fa-envelope"></i> <a href="mailto:HanlardResearch@gmail.com">Email</a></li>
      <li><i class="fab fa-google-scholar"></i> <a href="https://scholar.google.com/citations?user=lhdgPb8AAAAJ&hl=zh-CN">Google Scholar</a></li>
    </ul>
  </div>

  <!-- 右侧部分：自我介绍和论文列表 -->
  <div style="flex: 2;">

  {% include_relative intro.md %}
  
  {% include_relative pub.md %}
  
  {% include_relative coauthor.md %}
  
  {% include_relative other.md %}
