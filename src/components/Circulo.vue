<template>
    <div>
        <div class="container">
            <div class="row">
                <div class="col">
                    <div class="container-portadaCirculo">
                        <div class="capa-gradient">
                        </div>
                        <div class="container-details">
                            <div class="details">
                            
                            <p>
                                Circulo
                            </p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col">  
                    <div class="container-calculo">
                        <br><br><br>
                        <form>
                    <label for="LCir" class="form-label">Radio</label>
                    <input type="text" class="form-control" id="LCir" value="000" required>
                    <div class="valid-feedback">
                    Looks good!
                    </div>
                    <br>

                <a href="#" class="btn btn-dark">Calcular</a>
                    <br><br>
                <label for="ACir" class="form-dark">Área</label>
                <input type="text" class="form-control" id="ACir" value="000">
                <label for="PCir" class="form-dark">Perímetro</label>
                <input type="text" class="form-control" id="PCir" value="000">
              </form>
                    </div>

                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Circulo'
}
</script>

<style>
.container-portadaCirculo{
    width: 100%;
    height: 400px;
    background-image: url(https://ak.picdn.net/shutterstock/videos/1015676170/thumb/1.jpg);
    background-size: 120%;
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