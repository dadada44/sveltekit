<section class="hero">
    <img src="https://www.souepl.cz/wp-content/uploads/2016/10/logo_stredni-1.jpg" alt="">
    <h1>Welcome</h1>
    <p>
        ahoj
    </p>
    <div class="hero-buttons">
        <a href="/about">About</a>
        <a href="/" id="gost">About</a>
    </div>

</section>

<style>
    .hero{
        width: 100%;
        min-height: calc(100vh - 100px);
        max-width: 1300px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
    }

    .hero img{
        width: 250px;
    }

    .hero-buttons{
        display: flex;
        gap: 36px;
    }

    .hero-buttons a{
        color: blanchedalmond;
        background-color: #8b4b20;
        text-decoration: none;
        width: 150px;
        height: 50px;
        border-radius: 10px;
        justify-content: center;
        align-items: center;
        display: flex;
        font-size: large;
        font-family: Sans-serif;
        transition: ease .3s;
    }

    #gost{
        color: black;
        background: none;
        border: 1px solid black;
        transition: ease 0.5s;

    }

    #gost:hover{
        color: white;
        background: rgb(4, 97, 11);
        border: 1px solid ;
    }

    .hero-buttons a:hover{
        color: white;
        background: rgb(4, 97, 11);
    }

</style>


