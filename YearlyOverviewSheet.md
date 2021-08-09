### Metric Definitions:

Metric | Definition
-------|-------
Unique Conversations | Count of independent conversations, a string of messages inside the same user session
Messages Sent | Amount of messages sent by all users
Count of Bad Feedback | Count of times a user answered "No" to "Did this answer your question"
Missed Utterence Overview | Utterence: What the customer writes to the bot. A missed utterence is when the bot dosent know how to respond. 
Unique Conversations Graph | A monthly overview of the amount of unique conversations
Intent Overview | A monthly overview, of how many utterences corresponded to each intent. The dotted line represents the average amount of messages sent for the current year
Reason for bad feedback | The feedback the customer gives after they say "No" to "Did this answer your question"

**Actions** 
- Clicking on either of the monthly graphs (Unique Conversations or Intent Overview) will result in a navigation to the "Detailed Report" sheet. Depending on what month point you clicked in the graph will determine what the "Date" filter will be set to on the "Detailed Report" Sheet. The idea is users will see an interesting month they want to learn more about. They will then click on it to retrive more information about the particular month.

**Controls:**
- Exclude HelloIntent: This allows the user to decide weather they want to exclude the "helloIntent" from the sheet, this is because the "helloIntent" significantly effects results. This can be seen when deselecting it, it is now no longer exclued, this results in  "Unique Conversations" metric to go up by almost 3000 (as of 9/8/21) meaning there were almost 3000 conversations that only included the helloIntent and nothing further.
