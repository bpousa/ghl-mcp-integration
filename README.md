# GHL MCP Integration

This project implements a Model Context Protocol (MCP) server that integrates with Go High Level (GHL) to automatically generate and manage API keys for sub-accounts.

## Features

- Automated GHL login
- Sub-account API key generation
- Database storage of generated API keys
- MCP-compliant server implementation

## Setup

1. Clone the repository
2. Install dependencies: `npm install`
3. Copy `.env.example` to `.env` and fill in your credentials
4. Create the database using `src/database/schema.sql`
5. Start the server: `npm start`