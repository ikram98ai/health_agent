# Project Setup Instructions

Follow these steps to set up and start the project:

## Prerequisites

- Node.js (v14 or higher)
- Docker

## Steps

1. **Clone the repository:**
    ```bash
    git clone https://github.com/ikram98ai/healthjay_agent.git
    cd healthjay_agent
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Create the `.env` file:**
    ```bash
    cp .env.example .env
    ```

4. **Install and run Qdrant using Docker:**
    ```bash
    docker pull qdrant/qdrant
    docker run -p 6333:6333 qdrant/qdrant
    ```

5. **Start the project:**
    ```bash
    npm run start
    ```

You should now have the project running locally.