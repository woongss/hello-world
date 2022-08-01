<template>
<div class="container middlepost">
    <div class="row com"> 
        <div class="col-sm-6 comimg">
                <div class="imagebox01">이미지 박스</div>
        </div>
        <div class="col-sm-6 comtext">
                <div class="textbox01">
                    <h1>캐치프레이즈 텍스트</h1>
                </div>
        </div>
    </div>
    
</div>
    
</template>

<script>
export default {
    name: 'MainMiddle',

}
</script>

<style scoped>
.middlepost { 
height:500px;
}

.com {height:100%}

.comimg { height:400px; margin:auto 0;}
.comtext { height:200px; margin:auto 0;}
.imagebox01 {
margin: auto;
width: 400px; 
height: 100%;
background-color: rgb(255, 204, 204);
border-radius: 10px;}

</style>