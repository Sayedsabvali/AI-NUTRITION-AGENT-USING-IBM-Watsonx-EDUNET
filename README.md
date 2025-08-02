# AI-NUTRITION-AGENT-USING-IBM-Watsonx-EDUNET
**Problem Statement 8**
**Build an AI agent that provides personalized dietary recommendations and health tips using structured nutrition knowledge, ensuring user-specific guidance for weight loss, muscle gain, and chronic conditions like diabetes.**

**Features**
Personalized nutrition advice based on user goals (weight loss, muscle gain, diabetic-friendly, vegan, etc.).
Health guidance beyond diet (hydration, exercise, mindful eating).
Friendly and supportive conversational style (motivational responses).
Uses structured data (50 foods + 10 meal plans) with nutrition facts and health benefits.
Deployed on IBM Watsonx.ai with Agent Builder and Vector Index.
**Technology Stack**
IBM Watsonx.ai – Agent Builder (RAG approach)
Vector Index (Knowledge Base) – Nutrition dataset
IBM Cloud Object Storage – File storage and project support
TXT Knowledge File – 50 foods + 10 meal plans
Python (for dataset preparation) – Data formatting and pre-processing
**Dataset**
50 food items and 10 meal plans with:
Calories, protein, carbs, fats
Diet type (vegan, vegetarian, non-veg, diabetic-friendly)
Health benefits and food swap tips
**Process Overview**
Created a project on IBM Watsonx.ai (London region).
Prepared rich nutrition dataset (50 foods + 10 meal plans) and converted to TXT.
Uploaded TXT file as Vector Index in Agent Builder (Knowledge tab).
Added friendly health & dietician-style instruction prompt.
Tested and deployed agent for real-time queries.
**Future Scope**
Add fitness tracker and calorie calculator.
Voice integration for real-time health coaching.
Expand dataset to 200+ foods and regional meal plans.
Acknowledgements
Edunet Foundation for internship opportunity.
IBM SkillsBuild for Watsonx.ai platform and training.
