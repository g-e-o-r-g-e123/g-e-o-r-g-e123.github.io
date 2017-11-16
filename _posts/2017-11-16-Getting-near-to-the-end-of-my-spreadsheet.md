---
title: Getting near to the end of my spreadsheet
layout: post
author: george.dawson
permalink: /getting-near-to-the-end-of-my-spreadsheet/
source-id: 1txbEYv55Uri-iBzM9Q0ME9lPgn558ZlQC9PrYo-GW4k
published: true
---
13/11

Today, I added a shipping option, grand total and made the spreadsheet look better. I did this by doing a similar thing as I did to make the selection of items. I just used data validation to create a list of the shipping options to select and adding a table to see the prices of them. Then I needed to add this to the total by using 

'=(the total)+iferror(vlookup(the cells of the chosen delivery option,the top left of the table:the bottom right of the table,2,FALSE),0)'

Then I tidied it up so it would be easier to use.

