<script>
import { VueFhirSample } from './entry';
export default {
    name:  'VueFhirLibDev', // vue library dev component
    components: {
        VueFhirSample,
    },
}
</script>

<template>
    <div class="vue-fhir-lib-dev">
        <vue-fhir-sample></vue-fhir-sample>
    </div>
</template>

<style scoped>
    .vue-fhir-lib-dev {
        display: block;
        width: 400px;
        margin: 25px auto;
    }
</style>
