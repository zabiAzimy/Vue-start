<template>
<h4 id="pages">Two Way Binding with multiple input boxes</h4>

<label for="Cricket">Cricket</label>
<input type="checkbox" name="Cricket" value="cricket" v-model="sports">
&nbsp;

<label for="Hockey">Hockey</label>
<input type="checkbox" name="Hockey" value="hockey" v-model="sports">
&nbsp;

<label for="Football">Football</label>
<input type="checkbox" name="Football" value="football" v-model="sports">
<h3>Selected Sports: {{ sports }}</h3>

<br><br>
<hr>
<label for="name">Smith</label>
<input type="radio" name="name" value="Smith" v-model="player">
&nbsp;

<label for="name">Jira</label>
<input type="radio" name="name" value="Jira" v-model="player">
<h3>Selected Player: {{ player }}</h3>

</template>



<script>
export default{
    name: 'input-boxes',

    data(){
        return {
            sports: [],
            player: []
        }
            
    },
    methods:{


    }
}
</script>





<style>
#pages{
    color: rgb(22, 165, 58);
}
</style>