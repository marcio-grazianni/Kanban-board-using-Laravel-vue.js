
Overview: This is a mock programming practice for us to get to know some of
your skill sets for the job better.
Time required: We do not expect that you to spend any more than 8 hours for
the completion of this project and we understand that it is possible to spend way
more time to get into a lot of details. We will primarily judge your work based on
the details indicated in the next pages. Alternatively, you may choose to spend
more than 8 hours at your own discretion and go above and beyond if you wish.
Use your own judgement.
Deadline: Within 2 business days of receipt of this project. Regrettably, late
submissions will not be considered.

Tech Stack:
1. PHP and Laravel (https://laravel.com/) -Use for all the back-end
operations
2. VueJS 2 (https://vuejs.org/v2/guide/) - Use for all front-end operations, do
not use any other library or addon, anything not included with vue will
have to be done with Vanilla js (http://vanilla-js.com/)
3. SCSS (https://sass-lang.com/documentation/syntax#scss) with the BEM
standard (http://getbem.com/introduction/) - Used for all the styling.
We use these technologies in BeMo and want to see your proficiency in ALL of
them.
Deliverables:
1. A link to the online version of your project - You need to deploy and
host the project yourself for us to see it online
2. A link to a GitHub repository - You need to upload all your code to
github and send us the repository
3. The API URL and access token – Include the API URL and access token
hash into the email you send us
We will use these two to check and rate your project. If your response doesn’t
include BOTH it will not be considered.

Requirements:

1. Columns:
a. Every column has a title.
b. The title should be at the top of the column.
c. At the top of the column there will be a button to delete that column.
d. When column is deleted all cards in it are also deleted.
e. There needs to be a way to add a new column.
f. There needs to be a way to add a card to column.

2. Cards:
a. Every card has title and description.
b. Every card belongs to a column.
c. In the column the card shows only the title.
d. When clicked a card opens in a modal. (you can use
https://www.npmjs.com/package/vue-js-modal for this)
e. The modal of card shows and allows to edit the title and
description.
f. Cards have the drag and drop option so they can be moved
sideways to other columns and up and down on their current
column. You can use: https://github.com/SortableJS/Vue.Draggable
for that.

3. Backend:
a. Each one of the actions need to be remembered in the database,
so the board is in the state it was left when we come back.
b. We need to have a button to export the board database as sql (you
can use https://github.com/spatie/db-dumper for this)
c. When the page is refreshed or navigated to is should remember the
last state.
d. There should be a simple GET API method to list all cards in the
JSON format. The method should receive an access token
(required) and a couple optional filters. If the access token is
missing or wrong, the API should not return anything. Filters
requested:
i. Creation date: format YYYY-MM-DD. If empty, bring all
creation dates.
ii. Status: value 1 for active, and 0 for deleted cards. If empty,
bring both.
Example of how this API call should look like:
https://mydomain.com/api/list-cards?access_token=42gA1S5&date=2021-12-05&status=1
Example response:
[{"id":1, "title":"Title 1","created_at":"2021-11-05
10:00:11","description":"Lorem ipsum si dalet", "deleted_at":
NULL},{"id":2, "title":"Title 2","created_at":"2021-12-11
22:15:00","description":"Dalet ipsum lorem si", "deleted_at": "2021-
12-08 00:00:00"}]

4. Style:
a. The UI needs to be simple but user friendly. As long as it is intuitive
and similar to the sketches, we will allow for freedom in it.

Bonus points:
• AJAX: if all actions are done without page refresh (you can use
https://www.npmjs.com/package/axios for that)
• Style: If the UI look nice.
