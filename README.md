# 86-quiz

This is a quiz to help assess your risk of getting asked to leave from Noisebridge.

To add a question go to the question array in the index.html

Add a new object to the array as follows:

```

{
    "question": "You see a half built project at Noisebridge with a note saying 'Do Not Hack' and it is dated from 1 week ago, is it ok to hack it?",
    "answers": [
        ["No, under no circumstances",2,"Everything is possible."],
        ["Yes, but only after asking the project owner",0,"It is excellent to improve projects at Noisebridge."],
        ["Yes, I can do whatever I want",25,"Your risk of getting banned just increased."],
    ]
},

```


To do:
Escape single quotes in the question array, as this causes the quiz to freeze
