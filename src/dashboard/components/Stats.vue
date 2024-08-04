<template>
    <div class="stats">
        <h2>Stats Overview</h2>
        <div class="stats-bar">
            <div class="stat">
                <label>Health</label>
                <div class="progress">
                    <div
                        class="progress-bar"
                        style="width: 70%"
                    >
                        70%
                    </div>
                </div>
            </div>
            <div class="stat">
                <label>Body</label>
                <div class="progress">
                    <div
                        class="progress-bar"
                        style="width: 50%"
                    >
                        50%
                    </div>
                </div>
            </div>
            <div class="stat">
                <label>Intelligence</label>
                <div class="progress">
                    <div
                        class="progress-bar"
                        style="width: 90%"
                    >
                        90%
                    </div>
                </div>
            </div>
            <div class="stat">
                <label>Social</label>
                <div class="progress">
                    <div
                        class="progress-bar"
                        style="width: 80%"
                    >
                        80%
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "stats-section",
    };
</script>

<style>
    .stats {
        padding: 1rem;
        border: 1px solid #ccc;
        border-radius: 8px;
    }
    .stats-bar {
        display: flex;
        flex-direction: column;
        gap: 1rem;
    }
    .stat {
        display: flex;
        flex-direction: column;
    }
    .progress {
        background-color: #f3f3f3;
        border-radius: 8px;
        overflow: hidden;
        height: 24px;
    }
    .progress-bar {
        background-color: #4caf50;
        height: 100%;
        color: white;
        text-align: center;
    }
</style>
