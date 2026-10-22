# Chat Handoff Context — Salesforce Marketing Cloud (SFMC) MCQ Questions

## Purpose
This file captures the useful context from the chat so another AI assistant can continue without needing the original screenshots. The user shared screenshots of Salesforce Marketing Cloud / Email Studio / Journey Builder multiple-choice questions and asked for the answers to match the options shown in the images.

## User's instruction and response preference
- The user asked: “cross check your answer”.
- The user then asked: “give the answers exactly in the images provided”.
- The latest answer should be formatted using the exact option letters and wording shown in the screenshots.
- Important: some screenshots show more than one quiz/test set. Keep the sets separate and do not mix their question numbering.

---

# Set A — Latest screenshots (10-question beginner SFMC quiz)

These are the questions in the latest batch of screenshots, transcribed from the visible images.

### Q1. Soft bounce
**Question:** After sending a newsletter, you look at the tracking report and notice a high number of “Soft Bounces.” What is the most common reason for a soft bounce?

Options:
- A. The email address is completely fake or no longer exists.
- B. The recipient clicked the Unsubscribe link.
- C. The recipient's inbox is temporarily full or their mail server is down.
- D. The email was marked as spam by the recipient.

**Answer: C. The recipient's inbox is temporarily full or their mail server is down.**

### Q2. Test send
**Question:** Before sending a major campaign to 100,000 customers, the marketing team wants to send a live copy of the email to their internal team of 5 people to see exactly how it renders in Gmail and Outlook. Which feature should they use?

Options:
- A. Content Validator
- B. Test Send
- C. Send Throttling
- D. A/B Testing

**Answer: B. Test Send**

### Q3. Journey exit criteria
**Question:** You are building a “Welcome Journey” for new app users. You want the system to automatically pull a user out of the journey early if they make their first purchase. Which Journey Builder feature should you use?

Options:
- A. Wait by Duration
- B. Journey Goal / Exit Criteria
- C. Engagement Split
- D. Random Split

**Answer: B. Journey Goal / Exit Criteria**

### Q4. Journey branching by location
**Question:** You are building a Journey and want to send customers down Path A if they live in “New York” and Path B if they live anywhere else. Which Journey Builder activity do you use?

Options:
- A. Random Split
- B. Engagement Split
- C. Decision Split
- D. Wait Until Event

**Answer: C. Decision Split**

### Q5. Data Extension Primary Key
**Question:** You are creating a Data Extension to store a list of daily store purchases. What is the purpose of checking the “Primary Key” box next to the OrderID field?

Options:
- A. It makes the Data Extension sendable.
- B. It encrypts the data so it cannot be stolen.
- C. It ensures that every record in that column is unique, preventing duplicate orders from being saved.
- D. It automatically links the Data Extension to the Sales Cloud CRM.

**Answer: C. It ensures that every record in that column is unique, preventing duplicate orders from being saved.**

### Q6. All Subscribers status after unsubscribe
**Question:** A subscriber clicks the standard “Unsubscribe” link at the bottom of your weekly promotional newsletter. What status is immediately applied to this user on the All Subscribers list?

Options:
- A. Deleted
- B. Bounced
- C. Held
- D. Unsubscribed

**Answer: D. Unsubscribed**

### Q7. Testing subject lines
**Question:** You want to send an email to a list of subscribers, but you want to test two different subject lines to see which one gets a higher open rate. Which tool is designed specifically for this?

Options:
- A. Automation Studio Wait Step
- B. A/B Testing
- C. Send Throttling
- D. Content Validator

**Answer: B. A/B Testing**

### Q8. Making a Data Extension usable for email sends
**Question:** You are creating a new Data Extension and want to use it as an audience for an email send. What must you configure during the setup to allow this?

Options:
- A. Set a Primary Key on the email address field.
- B. Check the “Is Sendable” box and relate a field to the Subscriber Key.
- C. Link the Data Extension to an Attribute Group in Contact Builder.
- D. Apply a Data Retention Policy of 30 days.

**Answer: B. Check the “Is Sendable” box and relate a field to the Subscriber Key.**

### Q9. Personalized images without code
**Question:** A marketer wants to show a picture of a dog to subscribers who own a dog, and a picture of a cat to subscribers who own a cat. They want to do this within a single email without writing any code. Which Content Builder feature should they use?

Options:
- A. AMPscript
- B. A/B Testing
- C. Dynamic Content Block
- D. HTML Block

**Answer: C. Dynamic Content Block**

### Q10. Manual CSV import
**Question:** You have an Excel (CSV) file on your desktop with a list of 50 VIP customers that you want to add to Marketing Cloud right now. What is the simplest way to get this data into a Data Extension manually?

Options:
- A. Use a SQL Query Activity
- B. Create a File Drop Automation
- C. Use the “Import” button directly on the Data Extension in Email Studio
- D. Build an API integration

**Answer: C. Use the “Import” button directly on the Data Extension in Email Studio**

## Set A — Answer key only
1. C
2. B
3. B
4. C
5. C
6. D
7. B
8. B
9. C
10. C

---

# Set B — Earlier screenshots (SFMC concepts / Email Studio)

The earlier batch included several different questions. Some were visible only in partial screenshots, so the transcriptions below are limited to what could be read.

### B1. Correcting an email after it has been sent
**Question:** A marketer notices a glaring typo in the main text body of a promotional email that was completely deployed to 50,000 subscribers three hours ago. What action can the marketer take inside Email Studio to fix the text inside their customers’ standard inboxes?

Options:
- A. Edit the email asset inside Content Builder to overwrite the copy.
- B. Update the primary Send Classification template fields.
- C. Re-run a global Validation process on the original target Data Extension.
- D. Nothing; once a standard email is successfully delivered to an external inbox provider, the static content cannot be altered.

**Answer: D. Nothing; once a standard email is successfully delivered to an external inbox provider, the static content cannot be altered.**

### B2. Manual import of a local CSV
**Question:** A marketer has a small .csv file of new subscribers saved on their desktop computer. They want to manually import these records directly into an existing Data Extension without using Automation Studio or an external SFTP server. Which feature inside the Email Studio Data Extension workspace should they use?

Options:
- A. Data Extract Activity
- B. Import Wizard
- C. File Transfer Activity
- D. Journey Injection

**Answer: B. Import Wizard**

### B3. Mandatory elements attached to a send
**Question:** When a company deploys an email campaign, where are system-generated mandatory elements—like the physical mailing address and the generic unsubscribe link—usually stored and automatically attached?

Visible options:
- A. In the Delivery Profile
- B. In the Sender Profile
- C. In the Data Extension Attributes
- D. In the SQL Query Activity

**Answer: A. In the Delivery Profile**

### B4. Data Extension relationship field
**Question:** When creating a brand-new Sendable Data Extension from scratch, an administrator needs to define a unique field that acts as the primary relationship connector back to the platform’s central All Subscribers database table. What is this relationship mapping field context called?

Visible options:
- A. The Data Type Pattern
- B. The Data Retention Rule
- C. The Send Relationship
- D. The Content Linkage Schema

**Answer: C. The Send Relationship**

### B5. Bundled send settings
**Question:** When creating an email send strategy, an administrator bundles a single Sender Profile (which sets the “From” information) with a single Delivery Profile (which controls the IP routing and footer layouts). What is this combined package configuration called?

Visible options:
- A. Send Classification
- B. Subscriber Filter Activity
- C. Data Extract Action
- D. Data Designer Mapping

**Answer: A. Send Classification**

### B6. Looking up a subscriber’s status
**Question:** A customer success agent needs to check whether a specific customer opted into the corporate newsletter list and see whether their current system status is Active or Unsubscribed. Where is the fastest place to search for this individual profile directly inside the Email Studio navigation menu?

Visible options:
- A. Content Builder Assets folder
- B. All Subscribers workspace under the Subscribers tab
- C. Web Analytics Connector dashboard
- D. Send Classification setup window

**Answer: B. All Subscribers workspace under the Subscribers tab**

### B7. Bounce rate
**Question:** While receiving the tracking report for a recent product announcement, a marketer sees that out of 10,000 total messages sent, 200 were categorized as Bounces. How does Email Studio calculate the Bounce Rate percentage?

Visible options:
- A. Bounces divided by Unique Opens multiplied by 100
- B. Bounces divided by Total Sends multiplied by 100
- C. Bounces divided by Total Delivered multiplied by 100
- D. Bounces divided by Unique Clicks multiplied by 100

**Answer: B. Bounces divided by Total Sends multiplied by 100**

### B8. Hard bounce status
**Question:** An email address that has been permanently blocked by an ISP, or is determined to have a formatting error that will never work, is tracked by Email Studio so it won’t be emailed again. What is the exact system status assigned to a subscriber profile after it registers a definitive hard bounce?

Visible options:
- A. Active
- B. Bounced
- C. Held
- D. Unsubscribed

**Answer: B. Bounced**

### B9. Automatically suppressing competitor domains
**Question:** A corporate team wants to prevent competitors from receiving their early-access deals. They want a solution that automatically blocks specific competitor email domains across every single commercial email sent by any user within the Business Unit, without requiring manual steps during individual send flows. Which Email Studio feature is designed for this overarching automated task?

Visible options:
- A. A standard Publication List
- B. An Auto-Suppression List
- C. A Dynamic Content Block Rule
- D. A standard test audience block

**Answer: B. An Auto-Suppression List**

### B10. General reminder about the All Subscribers list
One screenshot shows the standard All Subscribers unsubscribe question and its answer choices; this is also covered as Set A, Q6. Use the Set A transcription for the full wording.

## Set B — Answer key only
- B1. D
- B2. B
- B3. A
- B4. C
- B5. A
- B6. B
- B7. B
- B8. B
- B9. B

---

# How another AI should continue
1. Treat this file as the context handoff for the SFMC MCQ work.
2. When asked to answer a question from a screenshot, preserve the exact option letter and wording where legible.
3. If asked to cross-check, verify Salesforce Marketing Cloud product terminology carefully and flag any ambiguity instead of confidently guessing.
4. Keep separate quiz sets separate because question numbers repeat across screenshots.
5. The user prefers direct, concise answers and has asked for answers exactly as written in the images.

## Accuracy note
The answer keys above capture the answers given or inferred from the screenshots in this chat. They are a study aid, not an official Cognizant answer key. If the user asks for a rigorous verification, re-check Salesforce’s current documentation, especially where quiz wording simplifies product behavior.
