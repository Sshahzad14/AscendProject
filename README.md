# Team Ascend - Create your path, find your journey!

<p align="center">
    <img src='./images/ascend_logo.JPG'>
</p>

Ascend is a two-part solution which consists of a website and a dashboard aimed at attracting millennial clients and retaining beneficiaries. Ascend creates a seamless experience for both clients and financial advisors.

# Table of Contents

1. [Problem Description](#1-problem-description)
2. [Problem Analysis](#2-problem-analysis)
   - 2.1 [Problem Factors ](#21-problem-factors)
   - 2.2 [Main Questions](#22-main-questions)
3. [Solution Description](#3-solution-description)
4. [Business Considerations](#4-business-considerations)
5. [Technical Advisory Board - Questionnaire](#5-technical-advisory-board---questionnaire)
6. [Diagrams](#6-diagrams)
   - 6.1 [Architecture Diagram](#61-architecture-diagram)
   - 6.2 [Dashboard Data Flow](#62-dashboard-data-flow)
   - 6.3 [Prediction Model Data Flow](#63-prediction-model-data-flow)
   - 6.4 [Prediction Model with Einstein Analytics](#64-prediction-model-with-einstein-analytics)
   - 6.5 [Use-Case Diagrams](#65-use-case-diagrams)
   - 6.6 [User-Flow-Diagrams](#66-user-flow-diagrams)
        - 6.6.1 [Millennial Website](#661-millennial-website)
        - 6.6.2 [FA Dashboard](#662-fa-dashboard)
7. [Salesforce Einstein, Model Selection and Dataset Challenges](#7-salesforce-einstein,-model-selection,-and-dataset-challenges)
    - 7.1 [Salesforce Einstein](#71-salesforce-einstein)
    - 7.2 [Model Selection](#72-model-selection)
    - 7.3 [Dataset Challenges](#73-dataset-challenges)
8. [Project Timeline](#8-project-timeline)
9. [Roadblocks](#9-roadblocks)
10. [Future Roadmap](#10-future-roadmap)
    - 10.1 [Millennial Website](#101-millennial-website)
    - 10.2 [Financial Advisor Dashboard](#102-financial-advisor-dashboard)
11. [Authors](#11-authors)
12. [Acknowledgements](#12-acknowledgements)
    - 12.1 [Team Leads](#121-team-leads)
    - 12.2 [Executive Sponsors & Mentors](#122-executive-sponsors--mentors)
    - 12.3 [TAB](#123-tab)
    - 12.4 [Amplify Program Team](#124-amplify-program-team)
    - 12.5 [RBC WM Internship Program](#125-rbc-wm-internship-program)
    - 12.6 [RBC Employees and Vendors](#126-rbc-employees-and-vendors)
    - 12.7 [Other](#127-other)
13. [Logo Description](#13-logo-description)

# 1. Problem Description

**Original Problem Statement:**
We intend to have an Amplify team develop and execute a brand marketing campaign to introduce RBC Wealth Management to young investors. They will build services to connect Salesforce Marketing tools to multiple data sets within US Wealth Management in order to enable the marketing team to tailor the approach and content based on the client’s or prospect’s specific information.

**Revised Problem Statement:**
How might we help RBC attract new millennial clients and retain millennial beneficiaries?


# 2. Problem Analysis

## 2.1 Problem Factors
 * Currently, RBC is lacking platforms and tools that are geared towards young investors
 * Current applications are not easy for clients to use and are lacking a clean UI design
 * Currently, Financial Advisors (FA's) don't have enough education on investing topics trending among millennials
 * FA's can use more than 20 different applications to perform their daily tasks. This is time-consuming and affects productivity
 * FA's cannot initiate contact with a beneficiary directly without first getting the approval of the primary client

 ## 2.2 Main Questions
 * How are we marketing RBC to young investors?
 * How are we helping FA's attract new millennial clients and retain millennial beneficiaries?


# 3. Solution Description
Ascend is a combination of a millennial-facing website and a smart Salesforce dashboard for FA's.
It's predicted that within the next 25 years, we will see the largest wealth transfer in history as an estimated $68 trillion in assets are passed
down to the next generation. While millennials enjoy digital investing tools, they also want the reassurance that only a professional financial advisor can offer which creates a huge opportunity for RBC. Ascend is a two-part solution not only creates a personalized and unique experience for millennials but also provides FA’s with tools to connect with clients easily. Our Sales dashboard solution will help Financial
Advisors form connections with millennial beneficiaries and promote wealth management services, ensuring RBC can retain beneficiary clients during this wealth transfer. Additionally, our website is tailored towards millennials and will help attract young investors by providing them with personalized investing journeys tailored to their needs.

**Client-Facing Website**: The Ascend website targets millennial investors by using the Omnichannel
marketing technique. Omnichannel marketing refers to creating a brand's presence across multiple online and offline channels while ensuring seamless experience throughout the customer journey. Our website creates journeys for the different investing needs of millennials like
retirement planning, first-time investing, ESG investing, etc. RBC values putting their clients first, showing success
stories of current RBC millennial clients on our website demonstrates reliability and credibility. A big part our solution is being able to educate our users, after interviewing many millennials we realized that they don't know much about financial planning and why financial advisors could be extremely helpful in this journey. Ascend offers educational tools
through blogs, videos, and podcasts as well as a chat bot feature that allows users to quickly find answers to
frequently asked questions, making for a better UI experience and helping save FA time.

**Salesforce Dashboard**: The Ascend Salesforce dashboard helps financial advisors retain beneficiary clients by providing them
the predicted attrition rate of millennial beneficiaries along with their contact details. FA’s can use this information to
create experience-based events and Salesforce Marketing campaigns for clients and their beneficiaries
who are likely to leave the bank. Additionally, the dashboard provides data on potential leads from the Ascend
website who can become future RBC clients. FA’s can send Salesforce Marketing campaigns
directly from the dashboard to their clients and prospective clients. The Ascend dashboard also has an educational
area to help FA’s stay up-to-date with trending topics on millennial financial planning
and services.


# 4. Business Considerations
* Market Feasibility
    * Ensuring RBC stays successful with shifting customer demographics and demands
    * Staying competitive with an emerging market of individual investing tools

* Use of Existing Tools
    * Save training time by using familiar applications
    * Save cost by adapting existing tools

*  Longevity
    * Reusability and customization allows for a long-lasting, cost-saving solution
    * Using tools which will continue to be supported in the future

* Holistic Solution
    * Focus on internal and external solutions
    * Being mindful of the current business process and policies


# 5. Technical Advisory Board - Questionnaire

1. **Please describe the current proposed technology stack and any challenges in deciding on your tech stack.**
    * Salesforce with Tableau, Analytics Studio, and Einstein Discovery
    * Learning to build prediction models and dashboards using Salesforce with Tableau, Analytics Studio, and Einstein Discovery was challenging as this technology is new to the team.
    * Working within the bounds of these tools can be challenging. For instance, many features within the Salesforce website templates are 'locked', while starting a new Salesforce website from scratch can be time-consuming.

2. **What was the rationale used to select your tech stack?**
    * Salesforce is known as the world's #1 customer relationship management (CRM) platform, but it also offers powerful analytical tools and a quick time-to-market. Since being introduced to RBC a few years ago, Salesforce has become the FA's home desktop, streamlining tools and information into one easy-to-use solution. FA's are now familiar with the Salesforce platform, so very little time or training would be required to use this solution.

3. **What data sources will you need for your proposed solution and do you have access to those data sources?**
    * Data is available in Salesforce as 'Objects'. These objects can be used to create dataflows and datasets which are used to create the dashboard and prediction model.
    * We have access to QA 'test' data for creating our Salesforce FA dashboard.

4. **Please list the RBC teams you met with in order to research and influence your solution design.**
    * Financial Advisors and Branch Managers (Danielle Bryant, Andrew Leonard, Evan Malone, Brandon Fancher, Elise Morales, Natalie Miller)
    * Amplify Alumni mentors (Team Norman - Sarah Feroz, Min Luo, Sebastian Chavez)
    * Design and Tech mentors (Soojin Cha and Mackenzie Hung, Samiul Haque and Martin Mendoza)
    * Business Mentor (Ameel Baig)
    * TAB and Data Science Mentor (Diane Fenton)
    * Sponsors - RBC Wealth Management (Michael Palmer, Greg Beltzer)
    * Salesforce experts - (Eliza Brooks, Jamison Hull)
    * RBC WM Chief Administration Officer (Vikesh Nemani)
    * Tech Leads (Bill Wilson and Rohit Gupta)

5. **Please list any similar products or solutions discovered during your research phase.**
    * Amplify 2020 Team Norman - created prediction model for client attrition (not using Salesforce)
    * Amplify 2020 Team Wealthree - similar problem statement
    * Salesforce Client Attrition Modeling - started by Deloitte Salesforce team for RBC

6. **At the end of the term will your product be a demonstration application, a business tool, a data model, or other? Please describe your current understanding of the anticipated outcome.**
    * Our product will be a business tool which uses a data model. We plan to have a client-facing website and a FA-facing dashboard.

7. **Please describe which features are implemented and which features are not yet implemented from your full product scope**
    * Currently implemented:
        * Millennial client-facing website using high-fidelity prototype
        * Basic Salesforce FA dashboard

     * Future iterations:
        * Fully developed Salesforce website with customer journeys and educational areas
        * Fully developed Salesforce FA dashboard with finalized prediction model
## 6.1 Architecture Diagram
<p align="center">
    <img src='./images/architecture-diagram.PNG'>
</p>

## 6.2 Dashboard Data Flow
<p align="center">
    <img src='./images/dashboard-data-flow.JPG'>
</p>
The process for our Salesforce FA dashboard begins with gathering millennial data for the dashboard. In our case, the data is located
within Salesforce as an 'object' which is accessed via a ‘dataflow’ that we've created. The dataflow is used to create a dataset (a collection of data). The dataset is then passed through a
‘lens’ which is used to filter and visualize the data. The resulting information is displayed on the dashboard as a
chart or a report.

## 6.3 Prediction Model Data Flow
<p align="center">
    <img src='./images/prediction-model-data-flow.png'>
</p>
The process for our beneficiary attrition prediction model begins with gathering historical data.
In this case, data is located within Salesforce as an 'object' and is accessed via a 'dataflow' which is used to create a dataset.
We have used a 'Yes/No' indicator for the dependent variable 'Beneficiary Attrition'. Because this dependent variable is categorical (yes or no),
logistic regression can be used to determine which variables have a significant correlation with beneficiary attrition.
Einstein Analytics performs the model training within Salesforce using the dataset with the dependent variable. This is called creating a 'Story'.
Once the model is trained using the story, Einstein Analytics provides insights on the variables which have the strongest correlation with beneficiary attrition.
At this stage we are also able to view feedback on the accuracy of the model, allowing us to iterate and improve it.
Once the model is finalized, we are able to deploy it and use it within Salesforce by attaching an 'Einstein Discovery Prediction Field' to a Salesforce object.
This allows us to view predictions on the likelihood that a beneficiary will leave RBC after a wealth transfer occurs.

## 6.4 Prediction Model with Einstein Analytics
### Creating the Story
<p align="center">
    <img src='./images/einstein-insights.PNG'>
</p>
With Einstein Analytics we can easily create a 'Story' which provides insights on variables with a close correlation to our dependent variable.

### Assessing the Model
<p align="center">
    <img src='./images/einstein-model.PNG'>
</p>
Once the Story has been created, we can assess the accuracy of the model.

### Deploying the Model
<p align="center">
    <img src='./images/deploy-model.PNG'>
</p>
Once the model is finalized, we can deploy it and view predictions by attaching the model to a Salesforce object using an Einstein Discovery Prediction Field.

## 6.5 Use-Case Diagrams
<p align="center">
    <img src='./images/use-cases.png'>
</p>

## 6.6 User-Flow Diagrams
### 6.6.1 Millennial Website
<p align="center">
    <img src='./images/user-flow-website.png'>
</p>

### 6.6.2 FA Dashboard
<p align="center">
    <img src='./images/user-flow-dashboard.png'>
</p>

# 7. Salesforce Einstein, Model Selection, and Dataset Challenges

## 7.1 Salesforce Einstein
Salesforce Einstein is the game-changing AI software that analyzes and presents complex data that otherwise goes unused throughout the sales process. Salesforce Einstein shows how adding additional AI tools to the sales process can elevate the work of our financial advisors. Machine learning, natural language processing, and computer vision are all at the foundation of Einstein's features. In order to get a prediction attrition rate, we can use the Einstein Prediction Builder feature. There are several reasons why we decided to use Salesforce Einstein. First of all, it’s data-ready. We don’t have to do any data preparation or manage models, especially since our team was missing a data scientist. We simply had to use the data already located within Salesforce. Einstein is also production-ready. No devOps is needed since it is part of the Salesforce platform with model management and monitoring tools.

## 7.2 Model Selection
We made a comparison of the different models we had at our disposal in Einstein Analytics. We compared the Generalized Lineal Model (GLM), Random Forest and Gradient Boosting Machine (GBM). Our choice is based on the outcome of the comparison. GBMs are more accurate in predicting non-linear and interacting relationships and they also provide accurate results for each variables’ incremental impact.
Random forest can be used for both regression and classification tasks. A benefit to the random forests is that you do not have to specify aspects such as interactions and because of this, it may discover patterns in your data. However, RF doesn’t extrapolate. When using a Random Forest Regressor, the predicted values are never outside the training set values for the target variable. This behavior becomes problematic in situations where the training and prediction inputs differ in their range and/or distributions.
For GLMs, It’s well known that they are highly stable and transparent models. In th
