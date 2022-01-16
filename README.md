

.nav-toggle {
    display: none;
}

.nav-toggle-label {
    display: none;
}


@media (max-width: 750px) {
    header {
        height: 80px;
        background-color: var(--primary-nav-bkd-clr);
        display: grid;
        text-align: center;
    }
    header .logo {
        font-size: 40px;
        position: fixed;
        left: 5%;
        top: 20px;
    }
    nav {
        background-color: grey;
    }
    .nav-toggle {
        display: block;
    }

    .nav-toggle-label {
        top: 0;
        right: 0;
        margin-right: 1em;
        border: 1px solid red;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .nav-toggle-label span,
    .nav-toggle-label::before,
    .nav-toggle-label::after {
        display: block;
        background-color: grey;;
        background: white;
        height: 2px;
        width: 2em;
    }

    nav ul {
        position: fixed;
        top: 80px;
        left: 0;
        background: grey;
        height: 100vh;
        width: 100%;
        display: none;
        text-align: center;
    }

    .nav-toggle:checked ~ nav ul {
        display: block;
    }

    nav ul li {
        margin: 40px 0;
    }
}

<input type="checkbox" id="nav-toggle" class="nav-toggle">
            