
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


<!--Library.vue-->
2) then we open up our v-slot in template to bind title with slotProps
<template>
    <Book>
        <template v-slot:title="slotProps">
            <h1>{{ bookTitle }}</h1>
        </template>
    </Book>
</template>


<!--Book.vue-->
1) we are adding an attribute of bookTitle to our slot
<template>
    <div class="book">
        <slot name="title"
        
        
        
        />
    </div>
</template>

<script>
export default {
    data() {
        return {
            bookTitle: 'Child Providing Data'
        }
    }
}

</script>
