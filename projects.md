---
layout: default
title: Projects
permalink: /projects/
---

# Projects

<div class="project-section">
    <h2>Software Development</h2>
    <div class="project-card">
        <h3>E-commerce Shopcarts Microservice</h3>
        <p>Developed a Python-based E-commerce Shopcarts Microservice with Flask, Swagger API documentation, and Docker containerization, achieving 95% test coverage. Managed Kubernetes and OpenShift CD deployments within an Agile team environment to demonstrate CI/CD practices. <a href="https://github.com/JainiPriya/shopcarts" target="_blank">View on GitHub</a></p>
    </div>

    <div class="project-card">
        <h3>Driver Share App</h3>
        <p>Conceptualized a business model plan and an Android mobile application to help users share empty seats in owned private cars to carpool with friends, colleagues, and proximal registered users. Designed a 5-screen UI with functioning real-time maps using the OpenStreetMap API, developed with Java, Spring, MongoDB, and Git for version control.</p>
    </div>
</div>

<div class="project-section">
    <h2>Data Science/ML/Deep Learning</h2>
    <div class="project-card">
        <h3>Symptom Based Disease Prediction</h3>
        <p>Implemented PCA, SVM, Artificial Neural Network, Decision Tree, and Multinomial Naïve Bayes on a real-time dataset and achieved the highest accuracy of 95% using a decision tree model. Built a dynamic web application using the decision tree model to predict diseases based on symptoms and recommend nearby doctors of required specialization. <a href="https://github.com/JainiPriya/Disease-Prediction-System" target="_blank">View on GitHub</a></p>
    </div>
    <div class="project-card">
        <h3>Occupation-based Predictive Model for Cardiovascular Health Status</h3>
        <p>Analyzed National Health Interview Survey data from 2015 to 2021, encompassing a comprehensive study on the association between employment attributes and Cardiovascular Disease (CVD) risk. Implemented various ML models to predict CVD based on occupation and medical data, effectively addressing imbalanced classes through techniques like GANs, undersampling, and weighted loss, achieving a best accuracy of 93%. <a href="https://github.com/JainiPriya/Occupation-based-CVD-prediction" target="_blank">View on GitHub</a></p>
    </div>
    <div class="project-card">
        <h3>Video Prediction and Segmentation</h3>
        <p>Trained a frame prediction model on a dataset of 13,000 unlabelled videos to predict the 22nd frame from the first 11. Applied results to a semantic segmentation model trained on 1,000 labelled videos to obtain the result mask, leveraging Pytorch and UNet, and SimVP architectures. <a href="https://github.com/JainiPriya/Video-prediction" target="_blank">View on GitHub</a></p>
    </div>
    <div class="project-card">
        <h3>Air Quality Prediction</h3>
        <p>Built a Time Series based Machine Learning prediction model which can predict the quality of air and its constituents with 90% accuracy. Applied ARIMA and Prophet models to the cleaned dataset to devise an adaptive system to achieve maximum accuracy and prime variance.</p>
    </div>
    <div class="project-card">
        <h3>Analysis of Healthcare Access and Mental Health Disparities Using NHIS Data</h3>
        <p>Conducted data analysis on a 27,651-sample NHIS dataset to identify disparities in healthcare access and mental health, utilizing visualization tools like Python, matplotlib, and Tableau to reveal key demographic impacts. Developed predictive models using logistic regression, random forest, and SVM to classify mental health and healthcare access, providing actionable insights for policy intervention. <a href="https://github.com/JainiPriya/NHIS-data-analysis" target="_blank">View on GitHub</a></p>
    </div>
</div>

<style>
.project-section {
    margin-bottom: 2rem;
}

.project-card {
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 4px;
    padding: 1rem;
    margin-bottom: 1rem;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}

.project-card h3 {
    margin-top: 0;
}

.project-card p {
    font-size: 0.9rem;
    margin-bottom: 0.5rem;
    line-height: 1.5;
}

.project-card a {
    color: #007bff;
    text-decoration: none;
}

.project-card a:hover {
    text-decoration: underline;
}
</style>
