<template lang="pug">
  div
    header-bar
    h1.center.pa-5(style="color: #576fff") ABOUT US
    v-divider
    v-container.max-width
      v-row
        v-col(cols="12" md="6")
          p
            span.high-light 4M Vietnam Technology JSC &nbsp
            span was established in 2020 with the goal to be a stable and reputable supply chain and solution provider to the booming manufacturing industry.
        v-col(cols="12" md="6")
          p
            span.high-light Company Name: 4M Vietnam Technology JSC
          ul.pl-5
            li No 7/9 Le Duc Tho, My Dinh 2, Nam Tu Lien, Hanoi, Vietnam
            li (024) 7102 6888
            li services@4mvietnam.com.vn
        v-col(cols="12" md="6")
          p
            span.high-light Our Vision:
            span To be the company that best understands and satisfies the products, services to needs of customers
        v-col(cols="12" md="6")
          p
            span.high-light Core Values:
          p Quality: We take pride in providing high value products and services, which ensures customer satisfaction, profitability and the future of our employees and our growth
          p Customer Commitment:We provide quality products, efficient services, and innovative solutions resulting in value to customers. Innovation: We foster a work environment where creative thinking is encouraged and rewarded in order to create opportunities for process improvement and more cost-effective sustainable products and services.
    footer-bar
</template>

<script>
</script>


<style scoped>
/* Trong file CSS/SCSS của bạn */
.center {
  margin: 0 auto;
  text-align: center;
}
.max-width {
  max-width: 1300px;
  margin: 0 auto;
}
.high-light {
  font-size: 25px;
  color: #111111;
}
</style>