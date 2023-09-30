<!-- src/components/InfoBar.vue -->

<template>
    <div class="info-bar">
        <div class="card job-card mb-1 border"><!----><!---->
            <div class="card-body p-2 p-md-3"><!----><!---->
                <div class="row align-items-center">
                    <div class="justify-content-center align-items-center col-md-1 col-3">
                        <img :src="data.imagen" alt="Logo empresa" width="70" height="70" class="rounded">
                    </div>
                    <div class="col-md-11 col-9">
                        <div class="row align-items-center">
                            <div class="mb-2 col" style="text-align: justify;">
                                <a href="#" class="text-dark stretched-link d-inline d-md-inline-flex"
                                    style="text-decoration: none;">
                                    <h2 itemprop="title" class="job-title bold pl-md-2 pr-md-2 mb-0 pb-0" id="titulo">
                                        {{ data.trabajo }}
                                    </h2>
                                    <section class="d-inline d-md-inline-flex align-items-center">
                                        <div role="button">
                                            <b-button pill variant="outline-secondary"
                                                style=" font-size: 12px; align-items: center;">Liderazgo</b-button>
                                        </div>
                                        <div role="button">
                                            <b-button pill variant="outline-secondary"
                                                style=" font-size: 10px; align-items: center;">information
                                                analysis</b-button>
                                        </div>
                                        <div role="button">
                                            <b-button pill variant="outline-secondary"
                                                style=" font-size: 10px; align-items: center;">adaptation to
                                                changes</b-button>
                                        </div>
                                    </section> <!----> <!---->
                                </a>
                            </div>
                        </div>
                        <div class="row pl-md-2 mt-1 flex-column flex-md-row"
                            style="font-size: 0.9em; text-align: justify;">
                            <div class="text-truncate text-capitalize col">
                                <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img"
                                    aria-label="building" xmlns="http://www.w3.org/2000/svg" fill="currentColor"
                                    class="bi-building b-icon bi">
                                    <g>
                                        <path fill-rule="evenodd"
                                            d="M14.763.075A.5.5 0 0 1 15 .5v15a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5V14h-1v1.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V10a.5.5 0 0 1 .342-.474L6 7.64V4.5a.5.5 0 0 1 .276-.447l8-4a.5.5 0 0 1 .487.022zM6 8.694 1 10.36V15h5V8.694zM7 15h2v-1.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5V15h2V1.309l-7 3.5V15z">
                                        </path>
                                        <path
                                            d="M2 11h1v1H2v-1zm2 0h1v1H4v-1zm-2 2h1v1H2v-1zm2 0h1v1H4v-1zm4-4h1v1H8V9zm2 0h1v1h-1V9zm-2 2h1v1H8v-1zm2 0h1v1h-1v-1zm2-2h1v1h-1V9zm0 2h1v1h-1v-1zM8 7h1v1H8V7zm2 0h1v1h-1V7zm2 0h1v1h-1V7zM8 5h1v1H8V5zm2 0h1v1h-1V5zm2 0h1v1h-1V5zm0-2h1v1h-1V3z">
                                        </path>
                                    </g>
                                </svg>
                                <span itemprop="name">
                                    {{ data.empresa }}
                                </span>
                            </div>

                            <div itemprop="jobLocation" itemtype="http://schema.org/Place" class="text-truncate col"><svg
                                    viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img"
                                    aria-label="geo alt" xmlns="http://www.w3.org/2000/svg" fill="currentColor"
                                    class="bi-geo-alt b-icon bi">
                                    <g>
                                        <path
                                            d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z">
                                        </path>
                                        <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"></path>
                                    </g>
                                </svg> <span itemprop="name address">
                                    {{ data.ciudad }}
                                </span>
                            </div>

                            <div class="text-truncate col">
                                <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img"
                                    aria-label="cash" xmlns="http://www.w3.org/2000/svg" fill="currentColor"
                                    class="bi-cash b-icon bi">
                                    <g>
                                        <path d="M8 10a2 2 0 1 0 0-4 2 2 0 0 0 0 4z"></path>
                                        <path
                                            d="M0 4a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V4zm3 0a2 2 0 0 1-2 2v4a2 2 0 0 1 2 2h10a2 2 0 0 1 2-2V6a2 2 0 0 1-2-2H3z">
                                        </path>
                                    </g>
                                </svg> <span>
                                    $ {{ data.pago }}
                                </span>
                            </div>
                            <div class="d-none d-md-inline-block col">
                                <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img"
                                    aria-label="people" xmlns="http://www.w3.org/2000/svg" fill="currentColor"
                                    class="bi-people b-icon bi">
                                    <g>
                                        <path
                                            d="M15 14s1 0 1-1-1-4-5-4-5 3-5 4 1 1 1 1h8zm-7.978-1A.261.261 0 0 1 7 12.996c.001-.264.167-1.03.76-1.72C8.312 10.629 9.282 10 11 10c1.717 0 2.687.63 3.24 1.276.593.69.758 1.457.76 1.72l-.008.002a.274.274 0 0 1-.014.002H7.022zM11 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm3-2a3 3 0 1 1-6 0 3 3 0 0 1 6 0zM6.936 9.28a5.88 5.88 0 0 0-1.23-.247A7.35 7.35 0 0 0 5 9c-4 0-5 3-5 4 0 .667.333 1 1 1h4.216A2.238 2.238 0 0 1 5 13c0-1.01.377-2.042 1.09-2.904.243-.294.526-.569.846-.816zM4.92 10A5.493 5.493 0 0 0 4 13H1c0-.26.164-1.03.76-1.724.545-.636 1.492-1.256 3.16-1.275zM1.5 5.5a3 3 0 1 1 6 0 3 3 0 0 1-6 0zm3-2a2 2 0 1 0 0 4 2 2 0 0 0 0-4z">
                                        </path>
                                    </g>
                                </svg>
                                {{ data.vacante }} Vacante
                            </div>
                            <div class="text-truncate col">
                                <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img"
                                    aria-label="calendar3" xmlns="http://www.w3.org/2000/svg" fill="currentColor"
                                    class="bi-calendar3 b-icon bi">
                                    <g>
                                        <path
                                            d="M14 0H2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2zM1 3.857C1 3.384 1.448 3 2 3h12c.552 0 1 .384 1 .857v10.286c0 .473-.448.857-1 .857H2c-.552 0-1-.384-1-.857V3.857z">
                                        </path>
                                        <path
                                            d="M6.5 7a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-9 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm3 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2z">
                                        </path>
                                    </g>
                                </svg> <!----> <span itemprop="datePosted validThrough" class="sr-only">

                                </span> <time datetime="2023-09-28T14:11:42.061Z">{{ data.fecha }}</time>
                            </div>

                            <div class="d-flex justify-content-end"><!---->
                                <div role="button" title="Certificaciones">
                                    <b-button pill variant="outline-secondary"
                                        style=" font-size: 12px; align-items: center;">
                                        <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img"
                                            aria-label="file earmark check" xmlns="http://www.w3.org/2000/svg"
                                            fill="currentColor" class="bi-file-earmark-check b-icon bi">
                                            <g>
                                                <path
                                                    d="M10.854 7.854a.5.5 0 0 0-.708-.708L7.5 9.793 6.354 8.646a.5.5 0 1 0-.708.708l1.5 1.5a.5.5 0 0 0 .708 0l3-3z">
                                                </path>
                                                <path
                                                    d="M14 14V4.5L9.5 0H4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2zM9.5 3A1.5 1.5 0 0 0 11 4.5h2V14a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1h5.5v2z">
                                                </path>
                                            </g>
                                        </svg>
                                    </b-button>
                                </div>

                                <div role="button" title="Fiesta de fin de año">
                                    <b-button pill variant="outline-secondary"
                                        style=" font-size: 12px; align-items: center;">
                                        <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img"
                                            aria-label="emoji sunglasses" xmlns="http://www.w3.org/2000/svg"
                                            fill="currentColor" class="bi-emoji-sunglasses b-icon bi">
                                            <g>
                                                <path
                                                    d="M4.968 9.75a.5.5 0 1 0-.866.5A4.498 4.498 0 0 0 8 12.5a4.5 4.5 0 0 0 3.898-2.25.5.5 0 1 0-.866-.5A3.498 3.498 0 0 1 8 11.5a3.498 3.498 0 0 1-3.032-1.75zM7 5.116V5a1 1 0 0 0-1-1H3.28a1 1 0 0 0-.97 1.243l.311 1.242A2 2 0 0 0 4.561 8H5a2 2 0 0 0 1.994-1.839A2.99 2.99 0 0 1 8 6c.393 0 .74.064 1.006.161A2 2 0 0 0 11 8h.438a2 2 0 0 0 1.94-1.515l.311-1.242A1 1 0 0 0 12.72 4H10a1 1 0 0 0-1 1v.116A4.22 4.22 0 0 0 8 5c-.35 0-.69.04-1 .116z">
                                                </path>
                                                <path
                                                    d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zm-1 0A7 7 0 1 0 1 8a7 7 0 0 0 14 0z">
                                                </path>
                                            </g>
                                        </svg>
                                    </b-button>
                                </div>

                                <div role="button" title="Capacitaciones">
                                    <b-button pill variant="outline-secondary"
                                        style=" font-size: 12px; align-items: center;">
                                        <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img"
                                            aria-label="clipboard check" xmlns="http://www.w3.org/2000/svg"
                                            fill="currentColor" class="bi-clipboard-check b-icon bi">
                                            <g>
                                                <path fill-rule="evenodd"
                                                    d="M10.854 7.146a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 1 1 .708-.708L7.5 9.793l2.646-2.647a.5.5 0 0 1 .708 0z">
                                                </path>
                                                <path
                                                    d="M4 1.5H3a2 2 0 0 0-2 2V14a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V3.5a2 2 0 0 0-2-2h-1v1h1a1 1 0 0 1 1 1V14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3.5a1 1 0 0 1 1-1h1v-1z">
                                                </path>
                                                <path
                                                    d="M9.5 1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5v-1a.5.5 0 0 1 .5-.5h3zm-3-1A1.5 1.5 0 0 0 5 1.5v1A1.5 1.5 0 0 0 6.5 4h3A1.5 1.5 0 0 0 11 2.5v-1A1.5 1.5 0 0 0 9.5 0h-3z">
                                                </path>
                                            </g>
                                        </svg>
                                    </b-button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
  
<script>
export default {
    name: 'InfoBar',
    props: {
        data: Object, // Recibimos un objeto de datos completo como prop
    },
};
</script>
  
<style scoped>@import url('https://fonts.googleapis.com/css2?family=Oswald:wght@500&display=swap');
    .info-bar {
        background-color: #f0f0f0;
        padding: 10px;
    }

    .card {
        transition: box-shadow 0.1s;
    }

    .card:hover {
        box-shadow: 0 10px 10px rgba(0, 0, 0, 0.3); 
    }

    #titulo {
        font-weight: 600;
        font-size: x-large;
        padding-right: 10px;
    }
</style>
  