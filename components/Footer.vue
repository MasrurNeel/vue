<template>
    <div>
       <div class="container">
           <div class="flex mx-4 mb-10">
               <div class="w-1/4 px-4 flex items-center">
                   <div class="min-w-max mr-3">
                       <img src="~/assets/img/customer-support.png" class="mr-4" alt="" width="70">
                   </div>
                   <div class="w-full">
                       <h3 class="text-xl font-medium mb-2">24 Customer Support</h3>
                       Contact us 24 hours
                   </div>
               </div>

               <div class="w-1/4 px-4 flex items-center">
                   <div class="min-w-max mr-3">
                       <img src="~/assets/img/authentic-products.png" class="mr-4" alt="" width="70">
                   </div>
                   <div class="w-full">
                       <h3 class="text-xl font-medium mb-2">Authentic Products</h3>
                       Contact us 24 hours
                   </div>
               </div>

               <div class="w-1/4 px-4 flex items-center">
                   <div class="min-w-max mr-3">
                       <img src="~/assets/img/secure-payment.png" class="mr-4" alt="" width="70">
                   </div>
                   <div class="w-full">
                       <h3 class="text-xl font-medium mb-2">Secure Payment</h3>
                       Contact us 24 hours
                   </div>
               </div>

               <div class="w-1/4 px-4 flex items-center">
                   <div class="min-w-max mr-3">
                       <img src="~/assets/img/best-price.png" class="mr-4" alt="" width="70">
                   </div>
                   <div class="w-full">
                       <h3 class="text-xl font-medium mb-2">Best Prices & Offers</h3>
                       Contact us 24 hours
                   </div>
               </div>
           </div>
       </div>

        <div class="bg-gray-200 py-20">
            <div class="container">
                <div class="flex">
                    <div class="w-3/5 pr-10">
                        <Logo/>
                        <p class="my-8">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla diam ornare nam est gravida. Netus viverra rhoncus sit magna sapien ac eget parturient id. Est luctus dapibus quam aliquam in nisl turpis. Elit et dictum lacus morbi nec accumsan a in.</p>
                        <div class="flex">
                            <a class="mr-4" href="" target="_blank"><img src="~/assets/img/appstore.png" class="mr-4" alt="" width="90px"></a>
                            <a href="" target="_blank"> <img src="~/assets/img/playstore.png" class="mr-4" alt="" width="100px"></a>
                        </div>
                    </div>
                    <div class="w-1/5 pl-6">
                        <h3 class="text-2xl mb-6">About Us</h3>
                        <ul class="leading-loose">
                            <li><nuxt-link to="/">About Karte</nuxt-link></li>
                            <li><nuxt-link to="/"> Contact</nuxt-link></li>
                            <li><nuxt-link to="/">Career</nuxt-link></li>
                            <li><nuxt-link to="/"> Terms & Conditions</nuxt-link></li>
                            <li><nuxt-link to="/"> Category</nuxt-link></li>
                        </ul>
                    </div>
                    <div class="w-1/5 pl-6">
                        <h3 class="text-2xl mb-6">About Us</h3>
                        <ul class="leading-loose">
                            <li><nuxt-link to="/">About Karte</nuxt-link></li>
                            <li><nuxt-link to="/"> Contact</nuxt-link></li>
                            <li><nuxt-link to="/">Career</nuxt-link></li>
                            <li><nuxt-link to="/"> Terms & Conditions</nuxt-link></li>
                            <li><nuxt-link to="/"> Category</nuxt-link></li>
                        </ul>
                    </div>
                </div>

                <div class="flex">
                    <div class="w-1/3">

                    </div>
                    <div class="w-1/3">
                        <p><span>&copy;</span>2022 Copyright All Right Reserved by Bengal Shop</p>
                    </div>
                    <div class="w-1/3">
                        <a class="mr-4" href="" target="_blank"><img src="~/assets/img/payments.png" class="mr-4" alt="" width="175px"></a>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>
<script>
    export default {
        name: "Footer"
    }
</script>
<style scoped>

</style>
