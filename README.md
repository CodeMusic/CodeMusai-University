## 🎓 Welcome to CodeMusai University: Your AI-Powered Learning Platform 🎓

<img src="https://github.com/CodeMusic/CodeMusai-University/blob/main/CodeMusaiUniversity.jpg?raw=true" alt="MusaiSearch">

### How It Works

CodeMusai University is designed to learn about you as you interact, tailoring a personalized course on any topic of your choosing. Utilizing advanced AI, it supports third-party integrations, a locally hosted LLM, or our custom **CodeMusaiGPT**.

Initially, CodeMusai University leverages OpenAI with **cmSoftCoding** as a gateway to the internet. As the platform evolves, CodeMusaiGPT will take the lead, enabling seamless integration with any compliant local LLM.

### 🧠 The Process:

1. **Query Input:** You ask a question or make a request.
2. **Web Scraping:** CodeMusai University scours Google for relevant information.
3. **Content Parsing:** Extracts text from the most relevant pages.
4. **Prompt Generation:** Combines your query with the extracted text.
5. **AI Response:** Calls the OpenAI API to generate a response.
6. **User Interaction:** Streams the answer directly to you.

### 🔧 Requirements

Before the next version, you’ll need an OpenAI API key. Get yours [here](https://openai.com/api/).

### 🛠 Running Locally

1. **Clone the Repository:**

```bash
git clone https://github.com/CodeMusic/MusaiSearch.git
```

2. **Install Dependencies:**

```bash
npm i
```

3. **Run the App:**

```bash
npm run dev
```

### 🚀 What’s Next? (Backlog)

- **Speed Optimization:** Replace link scraping with the Google Search API.
- **Follow-Up Searches:** Add functionality for continuous queries.
- **Prompt Enhancement:** Porting the dtourVariant of CodeMusai for a more personalized experience.
- **Integrate CodeMusaiGPT:** Fully port CodeMusaiGPT into the system.
- **Continuous Learning Module:** Improve the model’s ability to learn from you over time.
- **Lobotomy Mode:** Option to disable the continuous learning feature.

