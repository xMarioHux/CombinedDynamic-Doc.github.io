请选择语言 Please select a language:</br>
<select name="language" id="language">
    <option value="zh_CN">简体中文</option>
    <option value="en_US">English</option>
</select></br>
<button id="check">OK</button>

<script>
    const lang = document.getElementById("language")
    function check(){
        window.location.href = `./${lang.value}/index.md`;
    }
    button.addEventListener("check", check);
</script>