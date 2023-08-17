<template>
    <section class="property-listing">
        <div class="property-card">
            <img src="property-image.jpg" alt="property img">
            <p class="description">Experience luxury living with easy search for properties and cars to buy or rent at PataKejah. We provide exquisite service linking you up with the your dream home or car with ease at budget friendly costs. Our listed properties and cars are of quality standard ensuring that we fulfill your needs. Welcome to PataKejah. </p>
            <a href="#" class="btn">Learn More</a>
        </div>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

header {
    background-color: #2196F3;
    color: #fff;
    text-align: center;
    padding: 20px;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
}

.property-listing {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 50px;
}

.property-card {
    border: 1px solid #ccc;
    padding: 20px;
    text-align: center;
    background-color: #fff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.property-card img {
    max-width: 100%;
    height: auto;
    margin-bottom: 10px;
}

.price {
    color: #2196F3;
    font-size: 1.2rem;
    font-weight: bold;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    background-color: #2196F3;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.btn:hover {
    background-color: #1565C0;
}

</style>