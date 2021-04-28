<template>
  <section
    class="specialists bg-white pt-4 mb-12"
    data-aos="fade-down"
    data-aos-easing="linear"
    data-aos-once="true"
    data-aos-duration="500"
  >
    <div class="container mx-auto px-2 lg:px-4">
      <h2 class="text-center">
        Reviews
      </h2>
      <p class="text-center mb-4">
        Veja o que nossos clientes tem a comentar sobre nossos serviços de Consultoria em Marketing Digital.
      </p>
      <div class="specialist__items">
        <client-only placeholder="Loading...">
          <agile :options="agileOptions">
            <div class="slide slide--1">
              <div class="card overflow-hidden spec__card">
                <div class="card-body">
                  <div class="card-text text-black text-xl font-light leading-7">
                    “Me ajudaram a entender como entender meu cliente e implementar ações práticas”
                  </div>
                  <div class="spec__card-meta">
                    <div class="sec__card-meta-avatar">
                      <img
                        v-bind="specialist_avatar"
                        :src="require('~/assets/img/reviews-pictures/NeilPatel.jpg').src"
                        :srcset="require('~/assets/img/reviews-pictures/NeilPatel.jpg').srcSet"
                        :blank-src="require('~/assets/img/reviews-pictures/NeilPatel.jpg').placeholder"
                        alt="Neil Patel Photo"
                      >
                    </div>
                    <div class="spec__card-meta-details">
                      <div class="name">
                        Jorge da Silva
                      </div>
                      <div class="job">
                        Cliente Fake 1
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="slide slide--2">
              <div class="card overflow-hidden spec__card">
                <div class="card-body">
                  <div class="card-text text-black text-xl font-light leading-7">
                    “O pessoal da ZMOT Institute é muito profissional. Me ajudaram a dobrar o faturamento”
                  </div>
                  <div class="spec__card-meta">
                    <div class="sec__card-meta-avatar">
                      <img
                        v-bind="specialist_avatar"
                        :src="require('~/assets/img/reviews-pictures/Jim_Lecinsk.jpeg').src"
                        :srcset="require('~/assets/img/reviews-pictures/Jim_Lecinsk.jpeg').srcSet"
                        :blank-src="require('~/assets/img/reviews-pictures/Jim_Lecinsk.jpeg').placeholder"
                        alt="Jim Lecinsk Photo"
                      >
                    </div>
                    <div class="spec__card-meta-details">
                      <div class="name">
                        Isabela da Silva
                      </div>
                      <div class="job">
                        Cliente Fake 2
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="slide slide--3">
              <div class="card overflow-hidden spec__card">
                <div class="card-body">
                  <div class="card-text text-black text-xl font-light leading-7">
                    “Vale cada centavo investido... tive um retorno muito rápido”
                  </div>
                  <div class="spec__card-meta">
                    <div class="sec__card-meta-avatar">
                      <img
                        v-bind="specialist_avatar"
                        :src="require('~/assets/img/reviews-pictures/David_Meerman_Scott.png').src"
                        :srcset="require('~/assets/img/reviews-pictures/David_Meerman_Scott.png').srcSet"
                        :blank-src="require('~/assets/img/reviews-pictures/David_Meerman_Scott.png').placeholder"
                        alt="David Meerman Scott Photo"
                      >
                    </div>
                    <div class="spec__card-meta-details">
                      <div class="name">
                        Elisa dos Santos
                      </div>
                      <div class="job">
                        Empresa 2
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="slide slide--4">
              <div class="card overflow-hidden spec__card">
                <div class="card-body">
                  <div class="card-text text-black text-xl font-light leading-7">
                    “Nunca tinha visto nada igual! Abordagem de primeira sobre o marketing”
                  </div>
                  <div class="spec__card-meta">
                    <div class="sec__card-meta-avatar">
                      <img
                        v-bind="specialist_avatar"
                        :src="require('~/assets/img/reviews-pictures/avinash_kaushik.png').src"
                        :srcset="require('~/assets/img/reviews-pictures/avinash_kaushik.png').srcSet"
                        :blank-src="require('~/assets/img/reviews-pictures/avinash_kaushik.png').placeholder"
                        alt="Avinash Kaushik Photo"
                      >
                    </div>
                    <div class="spec__card-meta-details">
                      <div class="name">
                        Bernardo Junqueira
                      </div>
                      <div class="job">
                        Empresa 1
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="slide slide--5">
              <div class="card overflow-hidden spec__card">
                <div class="card-body">
                  <div class="card-text text-black text-xl font-light leading-7">
                    “Abriram minha cabeça para o que é marketing de verdade. Agora sei como escalar minha empresa.”
                  </div>
                  <div class="spec__card-meta">
                    <div class="sec__card-meta-avatar">
                      <img
                        v-bind="specialist_avatar"
                        :src="require('~/assets/img/reviews-pictures/bryan_eisenberg.png').src"
                        :srcset="require('~/assets/img/reviews-pictures/bryan_eisenberg.png').srcSet"
                        :blank-src="require('~/assets/img/reviews-pictures/bryan_eisenberg.png').placeholder"
                        alt="Bryan Eisenberg Photo"
                      >
                    </div>
                    <div class="spec__card-meta-details">
                      <div class="name">
                        Jonas Rocha
                      </div>
                      <div class="job">
                        Empresa 3
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <template slot="prevButton">
              <svg class="h-8 fill-current inline" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 477.175 477.175">
                <g>
                  <path d="M360.731,229.075l-225.1-225.1c-5.3-5.3-13.8-5.3-19.1,0s-5.3,13.8,0,19.1l215.5,215.5l-215.5,215.5c-5.3,5.3-5.3,13.8,0,19.1c2.6,2.6,6.1,4,9.5,4c3.4,0,6.9-1.3,9.5-4l225.1-225.1C365.931,242.875,365.931,234.275,360.731,229.075z "/>
                </g>
              </svg>
            </template>
            <template slot="nextButton">
              <svg class="h-8 fill-current inline" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 477.175 477.175">
                <g>
                  <path d="M145.188,238.575l215.5-215.5c5.3-5.3,5.3-13.8,0-19.1s-13.8-5.3-19.1,0l-225.1,225.1c-5.3,5.3-5.3,13.8,0,19.1l225.1,225c2.6,2.6,6.1,4,9.5,4s6.9-1.3,9.5-4c5.3-5.3,5.3-13.8,0-19.1L145.188,238.575z"/>
                </g>
              </svg>
            </template>
          </agile>
        </client-only>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionZmotAuditReviews',
  data: () => ({
    specialist_avatar: { blank: false, width: 85, height: 85, class: 'm-2' },
    agileOptions: {
      autoplay: true,
      mobileFirst: true,
      navButtons: false,
      centerMode: true,
      infinite: true,
      slidesToShow: 1,
      dots: true,
      responsive: [
        {
          breakpoint: 600,
          settings: {
            slidesToShow: 2
          }
        },
        {
          breakpoint: 900,
          settings: {
            slidesToShow: 3
          }
        }
      ]
    }
  })
}
</script>
