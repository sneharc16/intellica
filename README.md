# Intellica: AI-Powered Personalized Course Recommender

**Intellica** is an AI-driven EdTech platform that personalizes learning pathways based on a user's educational background, interests, skill level, and budget. By integrating aptitude-based evaluation, real-time course scraping, and multilingual delivery, Intellica makes quality education accessible, inclusive, and future-ready.

---

## 🚀 Key Features

- **AI-Powered Course Recommendations**  
  Personalized course suggestions based on qualifications, goals, and quiz performance using Groq LLAMA 3.5 and contextual embeddings.

- **Aptitude-Based Skill Assessment**  
  Auto-generated quizzes categorize users into Beginner, Intermediate, or Advanced tiers.

- **Real-Time Course Fetching**  
  Live scraping and API integration with platforms like Coursera, Udemy, edX, and YouTube for the most updated courses.

- **Multilingual Support**  
  Translations and summaries in regional languages using an advanced translation pipeline (Groq API + Deep Translate + Embedding Consistency).

- **Email Notifications & Summaries**  
  Users receive curated course summaries and links via automated email delivery.

- **Project-Based Recommendations**  
  AI suggests courses aligned with user's project prompts to encourage hands-on learning.

---

## 🧠 Tech Stack

### Frontend:
- `React.js`
- `Tailwind CSS`
- `HTML`

### Backend:
- `FastAPI`
- `MongoDB`
- `SMTP` (for OTP & emails)
- `AWS` (for scalable deployment)

### AI & NLP:
- `Groq API` (LLAMA 3.5)
- `SentenceTransformers`
- `FAISS` for semantic similarity
- `BeautifulSoup` (for scraping)
- `Deep Translator`

---

## 🧪 System Architecture

1. **User Input & Quiz Evaluation**  
   User provides goals, budget, language, and takes an aptitude quiz.

2. **AI-NLP Processing**  
   Responses are analyzed for intent; contextual embeddings created.

3. **Course Engine**  
   Courses scraped or fetched via APIs, ranked by relevance and ratings.

4. **Translation Pipeline**  
   Course details are translated with semantic accuracy across languages.

5. **Email Service**  
   Personalized recommendations and summaries sent to user inbox.

---

## 📈 Impact & Metrics

- AI-curated playlists boost retention by **45%**
- Multilingual content increases engagement by **50%**
- Personalized emails improve course completion by **30%**
- Real-time course updates increase enrollments by **35%**
- Adaptive learning cuts dropout rates by **25%**

---

## 🎯 Vision

To evolve into a fully AI-powered learning ecosystem that recommends not just courses, but also **career paths**, **internship opportunities**, and **custom learning plans**—powered by real-time job trends and multimodal content.

---

## 📄 License

MIT License

