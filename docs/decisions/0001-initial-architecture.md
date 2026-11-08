
# ADR 0001: Initial Architecture

**Status:** Proposed

## Context

Skylark is being developed by three part-time contributors.

We want a maintainable architecture that supports full-stack functionality first, followed by geospatial and AI capabilities.

## Decisions

### Frontend

React with TypeScript and Vite.

### Backend

Python FastAPI organized as a modular monolith.

### Database

PostgreSQL.

### Authentication

Amazon Cognito.

### Frontend Deployment

Amazon S3 and CloudFront.

## Open Decision: Backend Hosting

Two options remain under evaluation:

1. Amazon ECS Fargate with Application Load Balancer.
2. Amazon EC2 with Docker and Caddy.

The team will evaluate cost, operational complexity, security, and learning objectives before selecting a deployment approach.

