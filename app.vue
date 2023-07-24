<template>
  <NuxtLayout>
    <Head>
      <Title>
        خیریه مینو
      </Title>
    </Head>
    <NuxtPage />
  </NuxtLayout>
</template>
<script>
export default {
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
