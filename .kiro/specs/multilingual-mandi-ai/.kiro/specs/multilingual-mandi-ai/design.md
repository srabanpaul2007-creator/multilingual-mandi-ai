# Design – Multilingual Mandi AI

## Overview
The system provides a real-time AI-powered bridge between buyers and sellers in local markets, enabling fair pricing and multilingual communication.

## Architecture
- Frontend: Web application (mobile-first)
- Speech Processing: AWS Transcribe
- Language Translation: AWS Translate
- Generative AI Engine: AWS Bedrock
- Backend Services: AWS Lambda and API Gateway
- Data Storage: DynamoDB

## User Flow
Vendor speaks in native language → AI translates → AI suggests fair price → AI assists negotiation → Deal confirmation
