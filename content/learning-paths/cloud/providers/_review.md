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
            What is the name of the cloud service provided by Microsoft?
        answers:
            - "AWS"
            - "Azure"
            - "OCI"
        correct_answer: 2
        explination: >
            Microsoft Azure is the umbrella name of their cloud based services.

    - questions:
        question: >
            What is the name of the Arm based processor that powers AWS?
        answers:
            - "Graviton"
            - "Groverton"
            - "Gallileo"
        correct_answer: 1
        explination: >
            AWS Graviton processors are used. The instances can be identified with a 'g' in their name.
               
    - questions:
        question: >
            Which of these cloud service providers offer Arm-based solutions?
        answers:
            - "Alibaba"
            - "AWS"
            - "Google"
            - "Microsoft"
            - "Oracle"
            - "All the above"
        correct_answer: 6
        explination: >
            All major cloud service providers offer Arm-based solutions, at rapidly expanding availability.

# ================================================================================
#       FIXED, DO NOT MODIFY
# ================================================================================
title: "Review"                 # Always the same title
weight: 20                      # Set to always be larger than the content in this path
layout: "learningpathall"       # All files under learning paths have this same wrapper
---
