<template>
    <div>
        <nav>
            <!-- Navigation bar -->
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/about">About</a></li>
                <li><a href="/contact">Contact</a></li>
            </ul>
        </nav>

        <div class="container">
            <!-- Main content -->
            <div class="content">
                <h1>Welcome to the Landing Page</h1>
                <p>This is the landing page content.</p>
            </div>
        </div>
    </div>
</template>
<style>
.container {
    display: flex;
}

.panel {
    width: 200px;
    background-color: #f0f0f0;
    transition: width 0.3s;
}

.collapsed {
    width: 0;
}

.content {
    flex: 1;
    padding: 20px;
}
</style>