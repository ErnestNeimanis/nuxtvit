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

    <div>
        <slot />
    </div>

</template>