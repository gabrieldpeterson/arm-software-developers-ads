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
            Does Kafka run on Arm servers?
        answers:
            - "Yes"
            - "No"
        correct_answer: 1                    
        explination: >
            Kafka is fully supported on 64-bit Arm servers running Linux. 
               
    - questions:
        question: >
            What software is required to run Zookeeper and Kafka?
        answers:
            - "None"
            - "Arm Assembly"
            - "Go"
            - "Java"
        correct_answer: 4                    
        explination: >
            You will need Java installed.




# ================================================================================
#       FIXED, DO NOT MODIFY
# ================================================================================
title: "Review"                 # Always the same title
weight: 20                      # Set to always be larger than the content in this path
layout: "learningpathall"       # All files under learning paths have this same wrapper
---
