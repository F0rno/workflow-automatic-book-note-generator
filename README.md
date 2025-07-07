# 📝 Note Processor Workflow

Process your notes efficiently using **Gemini 2.0 Flash** in a streamlined Dockerized workflow.

## 🚀 Quick Start

Follow these steps to get up and running:

### 1. Start the Docker Environment

Launch the environment with:

```bash
docker-compose up -d
```

---

### 2. Open the Web Interface

Access the interface in your browser to manage workflows.

---

### 3. Import the Workflow File

Use the interface to import the prebuilt workflow file included in this repository.

---

### 4. Create an API Key for Gemini 2.0 Flash

Generate an API key from:

👉 [https://aistudio.google.com/apikey](https://aistudio.google.com/apikey)

Make sure to select **gemini-2.0-flash** as the model.

---

### 5. Add Your Gemini Credentials

In the Gemini nodes of the imported workflow:

* Open the node settings
* Paste your API key into the **credentials** section

---

### 6. Add Your Input Notes

Place your notes in the following path in your computer:

```
data/input
```

---

### 7. Run the Workflow

Execute the workflow through the web interface.

---

### 8. Retrieve Your Results

Find your processed notes in:

```
data/output
```

Enjoy