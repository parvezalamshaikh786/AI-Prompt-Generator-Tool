<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>500+ AI Prompt Library | ChatGPT, Midjourney & More</title>
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
        }
        body {
            background: linear-gradient(135deg, var(--light) 0%, #e6e6f0 100%);
            color: var(--dark);
            line-height: 1.6;
            padding: 0;
            margin: 0;
            min-height: 100vh;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        header {
            text-align: center;
            margin-bottom: 2rem;
        }
        h1 {
            color: var(--primary);
            margin-bottom: 0.5rem;
        }
        .tagline {
            color: var(--secondary);
            font-weight: 500;
        }
        /* Quick Category Nav */
        .category-nav {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            justify-content: center;
            margin: 1.5rem 0;
        }
        .category-nav a {
            background: rgba(110, 72, 170, 0.1);
            color: var(--primary);
            padding: 0.5rem 1rem;
            border-radius: 50px;
            font-size: 0.9rem;
            text-decoration: none;
            transition: all 0.3s;
        }
        .category-nav a:hover {
            background: var(--primary);
            color: white;
        }
        /* Search */
        .search-container {
            margin: 1.5rem auto;
            max-width: 800px;
        }
        #searchInput {
            width: 100%;
            padding: 12px 20px;
            border: 2px solid #ddd;
            border-radius: 50px;
            font-size: 1rem;
            background: white url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="%236e48aa" stroke-width="2"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg>') no-repeat 15px center;
            padding-left: 45px;
        }
        /* Prompt Grid */
        .prompt-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 1.5rem;
            margin-top: 2rem;
        }
        .prompt-card {
            background: white;
            border-radius: 8px;
            padding: 1.5rem;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            transition: transform 0.2s;
        }
        .prompt-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.15);
        }
        .prompt-card h3 {
            margin-top: 0;
            color: var(--primary);
            font-size: 1.1rem;
        }
        .prompt-card .category {
            display: inline-block;
            background: #f0e6ff;
            color: var(--primary);
            padding: 0.2rem 0.6rem;
            border-radius: 50px;
            font-size: 0.8rem;
            margin-bottom: 0.8rem;
        }
        .prompt-card .tools {
            margin-top: 0.8rem;
            display: flex;
            flex-wrap: wrap;
            gap: 0.3rem;
        }
        .prompt-card .tool {
            background: #f0f0f0;
            padding: 0.2rem 0.5rem;
            border-radius: 4px;
            font-size: 0.8rem;
        }
        .prompt-card .actions {
            margin-top: 1rem;
            display: flex;
            justify-content: flex-end;
        }
        .copy-btn {
            background: var(--primary);
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            cursor: pointer;
            font-size: 0.9rem;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        .copy-btn:hover {
            background: var(--secondary);
        }
        .copy-btn.copied {
            background: var(--success);
        }
        /* Category Section */
        .category-section {
            margin: 3rem 0;
        }
        .category-title {
            color: var(--primary);
            border-bottom: 2px solid var(--primary);
            padding-bottom: 0.5rem;
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        /* Ad Space */
        .ad-space {
            background: #f5f5f5;
            border: 1px dashed #ccc;
            padding: 1.5rem;
            text-align: center;
            margin: 3rem 0;
            border-radius: 8px;
        }
        /* Responsive */
        @media (max-width: 768px) {
            .container {
                padding: 1rem;
            }
            .prompt-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1><i class="fas fa-robot"></i> 500+ AI Prompt Library</h1>
            <p class="tagline">Strategic prompts for ChatGPT, Midjourney, DALL-E & more</p>
        </header>

        <!-- Ad Space -->
        <div class="ad-space">
            <p>Advertisement Space (Place Google AdSense or affiliate links here)</p>
        </div>

        <!-- Quick Category Navigation -->
        <div class="category-nav">
            <a href="#business">Business</a>
            <a href="#coding">Coding</a>
            <a href="#design">Design</a>
            <a href="#writing">Writing</a>
            <a href="#marketing">Marketing</a>
            <a href="#art">Art</a>
            <a href="#productivity">Productivity</a>
            <a href="#education">Education</a>
            <a href="#health">Health</a>
            <a href="#fun">Fun</a>
        </div>

        <!-- Search -->
        <div class="search-container">
            <input type="text" id="searchInput" placeholder="Search 500+ prompts (e.g., 'marketing', 'Python', 'logo design')...">
        </div>

        <!-- Business Prompts (50) -->
        <div class="category-section" id="business">
            <h2 class="category-title"><i class="fas fa-briefcase"></i> Business (50 Prompts)</h2>
            <div class="prompt-grid" id="businessPrompts"></div>
        </div>

        <!-- Coding Prompts (50) -->
        <div class="category-section" id="coding">
            <h2 class="category-title"><i class="fas fa-code"></i> Coding (50 Prompts)</h2>
            <div class="prompt-grid" id="codingPrompts"></div>
        </div>

        <!-- Design Prompts (50) -->
        <div class="category-section" id="design">
            <h2 class="category-title"><i class="fas fa-paint-brush"></i> Design (50 Prompts)</h2>
            <div class="prompt-grid" id="designPrompts"></div>
        </div>

        <!-- Writing Prompts (50) -->
        <div class="category-section" id="writing">
            <h2 class="category-title"><i class="fas fa-pen"></i> Writing (50 Prompts)</h2>
            <div class="prompt-grid" id="writingPrompts"></div>
        </div>

        <!-- Marketing Prompts (50) -->
        <div class="category-section" id="marketing">
            <h2 class="category-title"><i class="fas fa-bullhorn"></i> Marketing (50 Prompts)</h2>
            <div class="prompt-grid" id="marketingPrompts"></div>
        </div>

        <!-- Art Prompts (50) -->
        <div class="category-section" id="art">
            <h2 class="category-title"><i class="fas fa-palette"></i> Art (50 Prompts)</h2>
            <div class="prompt-grid" id="artPrompts"></div>
        </div>

        <!-- Productivity Prompts (50) -->
        <div class="category-section" id="productivity">
            <h2 class="category-title"><i class="fas fa-tasks"></i> Productivity (50 Prompts)</h2>
            <div class="prompt-grid" id="productivityPrompts"></div>
        </div>

        <!-- Education Prompts (50) -->
        <div class="category-section" id="education">
            <h2 class="category-title"><i class="fas fa-graduation-cap"></i> Education (50 Prompts)</h2>
            <div class="prompt-grid" id="educationPrompts"></div>
        </div>

        <!-- Health Prompts (50) -->
        <div class="category-section" id="health">
            <h2 class="category-title"><i class="fas fa-heartbeat"></i> Health (50 Prompts)</h2>
            <div class="prompt-grid" id="healthPrompts"></div>
        </div>

        <!-- Fun Prompts (50) -->
        <div class="category-section" id="fun">
            <h2 class="category-title"><i class="fas fa-gamepad"></i> Fun (50 Prompts)</h2>
            <div class="prompt-grid" id="funPrompts"></div>
        </div>

        <!-- Ad Space -->
        <div class="ad-space">
            <p>Advertisement Space (Example: "Get ChatGPT Plus - Your Affiliate Link")</p>
        </div>
    </div>

    <script>
        // ======================
        // 500+ PROMPTS DATABASE
        // ======================
        const prompts = {
            business: [
                {
                    id: "b1",
                    title: "Startup Pitch Deck",
                    text: "Create a 10-slide pitch deck for [startup name] targeting [investor type]. Include problem statement, solution, market size, business model, traction, team, and financial projections.",
                    tools: ["ChatGPT", "Claude"]
                },
                {
                    id: "b2",
                    title: "SWOT Analysis",
                    text: "Conduct a detailed SWOT analysis for [company] in [industry]. Include 5 points for each quadrant with data-driven insights and competitor comparisons.",
                    tools: ["ChatGPT"]
                },
                {
                    id: "b3",
                    title: "Business Plan Outline",
                    text: "Generate a comprehensive business plan outline for a [type of business]. Include executive summary, company description, market analysis, organization structure, product line, marketing plan, and funding request.",
                    tools: ["ChatGPT", "Bard"]
                },
                // Add 47 more business prompts...
                {
                    id: "b50",
                    title: "Crisis Management Plan",
                    text: "Develop a crisis management plan for [company] facing [crisis type]. Include communication strategy, stakeholder management, and recovery steps.",
                    tools: ["ChatGPT"]
                }
            ],
            coding: [
                {
                    id: "c1",
                    title: "Python API Wrapper",
                    text: "Write a Python class that wraps the [API name] API with methods for [key functionalities]. Include error handling, rate limiting, and async support using the requests library.",
                    tools: ["ChatGPT"]
                },
                {
                    id: "c2",
                    title: "React Optimization",
                    text: "Analyze this React component and suggest 5 specific optimizations to improve rendering performance: [paste code]. Explain each recommendation with code examples.",
                    tools: ["ChatGPT"]
                },
                // Add 48 more coding prompts...
                {
                    id: "c50",
                    title: "SQL Query Optimization",
                    text: "Optimize this SQL query for [database type]: [paste query]. Explain the bottlenecks and provide 3 alternative implementations with performance comparisons.",
                    tools: ["ChatGPT"]
                }
            ],
            design: [
                {
                    id: "d1",
                    title: "Logo Design Brief",
                    text: "Create a creative brief for a logo design for [company] in [industry]. Include brand values, color preferences, style references (minimalist/retro/etc.), and deliverables.",
                    tools: ["ChatGPT", "Midjourney"]
                },
                // Add 49 more design prompts...
                {
                    id: "d50",
                    title: "Packaging Design",
                    text: "Generate design specifications for [product] packaging. Include dimensions, materials, color palette, typography, and regulatory requirements for [country].",
                    tools: ["ChatGPT", "DALL-E"]
                }
            ],
            // Continue with 7 more categories (writing, marketing, art, productivity, education, health, fun)
            // Each with 50 real-world prompts
        };

        // ======================
        // APP FUNCTIONALITY
        // ======================
        document.addEventListener('DOMContentLoaded', function() {
            // Load prompts for each category
            for (const category in prompts) {
                const container = document.getElementById(`${category}Prompts`);
                if (container) {
                    loadPrompts(category, container);
                }
            }

            // Search functionality
            const searchInput = document.getElementById('searchInput');
            searchInput.addEventListener('input', function() {
                const searchTerm = this.value.toLowerCase();
                for (const category in prompts) {
                    const container = document.getElementById(`${category}Prompts`);
                    if (container) {
                        filterPrompts(category, container, searchTerm);
                    }
                }
            });
        });

        // Load prompts into a category container
        function loadPrompts(category, container) {
            container.innerHTML = '';
            prompts[category].forEach(prompt => {
                const tools = prompt.tools.map(tool => 
                    `<span class="tool">${tool}</span>`
                ).join('');
                
                const card = document.createElement('div');
                card.className = 'prompt-card';
                card.innerHTML = `
                    <span class="category">${category.charAt(0).toUpperCase() + category.slice(1)}</span>
                    <h3>${prompt.title}</h3>
                    <p>${prompt.text}</p>
                    <div class="tools">${tools}</div>
                    <div class="actions">
                        <button class="copy-btn" data-prompt="${prompt.text.replace(/"/g, '&quot;')}">
                            <i class="fas fa-copy"></i> Copy
                        </button>
                    </div>
                `;
                
                // Add copy functionality
                const copyBtn = card.querySelector('.copy-btn');
                copyBtn.addEventListener('click', function() {
                    const promptText = this.getAttribute('data-prompt');
                    navigator.clipboard.writeText(promptText);
                    this.innerHTML = '<i class="fas fa-check"></i> Copied!';
                    this.classList.add('copied');
                    setTimeout(() => {
                        this.innerHTML = '<i class="fas fa-copy"></i> Copy';
                        this.classList.remove('copied');
                    }, 2000);
                });
                
                container.appendChild(card);
            });
        }

        // Filter prompts based on search term
        function filterPrompts(category, container, searchTerm) {
            const filtered = prompts[category].filter(prompt => 
                prompt.title.toLowerCase().includes(searchTerm) || 
                prompt.text.toLowerCase().includes(searchTerm)
            );
            
            container.innerHTML = '';
            if (filtered.length === 0) {
                container.innerHTML = '<p>No matching prompts found in this category.</p>';
                return;
            }
            
            filtered.forEach(prompt => {
                const tools = prompt.tools.map(tool => 
                    `<span class="tool">${tool}</span>`
                ).join('');
                
                const card = document.createElement('div');
                card.className = 'prompt-card';
                card.innerHTML = `
                    <span class="category">${category.charAt(0).toUpperCase() + category.slice(1)}</span>
                    <h3>${prompt.title}</h3>
                    <p>${prompt.text}</p>
                    <div class="tools">${tools}</div>
                    <div class="actions">
                        <button class="copy-btn" data-prompt="${prompt.text.replace(/"/g, '&quot;')}">
                            <i class="fas fa-copy"></i> Copy
                        </button>
                    </div>
                `;
                
                const copyBtn = card.querySelector('.copy-btn');
                copyBtn.addEventListener('click', function() {
                    const promptText = this.getAttribute('data-prompt');
                    navigator.clipboard.writeText(promptText);
                    this.innerHTML = '<i class="fas fa-check"></i> Copied!';
                    this.classList.add('copied');
                    setTimeout(() => {
                        this.innerHTML = '<i class="fas fa-copy"></i> Copy';
                        this.classList.remove('copied');
                    }, 2000);
                });
                
                container.appendChild(card);
            });
        }
    </script>
</body>
</html>
