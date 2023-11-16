<template>
<button v-on:click="display = !display">{{ display == true ? 'Hide':'Show' }}</button>

<p id="para" v-if="display">Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat explicabo rerum eaque neque earum obcaecati. Perspiciatis ullam, magni, fugit architecto repellendus quo animi sunt nostrum aliquid eligendi suscipit omnis porro.</p>

<h4 v-else>The paragraph is hidden.</h4>
</template>

<script>
export default{
    name: 'ShowHide',
    data() {
        return{
            display: false,
        }

    }
}
</script>


<style>
#para {
    padding: 20px;
    border: dashed rgb(234, 63, 63);
    border-radius: 5px;
}

</style>