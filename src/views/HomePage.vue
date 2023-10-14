<template>
    <div class="min-h-screen bg-gray-900 text-white flex flex-col items-center justify-center">
        <h1 class="text-2xl mb-5">
            Template Vue / Vite :
            <a
                href="https://github.com/TheoLaperrouse/TemplateViteVue3"
                target="_blank"
                rel="noopener noreferrer"
                class="text-white"
            >
                <FontAwesomeIcon :icon="['fab', 'github']" /> GitHub
            </a>
        </h1>
    </div>
</template>
<script>
import FontAwesomeIcon from '../../fontawesome';

export default {
    components: {
        FontAwesomeIcon,
    },
};
</script>
