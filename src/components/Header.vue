<template>
    <header>
        <div class="header container">
            <a href="#">
                <img src="@/assets/img/dc-logo.png" alt="Logo DC">
            </a>

            <div class="lista-header">
                <ul>
                    <li>
                        <a href="#">Characters</a>
                    </li>
                    <li>
                        <a href="#">Comic</a>
                    </li>
                    <li>
                        <a href="#">Movies</a>
                    </li>
                    <li>
                        <a href="#">Tv</a>
                    </li>
                    <li>
                        <a href="#">Games</a>
                    </li>
                    <li>
                        <a href="#">Collectibles</a>
                    </li>
                    <li>
                        <a href="#">Videos</a>
                    </li>
                    <li>
                        <a href="#">Fans</a>
                    </li>
                    <li>
                        <a href="#">News</a>
                    </li>
                    <li>
                        <a href="#">Shop</a>
                    </li>

                </ul>
            </div>

        </div>
    </header>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style>
.container{
    max-width: 1170px;
    margin: 0 auto;
}

.header{
    display: flex;
    align-items: center;
    flex-basis: 100%;
    padding: 1rem;
    font-family: sans-serif;
}

.lista-header{
    display: flex;
    justify-content: flex-end;
    flex-basis: 100%;
}

.lista-header ul{
    display: flex;
    list-style: none;
}

.lista-header ul a{
    text-decoration: none;
    color: #000;
    font-weight: bold;
    margin-left: 1rem;
}

</style>