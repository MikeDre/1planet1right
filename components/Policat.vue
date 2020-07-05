<template>
    <div>
        <div id="policat" ref="policat"></div>
    </div>
</template>

<script>
export default {
  mounted() {
    const script = document.createElement("script");
    script.type = "text/javascript";
    script.src = "https://www.policat.org/api/js/widget/9235";
    document.body.appendChild(policat);
  }
}
</script>


<style lang="scss">
</style>
