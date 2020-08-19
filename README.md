# Get Characters from Excel Rows using LEFT, RIGHT Functions
Getting Characters from Excel Rows

= LEFT(text, num_chars)
= RIGHT(text, num_chars)

As you can see in the Sheet1 there were the following Requirements:-

1) Get Address from the Mailing Address Column
2) GET Zip Code from the Mailing Address Column

To solve this problem I have used LEFT, RIGHT, LEN Functions of Excel in the OUTPUT Sheet.

1) To get the Address I have used LEFT Function in this way >>> =LEFT(A2,LEN(A2)-15) in Address Column

This will simple get the all the text but not the last 15 characters as I have subtracted from the length of the Text

2) To get the Zip Code I have used LEFT Function in this way >>> =RIGHT(A2,10) in Zip Column

I got the last 10 Characters from the Right and then I used =LEFT(H2,5) in Zip Code Column to get the first five Characters

