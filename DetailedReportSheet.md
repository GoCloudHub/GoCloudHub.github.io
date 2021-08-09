---
title-heading: false
---
# Detailed Report Sheet
### Metric Definitions:

Metric | Definition
-------|-------
Intent Overview | A count for each intent of how many messages corresponded to the intent. This can be used to see what the most popular topics customers are asking about
Unique Conversations | Count of independent conversations, a string of messages inside the same user session
Messages Sent | Amount of messages sent by all users
Count of Bad Feedback | Count of times a user answered "No" to "Did this answer your question"
Missed Utterence Overview | Utterence: What the customer writes to the bot. A missed utterence is when the bot dosent know how to respond. 
Missed Utterences | The exact transciprt of what the customer wrote in that caused the bot to not know how to respond.
Transcripts | The exact transcirpt of what the customer sent to the bot for all messages
Unique Conversations Per Day | The amount of independent conversations per day, an independent conversation includes multiple messages sent by the customer.
Unique Conversations Per Hour | The same definition as the previous metric however, the amount of unique conversations that were within each hour. Can be used to see what the peak times of bot usage are.

**Actions**
- Clicking on an intent in the "Intent Overview" sheet, will result in the "Transcripts" metric to be filtered to include transcripts that included that specific intent. This can be used to see what the transcripts are for each intent. To return to normal view, reclick on the intent that was selected.

**Controls:**
- **Date:** The date that the user wants to investigate.
- **Scope:**  The scope of how the user wants the "Date" control to be interperetted. For example, if the user clicks "This Month" then the data will be filtered by whichever month that the "Date" control is set to i.e if "Date" is set to 7/8/21 then the data will be filtered for the month of August.
-  **Exclude HelloIntent:** This allows the user to decide weather they want to exclude the "helloIntent" from the sheet, this is because the "helloIntent" significantly effects results. This can be seen when deselecting it, it is now no longer exclued, this results in  "Unique Conversations" metric to go up by almost 3000 (as of 9/8/21) meaning there were almost 3000 conversations that only included the helloIntent and nothing further.
