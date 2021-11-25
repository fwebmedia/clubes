<template>
    <div class="container py-5 px-5">
        <form class="py-5" action="">

            <div class="columns">
                <div class="column has-text-centered">
                    <div class="titular">
                        <h2 class="title py-2 px-3 is-4">
                        Ingresa tus datos
                        </h2>
                    </div>
                    <hr class="hr-azul">
                </div>
            </div>

            <div class="columns">
                <div class="column">
                        <div class="field">
                        <label class="label">*Cédula</label>
                        <div class="control">
                            <input class="input is-rounded has-background-light" type="text" placeholder="">
                        </div>
                    </div>
                </div>
                 <div class="column">
                        <div class="field">
                        <label class="label">*Celular</label>
                        <div class="control">
                            <input class="input is-rounded has-background-light" type="text" placeholder="">
                        </div>
                    </div>
                </div>
            </div>

            <div class="columns">
                <div class="column">
                        <div class="field">
                        <label class="label">*Correo Electrónico</label>
                        <div class="control">
                            <input class="input is-rounded has-background-light"  type="text" placeholder="">
                        </div>
                    </div>
                </div>
                 <div class="column">
                        <div class="field">
                        <label class="label">*Fecha de nacimiento</label>
                        <div class="control">
                            <input class="input is-rounded has-background-light" type="date" placeholder="" name="fecha" id="fecha">
                        </div>
                    </div>
                </div>
            </div>

            <div class="columns">
                <div class="column">
                        <div class="field">
                        <label class="label">*Dirección</label>
                        <div class="control">
                            <input class="input is-rounded has-background-light" type="text" placeholder="">
                        </div>
                    </div>
                </div>
                 <div class="column">
                    <div class="field">
                        <label class="label">*Ciudad</label>
                        <div class="control">
                            <div class="select is-rounded" style="width:100%;">
                                <select style="width:100%;" class="has-background-light">
                                    <option>Seleccione una ciudad</option>
                                    <option>With options</option>
                                </select>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="columns">
                <div class="column has-text-centered">
                    *Verifica que los datos ingresados sean correctos
                </div>
            </div>

             <hr class="hr-azul">

            <div class="columns">
                <div class="column has-text-centered">
                    <h2 class="title is-4 pt-3">Elige el o los Clubes a los cuales quieras afiliarte</h2>
                </div>
            </div>

            <div class="columns">

                <div class="column is-flex has-text-centered is-align-items-center ">
                    <label class="checkbox">
                       <img src="../assets/images/logo-pmc.png" alt="Fybeca" class="pr-2">
                    </label>
                    <input type="checkbox">
                </div>

                <div class="column is-flex has-text-centered is-align-items-center">
                    <label class="checkbox">
                       <img src="../assets/images/logo-bebitos.png" alt="Fybeca" class="pr-2">
                    </label>
                    <input type="checkbox">
                </div>

                <div class="column is-flex has-text-centered is-align-items-center">
                    <label class="checkbox">
                       <img src="../assets/images/logo-beauty.png" alt="Fybeca" class="pr-2">
                    </label>
                    <input type="checkbox">
                </div>

            </div>

            <hr class="hr-celeste">

            <div class="clumns has-text-centered">
                <div class="column">
                    <label class="checkbox">
                    <input type="checkbox">
                    Acepto <a href="#">términos y condiciones</a>
                    </label>
                </div>
            </div>

            <div class="columns pt-5">
                <div class="column has-text-centered">
                    <button type="submit" class="button is-info is-outlined1 is-medium is-rounded">
                        <span class="icon is-small">
                        <i class="fas fa-check"></i>
                        </span>
                        <span>
                            AFÍLIATE AQUÍ
                        </span>
                    </button>
                </div>
            </div>

        </form>
    </div>
</template>
<script>
export default {
    name: 'Content'
}
</script>
<style>
h1,h2,h3,h4,h5,h6{
    color:#1f4164!important;
}
label{
    color:#1f4164!important;
    font-weight:500!important;
}
.hr-azul {
    background-color: #1f4164!important;
    height: 5px;
}
.hr-celeste {
    background-color: #008fd6!important;
    height: 5px;
}
a{
    color:#1f4164!important;
}
a:hover{
    color:#008fd6!important;
}
.titular{
    background:#ffffff;
    display:inline-block;
    left:50%;
    margin-left:-110px;
    margin-top:5px;
    position:absolute;
    width:220px;
}

</style>