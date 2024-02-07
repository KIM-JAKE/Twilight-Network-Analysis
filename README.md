# Twilight-Network-Analysis

![image](https://github.com/KIM-JAKE/Twilight-Network-Analysis/assets/138518817/7dcdeb0f-272f-4f7a-b7a1-bfb6603cad10)

## Overview
This project was conducted for the purpose of analyzing the emotional network and importance between the characters of the novel 'Twilight'. As a dataset, we downloaded [4 books](https://blog.naver.com/PostView.naver?blogId=punch833&logNo=220808271039) in English of Twilight and analyzed them based on natural language processing and graph theory.

## Why Character Network? 
- Understanding the interactions and relationships between characters.

- Identifying the key central characters in the story.

- Grasping the structure of the narrative.

- Engaging the reader's emotional connection.

## Research Questions
- Can we identify the **main characters** based on the **frequency** of their mention throughout the overall text of the book?
  
    ☞ Analysis of character importance in the novel

- Can we understand the depth of relationships and **emotional connections** between characters based on how often two characters are mentioned within the same sentence?

    ☞ Analysis of character relationships in the novel

- Can we successfully **cluster** characters by applying a community detection algorithm to the relationship analysis results?
(Good and evil / Wizards and humans / Vampires and humans, etc.)

    ☞ Clustering analysis using Community Detection Algorithm

## Methods
**1. method ①**
- Analyzing characters who are frequently mentioned throughout the book (e.g., Top 25 characters by mention frequency)
- Characters who are mentioned often could be important in the story
- There is a possibility that they may not be central characters in the overall narrative

![image](https://github.com/KIM-JAKE/Twilight-Network-Analysis/assets/138518817/bb4456cf-0ac4-4a61-b861-5eda09a55946)

![image](https://github.com/KIM-JAKE/Twilight-Network-Analysis/assets/138518817/8f8805b4-61f1-4a9d-a95b-883c468ef93d)

![image](https://github.com/KIM-JAKE/Twilight-Network-Analysis/assets/138518817/2fb370d5-c2eb-46e6-8380-e68ceceba1b2)

![image](https://github.com/KIM-JAKE/Twilight-Network-Analysis/assets/138518817/6db1d2f4-d733-4672-b9ca-ebb074cc0a5f)



**2. method ②**
- After extracting characters that are mentioned more than a certain threshold throughout the book, delete characters who do not belong to a major network
- It is possible to identify important characters in the overall story flow
- There is a possibility of deleting important characters

![image](https://github.com/KIM-JAKE/Twilight-Network-Analysis/assets/138518817/b1546238-6e75-4906-8c11-32704ef086f7)

![image](https://github.com/KIM-JAKE/Twilight-Network-Analysis/assets/138518817/262ba6a9-e793-4be5-a0dc-ee16d8aad17f)

## Additional task
- **Community Detection**
- 
![image](https://github.com/KIM-JAKE/Twilight-Network-Analysis/assets/138518817/b8214ae5-bc5b-4bc7-a4d2-59cdbd345bcf)

- **Analyzing the well-known 'Romeo and Juliet'**
- 
![image](https://github.com/KIM-JAKE/Twilight-Network-Analysis/assets/138518817/e499b186-8f27-4192-848c-a66f5a281c1a)

