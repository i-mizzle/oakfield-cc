<template>
    <section class="half flex-display">
        <div>
            <div class="container">
                <div class="row">
                    <div class="col-md-6 ml-auto mr-auto text-center">
                        <h4>Have any legal problems?</h4>
                        <p>Here at Oakfield Consulting Chambers, We are always ready to listen... go ahead, get in touch for a consultation</p>
                        <a href="">Contact us </a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>

export default {
  components: {
  },
}
</script>

<style scoped>
    section{
        background-color: #1B1A1A;
        justify-content: center;

    }

    h5, h4{
        color: #ffffffda;
        margin-bottom: 20px;
        font-family: 'Poppins', sans-serif;
        font-weight: 700;
    }

    p{
        color:#ffffffd3;
    }

    a{
        color: #1e1d1d;
        background-color:#3FBEEB;
        font-size:0.8em;
        border:none;
        padding:15px;
        margin-bottom:15px;
        outline:none;
        transition: all 200ms ease;
        font-family: 'Poppins', sans-serif;
        border-radius: 3px;
        display: inline-block;
        margin-top: 20px;
        text-decoration: none;
    }
    a:hover{
        background-color:#15556d;
        color: #fff;
    }

</style>
