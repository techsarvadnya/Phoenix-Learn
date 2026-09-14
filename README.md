# Phoenix-Learn
An AI-based learning platform for Math and Science using Gemini API and Harkness Method.
--------------------------------------------------------------------------------------------------

# 🚀 Phoenix Learn — Interactive Web Application

Phoenix Learn is a discussion-based learning platform built with Python and Streamlit, designed to foster deep algorithmic thinking using the Harkness methodology.

---

### Main Application Architecture (`app.py`)

* **Purpose:** Serves as the interactive web interface and state manager for Phoenix Learn.
* **Tech Stack:** Python, Streamlit, Session State Management.

#### Key Architectural Systems:
1. **Session State Memory (`st.session_state`):** Persists user progress, active pages, and selected subjects across dynamic UI reruns.
2. **Multi-Stage Navigation:** Routes users seamlessly from the landing page through subject selection to the dedicated workspace.
3. **Responsive Grid Layout:** Uses Streamlit column containers (`st.columns`) for a modern, clean UI presentation.
