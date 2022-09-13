<template>
    <div class="content-main">
        <!--<hr id="linha-um">
        <hr class="linha-dois">
        -->
        <div class="content-one">
            <div class="alinhar-texto">
                <h3>Modelagem de Software</h3>
                <p>Lorem ipsum is placeholder text commonly used in the graphic, print, and publishing industries for previewing layouts and visual mockups.</p>
            </div>
        </div>

        <div class="content-two">
            <div class="alinhar-texto">
                <h3>Testes automatizados</h3>
                <p>Lorem ipsum is placeholder text commonly used in the graphic, print, and publishing industries for previewing layouts and visual mockups.</p>
            </div>
        </div>

        <div class="content-three">
            <div class="alinhar-texto"><h3>Desenvolvimento</h3>
            <p>Lorem ipsum is placeholder text commonly used in the graphic, print, and publishing industries for previewing layouts and visual mockups.</p></div>
        </div>
    </div>
    
</template>

<script>
    export default {
        name: 'Main'
    }
</script>

    

<style scoped>

.content-main {
    display: grid;
    grid-template-areas: 
    'content-one' 'content-one' 'content-one'
    'content-two' 'content-two' 'content-two'
    'content-three' 'content-three' 'content-three';
}

.content-one {
    display: grid;
    grid-area: content-one;
    background: blue;
}

.content-one .alinhar-texto {
    margin-left: 64px;
}

.content-one .alinhar-texto p{
    background: red;
    width: 30%;

}

.content-two {
    display: grid;
    grid-template-areas: 
    'alinhar-texto' 'alinhar-texto' 'alinhar-texto';
}

.content-two .alinhar-texto {
    background-color: brown;
    grid-area: alinhar-texto;
    justify-self: flex-end;
    display: grid;
}

.content-two .alinhar-texto p{
    background: red;
    width: 30%;
}
.content-three {
    display: grid;
    grid-area: content-three;
    background: blue;
}

.content-three .alinhar-texto {
    margin-left: 64px;
}

.content-three .alinhar-texto p{
    background: red;
    width: 30%;

}




</style>