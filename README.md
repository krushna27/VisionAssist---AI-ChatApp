# VisionAssist---AI-ChatApp
AI for Scene Understanding, Text Extraction &amp; Speech for the Visually Impaired.

Problem Statement
Visually impaired individuals encounter significant obstacles in their daily lives due to their inability to perceive and interpret visual information. Tasks such as understanding their environment, reading text, recognizing objects, and safely navigating spaces often require external assistance or specialized tools. Despite the availability of some assistive technologies, gaps remain in providing a comprehensive, real-time, and user-friendly solution.

This project seeks to leverage Generative AI and other advanced technologies to develop an AI-powered application that empowers visually impaired individuals by addressing these challenges. The solution focuses on providing:

Provides real-time scene understanding to describe environments to visually impaired individuals.
Extracts text from images to make printed and digital content accessible.
Converts visual information into audio to ensure seamless interaction.
Assists in navigation and daily tasks by recognizing objects and providing contextual guidance.
By integrating these functionalities into an intuitive interface built on Streamlit, the application aims to enhance independence and improve the quality of life for visually impaired users.


** Case Studies
1. Real-Time Scene Understanding: Navigating Unknown Spaces
* Scenario: A visually impaired user is in a new location, such as a park, and needs to understand their surroundings to move safely and confidently.
* Solution:
The user uploads an image of the environment through the application.
The AI, using a combination of Google Generative AI (Gemini) and LangChain, generates a descriptive textual output such as:
"You are in a park. There is a bench to your left, trees ahead, and a pathway leading forward."
The description is read aloud to the user via text-to-speech conversion.
* Impact:
The user gains a clear mental image of their environment, enabling them to navigate safely without needing external assistance.



2. Text-to-Speech Conversion for Accessible Reading
* Scenario: The user receives a printed invitation but cannot read the text due to visual impairment.
* Solution:
The user uploads a photo of the invitation to the application.
PyTesseract extracts the text from the image, and pyttsx3 converts it into speech.
The system reads aloud:
"You are invited to the Annual Gala Dinner on December 10th, at 7:00 PM, Grand Ballroom, City Hotel."
* Impact:
This feature ensures that visually impaired individuals can independently access written content, such as invitations, menus, or signs, without relying on someone else to read for them.

3. Personalized Assistance for Daily Tasks
* Scenario: The user is sorting groceries at home and needs help identifying products, such as distinguishing a can of soup from a can of beans.
* Solution:
The user uploads images of the products.
The system analyzes the labels using OCR and context from LangChain, providing detailed output:
"This is a can of chicken noodle soup, Campbell's brand."
The system can also provide cooking instructions or storage tips, depending on user needs.
* Impact:
The user can independently manage daily tasks, such as organizing items, cooking, or shopping, making them more self-reliant and reducing dependency on others.

This project addresses the unique challenges faced by visually impaired individuals by offering a versatile and intelligent solution that integrates Generative AI, OCR, and text-to-speech technologies. By enabling real-time scene understanding, text extraction, object detection, and personalized assistance, the application empowers users to navigate their world with greater independence, confidence, and ease.
