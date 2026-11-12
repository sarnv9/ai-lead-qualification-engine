# Smart Lead Qualification & CRM Setup

## Overview
This system automatically handles new leads for the company the second they arrive. Instead of doing manual research, the system looks up the client's company, uses artificial intelligence to figure out how serious they are, and automatically sends them to the right place or replies for you.

# What Powers It

**Automation:** n8n

**Intelligence:** OpenAI (GPT-4o-mini)

**Tools Used:** JavaScript, HubSpot CRM, and Gmail

# How It Works

1. Receiving & Researching the Client

**Instant Capture:**Grabs form entries straight from your website instantly and securely.

***Company Check:** Looks at the email address. If it is a company email (not a personal Gmail or Yahoo account), it automatically visits their website to see what they do.

**Content Cleanup:** Cleans up the website text so the AI can easily read it.

2. AI Evaluation

**Smart Scoring:** Sends the client's message and company details to the AI.

**Clear Results:** The AI gives every lead a score from 0 to 100, detects their main pain points, and summarizes what they need.

3. Automatic Sorting
The system automatically routes the lead based on their score:

🔥 **High Interest (Score 75+)**:

Instantly saves or updates their profile in your HubSpot CRM.

Sends an immediate alert to your inbox with a clean summary, their core problems, and recommended next steps.

🌤️ **Medium Interest (Score 40–74)**:

Automatically sends a polite email asking for a few more details about their project or current tools.

❄️ **Low Interest / Not a Fit (Score under 40)**:

Sends a professional, automated thank-you-and-rejection email so you don't waste time on dead ends.

## Business Impact

This cuts your response time from hours down to seconds. High-value clients get your attention immediately, while routine or unqualified inquiries are handled entirely on autopilot.