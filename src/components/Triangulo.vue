<template>
    <div>
        <div class="container">
            <div class="row">
                <div class="col">
                    <div class="container-portada">
                        <div class="capa-gradient">
                        </div>
                        <div class="container-details">
                            <div class="details">
                            
                            <p>
                                Triángulo
                            </p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col">  
                    <div class="container-calculo">
                        <form>
                    <label for="LTri" class="form-label">Lados</label>
                    <input type="text" class="form-control" id="LTri1" value="000" required>
                    <input type="text" class="form-control" id="LTri2" value="000" required>
                    <input type="text" class="form-control" id="LTri3" value="000" required>
                    <div class="valid-feedback">
                    Looks good!
                    </div>
                    <br>

                <a href="#" class="btn btn-dark">Calcular</a>
                    <br><br>
                <label for="TA" class="form-label">Área</label>
                <input type="text" class="form-control" id="TA" value="000">
                <label for="TP" class="form-label">Perímetro</label>
                <input type="text" class="form-control" id="TP" value="000">

              </form>
                    </div>

                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Triangulo'
}
</script>

<style>
.container-portada{
    width: 100%;
    height: 400px;
    background-image: url(https://p4.wallpaperbetter.com/wallpaper/972/483/705/minimalism-gray-geometry-black-wallpaper-preview.jpg);
    background-size: 150%;
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
    background-image: url(https://media.istockphoto.com/photos/texture-of-dust-scratches-dirt-stains-vintage-black-and-white-grunge-picture-id942860746);
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