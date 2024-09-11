---
layout: base
toc: True
title: SASS Project
description: Project utilizing SASS styles
type: ccc
permalink: /sassproject
---

<style>
/* Variables */
:root {
    --primary-color: #3498db;
    --secondary-color: #2ecc71;
    --accent-color: #e74c3c;
    --font-stack: Helvetica, sans-serif;
    --button-padding: 10px 20px;
}

/* General styles */
body {
    font-family: var(--font-stack);
    background-color: #f4f4f4;
    padding: 20px;
    margin: 0;
}

/* Header styles */
header {
    background-color: var(--primary-color);
    color: white;
    text-align: center;
    padding: 15px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

header h1 {
    margin: 0;
    font-size: 2rem;
}

/* Button styles with hover and active states */
button {
    color: white;
    border: none;
    padding: var(--button-padding);
    cursor: pointer;
    font-size: 16px;
    border-radius: 5px;
    transition: background-color 0.3s ease, transform 0.2s ease;
}

button:hover {
    filter: brightness(90%);
    transform: translateY(-2px);
}

button:active {
    transform: translateY(2px);
}

.button-primary {
    background-color: var(--primary-color);
}

.button-secondary {
    background-color: var(--secondary-color);
}

.button-accent {
    background-color: var(--accent-color);
}

/* Layout styles */
main {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 30px;
}

/* Media query for responsiveness */
@media (max-width: 600px) {
    header h1 {
    font-size: 1.5rem;
    }

    main {
    flex-direction: column;
    align-items: center;
    }

    button {
    width: 100%;
    max-width: 200px;
    }
}

/* Output styles */
.output {
    text-align: center;
    margin-top: 20px;
    font-size: 1.2rem;
    font-weight: bold;
}

/* Output colors */
.primary-color {
    color: var(--primary-color);
}

.secondary-color {
    color: var(--secondary-color);
}

.accent-color {
    color: var(--accent-color);
}
</style>

<!-- Header -->
<header>
<h1>SASS Mini Project</h1>
</header>

<!-- Buttons Section -->
<main>
<button class="button-primary" onclick="showOutput('Primary Button', 'primary-color')">Primary Button</button>
<button class="button-secondary" onclick="showOutput('Secondary Button', 'secondary-color')">Secondary Button</button>
<button class="button-accent" onclick="showOutput('Accent Button', 'accent-color')">Accent Button</button>
</main>

<!-- Output Section -->
<div class="output" id="output"></div>

<script>
// Function to display the output with the specified color
function showOutput(buttonName, colorClass) {
    const outputDiv = document.getElementById('output');
    outputDiv.textContent = buttonName;
    outputDiv.className = `output ${colorClass}`;  // Assign the color class
}
</script>
