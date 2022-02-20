# GoogleForm
This python script enables you to fill any Google form with random responses. Also, for text field like name and email, there are at least two hundred names and emails present in the script to fill the Google form already. (They can be generated from free websites.)  Although, this script is not supporting a multiple choice grid currently, I'm sure that making this script public will invite other people to contribute and enhance it.
Watch the end result here: https://www.facebook.com/TheParin/posts/3040619756216527 

I kept a Google Colab version here, too: https://colab.research.google.com/drive/173E8Lx0TBe2L8vll_u81ewOwyPgKLk1z?usp=sharing , But, This script is recommended on a local machine

Some web resources for the code:
https://medium.com/swlh/automatically-filling-multiple-responses-into-a-google-form-with-selenium-and-python-176340c5220d

https://www.youtube.com/watch?v=kVFcE4M6lw0

https://www.youtube.com/watch?v=YbGAUEjTKg4

https://towardsdatascience.com/automating-submission-forms-with-python-94459353b03e

Notes:
The example of the Google Form used is this: https://forms.gle/8o1CBnNZhzgeW4Ry9 .

I have used the TEXT-type entries and RADIO button-type entries. For other types, You may require to understand terms place codes accordingly ( e.g. Check boxes, etc. )

You will need to install Chrome Web Driver according the CHROME Browser version in your PC/Laptop. Learn to do that here: https://www.softwaretestinghelp.com/chromedriver-selenium/

For any other Google form, You will require to find elements of each section and insert them one-by-one in the Code below, replacing my codes sections.

Also, each question in the google form would have the set of choices. So, to ensure the code make random selections every time but makes at least one entry in each question, I have described the list ( i.e. Square brackets) in the code below.
