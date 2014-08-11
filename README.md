#Dominos Web Apache Challenge

In this challenge, players will need to traverse a poorly rights-protected directory try by 
viewing the source of certain webpages and using basic HTML and CSS knowledge.

### Solution
1. Visit index.html
2. Notice that the logo on the page has a broken link. View the source for the page and visit the `"/orders/logo.png"`.
3. Notice the Error 404. Visit the parent directory "/orders/" via the URL bar.
4. Scroll throught the directory listing. One of the files is saved as a .html file. Click on the link to this file.
5. Click on the link to "escalated priviledges".
6. The page says the user is restricted from accessing the page; however, there is a stylesheet referenced in the html document. View source and visit the "/theyllneverfindthis/styles.css" file.
7. It seems to be a normal css file, so visit "/theyllneverfindthis/".
8. In the directory listing, the digits to the key are listed out of order. Visit "/THE_ORDER_IS_DEFINITELY_NOT_FOUND_IN_HERE/".
9. The page appears to be normal at first. View source and find that there is a massive amount of random Italian text. The order is revealed in the heading tags scattered in the text. Read through to form the key.
10. (Alternatively) Remove  'style="visibility: hidden; display: none;"' from the div in the html via some sort of browser inspector or debugging tools. This will reveal the order more easily.

**Key** : MCA-F75C12EB