<div class="box">
    <header>
        <slot name="header" />
    </header>
    <article>
        <slot name="body" />
    </article>
    <footer>
        <slot name="footer" />
    </footer>
</div>

<style>
    .box {
        text-align: center;
        width: 300px;
        border: 2px solid #aaa;
        border-radius: 40px;
        padding: 2rem;
        background: white;
    }
</style>
