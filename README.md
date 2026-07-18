<div align="center">

<img src="https://capsule-render.com/api?type=waving&color=0:0EA5E9,50:7DD3FC,100:38BDF8&height=230&section=header&text=Hi,%20I%20am%20Fatima%20Sheraz&fontSize=36&fontColor=ffffff&animation=twinkling&fontAlignY=32&desc=AI%20|%20Deep%20Learning%20|%20Computer%20Vision&descAlignY=52&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=1000&color=7DD3FC&center=true&vCenter=true&width=650&lines=Artificial+Intelligence+Student;Deep+Learning+%26+Computer+Vision+Developer;Building+YOLOv8+%2B+OCR+Systems;Exploring+NLP+%26+Sentiment+Analysis;Turning+Research+into+Real+Products" alt="Typing SVG" />

![Profile Views](https://komarev.com/ghpvc/?username=fatimasheraz&color=7DD3FC&style=for-the-badge&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/fatimasheraz?label=FOLLOWERS&style=for-the-badge&color=0EA5E9&labelColor=0d1117)

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight&border=false" width="65%"/>

<br/>

<p align="center">
  <a href="#-who-i-am">Who I Am</a> •
  <a href="#-featured-projects">Projects</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-github-stats">Stats</a> •
  <a href="#-contribution-snake">Snake 🐍</a> •
  <a href="#-connect-with-me">Connect</a>
</p>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%" height="4px"/>

## 👩‍💻 Who I Am

```typescript
const fatimaSheraz = {
  title: "Artificial Intelligence Student & Deep Learning / Computer Vision Developer",
  university: "University of Faisalabad",
  stack: {
    languages: ["Python", "C++", "C"],
    aiAndMl: [
      "PyTorch", "TensorFlow", "Keras", "Scikit-learn",
      "YOLOv8", "OpenCV", "EasyOCR", "ONNX"
    ],
    backend: ["FastAPI", "Gradio"],
    databases: ["MySQL", "SQLite"],
    tools: ["Git", "GitHub", "VS Code", "Google Colab", "Jupyter Notebook", "Hugging Face"],
    integrations: ["Twilio"]
  },
  launchedProjects: [
    "Automatic Vehicle Gate Pass Generation System",
    "Explainable Ensemble Learning for Thyroid Cancer Classification",
    "Pakistan Sign Language Recognition",
    "YouTube Live Comment Sentiment Analysis"
  ],
  status: "Building deep learning & computer vision systems — from research notebooks to deployed apps",
};
```

<br/>

## 🚀 Featured Projects

### 🚗 Automatic Vehicle Gate Pass Generation System

An automated vehicle gate-pass and challan generation system that detects vehicles and license plates in real time using YOLOv8, extracts plate numbers with EasyOCR, and auto-generates official challan/gate-pass documents as PDFs with ReportLab. The system runs on a FastAPI + Gradio backend paired with a custom HTML/CSS/JS frontend, and is deployed live on Hugging Face Spaces — turning raw video or image input into a fully processed, downloadable gate pass in seconds.

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=fatimasheraz&repo=Automatic_Challan_Video_Image&hide_border=true&bg_color=0D1117&title_color=7DD3FC&icon_color=7DD3FC&text_color=C9D1D9)](https://github.com/fatimasheraz/Automatic_Challan_Video_Image)

<details>
<summary>📋 Tech breakdown</summary>
<br/>

| Layer | Technology |
|---|---|
| Detection | YOLOv8 |
| OCR | EasyOCR |
| Document Generation | ReportLab |
| Backend | FastAPI, Gradio |
| Frontend | HTML, CSS, JavaScript |
| Deployment | Hugging Face Spaces |

</details>

🔗 **Code:** [github.com/fatimasheraz/Automatic_Challan_Video_Image](https://github.com/fatimasheraz/Automatic_Challan_Video_Image)

<br/>

### 🩺 Explainable Ensemble Learning for Thyroid Cancer Classification

An explainable ensemble deep learning framework for thyroid cancer classification that combines ResNet-18, DenseNet-121, and EfficientNet-B0 through stacking to boost predictive performance. The pipeline uses early stopping to prevent overfitting, test-time augmentation (TTA) to stabilize inference, and Grad-CAM to visualize which regions of each scan drove the model's decision — making the ensemble's predictions interpretable rather than a black box. Built and trained end-to-end in Google Colab/Jupyter Notebook using PyTorch and the wider Python data-science stack.

<details>
<summary>📋 Tech breakdown</summary>
<br/>

| Layer | Technology |
|---|---|
| Models | ResNet-18, DenseNet-121, EfficientNet-B0 |
| Ensembling | Stacking |
| Explainability | Grad-CAM |
| Training Techniques | Early Stopping, Test-Time Augmentation (TTA) |
| Core Stack | PyTorch, Scikit-learn, NumPy, Pandas |
| Visualization | Matplotlib, Seaborn, Pillow |
| Environment | Google Colab / Jupyter Notebook |

</details>

### 🤟 Pakistan Sign Language Recognition

A computer vision system that recognizes Pakistan Sign Language gestures from images/video, built on a fine-tuned MobileNetV2 CNN and trained with heavy data augmentation for robustness. The model reaches **97% accuracy**, with test-time augmentation (TTA) used to further stabilize predictions and Grad-CAM used to visualize which hand regions the network focuses on for each sign. Callbacks like early stopping, model checkpointing, and learning-rate reduction on plateau keep training efficient and prevent overfitting.

<details>
<summary>📋 Tech breakdown</summary>
<br/>

| Layer | Technology |
|---|---|
| Model | MobileNetV2 (CNN, Transfer Learning) |
| Framework | TensorFlow, Keras |
| Explainability | Grad-CAM |
| Robustness | Test-Time Augmentation (TTA) |
| Training Callbacks | Early Stopping, Model Checkpoint, ReduceLROnPlateau |
| Evaluation | Scikit-learn (Classification Report, Confusion Matrix) |
| CV Utilities | OpenCV |
| Accuracy | 97% |

</details>

### 💬 YouTube Live Comment Sentiment Analysis

A natural language processing project that analyzes sentiment in real-time comments on live YouTube videos, classifying viewer reactions as positive, negative, or neutral as they come in.

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=fatimasheraz&repo=Sentiment-Analysis-of-live-Youtube-video-comments-&hide_border=true&bg_color=0D1117&title_color=7DD3FC&icon_color=7DD3FC&text_color=C9D1D9)](https://github.com/fatimasheraz/Sentiment-Analysis-of-live-Youtube-video-comments-)

<details>
<summary>📋 Tech breakdown</summary>
<br/>

| Layer | Technology |
|---|---|
| Language | Python |
| Task | NLP / Sentiment Classification |
| Data Source | Live YouTube Comments |

</details>

🔗 **Code:** [github.com/fatimasheraz/Sentiment-Analysis-of-live-Youtube-video-comments-](https://github.com/fatimasheraz/Sentiment-Analysis-of-live-Youtube-video-comments-)

<br/>

## 🛠️ Tech Stack

**Languages**

![Languages](https://skillicons.dev/icons?i=py,cpp,c&theme=dark)

**AI / ML / Databases**

![AI-ML-DB](https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv,mysql,sqlite&theme=dark)

**Backend & Dev Tools**

![Backend-Tools](https://skillicons.dev/icons?i=fastapi,git,github,vscode&theme=dark)

<details>
<summary>Tools without a dedicated icon</summary>
<br/>

Keras, YOLOv8, EasyOCR, ONNX, Gradio, Hugging Face, Google Colab/Jupyter, and Twilio — all listed in the stack object and project tables above.

</details>

<br/>

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=fatimasheraz&show_icons=true&hide_border=true&bg_color=30,0D1117,102A43&title_color=7DD3FC&icon_color=7DD3FC&text_color=C9D1D9&border_radius=12" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=fatimasheraz&layout=compact&hide_border=true&bg_color=30,0D1117,102A43&title_color=7DD3FC&text_color=C9D1D9&border_radius=12" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=fatimasheraz&hide_border=true&background=0D1117&ring=7DD3FC&fire=7DD3FC&currStreakLabel=7DD3FC&sideLabels=C9D1D9&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=8B949E&stroke=0D1117&border_radius=12" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=fatimasheraz&theme=dracula&no-frame=true&column=7&margin-w=8&margin-h=8" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=fatimasheraz&bg_color=0D1117&color=7DD3FC&line=7DD3FC&point=FFFFFF&area=true&area_color=0EA5E9&hide_border=true" />
</p>

<br/>

## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/fatimasheraz/fatimasheraz/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/fatimasheraz/fatimasheraz/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/fatimasheraz/fatimasheraz/output/github-contribution-grid-snake.svg" width="100%"/>
  </picture>
</p>

<details>
<summary>⚙️ One-time setup (required to activate this)</summary>
<br/>

This animation is generated by a GitHub Action, so it needs a one-time setup in your `fatimasheraz/fatimasheraz` repo:

1. Create a file at `.github/workflows/snake.yml` — I've packaged it for you as a separate download alongside this README.
2. Push it to your `main` branch (or run it manually from the **Actions** tab).
3. It creates an `output` branch with the animated SVGs and refreshes daily — the image above will then render automatically.

</details>

<br/>

## 🔗 Connect With Me

<p align="center">
  <a href="https://github.com/fatimasheraz">
    <img src="https://img.shields.io/badge/GitHub-fatimasheraz-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/fatima-sheraz-0bb4322a2/">
    <img src="https://img.shields.io/badge/LinkedIn-Fatima%20Sheraz-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:fsheraz265@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-fsheraz265%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<img src="https://capsule-render.com/api?type=waving&color=0:38BDF8,50:7DD3FC,100:0EA5E9&height=150&section=footer" width="100%"/>
