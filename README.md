# Note Processor Workflow

This project allows you to run a workflow using Gemini 2.0 Flash to process your notes.

## 🚀 How to Use

1. **Start the Docker Compose environment**

```bash
docker-compose up -d
```

2. **Create a new workflow**

   Open the web interface and create a new workflow.

3. **Import the workflow from file**

   Use the interface to import the workflow file provided in this repository.

4. **Create an API key for Gemini 2.0 Flash**

   Visit [https://aistudio.google.com/apikey](https://aistudio.google.com/apikey) and create an API key for **gemini-2.0-flash**.

5. **Add your Gemini credentials to the workflow**

   In the Gemini nodes of the workflow, insert your API key in the credentials section.

6. **Insert your notes**

   Place your input notes in the `data/input` file in the container’s file system.

7. **Run the workflow**

   Execute the workflow from the interface.

8. **Get your results**

   Retrieve the output from the `data/output` file.

Enjoy