<template>
    <h1>This is a calculator</h1>
    <DisplayCalculator :value="displayValue" />
    <NumbersCalculator :onClickNumber="handleClickNumber" />
    <OperatorsCalculator :onClickOperator="handleClickNumber" />
</template>

<script>
import DisplayCalculator from '../Display/index.vue'
import NumbersCalculator from '../Numbers/index.vue'
import OperatorsCalculator from '../Operators/index.vue'

export default {
    name: 'FirtsCalculator',
    components: {
        DisplayCalculator,
        NumbersCalculator,
        OperatorsCalculator,
    },
    data() {
        return {
            displayValue: ''
        };
    },
    methods:{
        handleClickNumber(number){
            this.displayValue += number;
        }
    }
}
</script>