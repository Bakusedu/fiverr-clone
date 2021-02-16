<template>
    <div class="px-8 py-4 flex items-center text-white justify-between">
        <Logo />
        <div>
            <ul class="flex">
                <li class="font-bold p-1 mr-2"><span>Fiverr Business</span></li>
                <li class="font-bold p-1 mr-2"><span>Explore</span></li>
                <li class="font-bold p-1 flex items-center mr-2"><web :size="20" class="mr-1" /><span>English</span></li>
                <li class="font-bold uppercase flex items-center mr-2 p-1 mr-2"><usd :size="20" /><span>Usd</span></li>
                <li class="font-bold p-1 mr-2"><span>Become a Seller</span></li>
                <li class="font-bold p-1 mr-2"><span>Sign in</span></li>
                <li class="font-bold py-1 px-5 border border-white rounded-md"><span>Join</span></li>
            </ul>
        </div>
    </div>
</template>

<script>
import Web from 'vue-material-design-icons/Web.vue';
import Usd from 'vue-material-design-icons/CurrencyUsd.vue';
export default {
    components: {
        Web,Usd
    }
}
</script>

<style>

</style>