<template>
    <div className="container-numbers">

        <button className="numbers" @click="handleClickNumber(1)">
            1
        </button>

        <button className="numbers" @click="handleClickNumber(2)">
            2
        </button>

        <button className="numbers" @click="handleClickNumber(3)">
            3
        </button>

        <button className="numbers" @click="handleClickNumber(4)">
            4
        </button>

        <button className="numbers" @click="handleClickNumber(5)">
            5
        </button>

        <button className="numbers" @click="handleClickNumber(6)">
            6
        </button>

        <button className="numbers" @click="handleClickNumber(7)">
            7
        </button>

        <button className="numbers" @click="handleClickNumber(8)">
            8
        </button>

        <button className="numbers" @click="handleClickNumber(9)">
            9
        </button>

        <button className="numbers" @click="handleClickNumber(0)">
            0
        </button>

    </div>
</template>

<script>
export default {
    name: 'NumbersCalculator',
    props: {
        onClickNumber: Function
    },
    methods: {
        handleClickNumber(number){
            this.onClickNumber(number)
        }
    }
}
</script>