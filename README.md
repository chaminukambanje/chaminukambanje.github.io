<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dynamics 365 Business Central Functional Consultant Guide</title>
    <style>
        :root {
            --primary-color: #0078d4; /* Microsoft Blue */
            --secondary-color: #2b88d8;
            --text-dark: #333;
            --text-light: #666;
            --bg-light: #f4f4f4;
            --white: #ffffff;
            --accent: #d83b01; /* Alert/Important color */
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-dark);
            background-color: var(--bg-light);
        }

        /* Layout Utilities */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header & Nav */
        header {
            background: var(--white);
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--primary-color);
            text-decoration: none;
        }

        .nav-links a {
            margin-left: 20px;
            text-decoration: none;
            color: var(--text-dark);
            font-weight: 500;
        }

        .nav-links a:hover {
            color: var(--primary-color);
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: var(--white);
            padding: 4rem 0;
            text-align: center;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto;
        }

        /* Main Content Grid */
        .content-wrapper {
            display: grid;
            grid-template-columns: 3fr 1fr;
            gap: 2rem;
            padding: 2rem 0;
        }

        /* Blog Post Styling */
        .study-module {
            background: var(--white);
            padding: 2rem;
            margin-bottom: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }

        .module-tag {
            background: #e1f0fa;
            color: var(--primary-color);
            padding: 4px 10px;
            border-radius: 4px;
            font-size: 0.8rem;
            font-weight: bold;
            display: inline-block;
            margin-bottom: 1rem;
        }

        h2 {
            color: var(--primary-color);
            margin-bottom: 1rem;
        }

        h3 {
            margin-top: 1.5rem;
            margin-bottom: 0.5rem;
            color: var(--text-dark);
            border-bottom: 2px solid #eee;
            padding-bottom: 5px;
        }

        ul {
            list-style-position: inside;
            margin-bottom: 1rem;
        }

        li {
            margin-bottom: 0.5rem;
        }

        .tip-box {
            background-color: #fff4ce;
            border-left: 4px solid #ffb900;
            padding: 1rem;
            margin: 1rem 0;
        }

        /* Sidebar */
        .sidebar-widget {
            background: var(--white);
            padding: 1.5rem;
            margin-bottom: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }

        .sidebar-widget h3 {
            border-bottom: none;
            margin-top: 0;
        }

        .progress-bar {
            background-color: #eee;
            border-radius: 10px;
            height: 20px;
            width: 100%;
            margin-bottom: 10px;
        }

        .progress-fill {
            background-color: var(--primary-color);
            height: 100%;
            border-radius: 10px;
            text-align: center;
            color: white;
            font-size: 0.8rem;
            line-height: 20px;
        }

        /* Footer */
        footer {
            background: #333;
            color: var(--white);
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .content-wrapper {
                grid-template-columns: 1fr;
            }
            .nav-links {
                display: none; /* Simplified for mobile example */
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <nav>
                <a href="#" class="logo">BC Consultant Prep</a>
                <div class="nav-links">
                    <a href="#intro">Start Here</a>
                    <a href="#setup">Setup</a>
                    <a href="#financials">Financials</a>
                    <a href="#sales-purchasing">Sales & Purchase</a>
                    <a href="#operations">Operations</a>
                </div>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>Mastering MB-800: Business Central</h1>
            <p>Your complete, functional guide to passing the Microsoft Certified: Dynamics 365 Business Central Functional Consultant Associate exam.</p>
        </div>
    </section>

    <div class="container content-wrapper">
        
        <main>
            
            <article id="setup" class="study-module">
                <span class="module-tag">20-25% of Exam</span>
                <h2>Module 1: Set Up Business Central</h2>
                <p>This is the foundation. Before transactions can occur, the environment must be configured. This section focuses on the "RapidStart" methodology and core system settings.</p>

                <h3>1.1 Create and Configure a New Company</h3>
                <ul>
                    <li><strong>Configuration Packages:</strong> Mastering the use of Excel to import data. You must know how to validate, apply packages, and troubleshoot errors in the *Config. Package Card*.</li>
                    <li><strong>Role Centers:</strong> Assigning profiles to users. Know the difference between a <em>Profile</em> (UI customization) and a <em>User Group</em> (Permissions).</li>
                    <li><strong>Assisted Setup:</strong> Know which wizards exist (e.g., Set up Company, Set up Email).</li>
                </ul>
                
                <h3>1.2 Manage Security</h3>
                <ul>
                    <li><strong>Permission Sets:</strong> Understand the difference between system permission sets (e.g., D365 BUS FULL ACCESS) and user-defined sets.</li>
                    <li><strong>User Setup:</strong> This is distinct from permissions. User Setup controls posting dates and specific allowances per user.</li>
                </ul>

                <div class="tip-box">
                    <strong>Exam Tip:</strong> Don't confuse <em>General Ledger Setup</em> (global rules) with <em>User Setup</em> (individual exceptions). If a user can't post in a specific date range, check User Setup first!
                </div>
            </article>

            <article id="financials" class="study-module">
                <span class="module-tag">25-30% of Exam</span>
                <h2>Module 2: Configure Financials</h2>
                <p>The financial core is the heaviest weighted section. It requires deep knowledge of the Chart of Accounts (COA) and Posting Groups.</p>

                <h3>2.1 Finance Essentials</h3>
                <ul>
                    <li><strong>Chart of Accounts:</strong> Understand Account Types (Posting, Heading, Total, Begin-Total, End-Total). Know how to indent the COA for reporting.</li>
                    <li><strong>Dimensions:</strong> This is critical. Know the difference between Global Dimensions (2), Shortcut Dimensions (6), and Default Dimensions (set on Master Data like Customer/Vendor cards).</li>
                </ul>

                <h3>2.2 Posting Groups (The Engine)</h3>
                <p>Business Central uses a "sub-ledger" system. You must memorize what these do:</p>
                <ul>
                    <li><strong>General Business Posting Group:</strong> Who we sell to/buy from (Domestic, EU, Export).</li>
                    <li><strong>General Product Posting Group:</strong> What we sell/buy (Retail, Service, Raw Mat).</li>
                    <li><strong>VAT/Tax Posting Groups:</strong> Dictates the tax % calculation.</li>
                    <li><strong>Customer/Vendor Posting Groups:</strong> Links the sub-ledger to the G/L (Receivables/Payables Accounts).</li>
                </ul>

                
            </article>

            <article id="sales-purchasing" class="study-module">
                <span class="module-tag">10-15% of Exam</span>
                <h2>Module 3: Configure Sales and Purchasing</h2>
                <p>This section covers the trade logistics side of the system, including inventory costing and pricing strategies.</p>

                <h3>3.1 Inventory Configuration</h3>
                <ul>
                    <li><strong>Costing Methods:</strong> Know the impact of FIFO, LIFO, Average, Standard, and Specific. (e.g., Standard is often used for manufacturing).</li>
                    <li><strong>Item Charges:</strong> How to apply landed costs (freight, insurance) to the cost of inventory items *after* the invoice is posted.</li>
                </ul>

                <h3>3.2 Pricing and Discounts</h3>
                <ul>
                    <li><strong>Sales Price Lists:</strong> Configuring prices based on Minimum Quantity, Customer Price Group, or Dates.</li>
                    <li><strong>Invoice Discounts:</strong> Automatic discounts applied when the document total exceeds a threshold.</li>
                </ul>
            </article>

            <article id="operations" class="study-module">
                <span class="module-tag">30-35% of Exam</span>
                <h2>Module 4: Perform Business Central Operations</h2>
                <p>The practical application. This tests your ability to actually perform the daily tasks a user would do.</p>

                <h3>4.1 Purchasing & Sales Cycles</h3>
                <ul>
                    <li><strong>The Flow:</strong> Quote -> Order -> Receipt/Shipment -> Invoice -> Credit Memo.</li>
                    <li><strong>Requisition Worksheet:</strong> How to calculate a plan to replenish inventory based on demand.</li>
                </ul>

                <h3>4.2 Financial Operations</h3>
                <ul>
                    <li><strong>General Journals:</strong> Using Recurring Journals for monthly expenses (Rent/Leases).</li>
                    <li><strong>Payment Registration:</strong> How to quickly process customer payments and reconcile bank accounts.</li>
                </ul>
                
                <div class="tip-box">
                    <strong>Critical Concept:</strong> Understanding <em>Document Dating</em>. 
                    <br><strong>Posting Date:</strong> When it hits the G/L. 
                    <br><strong>Document Date:</strong> The date on the physical invoice (used for due date calc).
                </div>
            </article>

        </main>

        <aside>
            <div class="sidebar-widget">
                <h3>Exam Profile</h3>
                <p><strong>Exam Code:</strong> MB-800</p>
                <p><strong>Role:</strong> Functional Consultant</p>
                <p><strong>Passing Score:</strong> 700/1000</p>
                <p><strong>Time:</strong> 120 Minutes</p>
            </div>

            <div class="sidebar-widget">
                <h3>Your Progress</h3>
                <p>Setup</p>
                <div class="progress-bar"><div class="progress-fill" style="width: 100%">Done</div></div>
                <p>Financials</p>
                <div class="progress-bar"><div class="progress-fill" style="width: 60%">60%</div></div>
                <p>Sales & Purchasing</p>
                <div class="progress-bar"><div class="progress-fill" style="width: 30%">30%</div></div>
                <p>Operations</p>
                <div class="progress-bar"><div class="progress-fill" style="width: 0%">0%</div></div>
            </div>

            <div class="sidebar-widget">
                <h3>Official Resources</h3>
                <ul>
                    <li><a href="https://learn.microsoft.com/en-us/credentials/certifications/d365-business-central-functional-consultant-associate/">Official Exam Page</a></li>
                    <li><a href="https://learn.microsoft.com/en-us/dynamics365/business-central/">BC Documentation</a></li>
                    <li><a href="#">Join the Community</a></li>
                </ul>
            </div>
        </aside>

    </div>

    <footer>
        <div class="container">
            <p>&copy; 2023 BC Consultant Prep | Not affiliated with Microsoft.</p>
            <p>Built for the MB-800 Learning Path.</p>
        </div>
    </footer>

</body>
</html>
