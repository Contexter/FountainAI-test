# FountainAI: Enhanced Screenplay Writing with AI

## Introduction and Goals
FountainAI is aimed at democratizing Ai model training & the writing process by integrating and training advanced AI features. Building upon a classic writing app ( a Fountain screenplay app ), this project infuses AI capabilities using Replicate and OpenAI APIs, complemented by a robust Strapi backend for detailed interaction logging. The goal is to provide  writers with an intuitive, AI-enhanced tool that simplifies and enriches the creative writing process AND manages data to format and train a specialized AI model.

## Project Overview
The primary objective is to enhance the Fountain app with AI-driven features for script analysis, suggestion, and content generation, while ensuring seamless user experiences. The project involves:
- Refactoring and updating the existing Fountain codebase.
- Integrating OpenAI API for advanced text processing and generation.
- Incorporating Replicate for additional AI functionalities.
- Implementing a Strapi backend for logging API interactions and user activities to user authorized access.

## Detailed Implementation Plan

### Phase 1: Preparation and Analysis
- Review the existing Fountain app codebase.
- Familiarize with the Replicate SwiftUI starter project.
- Understand OpenAI API capabilities and obtain necessary API keys.
- Set up and configure the Strapi backend for logging.

### Phase 2: Development Setup
- Create a new Swift project or add Swift files to the existing Fountain project.
- Establish a bridging header for Swift and Objective-C interoperability.

### Phase 3: Core Development
- Develop `OpenAIService` in Swift for OpenAI API interaction.
- Integrate Replicate API logic into the Swift codebase.
- Rewrite essential components of Fountain from Objective-C to Swift.
- Implement networking in Swift for Strapi backend communication.

### Phase 4: Testing and Quality Assurance
- Conduct unit and integration tests for Swift components.
- Test OpenAI and Replicate API integrations and UI interactions.
- Validate Strapi backend logging and data security.

### Phase 5: Documentation and Deployment
- Document the new features, code changes, and usage instructions.
- Deploy the updated Fountain app with integrated AI features.

### Phase 6: Compliance and Security
- Ensure compliance with OpenAI’s usage policies and data privacy laws.
- Implement security measures for API key storage and data transmission.

### Phase 7: Post-Deployment
- Address any immediate post-deployment bugs or issues.
- Plan for future updates and potential feature enhancements.

### Training Model Using Strapi Logging Data
- Access and export Strapi data for model training.
- Select a Model Training Platform.
- Upload and train the model using platform tools.
- Evaluate model performance and iterate if necessary.
- Deploy the trained model and monitor its performance in the application.
- Maintain documentation and ensure data compliance.

## Success Metrics and Risk Management
- Successful AI feature integration without disrupting core functionalities.
- Robust and secure logging of interactions.
- Positive user feedback and seamless user experience.
- Regular backups, prepared rollback plans, and API usage monitoring.
