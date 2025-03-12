<template>
  <div>
  <BaseAlert v-if="showAlert" :variant="variant" @close="onClose()" :text="text"/>
  </div>
</template>
<script>
import BaseAlert from './components/BaseAlert.vue';

export default {
  name: 'App',
  components: {BaseAlert},
  data(){
    return{
      showAlert: true,
      variant: 'success',
      text: 'Seu formulário foi enviado!'
    }
  },
  beforeCreate(){
  },
  created(){
  },
  beforeMount(){
  },
  mounted(){
  },
  beforeUnmount(){
  },
  unmounted(){
  },
  watch: {
   
  },
  computed: {

  },
  methods: {
    onClose() {
      this.showAlert = false
      console.log("On Close")
    }
  },
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>

<!--
<template>
  <div>
  
  </div>
</template>
<script>
export default {
  name: 'App',
  components:,
  data(){
    return{
    }
  },
  beforeCreate(){
  },
  created(){
  },
  beforeMount(){
  },
  mounted(){
  },
  beforeUnmount(){
  },
  unmounted(){
  },
  watch: {
   
  },
  computed: {

  },
  methods: {

  },
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>

<template>
  <div>
  <BaseAlert :variant="variant" :text="text"/>
  </div>
</template>
<script>
import BaseAlert from './components/BaseAlert.vue';

export default {
  name: 'App',
  components: {BaseAlert},
  data(){
    return{
      variant: 'success',
      text: 'Seu formulário foi enviado!'
    }
  },
  beforeCreate(){
  },
  created(){
  },
  beforeMount(){
  },
  mounted(){
  },
  beforeUnmount(){
  },
  unmounted(){
  },
  watch: {
   
  },
  computed: {

  },
  methods: {

  },
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>

<template>
  <div>
  <div class="card">
    teste
  </div>
    <BaseCard/>
  </div>
</template>
<script>
import BaseCard from './components/BaseCard.vue';

export default {
  name: 'App',
  components: {BaseCard},
  data(){
    return{
    }
  },
  beforeCreate(){
  },
  created(){
  },
  beforeMount(){
  },
  mounted(){
  },
  beforeUnmount(){
  },
  unmounted(){
  },
  watch: {
   
  },
  computed: {

  },
  methods: {

  },
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>

<template>
  <div>  
    <TheHeader>
      <template v-slot:title>
        <h1>Home</h1>
      </template>
      <template v-slot:description>
        <p>Hello people, books on the table</p>
      </template>
      Content do header - menu ...
    </TheHeader>
  </div>
</template>
<script>
import TheHeader from '@/components/TheHeader.vue'
export default {
  name: 'App',
  components: {TheHeader},
  data(){
    return{
    }
  },
  beforeCreate(){
  },
  created(){
  },
  beforeMount(){
  },
  mounted(){
  },
  beforeUnmount(){
  },
  unmounted(){
  },
  watch: {
   
  },
  computed: {

  },
  methods: {

  },
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>

<template>
  <div>
    <h1>Hello Word</h1>
    {{ name }}
  </div>
</template>
<script>
export default {
  name: 'App',
  data(){
    return{
      name: 'Davi Teles'
    }
  },
  //Criação
    //Preparar o componente
    // Ajax, inicializar algumas variaveis
    // não tem acesso ao Template(DOM)
  //Montagem
    // inicializar uma lib externa (new lib)
    //Precisa de acesso ao template (DOM)
    // Tem acesso ao template (DOM)
  //Atualização
    //Debug
    //Update
  //Desmontagem
    // Remover tudo o que for necessário para liberar memória (lib->destroy())

  //Hooks
  beforeCreate(){
    console.log('beforeCreate');
    console.log('Estado do componente: ',this.name);
    console.log('DOM', this.$el);
  },
  created(){
    console.log('created');
    console.log('Estado do componente: ',this.name);
    console.log('DOM', this.$el);
  },
  beforeMount(){
    console.log('beforeMount');
    console.log('Estado do componente: ',this.name);
    console.log('DOM', this.$el);
  },
  mounted(){
    console.log('mounted');
    console.log('Estado do componente: ',this.name);
    console.log('DOM', this.$el);
  },
  beforeUnmount(){
    console.log('beforeUnmount')
  },
  unmounted(){
    console.log('unmounted')
  },
  watch: {
   
  },
  computed: {

  },
  methods: {

  },
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
<template>
</template>
<script>
export default {
  name: 'App',
  data(){
    return{
    }
  },
  watch: {
   
  },
  computed: {

  },
  methods: {

  },
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>

<template>
  <div>
    <input v-model="name" text="text">
  </div>
  <br/>
  {{ name }}
  <br/><br/><br/>
  <input v-model="user.first_name" text="text">
  <br/>
  <input v-model="user.last_name" text="text">
  <br/>
  <br/>
  {{ user.first_name }} {{ user.last_name }}
  <br/> <br/>
  <select v-model="pageCount">
    <option value="5">5</option>
    <option value="10">10</option>
    <option value="15">15</option>
  </select> <br>
  {{ pageCount }}
</template>
<script>
export default {
  name: 'App',
  data(){
    return{
      name: 'Davi',
      pageCount: 5,
      user: {
        first_name: '',
        last_name: '',
      }
    }
  },
  watch: {
    name(vl) {
      if(vl.length >=3){
        this.saveUserName()
      }
    },
    pageCount() {
      this.changePage();
    },
    user: {
      handler (){
        console.log('User alterado');
      },
      deep: true
    }
  },
  computed: {

  },
  methods: {
    saveUserName(){
      console.log('Ajax');
      console.log(this.name);
    },
    changePage(){
      console.log('Ajax ChangePage')
    }
  },
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>


<template>
  <button @click="Click">Clicar</button>
  {{fullName}}<br/>
  <br>
  <h2>Todos em aberto</h2>
<div v-for="todo in uncompletedtodos" :key="todo.id">
{{ todo.title }} 
</div>
<h2>Todos completas</h2>
<div v-for="todo in completedtodos" :key="todo.id">
{{ todo.title }} 
</div>
<h2>Todos</h2>
<div v-for="todo in todos" :key="todo.id">
  <input v-model="todo.completed" type="checkbox">
{{ todo.title }} 
</div>
</template>
<script>
export default {
  name: 'App',
  data(){
    return{
      user: {
        first_name:'Avraham',
        last_name: 'Avinu',
      },
        todos: [
              {
                "userId": 1,
                "id": 1,
                "title": "delectus aut autem",
                "completed": false
              },
              {
                "userId": 1,
                "id": 2,
                "title": "quis ut nam facilis et officia qui",
                "completed": false
              },
              {
                "userId": 1,
                "id": 3,
                "title": "fugiat veniam minus",
                "completed": false
              },
              {
                "userId": 1,
                "id": 4,
                "title": "et porro tempora",
                "completed": true
              },
              {
                "userId": 1,
                "id": 5,
                "title": "laboriosam mollitia et enim quasi adipisci quia provident illum",
                "completed": false
              }
              ],
      }   
    },
  computed:{
    fullName() {
     return `${this.user.first_name} ${this.user.last_name}`;
    },
    uncompletedtodos(){
      return this.todos.filter(todo => !todo.completed);
    },
    completedtodos(){
      return this.todos.filter(todo=>todo.completed);
    }
  },
  methods:{
    Click(){
      console.log(this.user);
    }
  }
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>


-- Default
<template>

</template>
<script>
export default {
  name: 'App',
  data(){
    return{
      
    }
  }
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
--------------------------------

<template>
  <main>
    <button v-on:click="onClick">
      Enviar
    </button>
    <button @click.once="onClick">
      Enviar
    </button>
    <div @mouseover="onMouseOver" @mouseout="onMouseOut">
      Mouse Over
    </div>
    <br><br>

    <form action="https://google.com" @submit.prevent="onSubmit">
      <input type="text" @keyup.enter="onKeyUp">
    <button type="submit">
      Enviar
    </button>
  </form>
  </main>
</template>
<script>
export default {
  name: 'App',
  data(){
    return{
      
    }
  },
  methods: {
    onClick($evt){
      console.log('click', $evt);
    },
    onMouseOver($evt){
      console.log('Mouse Over', $evt)
    },
    onMouseOut($evt){
      console.log('Mouse Out', $evt)
    },
    onSubmit($evt){
      console.log('submit', $evt)
    },
    onKeyUp($evt) {
      console.log('OnKeyUp', $evt)
    }
  }
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>

-- Two Way Data Binding

<template>
    <main>
      <div class="divisao">
        One-way data binding <br>
        Two-way data binding <br>
        v-model -> formulários
      </div>
      <br/><br/>
      <div class="divisao">
        <label>Nome</label><br>
        <input v-model="name" type="text"><br>
        {{ name }}
      </div>
      <br><br>
      <div class="divisao">
        <label>Sports</label>
        <select v-model="sports">
          <option value="">Escolha</option>
          <option value="futebol">Futebol</option>
          <option value="skate">Skate</option>
          <option value="tenis">Tênis</option>
        </select>
        <br>
        {{ sports }}
      </div>
      <br/><br/>
      <div class="divisao">
        <label>Newsletter</label><br>
        <input v-model="newsletter" type="radio" value="Sim">Sim
        <input v-model="newsletter" type="radio" value="Não">Não
        <br>
        {{ newsletter }}
      </div>
      <br><br>
      <div class="divisao">
        <label>Contrato</label><br>
        <input v-model="contract" type="checkbox">
        <br>
        >Aceita nessos termos ... <br>
        {{ contract }}
      </div>
      <br/><br/>
      <div class="divisao">
        <label>Cores que você mais gosta</label><br>
        <input v-model="colors" type="checkbox" value="Azul">Azul
        <input v-model="colors" type="checkbox" value="Amarelo">Amarelo
        <br>
        {{ colors }}
      </div>
    </main>
</template>
<script>
export default {
name: 'App',
data(){
    return {
        name: 'Judá Cohen',
        sports: '',
        newsletter: '',
        contract: 'false',
        colors: [],
    }
}
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

main {
  width: 50%;
  margin: 0 auto;
  text-align: center;
}

.divisao{
  display: inline-block;
}
</style>

-- Primeiras aulas

<template>
  <TheHeader v-if="showheader"/>
  <div v-show="showfirstname">
    Nome:{{ firstname }}<br/>
    Sobrenome:{{ lastname }}
  </div>
  <div v-show="showfirstname">
    <div v-if="acceslevel==='admin'">Usuário Admin</div>
    <div v-else-if="acceslevel==='marketing'"> Usuário Marketing</div>
    <div v-else>Usuário Normal</div>
  </div>
</template>

<script>

import TheHeader from './components/TheHeader.vue';
export default {
  name: 'App',
  components: {
    TheHeader
  },
  data() {
    return{
      showheader:true,
      firstname: 'Davi',
      lastname: 'Teles',
      showfirstname: false,
      showlastname: true,
      acceslevel: 'admin'
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
-->