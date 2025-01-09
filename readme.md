# Online Collaborative Text Editor

## Introduction
I have designed and implemented an online real-time collaborative text editor. This type of software enables multiple users on different machines to edit the same document simultaneously, similar to popular tools like Google Docs.

## Demo

https://github.com/user-attachments/assets/5ea69a1d-32ee-4533-a132-d8aaa3b0623a

## Features

### User Management
- **User Registration** and **Authentication**: Register and login to user accounts.

### Document Management
- **File Management**: Create, open, rename, and delete files.
- **Access Control**: Share documents with permissions (viewer or editor); ensure security with owner-only file deletion.
- **List Documents**: View owned and shared documents.

### Real-time Collaborative Editing
- **Support File Editing**: Edit document text with bold and italic formatting.
- **Support Concurrent Edits**: Enable multiple users to edit simultaneously; manage conflicts effectively.
- **Real-time Updates**: Track edits in real-time; see other users' cursors and active sessions.

## How to Run
1. Clone the repository using:
    ```sh
    git clone https://github.com/neeleshpandey/Online-Collaborative-Text-Editor.git
    ```
2. Redirect to the backend folder:
    ```sh
    cd Online-Collaborative-Text-Editor/backend
    ```
3. Build the `gradle.build` file:
    ```sh
    ./gradlew build
    ```
4. Run the Spring Boot app on localhost:
    ```sh
    ./gradlew bootRun
    ```
5. Redirect to the frontend folder:
    ```sh
    cd ../frontend
    ```
6. Install the dependencies:
    ```sh
    npm i
    ```
7. Run the development server:
    ```sh
    npm run dev
    ```
8. Open a web browser and go to the host link.
