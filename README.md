# Say It

The application gives the user the ability to share a story and view the stories of other users. 
When a user sends a story, he can specify the cost of the payment. Depending on the amount of payment, the story gets a color label. Thus, history stands out and gets more attention. 

![Story](https://github.com/shtift/SayIt/blob/master/images/message.png?raw=true)

![Badges](https://github.com/shtift/SayIt/blob/master/images/badges.png?raw=true)

Also, depending on the amount of payment, generated a daily, weekly, monthly top.

![Tops](https://github.com/shtift/SayIt/blob/master/images/tops.png?raw=true)

## Contract description

- `count()`

Return count of stories.
Badges
- `getByDate(unixStampDate)`

Returns stories created on the specified date. 
Parameter "unixStampDate" must contain a date without time in UnixTime format.

- `getByAuthor(author)`

Returns stories created by the specified author.

- `get(limit, offset)`

Returns a specified number of stories with the specified offset.

- `save(storyText, unixStamp, unixStampDate)`

Saves user story. Parameter "unixStamp" must contain the full time of creating a history in UnixTime format. Parameter "unixStampDate" must contain a date without time in UnixTime format.
