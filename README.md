VED AI: A Personalized AI Companion
VED AI harnesses the power of advanced technologies like Large Language Models (LLM) and Retrieval-Augmented Generation (RAG) to learn from user-customized knowledge bases. It is designed to deliver contextually relevant answers across a broad spectrum of inquiries, ensuring rapid and precise information retrieval. This capability not only enhances user experience but also supports a more efficient knowledge management process.

This project unveils an intuitive web-based administration interface for VED AI, meticulously designed to empower administrators with full control over the service's configuration and content. This administrative platform serves as the central hub for managing the underlying knowledge base, user interactions, and analytical insights.

Through this web interface, administrators can effortlessly curate and update the knowledge base to ensure the information remains current and relevant. It allows for the easy monitoring of user queries and feedback, enabling continuous improvement of the service based on real-world use.

# Quick Start Guide

1. clone project

```shell
git clone https://github.com/open-kf/smart-qa-admin.git
```

2. install dependencies

```shell
cd smart-qa-admin
npm install
```

This step is crucial for directing your application to the correct server location, ensuring that all API requests are routed to the appropriate endpoint.

3. start the project

```shell
npm run dev
```

open the browser and visit `http://localhost:5277`

4. build the project

```shell
npm run build
```

This command triggers the build process defined in your `package.json`, resulting in a dist directory that contains the optimized version of your application ready for deployment.

5. deploy

You can deploy the built application to any hosting service that supports static file hosting, such as Vercel, Netlify, or GitHub Pages. Simply upload the contents of the dist directory to your chosen hosting provider, and your application will be live and accessible to users.
