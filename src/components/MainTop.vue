<template>
    <div class="container toppanel">
        <div class="col-6 topimage ">
                <img src="@/assets/images/test.jpeg">
            </div>  
        <div class="row text01">
            <div class="col-6 infotext">
                <h1>메인탑 텍스트 입니다.</h1>
                <p>메인탑 서브 텍스트 입니다.</p>
                 <div class="subinfo">
                    <h2>메인탑 텍스트 입니다.</h2>
                    <p>메인탑 서브 텍스트 입니다.</p>

                    <h2>메인탑 텍스트 입니다.</h2>
                    <p>메인탑 서브 텍스트 입니다.</p>
        </div>   
            </div>                  
        </div>
              
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

.row {z-index:10;}
.toppanel{
    min-height: 93vh;
    background-color: rgb(255, 255, 255);
    display:grid;
}
.text01{margin: auto 0;}

.infotext h1{ font-size:50px;}

.infotext p{ font-size:20px;}

.topimage {display:contents;}

.topimage img { position: absolute;
    width:100%;
    right: 0px;
    width: 900px;
    height:700px;
}

.subinfo{
    margin-top: 50px;
    margin-bottom: 0px;
}
</style>