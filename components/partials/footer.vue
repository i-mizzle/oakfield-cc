<template>
    <footer>
        <section class="half">
            <div class="container">
                <div class="row">
                    <div class="col-lg-1"></div>
                    <div class="col-lg-5 col-md-5 col-xs-12">
                        <h5>Contact us</h5>
                        <form>
                            <input type="text" placeholder="your name" required>
                            <input type="email" placeholder="your email address" required>
                            <textarea placeholder="your message"></textarea>
                            <button type="submit"> Send a message </button>
                        </form>

                    </div>
                    <div class="col-lg-5 col-md-5 col-xs-12 text-right">
                        <h5>Find us here</h5>
                        <div class="contact-block">
                            <img src="../../assets/img/location.png">
                            <p>Suite 102, No. 6 Sapele Street, Off Ladoke Akintola Boulevard, <br>Garki II,
                                Abuja.
                            </p>
                        </div>
                        <div class="contact-block">
                            <img src="../../assets/img/mail.png">
                            <p>info@oakfieldcc.com.ng</p>
                        </div>
                        <div class="contact-block">
                            <img src="../../assets/img/phone.png">
                            <p>(+234) 813 647 6696</p>
                        </div>

                        <ul class="socials">
                            <li>
                                <a href="" target="_blank"><img src="../../assets/img/fb.png"></a>
                            </li>
                            <li>
                                <a href="" target="_blank"><img src="../../assets/img/tw.png"></a>
                            </li>
                            <li>
                                <a href="" target="_blank"><img src="../../assets/img/in.png"></a>
                            </li>
                        </ul>
                        
                    </div>
                    <div class="col-md-12 text-center">
                        <p class="copy">&copy; 2019 Property of Oakfield Consulting Chambers. All rights reserved.</p>
                    </div>
                </div>
            </div>
        </section>
    </footer>
</template>

<script>

export default {
  components: {
  },
}
</script>

<style scoped>

    footer{
        padding:100px;
        background-color: #131313;
    }

    .contact-block{
        padding-bottom:20px;
        clear: both;
        position: relative;
        overflow: hidden;
    }

    .contact-block img{
        float: right;
        margin-left: 10px;
        margin-bottom:10px;
    }

    .contact-block p{
        color:#ffffffb4;
        width: 85%;
        float: right;
    }

    p.copy{
        margin-top:50px;
        font-size: 0.8em;
        color:#ffffff59;
    }

    h5{
        color: #ffffffda;
        margin-bottom: 20px;
    }

    ul.socials{
        list-style: none;
        margin-left:0;
    }

    ul.socials li {
        float:right;
        margin-left:0;
        margin-left:10px;
    }

    ul.socials li a img{
        width:40px;
    }

    input[type=text], input[type=email], textarea{
        background-color: #1e1d1d;
        color:#ffffffe3;
        font-size:0.8em;
        border:none;
        padding:15px;
        width:100%;
        margin-bottom:15px;
        outline:none;
        transition: all 200ms ease;
        font-family: 'Poppins', sans-serif;
    }

    input[type=text]:focus, input[type=email]:focus, textarea:focus{
        background-color: #363636;
    }

    button{
        color: #1e1d1d;
        background-color:#3FBEEB;
        font-size:0.8em;
        border:none;
        padding:15px;
        margin-bottom:15px;
        outline:none;
        transition: all 200ms ease;
        font-family: 'Poppins', sans-serif;
    }
    button:hover{
        background-color:#15556d;
        color: #fff;
    }

    textarea{
        height:100px;
        resize:none;
    }

    img.qrcode{
        width:90%;
    }

    @media screen and (max-width: 1024px) {
        section{
            background-size:50%;
        }

        .contact-block p{
            font-size:0.8em;
        }

        ul.socials li a img{
            width:20px;
        }
    }

    @media screen and (max-width: 768px) {
        footer{
            padding:30px;
            background-color: #1a1919;
        }
        h5{
            margin-bottom: 20px;
            margin-top: 20px;
        }

    }

</style>
