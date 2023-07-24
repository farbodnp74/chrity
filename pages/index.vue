<template>
  <div lang="fa" class="min-h-screen bg-cyan-300" style="text-align: center">
    <TheWelcome class="top-0 sticky z-40 "/>
    <div class="container hidden md:flex text-center mx-auto items-center mb-5" >
      <button @click="redirect" class="justify-center text-center mx-auto items-center pb-12" >
        <section class="hexagon-gallery mx-auto text-center">
          <div class="hex  ">
            <img class="" src="~/public/prod/4.jpg" alt="ست جراحی"></div>
          <div class="hex animate-pulse">
            <img src="~/public/prod/5.jpg" alt="کلاه">
          </div>
          <div class="hex ">
            <img
                src="~/public/prod/6.jpg" alt="گان جراحی">
          </div>
          <div class="hex animate-pulse">
            <img src="~/public/prod/1.jpg" alt=" شلوار جراحی">
          </div>
          <div class="hex  ">
            <img src="~/public/prod/8.jpg" alt=" کلاه پزشک">
          </div>
          <div class="hex ">
            <img src="~/public/prod/7.jpg"  class="w-1/2" alt=" دراشیت">
          </div>
          <div class="hex animate-pulse">
            <img src="~/public/prod/3.jpg"  class="w-1/2 " alt=" دراشیت">
          </div>
<!--          <div class="hex">-->
<!--            <img src="~/public/product/8.jpg" alt="مینو">-->
<!--          </div>-->
<!--          <div class="hex">-->
<!--            <img src="~/public/product/9.jpg" alt=" خیریه مینو">-->
<!--          </div>-->
<!--          <div class="hex">-->
<!--            <img src="~/public/product/10.jpg" alt="تولیدی مینو">-->
<!--          </div>-->
        </section>
      </button>
    </div>
    <div class="md:hidden bg-cyan-200">
      <button @click="redirect" class="min-h-screen bg-cyan-300 mx-auto text-center pt-3">
<!--        <img src="~/assets/prod/1.jpg" style="width: 150px; height: 150px" class="rounded-full animate-bounce ml-6  text-left h-52 w-52">-->
<!--        <img src="~/assets/prod/2.jpg" style="width: 200px; height: 200px" class="rounded-full animate-bounce mx-auto text-center h-52 w-52">-->
<!--        <img src="~/assets/prod/3.jpg" style="width: 150px; height: 150px" class="rounded-full animate-bounce ml-24 my-3  text-right h-52 w-52">-->
        <img src="~/assets/prod/7.jpg" style="width: 200px; height: 200px" class="rounded-full animate-bounce  sm:ml-24 lg:ml-0 lg:mx-auto pb-3 h-52 w-52">

      </button>
    </div>

    <TheFooter class="py-5"/>
  </div>
</template>

<script>
import {navigateTo, useRouter} from "nuxt/app";
import TheWelcome from "../components/TheWelcome.vue";
import TheFooter from "../components/TheFooter.vue";
import TheHeroSectionComponent from "../components/TheHeroSectionComponent.vue";

export default {
  components:{TheHeroSectionComponent, TheFooter, TheWelcome},

  setup () {
    function redirect() {

         clearInterval(myInterval)

         return navigateTo('/home')

    }

    const myInterval = setInterval(myTimer, 5000);
    function myTimer() {
      redirect()
      clearInterval(myInterval)
    }
    return { redirect}
  },
  jsonld() {
    return {
      '@context': 'https://schema.org',
      '@type': 'Corporation',
      mainEntityOfPage: {
        '@type': 'WebPage',
        '@id': 'https://iranimarket.com/store'
      },
      headline: ' خیریه مینو',
      description: 'موسسه خیریه مهرو امید پویان مینو خراسان شمالی، سازمان غیر سیاسی، غیر دولتی، غیر انتفاعی است که با هدف ارتقاء سطح توانایی ‌های افراد دارای معلولیت از طریق فرآیند «آموزش خیاطی »،«توانبخشی» و حمایت موثر از« اشتغال و کارآفرینی» عزیزان معلولین جسمی حرکتی و نابینا و ناشنوا از سال 1390 شروع به کار کرد.',
      image: 'https://iranimarket.com/_nuxt/scrf1.47fd393c.jpeg',
      author: {
        '@type': 'Person',
        name: 'فربد نصیری پرتوی'
      },
      datePublished: '7/17/2022',
      dateModified: '7/17/2022',
      publisher: {
        '@type': 'Organization',
        name: 'خیریه مینو',
        logo: {
          '@type': 'ImageObject',
          url: 'httpS://nuxt.markazimarket.com/public/storage/product/11042345975840'
        }
      }
    };
  },
  head: {

    title: 'خیریه مینو',
    description: 'موسسه خیریه مهرو امید پویان مینو خراسان شمالی، سازمان غیر سیاسی، غیر دولتی، غیر انتفاعی است که با هدف ارتقاء سطح توانایی ‌های افراد دارای معلولیت از طریق فرآیند «آموزش خیاطی »،«توانبخشی» و حمایت موثر از« اشتغال و کارآفرینی» عزیزان معلولین جسمی حرکتی و نابینا و ناشنوا از سال 1390 شروع به کار کرد'
        , meta: [
      {name:"google-site-verification" ,content:"_Y9NTv1bukKVeHHLG0K71UFKgFTeH0dtwHoiR9bg0oI" },
      { name: 'description', content: 'در ایرانی مارکت هرچی بخواین با کمترین هزینه در اختیار شما با ارسال رایگان است برای خرید لطفا کلیک کنید ' },
      {
        hid: 'og:title',
        property: 'og:title',
        content: 'خیریه مینو'
      },
      {
        hid: 'og:description',
        property: 'og:description',
        content: 'موسسه خیریه مهرو امید پویان مینو خراسان شمالی، سازمان غیر سیاسی، غیر دولتی، غیر انتفاعی است که با هدف ارتقاء سطح توانایی ‌های افراد دارای معلولیت از طریق فرآیند «آموزش خیاطی »،«توانبخشی» و حمایت موثر از« اشتغال و کارآفرینی» عزیزان معلولین جسمی حرکتی و نابینا و ناشنوا از سال 1390 شروع به کار کردگ',

      },
      {
        hid: 'og:type',
        property: 'og:type',
        content: 'website',
      },
      {
        hid: 'og:url',
        property: 'og:url',
        content: 'https://iranimarket.com/'
      },
      {
        property: 'og:locale',
        content: 'de_DE'
      }
    ],
    link: [{ rel: 'icon', type: 'image/x-icon', href: '/favicon.ico' }]
  }
}

</script>
<style scoped>
img {
  width: 100%;
  height: auto;
  display: block;
  object-fit: cover;
}

.hexagon-gallery {
  margin: auto;
  margin-top: 50px;
  max-width: 1000px;
  display: grid;
  grid-template-columns: repeat(8, 1fr);
  grid-auto-rows: 200px;
  grid-gap: 14px;
  padding-bottom: 50px;
}
.hex {
  display: flex;
  position: relative;
  width: 240px;
  height: 265px;
  background-color: #424242;
  -webkit-clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
  clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
}

.hex:first-child  {
  grid-row-start: 1;
  grid-column: 2 / span 2;
}

.hex:nth-child(2) {
  grid-row-start: 1;
  grid-column: 4 / span 2;
}

.hex:nth-child(3) {
  grid-row-start: 1;
  grid-column: 6 / span 2;
}

.hex:nth-child(4) {
  grid-row-start: 2;
  grid-column: 1 / span 2;
}

.hex:nth-child(5) {
  grid-row-start: 2;
  grid-column: 3 / span 2;
}

.hex:nth-child(6) {
  grid-row-start: 2;
  grid-column: 5 / span 2;
}

.hex:nth-child(7) {
  grid-row-start: 2;
  grid-column: 7 / span 2;
}

.hex:nth-child(8) {
  grid-row-start: 3;
  grid-column: 2 / span 2;
}

.hex:nth-child(9) {
  grid-row-start: 3;
  grid-column: 4 / span 2;
}

.hex:nth-child(10) {
  grid-row-start: 3;
  grid-column: 6 / span 2;
}

.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  opacity: 0;
  transition: .5s ease;
  background-color: rgb(249 250 251 / var(--tw-text-opacity));
}

.container:hover .overlay {
  opacity: 1;
}

.text {
  color: black;
  font-size: 20px;
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  text-align: center;
}
</style>
