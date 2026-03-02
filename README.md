# Capstone-Step-Two
Accessibility 
Capstone Step 2 – Project Proposal

AccessAbility is a full-stack web application designed to centralize accessibility tools and resources for individuals who are deaf, blind, or visually impaired. Right now, helpful tools exist — but they’re scattered across the internet. This project aims to bring them into one organized, searchable, and user-friendly platform.

This capstone combines technical growth with meaningful impact. Accessibility isn’t an add-on here — it’s the foundation.

⸻

Tech Stack

Frontend
	•	React
	•	Responsive CSS (Tailwind or custom styling)
	•	Axios

Backend
	•	Node.js
	•	Express
	•	RESTful API
	•	JWT Authentication

Database
	•	PostgreSQL

Hosting
	•	Frontend: Vercel or Netlify
	•	Backend: Render or Heroku
	•	Database: Supabase or Railway

⸻

Focus

This will be an evenly focused full-stack application.

I want to challenge myself on both frontend usability and backend architecture. The goal is to build something that feels complete — not just visually polished, but structurally sound and secure.

⸻

Type

Responsive web application accessible across desktop, tablet, and mobile browsers.

⸻

Goal

The goal of AccessAbility is to create a centralized platform where users can:
	•	Discover accessibility tools
	•	Filter by support type (visual, auditory, mobility, communication)
	•	Read and leave reviews
	•	Save tools to a personal dashboard

The broader goal is to reduce the friction people face when searching for accessibility support.

⸻

Users

Primary Users
	•	Adults who are deaf or hard of hearing
	•	Adults who are blind or visually impaired

Secondary Users
	•	Caregivers
	•	Educators
	•	Social workers
	•	Family members

Usability and clarity will be a priority due to the nature of the audience.

⸻

Data

The app will store:
	•	Accessibility tools (apps, devices, services)
	•	Categories
	•	User accounts
	•	Reviews and ratings
	•	Saved/favorited tools

Each tool will include:
	•	Name
	•	Description
	•	Website link
	•	Category
	•	Price info (if applicable)
	•	Average rating

I will initially seed my own curated dataset to ensure quality and consistency. If a reliable API is available, I may integrate it later.

⸻

Database Structure (Initial Plan)

Users
	•	id
	•	username
	•	email
	•	password (hashed)
	•	role

Tools
	•	id
	•	name
	•	description
	•	category_id
	•	website_url
	•	price_type

Categories
	•	id
	•	name
	•	description

Reviews
	•	id
	•	user_id
	•	tool_id
	•	rating
	•	comment

SavedTools
	•	id
	•	user_id
	•	tool_id

⸻

Core Functionality
	•	User sign up and login
	•	Browse and filter tools
	•	Tool detail pages
	•	Leave reviews
	•	Save tools to dashboard
	•	Responsive design

⸻

Security
	•	Password hashing with bcrypt
	•	JWT authentication
	•	Protected routes
	•	Environment variables for secrets

No medical or highly sensitive data will be stored.

⸻

Stretch Goals
	•	Personalized recommendations
	•	Admin dashboard
	•	High-contrast mode toggle
	•	“Daily Accessibility Tip” feature
	•	Community discussion feature


I chose this project because it feels meaningful. I want my capstone to demonstrate technical growth, but also intentional design. Accessibility isn’t just a feature — it’s the foundation of this idea.
