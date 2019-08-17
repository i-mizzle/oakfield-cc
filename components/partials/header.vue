<template>
<header>
    <div class="container-fluid">
        <div class="row top-row">
            <div class="col-md-6">
                <p>
                    <img src="../../assets/img/phone.png"><span class="phone">(+234) 813 647 6696</span>
                    <img src="../../assets/img/mail.png"><span class="email">info@oakfieldcc.com.ng</span>
                </p>
            </div>
        </div>
        <div class="row">
            <div class="col-md-12">
                <nav class="navbar navbar-expand-lg">
                    <a class="navbar-brand" href="#">
                        <img class="logo" src="../../assets/img/oakfield-logo.png" alt="Oakfield Consulting Chambers">
                    </a>
                    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                        <!-- <span class="navbar-toggler-icon"></span> -->
                        <img src="../../assets/img/menu.svg">
                    </button>
                    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                        <div class="navbar-nav ml-auto">
                            <a class="nav-item nav-link" href="#about">who we are</a>
                            <a class="nav-item nav-link" href="#services">our practice areas</a>
                            <a class="nav-item nav-link" href="#firm">the firm</a>
                            <a class="nav-item nav-link" href="#contact">get in touch</a>
                        </div>
                    </div>
                </nav>
            </div>
        </div>
    </div>
</header>
</template>

<script>

export default {
  components: {
  },
  data(){
      return {}
  }
}
</script>

<style scoped>
    header{
        position:absolute;
        top: 20px;
        left:0;
        width:100%;
        z-index:999;
        padding-left:5%;
        padding-right:5%;
    }
    nav{
        padding:10px 30px;
        background-color: #fff;
    }
    a.navbar-brand{
        width:15%;
        margin-left:20px;
    }

    img.logo{
        width:100%;
    }

    a.nav-link{
        color:#000;
        font-size: 1em;
        font-family: 'Poppins', sans-serif;
    }

    span.phone, span.email {
        margin-left: 10px;
        margin-right:10px;
        color:#ffffffd2;
    }

    button.navbar-toggler-icon{
        color:#fff;
        z-index: 999;
    }

    @media screen and (max-width: 768px) {
        .top-row{
            display:none;
        }
        header{
            position:absolute;
            top: 0;
            left:0;
            width:100%;
            z-index:999;
            padding-left:1%;
            padding-right:1%;
            background: #fff;
        }
         img.logo{
            width:300%;
            max-width: unset;
        }
        nav{
            background-color:transparent;
        }
        .navbar-nav{
            padding:15px 30px;
            background-color: #fff;
        }

    }
</style>
