
<script >
    const code = `javascript:!function(){"use strict";const e=document.getElementsByClassName("mobile-topbar-header-content non-search-mode cbox")[0];function t(){e.insertAdjacentHTML("beforeend",'<svg id="killButton" xmlns="http://www.w3.org/2000/svg" height="24" viewBox="0 -960 960 960" width="24"><path d="M480-80q-83 0-156-31.5T197-197q-54-54-85.5-127T80-480q0-83 31.5-156T197-763q54-54 127-85.5T480-880q83 0 156 31.5T763-763q54 54 85.5 127T880-480q0 83-31.5 156T763-197q-54 54-127 85.5T480-80Zm0-80q134 0 227-93t93-227q0-54-17.5-104T732-676L284-228q42 33 92 50.5T480-160ZM228-284l448-448q-42-33-92-50.5T480-800q-134 0-227 93t-93 227q0 54 17.5 104t50.5 92Z"/></svg>');const t=document.getElementById("killButton");t.style.width="45px",t.style.height="45px",t.style.fill="white",t.onclick=()=>{document.getElementById("movie_player").classList.contains("ad-showing","ad-interrupting")&&function(){const e=document.getElementsByClassName("video-stream html5-main-video")[0],t=e.duration;e.currentTime=t+1}()}}function n(){document.querySelectorAll("ad-slot-renderer").forEach((e=>{e.style.display="none"}))}new MutationObserver(((e,o)=>{console.log(e),console.log("new video ?"),null==document.getElementById("killButton")&&(t(),n())})).observe(e,{attributes:!0,childList:!0,subtree:!0}),t(),document.head.insertAdjacentHTML("beforeend","<style>ytm-companion-slot.scwnr-content {display: none;}.mobile-topbar-header-sign-in-button{ display: none;}</style>"),setTimeout((()=>{n()}),1e3)}();`
    function copy(){ 
        const code = document.getElementById('code-block')
        code.select()
        code.setSelectionRange(0,99999999999)
        // navigator.clipboard.writeText(code.value)
        // navigator.clipboard.write(new ClipboardItem({ 'text/plain': 'potato'}))
    }
</script>


<textarea id="code-block">
    {code}
</textarea>
<button on:click={copy}>
    Select Bookmark Code
    
</button>


