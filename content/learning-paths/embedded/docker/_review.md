---
# ================================================================================
#       Edit
# ================================================================================

# Always 3 questions. Should try to test the reader's knowledge, and reinforce the key points you want them to remember.
    # question:         A one sentance question
    # answers:          The correct answers (from 2-4 answer options only). Should be surrounded by quotes.
    # correct_answer:   An integer indicating what answer is correct (index starts from 0)
    # explination:      A short (1-3 sentance) explination of why the correct answer is correct. Can add aditional context if desired


review:
    - questions:
        question: >
            A Dockerfile is a text file containing all the instructions to build your docker image.
        answers:
            - "True"
            - "False"
        correct_answer: 1                    
        explination: >
            True. The format of the file is very easy to understand.

    - questions:
        question: >
            Which command is used to interact with your docker container
        answers:
            - "docker run -t <image_name> /bin/bash"
            - "docker run -i -t <image_name>"
            - "docker run -i -t <image_name> /bin/bash"
        correct_answer: 3
        explination: >
            The '-i' option is for interactive.


# ================================================================================
#       FIXED, DO NOT MODIFY
# ================================================================================
title: "Review"                 # Always the same title
weight: 20                      # Set to always be larger than the content in this path
layout: "learningpathall"       # All files under learning paths have this same wrapper
---
