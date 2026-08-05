# 🎥 Interactive Media Plan Generator for Online Learning

An interactive, web-based planning tool designed for higher education faculty professional development. This application guides instructors through structuring focused, chunked mini-lectures and instantly generates a downloadable PDF blueprint to streamline Phase 1/Phase 2 Instructional Design consultations.

---

## 🎯 Pedagogical Intent & Value

* **Scaffolded Planning:** Helps faculty transition from broad lecture ideas to structured, bite-sized mini-lectures (~5–8 minutes / ~500–800 words max).
* **Chunking & Focus:** Encourages instructors to limit content to 2–4 key talking points per video, supporting cognitive load management and student retention.
* **Consultation Artifact:** Generates an actionable, standardized PDF artifact that faculty can bring to pre-production and storyboarding kickoff meetings with Instructional Designers and Media Producers.

---

## 🛠️ Features & Technical Highlights

* **Real-Time Dynamic Preview:** Formats the media plan in real-time as faculty complete the form inputs.
* **Direct Client-Side PDF Generation:** Uses `jsPDF` to compile and directly download a clean, styled PDF (`Media_Plan_[FacultyName].pdf`) into the user's downloads folder with zero print dialog friction or browser dependency.
* **Institutional Branding:** Aligned with university palette standards (GW Navy `#033C5A` and GW Buff `#FDFBF7`).
* **Zero Backend Dependencies:** Fully client-side application running on pure HTML5, CSS3, and vanilla JavaScript.

---

## 🚀 GitHub Pages Deployment

1. Rename the main code file to `index.html` and place it in the root directory.
2. Go to **Repository Settings** $\rightarrow$ **Pages**.
3. Under **Source**, select **Deploy from a branch**.
4. Set the **Branch** to `main` (or `master`) and folder to `/ (root)`.
5. Save. Your live link will be available at: `https://<your-username>.github.io/<your-repo-name>/`

---

## 🧩 LMS Integration (Blackboard Ultra / Canvas)

To embed this interactive tool directly inside an LMS module or document page, paste the following iframe code:

```html
<iframe 
  src="https://<your-username>.github.io/<your-repo-name>/" 
  width="100%" 
  height="900px" 
  style="border: none; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);"
  title="Build Your Media Plan Interactive Tool">
</iframe>
