---
content_type: page
description: This section provides information on the course projects.
learning_resource_types:
- Projects
ocw_type: CourseSection
title: Projects
uid: ce7d4f4a-59ad-4d14-4592-be7641ff9daf
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Project 1 – Hangman
-------------------

Project 1 ({{% resource_link 6b3bd210-f97d-0a35-9b72-cbacb174028c "PDF" %}}) was the game of Hangman. The handout guides you through the process. This process is called _incremental programming_. It allows you to tackle complex problems, like writing a game of Hangman, by tackling small sub-tasks first. In this case, we can tackle the problems of figuring out whether the user has guessed the word, or creating a string of the word with the letters guessed so far. With the sub-tasks taken care of, it's easier to take on the bigger task.

Optional project files: word list ({{% resource_link 505ed63e-7ecd-a091-d884-e02ad7726599 "TXT" %}}) contains many words; hangman\_lib.py ({{% resource_link 5db9c3ed-1a63-646b-2a39-154bb98947d0 "PY" %}}) contains helper functions to get a random word and to print a Hangman image; hangman.py ({{% resource_link 520ca17a-0526-01b8-8e01-377e0e2882ea "PY" %}}) contains example usage of hangman\_lib.

Example solution: hangman\_soln.py ({{% resource_link 477a7b86-e8c5-0486-b48c-02363f720bef "PY" %}}) (needs to be in same directory as above files)

Project 2 – Guitar Hero Clone
-----------------------------

Project 2 was a clone of the game of Guitar Hero. This is a decently complex game, and trying to do it all at once is not practical. Instead, we learn the importance of _modularity_ and _teamwork_ by breaking up the functional parts of the game (input, graphics, sound and logic) and completing these parts in teams. This approach even allowed us to have a working, playable prototype at the end of class, despite being incomplete.

Note: this project could not be included in MIT OpenCourseWare due to copyright restrictions.

Sample Program 1 – Tic-Tac-Toe
------------------------------

Many of you asked for us to write a tic-tac-toe program as one of our sample programs. In the beginning of class 6, Mihir wrote such a program in front of you all. The goal of that program was to be simple and straightforward, and it was successful.

I've written another version, with a different goal: to be polished. My implementation is considerably different, and that's fine; we all have different styles of programming. Take a look. It's extensively commented, but feel free to email with questions.

File: tictactoe.py ({{% resource_link 991ff5e6-3989-5ef1-7e01-2df5cc59d6e0 "PY" %}})

Sample Program 2 – Connect Four
-------------------------------

Here's another sample program with the goal of being polished. This is a great example where the implementation is not trivial (unlike in Tic-Tac-Toe), so abstraction is vital to prevent bugs and to keep the code readable.

There are some Python things in the code that you may not know yet. The assert statement just throws an error if the following condition isn't True. Writing a string with the % symbol lets you plug in the variables that follow into that spot in the string (%s means string, %i means integer and %c means one letter).

So take a look. It's not quite so extensively commented as the Tic-Tac-Toe program, so feel free to email me with questions.

File: connectfour.py ({{% resource_link e158cc0d-1bac-8d22-1523-704ec177eb9a "PY" %}})