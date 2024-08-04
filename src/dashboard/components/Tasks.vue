<template>
    <div class="tasks">
        <h2>Tasks</h2>
        <h3>Completed Tasks</h3>
        <ul>
            <li>Task 1</li>
            <li>Task 2</li>
            <li>Task 3</li>
        </ul>
        <h3>Upcoming Tasks</h3>
        <ul>
            <li>Task 4</li>
            <li>Task 5</li>
            <li>Task 6</li>
        </ul>
    </div>
</template>

<script>
    export default {
        name: "tasks-list",
    };
</script>

<style>
    .tasks {
        padding: 1rem;
        border: 1px solid #ccc;
        border-radius: 8px;
    }
</style>
