<template>
  <div>
      你好，这里是Vue3.0
  </div>
</template>

<script>
export default {
    setup() {
        const sayHello = () => {
            window.alert('hello')
        }
        return {
            sayHello
        }
    }

}
</script>

<style>
div{
    background-color: pink;
}

</style>