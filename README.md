Personal Portfolio Website

This is my personal portfolio website built as a single HTML file. I wanted something that felt minimal and fast without needing a whole React setup or deployment pipeline — just one file I can drop anywhere and it works.

What's in it

The site covers everything a recruiter or hiring manager would want to know — my projects, skills, internships, education, certifications, and contact details. Beyond the usual stuff, I added a few things that I think make it stand out:

Live ML demo — there's an interactive churn prediction model on the page where you can adjust sliders (contract type, tenure, charges, support tickets) and see the prediction update in real time. No backend, runs entirely in the browser.

EDA Playground — you can upload your own CSV or pick one of the sample datasets and get an instant exploratory data analysis: row/column counts, null values, data types, and AI-generated insights about the dataset. This is basically a stripped-down version of my major project DeepAnalyst running in the browser.

Model comparison charts — side by side comparison of my tuned Random Forest model against baseline models (Logistic Regression, Naive Bayes, Decision Tree) on the churn dataset, along with a confusion matrix and feature importance breakdown.

AI chat assistant — a chat widget that answers questions about my skills, availability, projects, and experience. It's keyword-based so it works without any API key or backend.

Neural network visualizer — an animated canvas showing data flowing through a network layer by layer. Mostly just looks cool but also illustrates how classification models work.

Skill orbit — technologies orbiting around a center node at different speeds depending on how core they are to my work. Inner ring is Python, SQL, ML, GenAI. Outer rings are the ecosystem tools.

Terminal easter egg — press / anywhere on the page and a fake dev terminal opens showing a full model training run with accuracy metrics at the end. It's a small detail but people who find it seem to enjoy it.

Role switcher — four buttons in the hero section (AI Engineer, Data Scientist, Data Analyst, Software Engineer) that change the headline and description depending on which role a recruiter is hiring for.

Tech used

Everything is vanilla HTML, CSS, and JavaScript. No frameworks, no build tools. Chart.js is pulled in from CDN for the radar chart and training accuracy graph. Google Fonts for Space Grotesk, Inter, and JetBrains Mono. That's it.

Sections


Hero with particle canvas and animated stats
About
Skills with radar chart and animated progress bars
Experience (two internships)
Education (BCA from BGS Institute of Management, Bangalore University)
Impact numbers with animated ring charts
Model benchmarks and confusion matrix
Live EDA playground
Why hire me comparison table
Tech orbit animation
Neural network visualizer
Live ML churn predictor
Data dashboard charts
Projects (DeepAnalyst, Customer Churn Prediction, House Price Prediction, Sales Dashboard)
GitHub activity heatmap
Certifications
Blog (placeholder for future articles)
Contact form and links
AI chat assistant


Running it

There's nothing to install. Just open index.html in a browser and it works. If you want to host it, drag the file into Netlify Drop or Vercel and it'll be live in under a minute.

Customising

All the personal information — name, email, LinkedIn, GitHub handle, project descriptions — is hardcoded in the HTML. Search for yashwanthcp to find the places you'd need to update if you're forking this for yourself.

The AI chat KB (knowledge base) is a JavaScript array near the bottom of the script tag. You can add or edit entries there to change what the assistant knows about you.

Projects featured

DeepAnalyst — my BCA final year project. An autonomous AI data analyst built with Python, Streamlit, Google Gemini API, and Ollama. You upload a CSV and it generates EDA, visualizations, answers questions about the data in natural language, and exports PDF reports. Built with Keerthan R S under the guidance of Ms. Drithi V at BGS Institute.

Customer Churn Prediction — classification model on the IBM Telco dataset. Used Random Forest with SMOTE balancing and GridSearchCV tuning. Final accuracy was 93.4% with an AUC-ROC of 0.968.

House Price Prediction — regression model predicting property prices using location, area, and amenity features. R² score of 0.88 on the test set.

Sales Dashboard — Power BI dashboard tracking KPIs, regional performance, and revenue trends. Built with DAX measures and connected to an Excel source.

Contact

yashwanthcp1411@gmail.com

linkedin.com/in/yashwanthcp

github.com/YashwanthCP14
