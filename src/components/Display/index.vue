<template>
    <textarea rows="4" cols="50" :value="value"></textarea>
</template>

<script>
export default {
    name: 'DisplayCalculator',
    props: {
        value: String
    }
}
</script>