<!-- Centered image -->
<p align="center">
  <img src="https://files.catbox.moe/8x81ut.jpg" alt="Queen Ashi MD Lite" width="300"/>
</p>

<!-- Typing effect -->
<h1 align="center">
  <span id="typing"></span>
</h1>

<!-- Optional description -->
<p align="center">
  Welcome to <strong>Queen Ashi MD Lite</strong> project! 💖
</p>

<!-- Adding script for typing effect -->
<script>
  const text = "Queen Ashi MD Lite";
  let index = 0;
  function type() {
    if(index < text.length){
      document.getElementById("typing").innerHTML += text.charAt(index);
      index++;
      setTimeout(type, 200); // Change speed here
    }
  }
  type();
</script>
