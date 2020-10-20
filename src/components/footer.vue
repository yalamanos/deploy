<template>
    <footer>
        <div class="wrapper">
            <div class="links">
                <ul>
                    <li>
                        <a href="#">About Deploy</a>
                    </li>
                    <li>
                        <a href="#">Our Heritage</a>
                    </li>
                    <li>
                        <a href="#">Careers</a>
                    </li>
                    <li>
                        <a href="#">Press Area</a>
                    </li>
                </ul>

                <ul>
                    <li>
                        <a href="#">Customer Service</a>
                    </li>
                    <li>
                        <a href="#">Delivery</a>
                    </li>
                    <li>
                        <a href="#">Track your order</a>
                    </li>
                    <li>
                        <a href="#">Returns</a>
                    </li>
                    <li>
                        <a href="#">Size Guides</a>
                    </li>
                    <li>
                        <a href="#">Find a Stockist</a>
                    </li>
                    <li>
                        <a href="#">FAQs</a>
                    </li>
                    <li>
                        <a href="#">Contact Us</a>
                    </li>
                </ul>
            </div>

            <div class="legal">
                <p>
                    Deploy is a division of Attain Design Limited 
                    <br class="mobile-show">
                    © 2019 
                    <br class="mobile-show">
                    Company reg: 07227833
                    <br class="mobile-show">
                    VAT number: 993 0738 85
                </p>

                <ul>
                    <li>
                        <a href="#">Terms &amp; Conditions</a>
                    </li>
                    <li>
                        <a href="#">Privacy Policy</a>
                    </li>
                    <li>
                        <a href="#">Cookie Policy</a>
                    </li>
                </ul>
            </div>
        </div>
    </footer>
</template>




<script>
export default {
    name: 'siteFooter',
}
</script>




<style lang="scss">

footer {
    padding: 80px 0 40px;
    font-size: 14px;

    @media only screen and (min-width: 675px) {
        padding: 152px 0 72px;
    }

    ul {
        padding-inline-start: 0;
        li {
            list-style: none;
            a {
                color: #394953;
                text-decoration: none;
                transition: .3s ease;

                &:hover {
                    opacity: .5;
                }
            }
        }
    }

    .links {
        display: flex;

        @media only screen and (min-width: 675px) {
            justify-content: flex-start;
        }
        
        ul {
            flex-basis: 50%;

            @media only screen and (min-width: 675px) {
                flex-basis: 25%;
            }

            li {
                padding: 8px 0;
            }
        }
    }

    .legal {
        font-size: 12px;
        padding-top: 24px;
        margin-top: 72px;
        display: flex;
        flex-direction: column;
        border-top: 1px solid #C4C4C4;

        @media only screen and (min-width: 675px) {
            flex-direction: row;
            justify-content: space-between;
        }

        p {
            font-size: 12px;
            color: #394953;
        }

        ul {
            display: flex;
            flex-direction: column;

            @media only screen and (min-width: 675px) {
                flex-direction: row;
            }

            li {
                margin: 16px 0;

                @media only screen and (min-width: 675px) {
                    margin: 0 0 0 32px;
                }
            }
        }
    }
}
    
</style>