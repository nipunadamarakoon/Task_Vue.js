<template>
    <div class="nav">
        <nav className='nav-bar'>

                <div>
                    <ul>
                            <li><img alt="logo" src="../assets/images/logo.svg"></li>
                            <li><h3>Featurers</h3></li>
                            <li><h3>Pricing</h3></li>
                            <li><h3>Resources</h3></li>
                            <li><h3>Login</h3></li>
                            <li><Button class="button-custom">Sign up</Button></li>
                    </ul>
                </div>
        </nav>


    </div>
</template>

<script>
    export default {
        name: 'Navbar',
        props: {
            msg: String,
            hey: String,
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h3 {
        margin: 25px 0 0;
    }
    ul {
        list-style-type: none;
        padding-top: 25px;

    }
    li {
        display: inline-block;
        margin: 0 10px;
    }
    a {
        color: #42b983;
    }



    /*nav-bar{*/
    /*    display:flex;*/
    /*    width: 100%;*/
    /*    min-height: 100px;*/
    /*    justify-content: center;*/
    /*}*/
</style>