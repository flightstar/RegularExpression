# RegularExpression
Some regular expression popular:

+ Matching a username: `/^[a-z0-9_-]{3,16}$/`
+ Matching a password: `/^[a-z0-9_-]{6,18}$/`
+ Matching a hex value: `/^[a-z0-9_-]{6,18}$/`
+ Matching a "slug": `/^[a-z0-9-]+$/`
+ Matching an email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`
+ Matching an URL:
  + `/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`
  + `^(https?|ftp|file)://[-a-zA-Z0-9+&@#/%?=~_|!:,.;]*[-a-zA-Z0-9+&@#/%=~_|]` 
  + `\\b(https?|ftp|file)://[-a-zA-Z0-9+&@#/%?=~_|!:,.;]*[-a-zA-Z0-9+&@#/%=~_|]`  **[Demo](https://github.com/flightstar/BFS_Algorithm_Crawl_Data)**
+ Matching an IP Address: `/^(?:(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\.){3}(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)$/`
+ Matching an HTML tag: `/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/`
