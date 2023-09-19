# Rusted_Ambition_tutorial
<button id="toggleLanguage">切换语言</button>

<script>
  const toggleButton = document.getElementById('toggleLanguage');
  const chineseContent = document.getElementById('chineseContent');
  const englishContent = document.getElementById('englishContent');
  
  let isChinese = true; // 初始为中文版本
  
  toggleButton.addEventListener('click', () => {
    if (isChinese) {
      chineseContent.style.display = 'none';
      englishContent.style.display = 'block';
      isChinese = false;
    } else {
      chineseContent.style.display = 'block';
      englishContent.style.display = 'none';
      isChinese = true;
    }
  });
</script>
