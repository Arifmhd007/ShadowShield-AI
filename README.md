# ShadowShield-AI
ShadowShield AI is an AI-powered parametric insurance platform that protects gig workers from income loss caused by external disruptions like weather, pollution, and curfews by automatically detecting events and triggering instant payouts

ShadowShield AI

Income Protection for Gig Workers
Requirement, Persona & Workflow
The Requirement

Delivery partners working with platforms like Swiggy and Zomato depend on daily earnings to support their lives.

But their income is fragile.

A sudden rain, pollution spike, or curfew can reduce their working hours and lead to significant income loss.
Today, there is no system that protects them from this uncertainty.

We aim to build a system that automatically protects their income when such disruptions occur.

Persona-Based Scenario

Ravi – 26, Food Delivery Partner

Works daily to earn ~₹1200

No fixed salary, no safety net

One day, due to heavy rain:

He earns only ₹700

Loses ₹500

For Ravi, this loss directly affects his daily needs.

Our solution ensures Ravi doesn’t face this loss alone.

Workflow of the Application

Onboarding

Ravi signs up on the mobile app

Links his delivery platform

Shares basic details (location, past earnings)

AI Predicts Income

System estimates his expected earnings (“Shadow Income”)

Disruption Monitoring

System tracks weather, pollution, and local disruptions

Income Comparison

Compares expected vs actual earnings

Automatic Payout

If income drops due to disruption → payout is triggered

Money is sent instantly via UPI

No claims, no paperwork — everything is automatic

Weekly Premium Model, Parametric Triggers & Platform Choice
Weekly Premium Model

We follow a weekly pricing model because gig workers earn weekly.

Basic Plan: ₹30/week → Covers up to ₹500

Premium Plan: ₹80/week → Covers up to ₹2000

This makes it:

Affordable

Easy to manage

Aligned with their earning cycle

Parametric Triggers

Instead of manual claims, payouts are triggered automatically when conditions are met:

Heavy rainfall above threshold 

High AQI levels 

Curfews or strikes 

When:

A disruption is detected

AND income drops

The system automatically calculates and pays compensation

Platform Choice: Mobile App

We chose Mobile App because:

Gig workers primarily use smartphones

Enables real-time tracking (location, activity)

Instant notifications and payouts

Simple and accessible for daily use

AI/ML Integration Plan
Earnings Prediction

AI predicts expected income based on past data

Dynamic Premium Calculation

Weekly premium adjusts based on:

Risk level

Location

Historical disruptions

Fraud Detection

GPS verification (to ensure worker presence)

Activity validation

Duplicate claim detection

Cross-check with real-time disruption data

Ensures fairness and prevents misuse

Tech Stack & Development Plan
Tech Stack

Frontend: Flutter / React Native (Mobile App)

Backend: Node.js / FastAPI

Database: MongoDB

AI/ML: Python (Scikit-learn)

Integrations

Weather APIs

Traffic / disruption APIs (mock acceptable)

Payment via UPI (Razorpay test mode)

Development Plan

Phase 1:

Idea, workflow, and UI design

Phase 2:

User onboarding

Premium calculation

Automated claim system

Phase 3:

Fraud detection

Instant payout simulation

Analytics dashboard

Additional Highlights

Fully automated system (no claims required)

Focused only on income protection (as required)

Affordable for gig workers

Scalable across cities and platforms

This solution is built with one simple belief:

A worker who shows up every day should not lose income due to things beyond their control.

ShadowShield AI ensures stability, dignity, and financial protection for gig workers.
