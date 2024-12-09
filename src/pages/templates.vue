<template>
    <v-container>
        <h1>Templates and Components</h1>
        <ol>
            <li>
                <p>You can use ready-made components and create new experiments based on them. To do this, you need to go to the <strong>admin panel</strong> and create a new experiment, then select a template from the list of templates.</p>
            </li>
            <li>
                <p>If your task is not included in the list of templates, you can create a new component and use it in your experiment. To create a new component, you need to go to the <strong>admin panel</strong> and create a new template, then write the component code in the <em>component</em> field.</p>
            </li>
            <li>
                <p>After that, you need to create the same Vue.js component in the project <code>client</code> at the path <code>client/src/components/templates</code> and use it in your experiment.</p>
            </li>
        </ol>
    </v-container>
</template>
<script lang="ts">
export default {
    name: 'Templates'
}
</script>