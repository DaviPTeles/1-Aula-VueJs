<template>
    <header class="header">
        <div class="title">
            <slot name="title"/>
        </div>
        <div class="description">
            <slot name="description"/>
        </div>
        <div class="content">
            <slot/>
        </div>
    </header>
</template>


<script>
export default {

}
</script>
<style>
   .header {
    background-color: black;
    color: white;
    text-align: left;
   }
</style>
<!--<template>
    <div>
        <h1 :class="tclass">
            Curso Vue 3
        </h1>
        <p :class="['text', {'title':false, 'text-home': ishome}]">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Id eveniet accusantium blanditiis eos dolorem placeat at? Mollitia, laudantium atque sit dolor quisquam, ipsam dicta incidunt quo aperiam vel optio distinctio!</p>
        <p :style="styleclass">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque in rerum aliquid vitae tenetur quae et expedita. Alias non temporibus voluptatem molestiae corporis asperiores sint similique pariatur natus? Eaque, eum!</p>
        <div>
            <label for="name">Nome: </label>
            <input type="text" v-model="name">
        <br>
        {{ name }}
        </div>
        <br>
        <div>
            <label for="sports">Sports</label><br>
            <select v-model="sports">
                <option value="">Escolha</option>
                <option value="futebol">Futebol</option>
                <option value="skate">Skate</option>
                <option value="tenis">tenis</option>
            </select><br>
            {{ sports }}
        </div>

        <div>
            <label for="">News letter</label>
            <input type="radio" value="Sim">Sim
            <input type="radio" value="Não">Não
        </div>  
        <img v-bind:src="imgSrc" v-bind:alt="imgAlt">
        <div v-for="(obj, index) in users" :key="obj.id" class="todos-items">
            <img v-bind:src="obj.imgSrc" v-if="obj.imgSrc">
           {{ index }} - {{ obj.
           name }}
        </div>
    </div>
</template>

<script>
export default {
    name: 'App',
    data () {
        return {
            users: [
        { id: 1, name: 'Alice', age: 28 , imgSrc: 'https://placehold.co/150x150'},
        { id: 2, name: 'Bob', age: 34, imgSrc: 'https://placehold.co/150x150'},
        { id: 3, name: 'Charlie', age: 25, imgSrc: 'https://placehold.co/150x150'},
        { id: 4, name: 'Diana', age: 42, imgSrc: 'https://placehold.co/150x150'},
        { id: 5, name: 'Jack', age: 33, }
      ],
            classvar:'title',
            pclass:'text',
            styleclass: {'color': 'aqua', 'backgroundColor':'black', 'fontSize':'20px'},
            ishome: true,
            tclass: {'title':false, 'title-home': true},
            name:'Davi Teles',
            sports:''
            
            //imgAlt:'Foto de Hello There',   
        }
    }
}
</script>
<style>
    .title {
        font-size: 20px;
        color: blue;
    }
    .title-home {
        font-size: 40px;
        color: green;
    }
    .text {
        color: gray;
    }
    .text-home {
        color:yellowgreen
    }
    .todos-items {
        background: #000;
        margin: 0 0 5px 0;
        padding: 3px 6px;
        color: #fff;
        text-align: left;
    }
    .TheHeader {
        background-color: #000;
        color: #fff;
    }

</style>-->