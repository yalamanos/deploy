<template>
    <section class="newsletter">
        <h2>Be the first to receive offers and news</h2>

        <p>Enter your email address below, unsubscribe anytime</p>

        <div>
            <input 
                type="email"
                placeholder="Email address"
            >
            <button type="submit">Sign up</button>
        </div>
    </section>
</template>




<script>
export default {
    name: 'newsletter',
}
</script>




<style lang="scss">

.newsletter {
    padding: 100px 8px;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    background-image: url(~@/assets/images/newsletter.png);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;

    @media only screen and (min-width: 675px) {
        padding: 144px 8px;
    }

    h2 {
        font-family: 'Barriecito', cursive;
        font-size: 41px;
        color: #F1395F;
    }

    p {
        color: #fff;
        margin: 32px 0;

        @media only screen and (min-width: 675px) {
            margin: 40px 0;
        }
    }

    div {
        display: flex;
        flex-direction: column;
        align-items: center;

        @media only screen and (min-width: 675px) {
            flex-direction: row;
        }

        input {
            font-size: 14px;
            width: 230px;
            padding: 16px 24px;
            border-radius: 4px;
            border: 1px solid #1D2324;
            outline: none;
            margin-right: 0;

            &::placeholder {
                color: #1D2324;
            }

            @media only screen and (min-width: 675px) {
                margin-right: 16px;
            }
        }

        button {
            width: 280px;
            height: 51px;
            color: #fff;
            background: #F1395F;
            border-radius: 4px;
            cursor: pointer;
            border: 1px solid #1D2324;
            margin-top: 16px;
            outline: none;
            transition: .3s ease;

            &:hover {
                border-color: #F1395F;
                background: #1D2324;
            }

            @media only screen and (min-width: 675px) {
                width: 130px;
                margin-top: 0;
            }
        }
    }
}
    
</style>