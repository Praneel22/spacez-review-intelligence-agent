# Spacez AI Review Intelligence Agent

Spacez receives guest reviews across Airbnb, Booking.com, and Google.

The challenge is not collecting reviews but converting them into actions.

Different stakeholders need different outputs:

- Operations
- Business
- Caretakers

Most review tools stop at sentiment analysis.

This project focuses on accountability routing and action generation.

## Live Prototype

https://spacez-whisperer.lovable.app

Built as part of the Spacez AI Product Associate assessment.

Objective:
Design an AI-powered review intelligence system that converts guest reviews into stakeholder-specific actions.

## Key Insight

Not every negative review should be sent to the caretaker.

Examples:

WiFi failure → Operations

Pool maintenance → Operations

Misleading listing photos → Business

Check-in delays → Caretaker

The system first identifies ownership before routing feedback.

## AI Workflow

Reviews
↓
Normalization
↓
Sentiment Detection
↓
Issue Extraction
↓
Root Cause Classification
↓
Stakeholder Routing
↓
Action Recommendation

## Stakeholder Outputs

### Operations
- Maintenance issues
- Cleanliness issues
- Vendor failures

### Business
- Reputation risks
- Listing accuracy
- Portfolio performance

### Caretakers
- Check-in experience
- Communication quality
- Guest handling

## What Makes This Different

Most review analytics tools answer:

"What happened?"

This system answers:

"Who should act?"

The focus is accountability assignment rather than sentiment reporting.

## Risks

- Sentiment misclassification
- Incorrect accountability assignment
- Over-reliance on automation
- Small review sample sizes

Human review remains part of the workflow.

## Future Roadmap

Phase 1:
Review Intelligence

Phase 2:
Stakeholder Routing

Phase 3:
Caretaker Coaching

Phase 4:
Predictive Risk Detection

Phase 5:
Automated Ticket Creation
