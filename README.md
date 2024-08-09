# Humanoid AI for Patient Engagement

## Project Overview

This project leverages Humanoid AI with Large Language Model (LLM) capabilities to engage patients in meaningful conversation, detect emotions, and provide cognitive brain games. The system aims to enhance patient interaction, emotional well-being, and cognitive health.

## Features

### Conversation and Emotion Detection
- **Engaging Conversations**: The Humanoid AI uses LLM to initiate and maintain engaging conversations with patients.
- **Emotion Detection**: Analyzes conversations for signs of anger. If detected, it adapts prompts to be more caring and supportive, offers calming activities, or suggests taking a break.

### Brain Games
- **Personalized Brain Games**: Proposes brain games based on patient preferences and engagement levels.
- **Adaptive Difficulty**: Adjusts game difficulty and frequency based on patient performance and engagement.

### Memory Reminiscing
- **Memory Database**: Stores family-provided memories which the LLM incorporates into conversations to promote emotional connections and reminiscing.

### Topic Exploration
- **Interest Tracking**: Identifies patient interests and periodically introduces related conversation topics.
- **Dynamic Updates**: Continuously gathers and updates information about evolving patient interests.

### Meal Reminders
- **Healthy Eating Habits**: Assists patients in maintaining healthy eating habits by providing meal reminders.

### Continuous Learning
- **Patient Interaction**: Uses patient interactions and feedback to improve conversation models and personalize experiences.
- **Model Retraining**: Periodically retrains conversational AI and cognitive game prompters using new data.

## System Architecture

### Patient Interface
- **Conversation Interface**: Patients interact with the conversational AI through this interface.
- **Cognitive Games**: The interface also supports playing cognitive games, with progress tracked and stored in the database.

### Caretaker Interface
- **Patient Data View**: Caretakers can view patient data and adjust game difficulty settings.
- **System Monitoring**: Logs all system activity and monitors key metrics.

### Workflow
1. **Conversation Initiation**: Humanoid AI engages the patient in conversation using LLM capabilities.
2. **Emotion Analysis**: The emotion detection module analyzes the conversation.
    - If anger is detected, the system adapts prompts and suggests calming activities.
    - If no anger is detected, the conversation continues as usual.
3. **Brain Games Proposal**: Periodically propose brain games based on patient preferences.
4. **Memory Integration**: Incorporate patient-specific memories into conversations.
5. **Interest-Based Topics**: Introduce new conversation topics based on tracked interests.
6. **Continuous Learning**: Use interactions and feedback to improve the AI and cognitive games.
