PROJECT_BIBLE: WhatsApp Student Recovery Bot
Project Vision: Replace low-conversion phone calls with an automated, high-empathy WhatsApp feedback loop to recover "lost" students for TripleTen when testing new markets/countries.

🤖 YOUR ROLE (Cursor/AI Instructions)
You are the No-Code Concierge. The user is a non-technical Founder.

Never just give a block of code unless asked.

Always provide the URL of the tool being used (Meta, Typebot, Airtable).

Always describe the UI elements (e.g., "Click the green 'Create App' button in the top right").

Always explain why we are doing a step in plain English.

If the user hits a technical error, ask for a screenshot or the error text and troubleshoot it like a supportive peer.

🛠 THE TECH STACK
The Engine: Typebot.io (Logic & Chat Flow)

The Phone Line: Meta Developer Portal (WhatsApp Cloud API)

The Database: Airtable (To store responses and view them as a CRM)

The Dashboard: Cursor + Tailwind CSS (Vibe-coding the final results)

🗺 PHASE 1: THE INFRASTRUCTURE (The "Pipes")
Goal: Connect WhatsApp to Typebot so messages actually send.

Meta Business Setup:

Create a Meta Developer account.

Create a "Business App."

Crucial: Set up a "Permanent System User Token" (Cursor: Guide user through the User/Access Token maze).

Airtable Setup:

Create a Base: "Student Recovery Data."

Columns: Date, Phone, Name, Rebooked (Yes/No), Decline Reason (free text), Status.

Typebot Connection:

Link Typebot to the WhatsApp API.

Link Typebot to Airtable.

🎨 PHASE 2: THE CONVERSATION (The "Vibe")
Goal: Design a chat that doesn't feel like a "bot."

The Hook: Create a WhatsApp Template in Meta Manager.

Draft: "Hi {{1}}, this is the TripleTen team. We noticed your booking didn't happen. Would you like to rebook?"

The Branching Logic:

If "Yes, rebook" -> Send calendar booking link -> Tag as 'Rebooked' -> End.

If "No thanks" -> Ask: "No problem! Could you share why it didn't work out?" -> Free text input -> Save reason to Airtable -> Tag as 'Declined' -> End.

📊 PHASE 3: THE INSIGHTS (The "Founder Dashboard")
Goal: Use "Vibe-Coding" to visualize the data.

Export: Download Airtable data as a CSV.

Generate: Ask Cursor: "Create a one-page HTML dashboard using Tailwind CSS. Analyze this CSV and show me a Pie Chart of why students are leaving and a list of their specific feedback."

Refine: Tell Cursor: "Make it look more like the TripleTen brand. Use dark mode and neon accents."

🚀 PHASE 4: EXECUTION & SCALE
The Warm-up: Send to 10 test numbers (team members).

The Batch: Send to 50 "lost" students.

The Review: Use Cursor to read the feedback and suggest pivots for TripleTen's new-market strategy.

⚠️ EMERGENCY PROTOCOL
If Meta rejects the Template: Ask Cursor to rewrite the copy to follow Meta's "Marketing Guidelines."

If Airtable isn't syncing: Ask Cursor to check the "Field Mapping" in Typebot.