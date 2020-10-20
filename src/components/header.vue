<template>
    <header>
        <div class="wrapper">
            <a href="#">
                <img 
                    class="logo"
                    src="~@/assets/images/logo.svg" 
                    alt="Deploy logo"
                >
            </a>

            <ul>
                <li>
                    <a href="#">
                        <img src="~@/assets/images/favourites.svg" alt="Favourites icon">
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="~@/assets/images/account.svg" alt="Account icon">
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="~@/assets/images/basket.svg" alt="basket icon">
                    </a>
                </li>
            </ul>
        </div>
    </header>
</template>




<script>
export default {
    name: 'siteHeader',
}
</script>




<style lang="scss">

header {
    position: relative;
    padding: 20px 0;

    .wrapper {
        display: flex;
        align-items: center;
        justify-content: space-between;

        .logo {
            width: 140px;

            @media only screen and (min-width: 675px) {
                width: 182px;
            }
        }

        ul {
            display: flex;
            padding-inline-start: 0;

            li {
                list-style: none;
                margin: 0 8px;

                &:last-of-type {
                    margin-right: 0;
                }

                img {
                    transition: .3s ease;
                }

                &:hover {
                    img {
                        opacity: .5;
                    }
                }

                @media only screen and (min-width: 675px) {
                    margin: 0 16px;
                }
            }
        }
    }
}

</style>