<template>
	<span />
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
	beforeCreate() {
		this.$router.push('/404')
	}
})
</script>
