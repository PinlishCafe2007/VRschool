<svelte:head>
    <title>Виртуальная экскурсия</title>
</svelte:head>

<div class='container'>
    <div class='info'>
        <div class='animate-background'>
            <div class='container info-container'>
                <div class='info-text'>
                    <h1>
                    <p class='animate-text-1'>Виртуальная экскурсия</p>
                    <p class='text-2'>по МБОУ "СОШ №26" г. Абакана</p>
                    </h1>
                </div>
                <h2 class='subtitle'>
                    Сейчас мы покажем вам нашу школу. Мы постарались описать кабинеты, залы и коридоры так, чтобы вы как будто очутились внутри.
                </h2>
                <div style='color:black' class='scroll-button animate-scroll' tabindex='0'>
                    <a href='/first'>Начать</a>
                    <div class='arrow'>→</div>
                </div>
            </div>
        </div>
    </div>
</div>
<div class='background-div'></div>

<style>
    .info {
        text-align: center;
        position: relative;
    }
    .info-container {
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: left;
        align-items: start;
    }
    .container {
        max-width: 1200px;
        margin: 150px 0 25px 2.5rem;
    }
    .info h1 {
        font-size: 4rem;
        margin: 0;
    }
    .info h1 p {
        position: relative;
        font: inherit;
        margin: 0;
        text-align: left;
        line-height: 130%;
        width: fit-content;
        font-weight: 800;
        letter-spacing: -0.03em;
    }
    .info h2 {
        max-width: 65ch;
        font-weight: 200;
        margin-top: 0.50rem;
    }
    .background-div {
        background-color: #87CEEB;
        width: 100%;
        height: 56vh;
        margin: -205px auto;
    }
    .info .info-text {
        position: relative;
    }
    .scroll-button {
        display: flex;
        border: none;
        outline: none;
        cursor: pointer;
    }
    .scroll-button .arrow {
        margin-left: 0.50rem;
    }
</style>