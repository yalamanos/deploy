<template>
    <section class="about wrapper">
        <h1>About us</h1>

        <img 
            class="about-hero"
            src="~@/assets/images/about.png" 
            alt="About us image"
        >

        <div class="inset">
            <h2>The inception of :Deploy eCommerce</h2>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vulputate auctor tortor nibh sit eu lorem. Condimentum tortor felis scelerisque quis pellentesque eget elementum. Vel ac aliquet neque sit urna et. Et scelerisque sit id in donec eget nunc. Cras purus venenatis amet nibh nunc ultricies.
            </p>
        </div>

        <div class="boxes">
            <div class="box">
                <img 
                    src="~@/assets/images/process.png" 
                    alt="Our process image"
                >
                <h2>Our process</h2>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vulputate auctor tortor nibh sit eu lorem. Condimentum tortor felis scelerisque quis pellentesque eget elementum. Vel ac aliquet neque sit urna et. Et scelerisque sit id in donec eget nunc. Cras purus venenatis amet nibh nunc ultricies.
                </p>
            </div>

             <div class="box">
                <img 
                    src="~@/assets/images/people.png" 
                    alt="Our process image"
                >
                <h2>Our people</h2>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vulputate auctor tortor nibh sit eu lorem. Condimentum tortor felis scelerisque quis pellentesque eget elementum. Vel ac aliquet neque sit urna et. Et scelerisque sit id in donec eget nunc. Cras purus venenatis amet nibh nunc ultricies.
                </p>
            </div>
        </div>
    </section>
</template>




<script>
export default {
    name: 'about',
}
</script>




<style lang="scss">

.about {
    padding: 40px 8px;

    @media only screen and (min-width: 675px) {
        padding: 80px 8px;
    }

    h1 {
        margin-bottom: 40px;

        @media only screen and (min-width: 675px) {
            margin-bottom: 80px;
        }
    }

    .about-hero {
        width: 100%;
    }

    .inset {
        max-width: 596px;
        margin: 16px auto 0;

        @media only screen and (min-width: 675px) {
            margin: 24px auto 0;
        }

        h2 {
            margin-bottom: 8px;
        }
    }

    .boxes {
        display: flex;
        flex-direction: column;
        margin: 40px 0 0;

        @media only screen and (min-width: 675px) {
            flex-direction: row;
            justify-content: space-between;
            margin: 80px 0 0;
        }

        .box {
            flex-basis: 48%;

            &:first-of-type {
                margin-bottom: 32px;

                @media only screen and (min-width: 675px) {
                    margin-bottom: 0;
                }
            }

            img {
                width: 100%;
            }

            h2 {
                margin: 24px 0 16px;

                @media only screen and (min-width: 675px) {
                    margin: 16px 0 8px;
                }
            }
        }
    }
}
    
</style>