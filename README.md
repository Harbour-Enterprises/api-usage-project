# API Usage & Billing System - Take Home Project

## Context
SuperDoc provides document conversion services through its API endpoints (e.g., `/convert` for converting documents between formats like DOCX to PDF, PDF to DOCX, DOCX to HTML). We need a system to track API usage and handle billing.

## Project Overview
Design and implement a usage tracking and billing system that will:
- Track API calls to document conversion endpoints
- Manage usage quotas
- Calculate billing based on usage

## Core Requirements

### 1. Usage Tracking
Track essential metrics for document conversions:
```json
{
  "account_id": "string",
  "endpoint": "string",
  "timestamp": "datetime",
  "status": "success|failure"
}
```

### 2. Billing System
Implement simple tiered pricing:
- Free tier: 100 requests/month
- Pro tier: $0.10 per request

### 3. Technical Requirements
- Use Python with FastAPI
- Implement proper authentication
- Handle concurrent requests
- Include error handling
- Add logging

## Required Deliverables

### 1. API Implementation
- Complete REST API with endpoints for:
  - Usage tracking
  - Usage statistics retrieval
  - Quota checking
  - Billing calculations
- Authentication mechanism
- Input validation
- Error handling
- Rate limiting (optional)

### 2. Database
- Schema design
- Indexes for performance (optional)

### 3. Tests
- Unit tests
- Integration tests
- Test coverage report
- Performance tests (optional)

### 4. Documentation
- API documentation (OpenAPI/Swagger)
- Setup instructions
- Architecture overview
- Design decisions explanation
- Future improvements

### 5. Code Quality
- Clean, maintainable code
- Proper error handling
- Logging
- Type hints
- Comments where necessary

## Evaluation Criteria

### API Design (30%)
- RESTful principles
- Authentication implementation
- Error handling
- Documentation quality

### Code Quality (25%)
- Clean code practices
- Error handling
- Testing coverage
- Type safety

### System Design (25%)
- Database schema
- Concurrency handling
- Performance considerations
- Scalability approach

### Documentation (20%)
- Setup instructions
- Architecture explanation
- Design decisions
- Future improvements

## Time Expectation
- Core requirements: 6-8 hours
- Additional features: 2-4 hours (optional)

## Submission Guidelines
1. Provide source code in a Git repository
2. Include comprehensive README.md
3. Document all assumptions and decisions
4. Note any shortcuts taken due to time constraints
5. Suggest future improvements

## Questions?
If you need any clarification about the requirements, please don't hesitate to ask. We want to ensure you can showcase your skills effectively.