# Google Cloud Platform (GCP) recources by GDG

You’ll get free Google Cloud access during the event—no credit card needed.

## How to redeem:

- Make sure you’re signed into a Gmail/Google account.

- Open our event’s unique link: https://trygcp.dev/claim/gdg-other-ai-accelerate-hack

- Follow the prompts to activate your account and access the Google Cloud Console.

## Generating Gemini API Keys

After completing the steps to access the Google Cloud Console, you can generate your Gemini API Keys for free. You can find the keys be going to Google AI Studio (https://aistudio.google.com/api-keys) with the same google account used in the steps above.
<img width="1905" height="493" alt="image" src="https://github.com/user-attachments/assets/4ec3a2d3-54cd-4858-979c-2b89fd2e0c17" />

## What is GCP?
Google Cloud Platform offers all the tools of the google cloud development environment to build your applications. It also offers free Gemini API Keys so you can leverage the full potential of generative AI during today's hacking!

These are some of the services the GCP offers ranging from backend & storage to scheduling and ML workloads. Some of them might be interesting to leverage during this case, especially the services enablign AI services! 

* **Vertex AI** : Train/host custom models, embeddings, batch prediction, Model Garden.
* **Vision API** : Labels, OCR, object detection.
* **Speech-to-Text / Text-to-Speech** : Voice features.
* **Translation API** : Multilingual apps fast.
* **Vertex AI Workbench** : Managed notebooks; GPUs/TPUs if available.

GCP offers a broad range of other services to allow for cloud deployment of applications. Feel free to check out the possibilities of GCP for your hacking today or future projects!


# ING Voice Assistant Hackathon 2025

## Overview
This repository contains synthetic banking data and website content chunks to support the development of an innovative voice-enabled assistant for ING Belgium customers. The goal is to create a solution that helps customers navigate banking services, find information, and initiate requests efficiently using natural language interaction.

## Project Objective
Create a voice-enabled assistant that:
- Guides customers through banking processes and requests
- Leverages customer data and banking information
- Supports Dutch (required), French and English (bonus)
- Provides natural, context-aware conversations
- Scales to handle various types of requests and data

## Dataset Structure

### 1. Banking Data
The repository includes synthetic banking data representing:

#### Customers (`customers.csv`)
- Customer demographics
- Segmentation (ADULT, CHILD, PROSPECT)
- Contact information
- Belgian context (addresses, names)

#### Products (`products.csv`)
- Various banking products (Current Account, Savings, Credit/Debit Cards, Loans)
- Product status tracking (Active, Blocked by ING, Blocked by Customer, Closed)
- Product-customer relationships

#### Transactions (`transactions.csv`)
- Comprehensive transaction history
- Transaction types (Credit, Debit)
- Realistic amounts and descriptions
- Date-based organization

### 2. Website Content
The `chunks` folder contains segmented content from ing.be:
- Organized by language (NL, FR, EN)
- One file per paragraph/section
- Covers banking processes and information

## Technical Requirements

### Core Features
1. Voice Interface
   - Natural language processing
   - Multi-language support (NL required, FR/EN bonus)
   - Dialect handling
   - Low latency response

2. Information Retrieval
   - Context-aware responses
   - Process guidance
   - Account information integration
   - Scalable knowledge base

3. Security
   - Secure data handling
   - Authentication mechanisms
   - Privacy compliance

### Implementation Considerations
- Scalable architecture
- AI/ML integration
- Performance optimization
- Error handling
- User experience
- Monitoring and analytics

## Evaluation Criteria

1. Functional and User Experience (40%)
   - Accuracy of responses
   - Language interpretation
   - Conversation fluidity
   - Response time
   - User interaction quality

2. Innovation and Creativity (25%)
   - Novel approaches
   - Creative solutions
   - Unique features

3. Technical Feasibility (20%)
   - Scalability
   - Implementation completeness
   - Security measures
   - Quality assurance

4. Demo and Presentation (15%)
   - Solution demonstration
   - Clear presentation
   - Documentation quality

## Submission Requirements

1. Live Demo
   - Working prototype
   - End-to-end flow demonstration

2. Documentation
   - One-page technical summary
   - Problem statement
   - Solution architecture
   - AI implementation details
   - Known limitations

3. Code/Prototype
   - Functional implementation
   - Setup instructions

4. Optional Presentation (3-5 slides)
   - Problem overview
   - Solution description
   - Technical architecture
   - Implementation flow

## Development Notes
- Sample data represents October 2025 timeframe
- Transactions include various types of banking activities
- Product statuses reflect real-world scenarios
- Customer segments represent different use cases
- Website content chunks enable flexible information retrieval

## Getting Started
1. Clone this repository
2. Review the data structure in `synthetic_data/`
3. Explore website content in `chunks/`
4. Set up your development environment
5. Start building your voice assistant solution

## Platform Options
- Google Cloud Platform (suggested)
- Alternative cloud platforms acceptable
- Local development supported



Good luck with your implementation!
