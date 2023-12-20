<template>
    <div class="container">
        <div class="row">
            <p class="lead">
                Razien's Portfolio &copy;
                <span>{{ currYear }}</span>
            </p>
        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return{
                currYear: new Date().getFullYear()
            }
        }
    }
</script>

<style scoped>

</style>