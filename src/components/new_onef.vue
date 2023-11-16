<template>
<div class="even">
    <h3>Enter a number below: </h3>

    <input type="text"  placeholder="Enter a number here" v-model="count">
    <h3>Even number: {{ count%2==0?'Yes':'No' }}</h3>
</div>
</template>

<script>
export default{
    name: 'PAGES',
    data(){
        return {
            email: 'zabi@gmail.com',
            mobile: "555",
            count:0,

            getName: function(param){
                return param;
            }
            }
        }
            
        }

</script>
<style scoped>
h1{
    color: rgb(79, 79, 180);
}

.even{
    padding: 20px;
    border: thick double #32a1ce;
    border-radius: 25px;
}
</style>