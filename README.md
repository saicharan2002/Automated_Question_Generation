# Automated_Question_Generation

## Overview
This project provides an automated system for generating objective evaluation questions, including multiple choice, fill in the blank, and match the following. With the shift towards online exams and objective evaluation, this system saves time for educators while also providing practice and self-evaluation opportunities for students.

## Project Structure
Data Preprocessing: This module is responsible for cleaning and processing the input text before feeding it into the question generation model.  
Informative Sentence Extraction: This module utilizes NLP techniques to extract informative sentences from the preprocessed text.  
Question Generation: This module takes the informative sentences and generates different types of questions, including MCQs, Fill in the Blanks, Match the Following, and True or False.  
Evaluation: This module evaluates the generated questions by comparing them with the handcrafted questions.  

## Features
Automated generation of objective evaluation questions  
Use of Wordnet and Sense2Vec to create distractions and produce query options  
Efficient in both time and money for educational organizations  
Encourages practice and self-evaluation for students

## Requirements
Python 3.x  
Wordnet  
Sense2Vec
