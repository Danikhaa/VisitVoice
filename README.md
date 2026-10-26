# VisitVoice
<img width="1102" height="695" alt="VisitVoice Web App (1)" src="https://github.com/user-attachments/assets/c71273d4-a60c-4f26-add6-79d7a0346b4f" />
# VisitVoice

A voice-first health journal for older adults. Talk about how you feel, AI organizes the note, you approve it, and it's saved. Before a doctor visit, it builds a report of your symptoms, patterns, and questions.

**Live demo:** https://visitvoice.vercel.app

> Not a medical device. It does not diagnose or give medical advice.

# Flowchart Architecture
<img width="1024" height="577" alt="1792999873022-1259ca4a-be3a-4d34-9f95-ce262856ac4a1_1" src="https://github.com/user-attachments/assets/114c43fa-e5bf-43f5-8ff6-6356c5badc53" />

**Built with:** HTML, CSS, vanilla JavaScript, Web Speech API, Node.js serverless function (Vercel), Claude API, localStorage, jsPDF

**Run it:** `npx vercel`, add `ANTHROPIC_API_KEY` with `npx vercel env add ANTHROPIC_API_KEY`, then `npx vercel --prod`.

**Limits:** notes stay in your browser, but the text you speak is sent to Claude to be organized. The urgent-phrase warning only matches certain phrases and doesn't call 911.



Built with assistance from Claude (Anthropic). License: MIT.
