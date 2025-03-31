document.addEventListener("DOMContentLoaded", function() {
    const btn = document.querySelector(".btn");

    btn.addEventListener("mouseover", function() {
        btn.style.backgroundColor = "#ffeb3b";
    });

    btn.addEventListener("mouseout", function() {
        btn.style.backgroundColor = "yellow";
    });
});
