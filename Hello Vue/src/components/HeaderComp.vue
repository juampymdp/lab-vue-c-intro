<script setup>
</script>

<template>
    <header>
        <img src='../images/ironhack_logo.png' alt="Vue Logo" class="headerlogo">
        <img src='../images/Burger_menu.png' alt="Menu" class="burgermenu">
    </header>

</template>

<style scoped>
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 38px;

    padding: 20px;
    background-color: #ffffff;
}

.headerlogo, .burgermenu {
    width: 35px;
    height: 38px;
}
.burgermenu {
    width: 22px; 
    height: 20px;
}
</style>
