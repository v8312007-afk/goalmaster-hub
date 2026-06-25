function toggleBox(id){
    const el = document.getElementById(id);
    el.style.maxHeight = el.style.maxHeight ? null : el.scrollHeight + "px";
}

function buy(product){
    const text = encodeURIComponent("Привет! Хочу купить: " + product);
    window.open("https://t.me/Isatra73?text=" + text, "_blank");
}
