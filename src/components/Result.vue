<template>
  <div class="result">
        <div class="title">You got sample result {{result}}!</div>
        <div class="desc">
            Enter a short description here about the result.
        </div>
    </div>
</template>

<script>
export default {
    name:'Result',
    props:['result']
    

}
</script>

<style>

</style>