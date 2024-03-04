<script setup>

</script>
<template>

   <header>
        <nav>
            <ul>
                <li>
                    <NuxtLink to="/">home</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/about">about</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/products/all">products</NuxtLink>
                </li>
            </ul>
        </nav>
    </header>

    <div>productsproducts
        <div>products layout</div>
        <slot />
    </div>

</template>