<template>
    <div>
        <div class="container">
            <div class="row">
                <div class="col">
                    <div class="container-portadaRectangulo">
                        <div class="capa-gradient">
                        </div>
                        <div class="container-details">
                            <div class="details">
                            
                            <p>
                                Rectangulo
                            </p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col">  
                    <div class="container-calculo">
                        <br>
                        <form>
                    <label for="LRec1" class="form-label">Lado</label>
                    <input type="text" class="form-control" id="LRec1" value="000" required>
                    <label for="LRec2" class="form-label">Lado</label>
                    <input type="text" class="form-control" id="LRec2" value="000" required>
                    <div class="valid-feedback">
                    Looks good!
                    </div>
                    <br>

                <a href="#" class="btn btn-dark">Calcular</a>
                    <br><br>
                <label for="ARec" class="form-dark">Área</label>
                <input type="text" class="form-control" id="ARec" value="000">
                <label for="PRec" class="form-dark">Perímetro</label>
                <input type="text" class="form-control" id="PRec" value="000">
              </form>
                    </div>

                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Rectangulo'
}
</script>

<style>
.container-portadaRectangulo{
    width: 100%;
    height: 400px;
    background-image: url(https://image.freepik.com/vector-gratis/marco-vintage-cuadrado-dorado-sombra-sobre-fondo-negro-borde-rectangular-lujo-dorado-ilustracion-realista_162695-1906.jpg);
    background-size: 110%;
    animation: movimiento 10s infinite linear alternate;
}
@keyframes movimiento {
    from{
        background-position: top left;
    }to{
        background-position: top right;
    }
    
}

.container-calculo{
    width: 100%;
    height: 400px;
    background-image: url(https://i.pinimg.com/originals/29/2d/dc/292ddcf1fdbcff99169b93d6507b59bf.jpg);
    background-size: 150%;
    animation: movimiento 10s infinite linear alternate;
}
@keyframes calculo {
    from{
        background-position: top left;
    }to{
        background-position: top right;
    }
    
}

.container-details{
    width: 100%;
    min-width: 500px;
    position: relative;
    margin: auto;
    
}

.container-details p{
    font-family: sans-serif;
    text-align: center;
}
.details{
    width: auto;
    min-width: 200px;
    position: relative;
    top: 20px;
    color: blanchedalmond;
}
</style>