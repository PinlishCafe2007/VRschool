<nav>
    <div class="nav-container">
        <a href="/" class="nav-logo" title="Back to Homepage">Главная страница</a>
        <div class="nav-links">
            <a href="/first" class="link">Первый этаж</a>
            <a href="/second" class="link">Второй этаж</a>
            <a href="/third" class="link">Третий этаж</a>
        </div>
    </div>
</nav>

<div class="container">
    <!-- Pages will be injected below -->
    <slot></slot>
</div>

<style>
    .container {
        max-width: 1400px;
        margin: 50px auto;
    }
</style>