# Team Ascend - Create your path, find your journey!

<p align="center">
   <img width="262" alt="image" src="https://user-images.githubusercontent.com/35118157/132926443-abeb1e88-90b9-41ea-863e-b3b83c86c91d.png">
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
For GLMs, It’s well known that they are highly stable and transparent models. In the hands of “regression artists’’ at large insurance and financial institutions, they can also be highly accurate. That’s probably one of the reason why Einstein chooses GLM by default for its prediction models.
However, as the 'no free lunch' theorem states, there is no one best model - every situation is different. And in our situation, we judged that GLM was a better option as it includes Logistic Regression which is the best option when the outcome is binary (yes/no in our case). And we also know that GLM are best when you have only one linear predictor in the systematic component (attriteIndicator in our case). And last but not least, we can use the regression line to extrapolate and predict values that are far from training data.

## 7.3 Dataset Challenges
Missing values:
the dataset that was available to us was missing a couple of values. Our predictive analytics uses historical data to predict beneficiaries that are likely to attrite. Typically, historical data is used to build a mathematical model that captures important trends. That predictive model is then used on current data to predict what will happen next, or to suggest actions to take for optimal outcomes. However, our dataset was missing historical data. Some other important fields were also missing. For example, there wasn't a specific field that said a wealth transfer occurred between a client and their beneficiary. Getting that information would require digging into the data, one account at a time to check whether that wealth transfer happened. It’s worth mentioning that we were working in the QA environment for security reasons, but the same issues persisted in production.
Our dataset was also unbalanced. As stated earlier, we were trying to build our predictive model in the QA environment, which doesn’t have accurate data. In our dataset, some accounts had assets exceeding $99 trillion, or they had unreasonable number of beneficiaries. Our model would definitely have been skewed if that unbalanced data was used to build it.


# 8. Project Timeline
* June 1:  Begin problem research
* June 7:  Begin user interviews - millennials and FA's
* June 11: First Sponsor meeting
* June 14: Ideas pitched to team leads and mentors
* June 21: Low-fidelity prototyping
* June 25: Sponsor Update #1 - feedback on ideas and prototypes
* July 6:  High-fidelity prototyping
* July 12: Feedback from users
* July 19: Implementation and iteration
* July 30: Sponsor Update #2 - feedback on pitch and final solution
* Aug 5:   Technical submission finalized
* Aug 6:   Pitch, deck, demo video finalized


# 9. Roadblocks
Our team faced several challenges during the creation of our solution. The greatest challenge we faced was a lack of access to historical data due to security concerns and the current methods for storing and accessing data within Salesforce. Currently, RBC does not explicitly track wealth transfers within Salesforce. Instead, Account information is updated outside of Salesforce with no fields indicating whether a wealth transfer occurred. This made it challenging to identify past wealth transfers while gathering data for building our prediction model.

Another challenge we faced was a limited time frame. As a U.S. team our group worked within a shortened timeline, starting several weeks later than our competitors. This made it difficult to 'catch up' to the other teams during the project timeline.

Another roadblock for our team was learning new technology, specifically Salesforce with Tableau, Analytics Studio, and Einstein Analytics. These tools were all new to our team, but they're also new to RBC. Salesforce has only recently been implemented at RBC, so much of our research was done online or by working with vendors like Deloitte.

A final challenge for our team was creating a data-driven solution with no data scientists on our team. With three developers and one business analyst, we had a lot to learn about data science during the build phase. Online research and working with teams within RBC helped us overcome this challenge.


# 10. Future Roadmap
<p align="center">
    <img src='./images/roadmap.png'>
</p>

## 10.1 Millennial Website
The millennial website can be built on Salesforce using Experience Cloud Community. The Experience Cloud site is a beautifully branded digital experience connected to the Salesforce CRM. Since the site will live in our Salesforce org, FA’s can choose exactly how their clients access content.
To create the website:
* From Setup, enter 'Digital Experiences' in the Quick Find box
* Select 'Sites', and then click 'New Site'
* The creation wizard opens with several templates to choose from. We can select a template, learn more about the key features, or create our own
* Select 'Get Started'
* Enter the name for the website and the URL
* Lastly, select 'Create' to create the site in Preview state
* The site can then be customized, managed, and moderated

## 10.2 Financial Advisor Dashboard
Our current dashboard is in Beta version. After implementing the features listed below we will release our first version of the Salesforce FA Dashboard:
* Search by client name and account number
* Filter by total asset value
* Filter by status for leads and referrals
* Extending to have options for Gen-Z and other clientele
* Restrict access based on primary rep code - only show data for clients and referrals for the logged-in rep code
* Migrate data from the dashboard to Marketing Campaign Central
* Updating dataflow to include more information on leads, client and beneficiary relationships
* Updating dataflow to include beneficiary percentage and role (primary, secondary, contingent)
* Adding more widgets to visualize the data
* Adding task and event widgets
* Automating the process of adding tasks for beneficiaries
* Automating the process of adding educational material including trending topics




# 11. Authors
* Ritika Chowdhury - Business Analyst
* Hadia Gueye - Developer
* Sumaira Shahzad - Developer
* Jessica Adamec - Developer


# 12. Acknowledgements
A special thank you to everyone who supported us on our project journey!

## 12.1 Team Leads
* Bill Wilson
* Rohit Gupta

## 12.2 Executive Sponsors & Mentors
* Michael Palmer - Sponsor
* Greg Beltzer - Sponsor
* Sarah Feroz - Alumni Mentor
* Martin Mendoza - Tech Mentor
* Samiul Haque - Tech Mentor
* Soojin Cha - Design Mentor
* Mackenzie Hung - Design Mentor
* Ameel Baig - Business Mentor
* Neda Paryab - Data Science Mentor

## 12.3 TAB
* Hussain Subhani
* Duke Butler
* Diane Fenton - TAB and Data Science Mentor

## 12.4 Amplify Program Team
* Rachael Rishworth - Manager and Program Rep
* Alyssa Citrigno - Senior Manager
* Aaron Yem - Tech Director
* Arun Sampath - Communications Analyst
* Julia Rikic - Manager
* Catherine Monteith-Pistor - Community Manager
* Meagan Fillion - Senior Director
* Karen Irvine - Director
* Lauren Piccoli - Sr. Recruiter and Resume Expert
* Jamie Holman - Manager

## 12.5 RBC WM Internship Program
* Aaron Merwin
* Ruchir Jaipuriyar
* Courtney Johnston
* Jaehwa Flandermeyer

## 12.6 RBC Employees and Vendors
* Vikesh Nemani - Head, RBC U.S. Wealth Management Strategy
* Min Luo - Data scientist with Amplify 2020 - Team Norman
* Sebastian Chavez - BA with Amplify 2020 - Team Norman
* Eliza Brooks - Salesforce Expert
* Jamison Hull - Salesforce Data Expert
* Danielle Bryant - Sr. Technology Experience Consultant
* Andrew Leonard - Financial Advisor (FA)
* Evan Malone - FA
* Natalie Miller - FA
* Brandon Fancher - FA
* Elise Morales - Client Associate, Branch Service Manager
* Nhi Vuong - RBC (Front Office)
* Tiffany Alvear - RBC
* Ameera Ali- Intern at RBC WM (Marketing)
* Grace Abifarin - Intern at RBC WM (Clearing & Custody)

## 12.7 Other
* Sample readme from https://gist.github.com/PurpleBooth/109311bb0361f32d87a2


# 13 Logo Description
<p align="center">
    <img src='./images/millennials-logo.JPG'>
</p>
<p align="center">
    <img src='./images/fa-logo.JPG'>
</p>
<p align="center">
    <img src='./images/ascend_logo.JPG'>
</p>
Ascend helps millennials and financial advisors reach their highest potential. With Ascend, RBC is now ready to welcome this new generation. Our logo showcases how millennials and financial advisors can come together and change the future of wealth management. RBC is trying to build their brand awareness in the US and it has been an important factor in all our marketing campaigns. The Ascend logo uses blue and yellow, similar to the RBC logo to make sure we are reminding users about the bank and its services. The blue color is for millennials which signifies that they can trust RBC with their financial goals and the yellow for financial advisors is associated with clarity in helping millennials reach their highest potential.
