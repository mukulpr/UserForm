<template>
    <ul>
        <li><button>Poor</button></li>
        <li><button>Average</button></li>
        <li><button>Button</button></li>
    </ul>
</template>
<style scoped>
ul{
    list-style: none;
    margin: 0.5rem;
    padding: 0;
    display: flex;
}
li{
    margin: 0 1rem;
    border: 1px solid #ccc;
    padding: 1rem;
    display: flex;
    justify-content: center;
    align-items: center
}
button{
    font: inherit;
    border: none;
    background-color: transparent;
    cursor: pointer;
}
</style>