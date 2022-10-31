<template>
    <div class="fondo">
        <table class="table">
            <tr>
                <th class="col"></th>
                <th class="col">INFORMACION TECNICA DEBIAN</th>
                <!-- <th scope="col-2"></th>
                <th scope="col-2"></th>
                <th scope="col-2"></th> -->
            </tr>
            <tr>
                <th class="row">NÚCLEO</th>
                <td>Linux</td>
                <td>FreeBSD</td>
                <td>Hurd</td>
            </tr>
            <tr>
                <th class="row">TIPO DE NÚCLEO</th>
                <td>Monolitico</td>
                <td>Micro</td>
            </tr>
            <tr>
                <th class="row">PLATAFORMAS ADMITIDAS</th>
                <td>IA-32</td>
                <td>IBM Z</td>
                <td>Power PC</td>
                <td>ARM</td>   
            </tr>
            <tr>
                <th class="row">INTERFAZ GRÁFICA PREDETERMINADA</th>
                <td>GNOME</td>
                <td>KDE</td>
                <td>Xfce</td>
                <td>LXDE</td>
            </tr>
            <tr>
                <th class="row">Sistemas de gestion de paquetes</th>
                <td>Programa dpkg</td>
            </tr>
            <tr>
                <th class="row">METODO DE ACTUALIZACION</th>
                <td>APT (Advanced Package Tool)</td>
            </tr>
        </table>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.fondo{
    background-color: white;
    position:relative;
    padding: 2rem;
}
.table{
    border: solid gray;
    position: relative;
}
.col{
    text-align: left;
}
.row{
    margin-left: 12rem;
    text-align: left;
}
</style>