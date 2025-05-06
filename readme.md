📌 Project Overview: Grace – WhatsApp Wholesale Assistant for AkanrabyAtuche
 Project Goal
Grace is an intelligent, WhatsApp-based sales assistant designed to streamline and automate the wholesale sales process for AkanrabyAtuche, a fashion-forward brand specializing in vibrant prints and custom dresses. Built with Flask, Twilio, OpenAI GPT, and SQLite, Grace handles everything from initial customer engagement to fabric selection, payment confirmation, and order tracking—while maintaining a tone that blends professionalism with persuasive, brand-aligned humor.

Core Capabilities
Conversational Sales Assistant
Grace mimics a persuasive, deal-closing human assistant. She’s designed to reduce response delays and close sales efficiently.

Memory & Personalization
Grace uses an SQLite database to remember previous interactions, payment statuses, and customer preferences, enabling personalized experiences.

Fabric Selection Workflow
Grace requests dress images from customers, sends back available fabric print options from the catalog, and helps customers make selections.

Order Confirmation & Payment Requests
After a customer selects prints, Grace generates a summary with a 50% deposit request, provides payment instructions, and requests proof of payment.

Smart Payment Confirmation
Upon receiving a screenshot or notification of payment, Grace logs the confirmation and notifies the operations team to verify and proceed.

Humor-Driven Redirection
Grace politely (but humorously) redirects off-topic messages like trivia, flattery, or idle chats back to the goal: getting paid and moving products.

 Tech Stack

Tool	Purpose
Flask	Backend framework for message routing and processing
Twilio	WhatsApp messaging integration
OpenAI GPT-4	Natural language understanding and response logic
SQLite	Lightweight database for user memory and payments
Ngrok	Secure local tunneling for webhook testing
AWS S3 (optional)	Storage for catalog images and fabric prints
 How It Works
Customer Messages on WhatsApp

Grace Welcomes & Identifies Intent (buying, asking, browsing)

Grace Requests Dress Image or Fabric Interest

Grace Sends Fabric Options from Catalog

Customer Picks Fabric(s)

Grace Summarizes Order & Requests Payment

Customer Sends Proof of Payment

Grace Notifies Ops Team, Confirms with Customer

Post-Sale Feedback, Follow-up, and Soft Upselling

 Potential Enhancements
Integrate with Stripe API for in-chat payment links.

Add voice note interpretation using speech-to-text.

Hook into CRM or Google Sheets for lead tracking.

Deploy to AWS Lambda for scalability.
