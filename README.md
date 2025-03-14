# Smart India Hackathon Workshop
# Date:14.03.2025
## Register Number:212224040295
## Name:SanthoshKumar.P
## Problem Title
Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
1.Expert-Candidate Interaction Simulation:

The solution should simulate a realistic interview environment, where experts can ask questions and candidates can respond just like in a real-life scenario.
This could involve a video conferencing platform or a text-based interview interface that mimics an interview boardroom setup.
2.Question Relevancy Scoring:

The system would analyze the area of expertise of the candidate and generate relevant questions accordingly.
The proposed solution could utilize Natural Language Processing (NLP) to identify the topic areas and relevance of each question to the applicant’s profile (e.g., education, experience, specialization).
Similarly, each question’s relevancy should be scored for accuracy, ensuring the question is aligned with the candidate's domain of expertise.
3.Candidate Response Evaluation:

Candidate responses should also be scored for relevance and depth with respect to the question asked.
An AI-powered system can evaluate the response based on a predefined rubric (e.g., key concepts, completeness, logical structure, and domain-specific knowledge).
Speech-to-Text (for verbal responses) and Sentiment Analysis can be used to capture the tone, clarity, and professionalism of the response.
Optionally, candidates’ responses could be analyzed for confidence and engagement, offering a more nuanced evaluation beyond just the factual correctness of their answers.
4.Scoring System:

The system should generate an overall score based on the relevancy of the question asked, the relevance of the candidate's response, and other factors like clarity, confidence, and depth.
The scoring could be represented as a final suitability score for the candidate based on the knowledge in their domain, the ability to answer in-depth technical questions, and their potential fit for the role.
5.Feedback and Recommendations:

After the interview, candidates could be provided with automated feedback based on their performance. This feedback can highlight the areas of improvement and the areas where they performed well.
Experts can also receive a feedback report based on the quality and relevance of the questions they asked, ensuring continuous improvement in the interview process.


## Proposed Solution / Architecture Diagram
![image](https://github.com/user-attachments/assets/f90c0849-0dd2-4817-8997-2e9c247135cd)


## Use Cases
![image](https://github.com/user-attachments/assets/a9b5d19b-5e10-4236-b6c9-652cc369a96e)


## Technology Stack
Web Application: A user-friendly interface where candidates and experts can interact, take part in interviews, and view feedback.

React.js or Angular for building responsive, interactive web interfaces.
HTML5/CSS3 for structure and styling.
Bootstrap or Material-UI for component libraries to ensure a polished, modern UI.
Mobile Application (Optional): For candidates and experts who prefer to participate via mobile devices.

Flutter (for cross-platform mobile development) or React Native.
Video/Voice Integration: For the boardroom simulation experience.

WebRTC: For real-time video and audio communication.


## Dependencies
 The system needs to ensure that user profiles are correctly created and managed, and relevant interview data is tied to both the expert and candidate profiles.
Frontend: React forms for candidate and expert profile creation.
Backend: Databases (PostgreSQL or MongoDB) store and manage user data securely.
