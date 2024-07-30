# Tab: Your Second Brain

## Overview
**Tab** is a wearable AI device acting as a personal assistant and life coach designed to manage and remember personal interactions and information. It records conversations, processes them with AI, and organizes the data into a structured database for easy recall and decision-making. It is also useful for individuals with ADHD, offering insights and proactive suggestions to enhance personal development and productivity.

## Technical Specifications

### Web App
- **Platform:** Web
- **Tech stack:** Next.js
- **Database:** Supabase (PostgreSQL)

### Hardware Device
- **Processor:** 1GHz, single-core CPU (Raspberry Pi Zero W)
- **RAM:** 512MB LPDDR2
- **Storage:** MicroSD card
- **Ports:** Mini HDMI, Micro USB OTG, Micro USB power, GPIO (40-pin header)

### Additional Hardware
- **UM790 Pro:**
  - AMD Ryzen 9 7940HS
  - AMD Radeon 780M
  - 32GB RAM
  - 512GB Storage

### Software
- **App Development:** Next.js
- **Backend Services:** Supabase (database, authentication, compute)
- **Deployment:** Docker
- **Programming Languages:** C++, TypeScript, PLpgSQL
- **AI Models:**
  - Mistral LLM
  - sentence-transformers/all-MiniLM-L6-v2
  - Whisper Large V3
  - OpenAI GPT-3.5

## Building Tab
![image](https://github.com/user-attachments/assets/bba703e2-4e91-4d9a-bbb9-e27e5edd0d3b)

### Software Development

#### Backend Setup
The backend leverages Supabase for database management, authentication, and compute functions. It processes audio recordings through serverless functions, including transcription and data storage. Additionally, it handles chat interactions and generates responses using AI models.

- **Supabase setup and deployment:** Refer to this guide: [Guide Link]
- **Functions:**
  - Process Audio: Handles audio uploads and transcription.
  - Chat Handler: Manages chat interactions and generates responses.
- **Utilities:**
  - Supabase client
  - CORS configuration
  - Error handling
  - Database Migrations: Schema definitions and modifications.

#### Web App Development
Enables user interaction with the personal assistant and access to conversation transcriptions and insights.

- **Setup and deployment:** Refer to this complete guide: [Guide Link]

### Hardware Development
Raspberry Pi Zero W with a microphone, power bank, and custom case for capturing and processing audio recordings.

#### Raspberry Pi Zero W Setup

**Components:**
- Raspberry Pi Zero W starter kit
- MicroSD card
- Microphone
- Power bank
- Soldering kit

**Assembly and Software Installation:** Refer to this complete guide: [Guide Link]

## Conclusion
Following these steps, Tab will be fully functional and ready for development, testing, and deployment. For more details and the complete process of development, please refer to this: [Complete Guide Link]

---


