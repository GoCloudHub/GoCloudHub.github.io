# Detailed Report Sheet
### Metric Definitions:

Metric | Definition
-------|-------
Intent Overview | Count of each time an intent was invoked with an utterance
Unique Conversations | Count of independent conversations, a string of messages inside the same user session
Messages Sent | Count of messages sent by all users
Count of Negative Feedback | Count of times a user answered "No" to "Did this answer your question"
Missed Utterances | The message that the user sent, when the bot did not know how to respond
Transcripts | The full list of messages sent to the bot
Unique Conversations Per Day | The amount of independent conversations per day, an independent conversation includes multiple messages sent by the customer.
Unique Conversations Per Hour | The amount of independent conversations per hour. This can suggest peak usage times for the bot.

**Actions**
- Clicking on an intent in the "Intent Overview" graph, will result in the "Transcripts" metric to be filtered to include transcripts that included that specific intent. This can be used to show transcripts relative to each intent. To return to normal view, re-click on the intent that was selected.

**Controls:**
- **Date:** The date that the user wants to investigate.
- **Control:**  The scope of how the user wants the "Date" control to be interpreted. For example, if the user clicks "This Month" then the data will be filtered by whichever month that the "Date" control is set to. (i.e if "Date" is set to 7/8/21 & "Control" is set to "This Month", then the data will be filtered for the month of August).
-  **Exclude HelloIntent:** This allows the user to decide whether they want to exclude the "helloIntent" from the sheet. This is excluded by default, as the "helloIntent" is included in every conversation.
