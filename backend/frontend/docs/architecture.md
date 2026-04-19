# AI Resume Matcher - Architecture

## Overview
This project is an AI-powered system that analyzes resumes and job descriptions to calculate a match score.

## Architecture

Frontend (HTML/JS UI)
   ↓
Backend API (Node.js + Express)
   ↓
Matching Engine (Keyword-based, extendable to AI)

## Workflow

1. User inputs resume and job description
2. Frontend sends request to backend API
3. Backend processes text and calculates match score
4. Result returned and displayed to user

## Future Enhancements

- AI-based semantic matching using LLMs
- Resume improvement suggestions
- Integration with Claude API
- Job scraping and recommendations
