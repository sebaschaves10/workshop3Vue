<!-- src/App.vue -->

<template>
  <div id="app">
    <!-- NAVBAR -->
    <nav class="navbar shadow px-2 py-0 border-bottom navbar-light bg-light navbar-expand-lg">
      <a class="navbar-brand order-0"><img height="60" src="./assets/logo-peaku.png" class=""></a>
      <div id="nav-collapse" class="order-4 order-md-1 navbar-collapse collapse" style="display:none;">
        <ul class="navbar-nav ml-md-auto align-items-md-center" style="text-align: right;">
          <div class="d-md-flex pl-3 p-md-none">
            <li class="nav-item mr-md-2 text-truncate"><a href="" aria-current="page" class="nav-link active">
                Empleos
              </a>
            </li>
            <li class="nav-item mr-md-2 text-truncate"><a href="" class="nav-link">
                Bootcamp
              </a>
            </li>
            <li class="nav-item mr-md-2 text-truncate"><a href="" class="nav-link">
                Sobre nosotros
              </a>
            </li>
            <li class="nav-item b-nav-dropdown dropdown mr-md-2 main-nav-dropdown"><a role="button" aria-haspopup="true"
                aria-expanded="false" href="#" class="nav-link dropdown-toggle"><span>Para
                  profesionales</span>
              </a>
              <ul tabindex="-1" class="dropdown-menu p-2 dropdown-menu-right">
                <li class="mb-1">
                  <a role="menuitem" href="#" class="dropdown-item">
                    Inicio
                  </a>
                </li>
                <li class="mb-1">
                  <a role="menuitem" href="#" class="dropdown-item">
                    Empleos
                  </a>
                </li>
                <li class="mb-1">
                  <a role="menuitem" href="#" class="dropdown-item">
                    Cursos y retos
                  </a>
                </li>
                <li class="mb-1">
                  <a role="menuitem" href="#" class="dropdown-item">
                    Preguntas
                  </a>
                </li>
                <li class="mb-1">
                  <a role="menuitem" href="#" class="dropdown-item">
                    Profesores
                  </a>
                </li>
                <li class="mb-1">
                  <a role="menuitem" href="#" class="dropdown-item">
                    Bootcamp
                  </a>
                </li>
              </ul>
            </li>
            <li class="nav-item b-nav-dropdown dropdown mr-md-2 main-nav-dropdown">
              <a aria-haspopup="true" aria-expanded="false" href="#" class="nav-link dropdown-toggle"><span>Para
                  empresas</span>
              </a>
              <ul tabindex="-1" class="dropdown-menu p-2 dropdown-menu-right">
                <li class="mb-1"><a role="menuitem" href="#" class="dropdown-item">
                    Inicio
                  </a>
                </li>
                <li class="mb-1">
                  <a role="menuitem" href="#" class="dropdown-item">
                    Publicar empleo
                  </a>
                </li>
                <li class="mb-1">
                  <a role="menuitem" href="#" class="dropdown-item">
                    Nuestro proceso
                  </a>
                </li>
                <li class="mb-1">
                  <a role="menuitem" href="#" class="dropdown-item">
                    Precios
                  </a>
                </li>
                <li class="mb-1">
                  <a role="menuitem" href="#" class="dropdown-item">
                    Pruebas Online
                  </a>
                </li>
                <li class="mb-1">
                  <a role="menuitem" href="#" class="dropdown-item">
                    Nómina
                  </a>
                </li>
                <li class="mb-1">
                  <a role="menuitem" href="#" class="dropdown-item">
                    Blog
                  </a>
                </li>
                <li class="mb-1">
                  <a role="menuitem" href="#" class="dropdown-item">
                    Comercial
                  </a>
                </li>
                <li class="mb-1">
                  <a role="menuitem" href="#" class="dropdown-item">
                    Calculadora de salario
                  </a>
                </li>
              </ul>
            </li>
          </div>
          <div class="w-100 px-2 m-0 p-0 mr-2 text-truncate">
            <li class="nav-item btn btn-outline-light btn-sm border">
              <a class="nav-link" role="button">
                <div class="d-flex align-items-center justify-content-center">
                  <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="globe"
                    fill="currentColor" class="bi-globe mr-1 b-icon bi" style="font-size: 120%;">
                    <g>
                      <path
                        d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8zm7.5-6.923c-.67.204-1.335.82-1.887 1.855A7.97 7.97 0 0 0 5.145 4H7.5V1.077zM4.09 4a9.267 9.267 0 0 1 .64-1.539 6.7 6.7 0 0 1 .597-.933A7.025 7.025 0 0 0 2.255 4H4.09zm-.582 3.5c.03-.877.138-1.718.312-2.5H1.674a6.958 6.958 0 0 0-.656 2.5h2.49zM4.847 5a12.5 12.5 0 0 0-.338 2.5H7.5V5H4.847zM8.5 5v2.5h2.99a12.495 12.495 0 0 0-.337-2.5H8.5zM4.51 8.5a12.5 12.5 0 0 0 .337 2.5H7.5V8.5H4.51zm3.99 0V11h2.653c.187-.765.306-1.608.338-2.5H8.5zM5.145 12c.138.386.295.744.468 1.068.552 1.035 1.218 1.65 1.887 1.855V12H5.145zm.182 2.472a6.696 6.696 0 0 1-.597-.933A9.268 9.268 0 0 1 4.09 12H2.255a7.024 7.024 0 0 0 3.072 2.472zM3.82 11a13.652 13.652 0 0 1-.312-2.5h-2.49c.062.89.291 1.733.656 2.5H3.82zm6.853 3.472A7.024 7.024 0 0 0 13.745 12H11.91a9.27 9.27 0 0 1-.64 1.539 6.688 6.688 0 0 1-.597.933zM8.5 12v2.923c.67-.204 1.335-.82 1.887-1.855.173-.324.33-.682.468-1.068H8.5zm3.68-1h2.146c.365-.767.594-1.61.656-2.5h-2.49a13.65 13.65 0 0 1-.312 2.5zm2.802-3.5a6.959 6.959 0 0 0-.656-2.5H12.18c.174.782.282 1.623.312 2.5h2.49zM11.27 2.461c.247.464.462.98.64 1.539h1.835a7.024 7.024 0 0 0-3.072-2.472c.218.284.418.598.597.933zM10.855 4a7.966 7.966 0 0 0-.468-1.068C9.835 1.897 9.17 1.282 8.5 1.077V4h2.355z">
                      </path>
                    </g>
                  </svg> <span>&nbsp;Español</span>
                </div>
              </a>
            </li>
          </div>
        </ul>
      </div>
      <div class="order-2 d-flex align-items-center">
        <div class="mr-2">
          <button type="button" class="btn d-inline-block position-relative btn-light collapsed" aria-expanded="false"
            aria-controls="notifications-sidebar" style="overflow-anchor: none;">
            <svg viewBox="0 0 16 16" width="1em" height="1em" class="bi-bell b-icon bi">
              <g>
                <path
                  d="M8 16a2 2 0 0 0 2-2H6a2 2 0 0 0 2 2zM8 1.918l-.797.161A4.002 4.002 0 0 0 4 6c0 .628-.134 2.197-.459 3.742-.16.767-.376 1.566-.663 2.258h10.244c-.287-.692-.502-1.49-.663-2.258C12.134 8.197 12 6.628 12 6a4.002 4.002 0 0 0-3.203-3.92L8 1.917zM14.22 12c.223.447.481.801.78 1H1c.299-.199.557-.553.78-1C2.68 10.2 3 6.88 3 6c0-2.42 1.72-4.44 4.005-4.901a1 1 0 1 1 1.99 0A5.002 5.002 0 0 1 13 6c0 .88.32 4.2 1.22 6z">
                </path>
              </g>
            </svg>
          </button>
        </div>
        <div class="dropdown b-dropdown order-2 profile-dropdown btn-group">
          <button aria-haspopup="menu" aria-expanded="false" type="button"
            class="btn dropdown-toggle btn-light p-0 p-md-1 dropdown-toggle-no-caret">
            <div class="d-flex align-items-center" style="font-size: 0.7em;">
              <span class="b-avatar badge-dark rounded-circle" style="width: 1.8rem; height: 1.8rem;">
                <svg width="1em" height="1em" role="img" aria-label="person" aria-hidden="true" alt="avatar"
                  class="bi-person b-icon bi">
                  <g>
                    <path
                      d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10z">
                    </path>
                  </g>
                </svg>
              </span>
            </div>
          </button>
        </div>
      </div>
    </nav>
    <!-- BARRA DE BUSQUEDA -->
    <div class="position-relative collapsed main-content"
      style="min-height: calc(100vh - 75px) !important; background-color: #5897fb;">
      <div class="p-0 pb-5 container-fluid" data-v-2d46ecad="">
        <div id="title-search" class="p-0 m-0 container-fluid">
          <div class="bg-blue py-3">
            <div class="container">
              <div class="row align-items-center justify-content-center">
                <div class="col-md-6 col-12">
                  <div>
                    <div role="group" class="input-group custom-input-group">
                      <div class="bg-light input-group-prepend">
                        <div class="input-group-text"><svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false"
                            role="img" aria-label="search" fill="currentColor" class="bi-search b-icon bi">
                            <g>
                              <path
                                d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z">
                              </path>
                            </g>
                          </svg></div>
                      </div> <input type="search" placeholder="Busca por cargo, salario, ubicación o empresa" value=""
                        class="form-control form-control-md">
                    </div>
                  </div>
                </div>
                <div class="text-md-right text-white text-truncate mt-2 mt-md-0 col-md-6 col-12">
                  <button type="button" class="btn btn-outline-light btn-sm rounded-pill">
                    Área
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" fill="currentColor"
                      class="bi-caret-down-fill b-icon bi">
                      <g transform="translate(8 8) scale(0.7 0.7) translate(-8 -8)">
                        <path
                          d="M7.247 11.14 2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z">
                        </path>
                      </g>
                    </svg></button> <button type="button" class="btn btn-outline-light btn-sm rounded-pill">
                    Cargo
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" fill="currentColor"
                      class="bi-caret-down-fill b-icon bi">
                      <g transform="translate(8 8) scale(0.7 0.7) translate(-8 -8)">
                        <path
                          d="M7.247 11.14 2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z">
                        </path>
                      </g>
                    </svg></button> <button type="button" class="btn btn-outline-light btn-sm rounded-pill">
                    Salario
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" fill="currentColor"
                      class="bi-caret-down-fill b-icon bi">
                      <g transform="translate(8 8) scale(0.7 0.7) translate(-8 -8)">
                        <path
                          d="M7.247 11.14 2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z">
                        </path>
                      </g>
                    </svg></button> <button type="button" class="btn btn-outline-light btn-sm rounded-pill">
                    Ubicación
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" fill="currentColor"
                      class="bi-caret-down-fill b-icon bi">
                      <g transform="translate(8 8) scale(0.7 0.7) translate(-8 -8)">
                        <path
                          d="M7.247 11.14 2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z">
                        </path>
                      </g>
                    </svg></button>
                </div>
              </div>
            </div>
          </div>
        </div>
        <InfoBar v-for="(barra, index) in barras" :key="index" :data="barra" />
      </div>
    </div>
    <!-- Utilizamos v-for para iterar sobre el arreglo de datos -->
  </div>
</template>

<script>
import InfoBar from './components/InfoBar.vue';


export default {
  name: 'App',
  components: {
    InfoBar,
  },
  data() {
    return {
      barras: [
        {
          imagen: 'https://s3-us-west-2.amazonaws.com/peaku-public/business/Company/logo_url/80893/offiemedicas.png',
          trabajo: 'ANALISTA DE INVENTARIOS',
          empresa: 'Offmedicas S:A',
          ciudad: 'Bucaramanga',
          pago: '1M - 1.2M COP',
          vacante: 1,
          fecha: 'hace 1 hora',
        },
        {
          imagen: 'https://s3-us-west-2.amazonaws.com/peaku-public/business/Company/logo_url/517011/Logo_Casa_Paramo.jpg',
          trabajo: 'Ejecutivo Comercial',
          empresa: 'Casa Páramo',
          ciudad: 'Híbrido',
          pago: '2M - 3M COP',
          vacante: 1,
          fecha: 'hace 2 horas',
        },
        {
          imagen: 'https://s3-us-west-2.amazonaws.com/peaku-public/business/Company/logo_url/2078/descarga_(1).png',
          trabajo: 'Reclutador IT Junior Bilingüe',
          empresa: 'PeakU Inc.',
          ciudad: 'Remoto',
          pago: '1.5M - 2.5M COP',
          vacante: 2,
          fecha: 'hace 5 horas',
        },
        {
          imagen: 'https://s3-us-west-2.amazonaws.com/peaku-public/business/Company/logo_url/52905/19.png',
          trabajo: 'Bussines analyst representative',
          empresa: 'Bankuish',
          ciudad: 'Remoto en Brazil',
          pago: '2.5K - 3.5K USD',
          vacante: 1,
          fecha: 'hace 6 días',
        },
        {
          imagen: 'https://peaku.co/img/company.svg',
          trabajo: 'Mercadeo y ventas',
          empresa: 'Kumanday Software',
          ciudad: 'No disponible',
          pago: '4.5M - 6.6M COP',
          vacante: 1,
          fecha: 'hace 7 días',
        },
        {
          imagen: 'https://s3-us-west-2.amazonaws.com/peaku-public/business/Company/logo_url/516597/brand_key.png',
          trabajo: 'Diseño Gráfico',
          empresa: 'Brandkey Agencia',
          ciudad: 'Híbrido - mix remoto',
          pago: '1.5M COP',
          vacante: 1,
          fecha: 'hace 19 horas',
        },
        {
          imagen: 'https://s3-us-west-2.amazonaws.com/peaku-public/business/Company/logo_url/515600/neduga.jpeg',
          trabajo: 'Ingeniero Desarrollador Fronted',
          empresa: 'NEDUGA TECH SAS',
          ciudad: 'Remoto en Colombia',
          pago: '2.5M - 3.5M COP',
          vacante: 1,
          fecha: 'hace 5 horas',
        },
        {
          imagen: 'https://s3-us-west-2.amazonaws.com/peaku-public/business/Company/logo_url/2078/descarga_(1).png',
          trabajo: 'Formación Bootcamp Desarroladores Fullstack cohorte 10',
          empresa: 'PeakU Inc.',
          ciudad: 'Remoto - Cualquier lugar',
          pago: 'Confidencial',
          vacante: 25,
          fecha: 'hace 3 días',
        }
      ],
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
}
</style>


