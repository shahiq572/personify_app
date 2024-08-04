<template>
    <div class="dashboard">
        <h1>Dashboard</h1>
        <div class="dashboard-sections">
            <Profile />
            <Tasks />
            <Stats />
        </div>
    </div>
</template>

<script>
    import Profile from "./components/Profile.vue";
    import Tasks from "./components/Tasks.vue";
    import Stats from "./components/Stats.vue";

    export default {
        name: "dashboard-component",
        components: {
            Profile,
            Tasks,
            Stats,
        },
    };
</script>

<style>
    .dashboard {
        padding: 2rem;
    }
    .dashboard-sections {
        display: flex;
        flex-direction: column;
        gap: 2rem;
    }
</style>
