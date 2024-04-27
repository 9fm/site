<template>
    <div class="border-4 m-2 rounded-xl   border-gray-400 flex">
        <Icon v-bind:name="icon" class="mt-1 align-middle min-h-[4rem] min-w-[4rem] ml-2"></Icon>
        <div class="mx-2 align-middle     ">
            <span class="text-xl mr-auto  font-extrabold text-left">

                {{ name }}
            </span>
            <p>{{ description }}</p>
        </div>
    </div>
</template>
<script setup  >
defineProps(['name','icon','description'])
</script>