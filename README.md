# Medical-image-diagnosis-agent

This repository contains a Streamlit-based tool for analyzing medical images using AI-powered models. It provides detailed diagnostic insights of the uploaded medical images. It review the medical images such as X-rays, MRIs, CT scans, and more.


# **Key Features**

**AI Integration:** 
Utilizes the Llama Vision model (llama-3.2-90b-vision-preview) from Groq for advanced vision analysis.

**Radiological Expertise:** Provides detailed and structured radiological analysis, including:

Identification of imaging modality and anatomical region.

Detection of abnormalities with severity ratings.

Diagnostic assessment with confidence levels.

Patient-friendly explanation of findings.

Research-backed insights from medical literature.

**User-Friendly Interface:** A simple Streamlit application for uploading and analyzing images.

**Educational Disclaimer:** Clearly states that this tool is for educational purposes only and should not replace professional medical evaluations.



# **Technology Stack**

**Streamlit:** For creating an interactive web interface.

**Pillow (PIL):** For image processing.

**Python Libraries:**

**dotenv:** To manage environment variables.

**os:** For file handling.

**phidata:** For AI tools and integration.

# **Groq’s Llama Vision Model:**

**Model ID:** llama-3.2-90b-vision-preview

# **3. AI Tools:**

**Google Search:** 

For finding relevant research and literature.

**DuckDuckGo:**

For additional web-based information.

# **Groq API key:**
(You can get the Groq API Key from https://console.groq.com/keys ).

# **How It Works**

**Upload Image:**

The user uploads a medical image in formats like JPG, JPEG, PNG, or DICOM.

The uploaded image is displayed on the interface.

**Analyze Image:**

Clicking the "Analyze Image" button sends the image to the AI model for analysis.

The Groq’s Llama Vision model processes the image and returns:

Detailed radiological insights.

**Results:**

A structured analysis report is presented with markdown formatting.

The report includes modality identification, key findings, diagnoses, and references.

# **Installation**

'''bash
**Clone the repository:**
https://github.com/Ali-Zia3500/medical-image-diagnosis-agent

**Install dependencies:**

 pip install -r requirements.txt

**Set up the .env file:**

Create a .env file in the root directory.

Add your Groq API key:

GROQ_API_KEY = your_groq_api_key

**Run the application:**

streamlit run app.py

 
# **Disclaimer**

This tool is for educational purposes only. It is not intended for clinical use or as a substitute for professional medical advice. All analyses should be reviewed by qualified healthcare professionals.
