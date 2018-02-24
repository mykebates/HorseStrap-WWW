<template>
    <div id="nuxt_wrapper">
        <header class="site_header">
            <div class="container">
                <div class="content">
                    <h1><img src="/images/horsestrap.svg" alt="HorseStrap"></h1>

                    <p>
                        An oppionated front-end stub that eNEIGHbles rapid but sturdy development. Fusce dapibus, tellus ac cursus commodo,
                        tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Maecenas faucibus mollis interdum. Morbi
                        leo risus, porta ac consectetur ac, vestibulum at eros. Nullam quis risus eget urna mollis ornare vel eu leo.
                    </p>
                </div>
                <img src="/images/nily.svg" alt="Whoooa Nily" class="nily">
            </div>
        </header>
    </div>
</template>

<script>
//import axios from 'axios';
export default {
    asyncData (context) {
        // return axios.get('https://quipvid.com/api/quips')
        // .then((res) => {
        //     console.log(res.data)
        //     return {
        //         name: 'World',
        //         quips: res.data
        //     }
        // });

        return { name: 'HorseStrap' }
    },

    head: {
        title: "Horse'n Around With HorseStrap",
        bodyAttrs: {
            class: 'home'
        },
        htmlAttrs: {
            class: ''
        },
    }
}
</script>
