<template lang="pug"> 
div.inner
	top
	main-article
	portfolio
</template>

<script>

import Header from './elements/common/Header.vue'
import MainArticle from './elements/home/MainArticle.vue'
import Features from './elements/home/Features.vue'
import Portfolio from './elements/home/Portfolio.vue'

export default {
	name: 'app',
	data () {
		return {
			msg: 'Welcome to Your Vue.js App'
		}
	},
	components: {
		'top': Header,
		'main-article': MainArticle,
		'features': Features,
		'portfolio': Portfolio
	}
}

</script>