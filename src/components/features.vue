<template>
    <div class="section-features">
        <div class="features">
            
            <div class="container-feature-one feature-item">
                <img  src="../assets/toggle-button-copy.png" class="icon-feature"></img>
                <div class="feature-item-description">
                    <h3 class="title-feature">Innovación</h3>
                    <p class="description-feature">Expertos creando productos innovadores que transforman tus ideas en soluciones.</p>
                </div>
            </div>

            <div class="container-feature-two feature-item">
                <img src="../assets/toggle-button.png" class="icon-feature"></img>
                <div class="feature-item-description">
                    <h3 class="title-feature">Seguridad</h3>
                    <p class="description-feature">Nuestros sistemas cuentan con capas de seguridad para proteger las bases de datos.</p>
                </div>
            </div>
        
        
            <div class="container-feature-one feature-item">
                <img src="../assets/toggle-button-copy.png" class="icon-feature"></img>
                <div class="feature-item-description">
                    <h3 class="title-feature">Tecnología</h3>
                    <p class="description-feature">Utilizamos herramientas de alta tecnologia para crear cosas asombrosas.</p>
                </div>
            </div>

            <div class="container-feature-two feature-item">
                <img src="../assets/toggle-button.png" class="icon-feature"></img>
                <div class="feature-item-description">
                    <h3 class="title-feature">Experiencia</h3>
                    <p class="description-feature">Contamos con un portafolio de proyectos que ha crecido con grandes casos de exito.</p>
                </div>
            </div>
        
        
            <div class="container-feature-one feature-item">
                <img src="../assets/toggle-button-copy.png" class="icon-feature"></img>
                <div class="feature-item-description">
                    <h3 class="title-feature">Consultoria</h3>
                    <p class="description-feature">Hacemos que tus productos y procesos sean aun mejores optimizando resultados.</p>
                </div>   
            </div>

            <div class="container-feature-two feature-item">
                <img src="../assets/toggle-button.png" class="icon-feature"></img>
                <div class="feature-item-description">
                    <h3 class="title-feature">Diseño</h3>
                    <p class="description-feature">Nos enfocamos en perfeccionar hasta el mas minimo detalle de nuestros productos</p>
                </div>
            </div>
            
        </div>
        <button class="btn-blue">Conocenos</button>
    </div>

</template>

<script>
export default {

}
</script>

<style>
.title-feature {
    color: #4a4a4a;
    font-family: 'Open Sans', sans-serif;
    font-size: 32px;
    font-weight: normal;
    letter-spacing: 0.5px;
    margin: 0;
}


.feature-item {
    display: flex;
    align-items: flex-start;
    width: 320px;
    margin: 50px 20px;
}

.features {
    max-width: 1200px;;
    margin-top:  50px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;

}
.section-features {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.feature-item-description {
    padding: 0 25px;
}

.icon-feature {
    width: 54px;
}

</style>
