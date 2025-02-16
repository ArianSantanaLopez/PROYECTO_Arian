const enlaces = document.querySelectorAll('nav ul li a');

enlaces.forEach(enlace => {
    enlace.addEventListener('mouseover', () => {
        enlace.style.color = 'gold';
    });
    enlace.addEventListener('mouseout', () => {
        enlace.style.color = 'white';
    });
});

document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});
