<template>
    <div id="MenuOverlay" class="fixed z-50 bottom-0 h-full w-full bg-white px-3">
        <div class="w-full flex items-center justify-center py-5 bg-blue-900">
            <NuxtLink class="gb-blue-900">
                <img 
                    width="170"
                    src="/logo.png"
                >
            </NuxtLink>

            <button
                class="rounded-full p-1 hover:bg-gray-200"
            >
                <Icon name="mdi:close" size="30" color="#ffffff"/>
            </button>
        </div>
    
    </div>
</template>

<script setup>
</script>