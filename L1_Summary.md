# L1_Summary.md – Architecture Summary

## 🔧 Stack Used
- React + TypeScript
- Vite bundler
- Axios for API
- CSS/Styled Components

## 🔍 Folder Structure
- `/src/components/ChatWindow.tsx`: Main chat UI
- `/src/App.tsx`: Initializes chat and loads components
- `/src/api`: Makes HTTP requests to the backend agent

## 🔁 Chat Flow
1. User types message in input
2. Message sent to backend via Axios
3. Backend responds with agent reply
4. UI updates and displays response

## 🌐 API Interaction
- Axios is used
- Endpoint: `POST /api/agent/message` (example)