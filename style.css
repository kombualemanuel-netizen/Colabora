/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

/* Variáveis de cor (Fáceis de mudar) */
:root {
    --bg-color: #0a0a0a;
    --text-color: #ffffff;
    --accent-color: #00ff88; /* Verde Neon */
    --card-bg: #1a1a1a;
}

body {
    background-color: var(--bg-color);
    color: var(--text-color);
    line-height: 1.6;
}

/* NAVBAR */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 5%;
    position: fixed;
    width: 100%;
    top: 0;
    background-color: rgba(10, 10, 10, 0.9);
    backdrop-filter: blur(10px); /* Efeito de vidro */
    z-index: 1000;
}

.logo {
    font-size: 28px;
    font-weight: bold;
    letter-spacing: 1px;
}

.logo span {
    color: var(--accent-color);
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 30px;
    align-items: center;
}

.nav-links a {
    text-decoration: none;
    color: var(--text-color);
    font-weight: 500;
    transition: color 0.3s;
}

.nav-links a:hover {
    color: var(--accent-color);
}

.btn-nav {
    background-color: var(--accent-color);
    color: #000 !important;
    padding: 10px 20px;
    border-radius: 5px;
    font-weight: bold;
}

/* HERO SECTION */
.hero {
    height: 100vh;
    display: flex;
    align-items: center;
    padding: 0 5%;
    background: linear-gradient(135deg, #0a0a0a 0%, #1a1a2e 100%);
}

.hero-content h1 {
    font-size: 4rem;
    line-height: 1.1;
    margin-bottom: 20px;
    max-width: 800px;
}

.highlight {
    color: var(--accent-color);
}

.hero-content p {
    font-size: 1.2rem;
    margin-bottom: 40px;
    max-width: 600px;
    color: #ccc;
}

.btn-primary {
    display: inline-block;
    background-color: var(--accent-color);
    color: #000;
    padding: 15px 30px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    transition: transform 0.3s;
}

.btn-primary:hover {
    transform: translateY(-3px);
}

/* SERVIÇOS */
.services, .portfolio {
    padding: 100px 5%;
}

.services h2, .portfolio h2 {
    font-size: 2.5rem;
    margin-bottom: 50px;
    text-align: center;
}

.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
}

.service-card {
    background-color: var(--card-bg);
    padding: 40px;
    border-radius: 10px;
    transition: transform 0.3s, box-shadow 0.3s;
    border-bottom: 3px solid transparent;
}

.service-card:hover {
    transform: translateY(-10px);
    border-bottom: 3px solid var(--accent-color);
    box-shadow: 0 10px 30px rgba(0, 255, 136, 0.1);
}

.service-card i {
    font-size: 2.5rem;
    color: var(--accent-color);
    margin-bottom: 20px;
}

.service-card h3 {
    margin-bottom: 15px;
    font-size: 1.5rem;
}

.service-card p {
    color: #aaa;
}

/* PORTFÓLIO */
.portfolio-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.portfolio-item {
    background-color: var(--card-bg);
    height: 300px;
    border-radius: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.5rem;
    font-weight: bold;
    color: #444;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}

.portfolio-item:hover {
    background-color: var(--accent-color);
    color: #000;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 40px;
    background-color: var(--card-bg);
    color: #888;
}

/* RESPONSIVIDADE (Telemóvel) */
@media (max-width: 768px) {
    .nav-links {
        display: none; /* Esconde o menu normal */
        flex-direction: column;
        position: absolute;
        top: 70px;
        left: 0;
        width: 100%;
        background-color: var(--card-bg);
        padding: 20px 0;
    }

    .nav-links.active {
        display: flex; /* Mostra o menu quando clicado */
    }

    .hamburger {
        display: block;
        font-size: 1.5rem;
        cursor: pointer;
    }

    .hero-content h1 {
        font-size: 2.5rem;
    }
}