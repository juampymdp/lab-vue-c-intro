<script setup></script>

<template>
<footer>
    <div class="feature">
        <img src='../images/USP-1.png' alt="Performant">
        <h3>Performant</h3>
        <p>Truly reactive, compiler-optimized rendering system that rarely requires manual optimization.</p>
    </div>
    <div class="feature">
        <img src='../images/USP-2.png' alt="Approachable">
        <h3>Approachable</h3>
        <p>Builds on top of standard HTML, CSS and JavaScript with intuitive API and world-class documentation.</p>
    </div>
    <div class="feature">
        <img src='../images/USP-3.png' alt="Versatile">
        <h3>Versatile</h3>
        <p>A rich, incrementally adoptable ecosystem that scales between a library and a full-featured framework.</p>
    </div>
</footer>
</template>

<style scoped>
footer {
    display: flex;
    justify-content: center;
    gap: 40px;
    padding: 20px;
    background-color: #39B983;
    text-align: center;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

.feature {
    max-width: 250px;
}

.feature img {
    width: 60px; /* Ajusta el tamaño de las imágenes según necesites */
    height: auto;
}

h3 {
    color: #000000;
    margin-top: 10px;
}

p {
    color: #000000;
    font-size: 12px;
    font-weight: lighter;
    line-height: 150%;
}
</style>
