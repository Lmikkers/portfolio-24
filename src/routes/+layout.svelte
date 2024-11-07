<!-- Navigation -->
 <nav>
    <section>
        <a href="/"><img src="" alt="Logo van Larissa Mikkers"></a>
        <p>Amsterdam | 14:00 | 8°C</p>
    </section>

    <ul>
        <li><a aria-label="projecten" href="/">Projecten</a></li>
        <li><a aria-label="blog i love web" href="/">i-love-web</a></li>
        <li><a aria-label="contact" href="/">Contact</a></li>
    </ul>
 </nav>

<slot></slot>

<!-- Footer -->
<footer>
    <ul>
        <li><a href="/contact">Contact</a></li>
        <li>©2024 Larissa Mikkers</li>
        <li><a href="/sitemap">Sitemap</a></li>
    </ul>
</footer>

<style>
    nav {
        width: 100vw  ;
        position: fixed;
        display: flex;
        justify-content: space-between;
    }

    footer {
        width: 100%;
        height: 4rem;
        background-color: rgb(239, 239, 239);
        display: flex;
        justify-content: center;
    }
    nav ul,
    footer ul {
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center;
        gap: 1rem;
        list-style: none;
    }
</style>