# GameRanking
Rank games played between multiple players, with ELO tracking.

This little project came about because I was working on a team that had a tabletennistable in our meeting room.

We played tabletennis and kept score on the whiteboards. After a while we had no more space for diagrams, charts, doodles, because there were too many game results on the whiteboards.

There was also no clear overview of who was the best player.

So, that's why I created this simple setup, consisting of a Microsoft Forms, a Microsoft Powerautomate (or "Flow") and an Excel file. By combining these items we now have a very easy way to keep track of who is the best player in our team (that is me, by the way).

It should be relatively straightforward to port this setup to Google Forms and Google Sheets. Most likely you won't even need a standalone script then.

## The form
This is the easiest part. Just execute the following steps:
1. Go to forms.office.com
2. Create a new form, for example "GameScores"
3. Create 4 questions:
- Player 1 Name. Make it a "Choice" question. Provide some names of people on your team. For example: John, Jane, Jill, Peter. Make sure you enable the "Other" option. That way you do not need to change the form when you want to add a new player.
- Player 1 Score. Set Restrictions to "Must be a number".
- Player 2 Name. Make it a "Choice" question. Provide some names of people on your team. For example: John, Jane, Jill, Peter. Make sure you enable the "Other" option. That way you do not need to change the form when you want to add a new player.
- Player 2 Score. Set Restrictions to "Must be a number".
4. Change the Theme, select a new background, look for something appropriate.
5. Save the form.

## The Spreadsheet
Took the longest to create.

## The Flow
