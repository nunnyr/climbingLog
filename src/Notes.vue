
<template>
    <BlogLayout>
        <template v-slot:header>
            <h1>Page title <h1>
        </template>

        <template>
            <p>my page content </p>
        </template>

        <template v-slot: sidebar>
            <ul>
                <li>Bullet #1 <li>
                <li>Bullet #2 <li>
            <ul>
        </template>
        </BlogLayout>
    </template>

<!--The slots will correspond with the slot name over in our BlogLayout component.
-->
<!-- Any slot without a name will be given the name="default. You are welcomed to omit this as well -->

<!-- Slots are great because they provide data and allow us to see what shows up inside of the child. -->