
<template>
    <div class="home-main">
         <div class="get-start">
            <div><div class="get-start-content">
                <h1>More than just shorter links</h1>
                <p>Build your brand's recognition and get detailed insight on how your links are performing.</p>
                <Button class="button-custom">GetStart</Button>
            </div>
            </div>
           <div> <img alt="illustration" src="../assets/images/illustration-working.svg"></div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'GetStart',
        props: {
            msg: String,
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

</style>

<!--const GetStart = (props) => {-->
<!--return<div className="get-start">-->
<!--    <div> <GetStartContents/></div>-->
<!--    <div><img src={illustSvg} /> </div>-->
<!--</div>;-->
<!--}-->
<!--export default GetStart;-->

<!--const GetStartContents = (props) => {-->
<!--return<>-->
<!--<div className="get-start-content">-->
<!--    <h1>More than just shorter links</h1>-->
<!--    <p>Build your brand's recognition and get detailed insight on how your links are performing.</p>-->
<!--    <Button className='cust'>GetStart</Button>-->
<!--</div>-->
<!--</>;-->
<!--}-->