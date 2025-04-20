<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Prompt Library | Business, Coding, Design & More</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #6e48aa;
            --secondary: #9d50bb;
            --dark: #1e1e2c;
            --light: #f5f5fa;
            --success: #4CAF50;
        }
        * {
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
        }
        body {
            background: linear-gradient(135deg, var(--light) 0%, #e6e6f0 100%);
            color: var(--dark);
            line-height: 1.6;
            min-height: 100vh;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem 1rem;
        }
        header {
            text-align: center;
            margin-bottom: 2rem;
        }
        h1 {
            color: var(--primary);
            margin-bottom: 0.5rem;
            font-size: 2.2rem;
        }
        .tagline {
            color: var(--secondary);
            font-weight: 500;
            font-size: 1.1rem;
        }
        /* Quick Navigation */
        .category-nav {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            justify-content: center;
            margin: 2rem 0;
        }
        .category-nav a {
            background: rgba(110, 72, 170, 0.1);
            color: var(--primary);
            padding: 0.6rem 1.2rem;
            border-radius: 50px;
            font-size: 0.9rem;
            text-decoration: none;
            transition: all 0.3s;
            font-weight: 500;
        }
        .category-nav a:hover {
            background: var(--primary);
            color: white;
        }
        /* Search */
        .search-container {
            margin: 1.5rem auto 2rem;
            max-width: 800px;
            position: relative;
        }
        #searchInput {
            width: 100%;
            padding: 14px 20px 14px 50px;
            border: 2px solid #ddd;
            border-radius: 50px;
            font-size: 1rem;
            background: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }
        .search-icon {
            position: absolute;
            left: 20px;
            top: 50%;
            transform: translateY(-50%);
            color: var(--primary);
        }
        /* Category Sections */
        .category-section {
            margin: 3rem 0;
            scroll-margin-top: 20px;
        }
        .category-title {
            color: var(--primary);
            border-bottom: 2px solid var(--primary);
            padding-bottom: 0.8rem;
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            gap: 0.8rem;
            font-size: 1.5rem;
        }
        .category-title i {
            font-size: 1.3rem;
        }
        /* Prompt Cards */
        .prompt-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
            gap: 1.5rem;
        }
        .prompt-card {
            background: white;
            border-radius: 10px;
            padding: 1.8rem;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
            transition: all 0.3s;
            position: relative;
        }
        .prompt-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.12);
        }
        .prompt-card h3 {
            color: var(--primary);
            margin-bottom: 1rem;
            font-size: 1.1rem;
            line-height: 1.4;
        }
        .prompt-card p {
            color: var(--dark);
            margin-bottom: 1.5rem;
            line-height: 1.5;
        }
        .copy-btn {
            background: var(--primary);
            color: white;
            border: none;
            padding: 0.6rem 1.2rem;
            border-radius: 5px;
            cursor: pointer;
            font-size: 0.9rem;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            width: 100%;
            justify-content: center;
        }
        .copy-btn:hover {
            background: var(--secondary);
        }
        .copy-btn.copied {
            background: var(--success);
        }
        /* Ad Spaces */
        .ad-space {
            background: #f8f9fa;
            border: 1px dashed #ccc;
            padding: 1.5rem;
            text-align: center;
            margin: 3rem 0;
            border-radius: 8px;
        }
        .ad-space p {
            color: #666;
            font-style: italic;
        }
        /* Responsive */
        @media (max-width: 768px) {
            .prompt-grid {
                grid-template-columns: 1fr;
            }
            .category-title {
                font-size: 1.3rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1><i class="fas fa-robot"></i> AI Prompt Library</h1>
            <p class="tagline">Strategic prompts for ChatGPT, Midjourney & more</p>
        </header>

        <!-- Ad Space -->
        <div class="ad-space">
            <p>Advertisement Space (Place Google AdSense or affiliate links here)</p>
        </div>

        <!-- Quick Navigation -->
        <div class="category-nav">
            <a href="#business"><i class="fas fa-briefcase"></i> Business</a>
            <a href="#coding"><i class="fas fa-code"></i> Coding</a>
            <a href="#design"><i class="fas fa-paint-brush"></i> Design</a>
            <a href="#writing"><i class="fas fa-pen"></i> Writing</a>
            <a href="#marketing"><i class="fas fa-bullhorn"></i> Marketing</a>
            <a href="#art"><i class="fas fa-palette"></i> Art</a>
            <a href="#productivity"><i class="fas fa-tasks"></i> Productivity</a>
            <a href="#education"><i class="fas fa-graduation-cap"></i> Education</a>
            <a href="#health"><i class="fas fa-heartbeat"></i> Health</a>
            <a href="#fun"><i class="fas fa-gamepad"></i> Fun</a>
        </div>

        <!-- Search -->
        <div class="search-container">
            <i class="fas fa-search search-icon"></i>
            <input type="text" id="searchInput" placeholder="Search prompts (e.g., 'marketing', 'Python', 'design')...">
        </div>

        <!-- Business Prompts -->
        <div class="category-section" id="business">
            <h2 class="category-title">
                <i class="fas fa-briefcase"></i> Business
            </h2>
            <div class="prompt-grid" id="businessPrompts">
                <!-- Prompts will be inserted here by JavaScript -->
            </div>
        </div>

        <!-- Coding Prompts -->
        <div class="category-section" id="coding">
            <h2 class="category-title">
                <i class="fas fa-code"></i> Coding
            </h2>
            <div class="prompt-grid" id="codingPrompts">
                <!-- Prompts will be inserted here by JavaScript -->
            </div>
        </div>

        <!-- Design Prompts -->
        <div class="category-section" id="design">
            <h2 class="category-title">
                <i class="fas fa-paint-brush"></i> Design
            </h2>
            <div class="prompt-grid" id="designPrompts">
                <!-- Prompts will be inserted here by JavaScript -->
            </div>
        </div>

        <!-- Writing Prompts -->
        <div class="category-section" id="writing">
            <h2 class="category-title">
                <i class="fas fa-pen"></i> Writing
            </h2>
            <div class="prompt-grid" id="writingPrompts">
                <!-- Prompts will be inserted here by JavaScript -->
            </div>
        </div>

        <!-- Marketing Prompts -->
        <div class="category-section" id="marketing">
            <h2 class="category-title">
                <i class="fas fa-bullhorn"></i> Marketing
            </h2>
            <div class="prompt-grid" id="marketingPrompts">
                <!-- Prompts will be inserted here by JavaScript -->
            </div>
        </div>

        <!-- Art Prompts -->
        <div class="category-section" id="art">
            <h2 class="category-title">
                <i class="fas fa-palette"></i> Art
            </h2>
            <div class="prompt-grid" id="artPrompts">
                <!-- Prompts will be inserted here by JavaScript -->
            </div>
        </div>

        <!-- Productivity Prompts -->
        <div class="category-section" id="productivity">
            <h2 class="category-title">
                <i class="fas fa-tasks"></i> Productivity
            </h2>
            <div class="prompt-grid" id="productivityPrompts">
                <!-- Prompts will be inserted here by JavaScript -->
            </div>
        </div>

        <!-- Education Prompts -->
        <div class="category-section" id="education">
            <h2 class="category-title">
                <i class="fas fa-graduation-cap"></i> Education
            </h2>
            <div class="
