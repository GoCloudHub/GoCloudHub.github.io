# Metric Definitions:

Metric | Definition
-------|-------
Unique Conversations | Count of independent conversations, a string of messages inside the same user session
Messages Sent | Count of messages sent by all users
Count of Negative Feedback | Count of times a user answered "No" to "Did this answer your question"
Unique Conversations Graph | Count of unique conversations by month
Intent Overview | A monthly overview, of how many utterances corresponded to each intent. The dotted line represents the average amount of messages sent for the current year.
Reason for negative feedback | The feedback the customer gives after they say "No" to "Did this answer your question"

**Actions** 
- Clicking on either of the monthly graphs (Unique Conversations or Intent Overview) will result in a navigation to the "Detailed Report" sheet. Depending on what month point you clicked in the graph will determine what the "Date" filter will be set to on the "Detailed Report" Sheet. The idea is users will see an interesting month they want to learn more about. They will then click on it to retrieve more information about the particular month.

**Controls:**
- Exclude HelloIntent: This allows the user to decide whether they want to exclude the "helloIntent" from the sheet. This is excluded by default, as the "helloIntent" is included in every conversation.
