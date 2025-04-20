# SpringAI

This project uses the Spring AI integration for OpenAI. To run the application, you need to provide an OpenAI API key 
as an environment variable.

## Add Your API Key in IntelliJ:
1. Open **IntelliJ** and go to `Run > Edit Configurations...`
2. Select your run configuration (e.g., `SpringAiApplication`)
3. Find the **Environment Variables** section and click `...`
4. Add the following key-value pair:
    - **Name:** `OPENAI_API_KEY`
    - **Value:** `your-openai-key-here`
5. Click **OK**, then **Apply**, and run the app.

## application.properties

Make sure your `application.properties` file contains:

```properties
spring.ai.openai.api-key=${OPENAI_API_KEY}