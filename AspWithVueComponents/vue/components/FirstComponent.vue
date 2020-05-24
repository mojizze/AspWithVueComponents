<template>
    <div>
        The year is {{ year }}
    </div>
</template>

<script>
    module.exports = {
        data() {
            return {
                year: new Date().getFullYear()
            }
        },
        mounted() {
            console.log("Hello there");
        }
    }
</script>