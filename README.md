# ResuMeme - AI-Powered Resume Analyzer

ResuMeme is an AI-powered resume analysis tool that evaluates resumes for ATS (Applicant Tracking System) compatibility, identifies strengths and weaknesses, checks for grammatical mistakes, and—if the user permits—delivers a humorous roast of the resume.

## Features

- **Resume Parsing:** Extracts text from uploaded PDF resumes.
- **ATS Score Evaluation:** Analyzes resume structure for ATS optimization.
- **Content Review:** Highlights key strengths and areas for improvement.
- **Grammar and Spelling Check:** Detects grammatical errors and suggests improvements.
- **Humorous Resume Roast:** Provides a lighthearted and brutally honest critique of the resume.
- **Drag & Drop File Upload:** Allows users to easily upload resumes for analysis.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend API:** OpenAI-compatible API endpoint
- **Libraries:**
  - [pdf.js](https://mozilla.github.io/pdf.js/) - For parsing and extracting text from PDFs
  - Google Fonts - "Bebas Neue" and "Space Mono" for modern typography

## Installation & Setup

### Prerequisites
Ensure you have a modern web browser that supports JavaScript.

### Running the Project Locally
1. Clone the repository:
   ```sh
    git clone https://github.com/adithyapaib/resuMeme
   ```
2. Navigate to the project directory:
   ```sh
   cd resumeme
   ```
3. Open `index.html` in your web browser.

### Deployment
Since this is a frontend-only project, you can deploy it easily on GitHub Pages, Netlify, or Vercel.

## Usage
1. Open the ResuMeme web page.
2. Drag and drop a resume PDF into the upload area or select a file manually.
3. The AI will analyze the resume, extract text, and evaluate it.
4. Receive feedback, including ATS optimization suggestions and a humorous roast if enabled.

## API Integration
ResuMeme sends resume data to an API for analysis:
- **Endpoint:** ``
- **Model Used:** `o3-mini`
- **Response Format:** JSON

## Roadmap
- [ ] Improve ATS scoring algorithm.
- [ ] Add support for DOCX files.
- [ ] Enhance UI/UX for better usability.
- [ ] Allow customization of the resume roast level (mild, medium, savage).

## Contributing
Pull requests are welcome! Feel free to fork the repository and submit improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, reach out to `your-email@example.com` or open an issue on GitHub.

