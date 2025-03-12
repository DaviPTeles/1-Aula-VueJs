<template>
    <div :class="baseclass">
        {{text}}
        <button @click="onCLick">
            x
        </button>
    </div>

</template>

<script>
export default {
    props: {
        variant: {
            type: String,
            default: ''
        }, 
        text: {
            type: String,
            default: 'test'
        },
    },
    computed: {
        baseclass() {
            return [
                'alert', this.variant ? `alert-${this.variant}` : ''
            ]
        }
    },
    methods:{
    onCLick() {
        this.$emit('close')
        console.log('Clickou!')
    }
}
}

</script>

<style scoped>
.alert {
    display: flex;
    justify-content: space-between;
    padding: 0.5rem;
    border-radius: 6px;
    color: gray;
    background: #ddd;
    font-weight: bolder;
}

.alert-success {
    background: #42b983;
    color: #fff;
}

.alert-danger {
    background: red;
    color: #fff
}
</style>