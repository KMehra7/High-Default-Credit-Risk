# High-Default-Credit-Risk
Applied Machine Learning Final Project 

# Abstract

The problem that has been provided is the Home Credit Default Risk. In this problem, the machine learning team is looking to create algorithms and pipelines that will predict which individual will have successful repayment on their loan without a traditional credit score. In this phase of the project, we have previously visualized, understood, and explored these data as well as running baseline algorithms. Here we have employed feature engineering, hyperparameter tuning, and a pipleline process to try to improve our score. After our experiments, we have found that the best preforming model is the Random Forest Pipeline with our tuned hyperparameters of max_depth = 10, max_features = "sqrt", n_estimators = 100. We saw that our scores were nearly the same as our Baseline model scores albeit lesser than them. This is because we were only running our pipelines for a subset of data which consists of the top 44 highly correlated features. We have a score of 0.71322 (private) and 0.71845 (public) for our Kaggle submission this time using RandomForest model. In this phase we improved the accuracy of our model the first neural network architecture had an accuracy of 73.55% and the second neural network architecture had an accuracy of 73.82% with binary cross entropy as loss function.


As part of this project the following tasks were done:

---------------
### *Phase 1*
<table>
  <tr>
   <td>Task
   </td>
   <td>Task Description
   </td>
   <td>Assigned Member
   </td>
   <td>Estimated Hours
   </td>
   <td>Actual Hours
   </td>
   <td>Start Date
   </td>
   <td>Completion Date
   </td>
  </tr>
  <tr>
   <td>Format Project Proposal
   </td>
   <td>Communicate to find group members’ desired tasks, write the abstract, and collect and display Team Photos.
<p>

   </td>
   <td>William Cutchin
   </td>
   <td>5
   </td>
   <td>5.5
   </td>
   <td>28/3/2023
   </td>
   <td>4/4/2023
   </td>
  </tr>
  <tr>
   <td>Data Description
   </td>
   <td>Create table figures of data sources with descriptions
   </td>
   <td>Krisha Mehta
   </td>
   <td>1
   </td>
   <td>1
   </td>
   <td>29/3/2023
   </td>
   <td>4/4/2023
   </td>
  </tr>
  <tr>
   <td>Machine Algorithms and Metrics
   </td>
   <td>Research and select appropriate  metrics and algorithms for the datasets.
   </td>
   <td>Group
   </td>
   <td>1.5
   </td>
   <td>2
   </td>
   <td>04/03/2023
   </td>
   <td>04/04/2023
   </td>
  </tr>
  <tr>
   <td>Machine Learning Pipeline (Diagram)
   </td>
   <td>Construct a block diagram which visualizes the suggested pipeline steps.
   </td>
   <td>Kalyani Malokar
   </td>
   <td>1.5
   </td>
   <td>2
   </td>
   <td>03/31/2023
   </td>
   <td>04/03/2023
   </td>
  </tr>
  <tr>
   <td>Gantt Chart of Tasks
   </td>
   <td>Construct a Gantt chart which displays the waterfall of tasks and their dependencies.
   </td>
   <td>Kalyani Malokar
   </td>
   <td>1
   </td>
   <td>1
   </td>
   <td>04/04/2023
   </td>
   <td>04/04/2023
   </td>
  </tr>
  <tr>
   <td>Machine Learning Pipeline Steps & Descriptions
   </td>
   <td>Describe and reason through the steps the pipeline will take.
   </td>
   <td>Kunal Mehra
   </td>
   <td>2
   </td>
   <td>2
   </td>
   <td>03/28/2023
   </td>
   <td>03/30/2023
   </td>
  </tr>
  <tr>
   <td>Additional Algorithms (Loss Functions) 
   </td>
   <td>Select reasonable loss functions, describe them, and display their formula
   </td>
   <td>Kunal Mehra
   </td>
   <td>0.5
   </td>
   <td>0.5
   </td>
   <td>03/31/2023
   </td>
   <td>04/04/2023
   </td>
  </tr>
</table>

---------------
### *Phase 2*

<table>
  <tr>
   <td>Task
   </td>
   <td>Task Description
   </td>
   <td>Assigned Member
   </td>
   <td>Estimated Hours
   </td>
   <td>Actual Hours
   </td>
   <td>Start Date
   </td>
   <td>Completion Date
   </td>
  </tr>
  <tr>
   <td>Data Retrieval & Preprocessing
   </td>
   <td>Retrieve data from the Kaggle API and begin loading the data and pre-processing.
   </td>
   <td>Krisha Mehta
   </td>
   <td>3
   </td>
   <td>4
   </td>
   <td>04/04/2023
   </td>
   <td>04/05/2023
   </td>
  </tr>
  <tr>
   <td>Feature Engineering (Round 1)
   </td>
   <td>Develop and deploy initial feature engineering, applying statistical techniques and log experiments.
<p>

   </td>
   <td>Kalyani Malokar
   </td>
   <td>6
   </td>
   <td>5.5
   </td>
   <td>04/05/2023
   </td>
   <td>04/06/2023
   </td>
  </tr>
  <tr>
   <td>Machine Pipelines & Baseline Experimentation
<p>

   </td>
   <td>Test ranges of parameters for the given features, record experiment results and optimize.
   </td>
   <td>Kunal Mehra
   </td>
   <td>6
   </td>
   <td>5.5
   </td>
   <td>04/05/2023
   </td>
   <td>04/07/2023
   </td>
  </tr>
  <tr>
   <td>Exploratory Data Analysis & Visual Analysis
   </td>
   <td>Handle missing values, perform descriptive analysis, and identify correlations.
   </td>
   <td>William Cutchin
   </td>
   <td>4.5
   </td>
   <td>6
   </td>
   <td>04/07/2023
   </td>
   <td>04/11/2023
   </td>
  </tr>
  <tr>
   <td>Video Presentation
   </td>
   <td>Summarize the project, describe work completed, layout plans for the future, and discuss blockers.
   </td>
   <td>William Cutchin
   </td>
   <td>2
   </td>
   <td>4
   </td>
   <td>04/10/2023
   </td>
   <td>04/11/2023
   </td>
  </tr>
</table>

---------------
### *Phase 3*

<table>
  <tr>
   <td>Task
   </td>
   <td>Task Description
   </td>
   <td>Assigned Member
   </td>
   <td>Estimated Hours
   </td>
   <td>Actual Hours
   </td>
   <td>Start Date
   </td>
   <td>Completion Date
   </td>
  </tr>
  <tr>
   <td>Feature Selection
   </td>
   <td>Observe and compare results from Feature engineering and decide which features are worth exploring further.
   </td>
   <td>Kalyani Malokar
   </td>
   <td>7
   </td>
   <td>8
   </td>
   <td>04/11/2023
   </td>
   <td>04/12/2023
   </td>
  </tr>
  <tr>
   <td>Hyper Parameter Tuning (Round 2)
<p>

   </td>
   <td>Test ranges of parameters for the given features that have been selected by the feature selection step.
   </td>
   <td>Kunal Mehra
   </td>
   <td>6
   </td>
   <td>5.5
   </td>
   <td>04/13/2023
   </td>
   <td>04/14/2023
   </td>
  </tr>
  <tr>
   <td>Feature Engineering (Round 2)
   </td>
   <td>Develop and deploy feature engineering on new selected features, log experiments and explore adding or removing features. Log these experiments.
   </td>
   <td>William Cutchin
   </td>
   <td>5
   </td>
   <td>9
   </td>
   <td>04/14/2023
   </td>
   <td>04/17/2023
   </td>
  </tr>
  <tr>
   <td>Ensemble Methods
   </td>
   <td>Combine the multiple models or pipelines used into a single process. Log the results and compare.
   </td>
   <td>Krisha Mehta
   </td>
   <td>3.5
   </td>
   <td>4
   </td>
   <td>04/14/2023
   </td>
   <td>04/18/2023
   </td>
  </tr>
  <tr>
   <td>Video Presentation
   </td>
   <td>Summarize the project, describe work completed, layout plans for the future, and discuss blockers.
   </td>
   <td>Krisha Mehta
   </td>
   <td>2
   </td>
   <td>3
   </td>
   <td>04/14/2023
   </td>
   <td>04/18/2023
   </td>
  </tr>
</table>

---------------
### *Phase 4*

<table>
  <tr>
   <td>Task
   </td>
   <td>Task Description
   </td>
   <td>Assigned Member
   </td>
   <td>Estimated Hours
   </td>
   <td>Actual Hours
   </td>
   <td>Start Date
   </td>
   <td>Completion Date
   </td>
  </tr>
  <tr>
   <td>Neural Network Implementation
   </td>
   <td>Develop and deploy an effective neural network, given the reasonings of previous ML algorithms. Test and log all experiments.
   </td>
   <td>Kunal Mehra
   </td>
   <td>8
   </td>
   <td>12
   </td>
   <td>04/18/2023
   </td>
   <td>04/20/2023
   </td>
  </tr>
  <tr>
   <td>Advanced Model Architectures
   </td>
   <td>Combine and understand previous models to construct an effective and advanced model.
   </td>
   <td>Krisha Mehta
   </td>
   <td>4.5
   </td>
   <td>6
   </td>
   <td>04/21/2023
   </td>
   <td>04/25/2023
   </td>
  </tr>
  <tr>
   <td>Advanced Loss & Additional Functions
   </td>
   <td>Continue to iterate and experiment with loss functions, optimizing further the model’s performance.
   </td>
   <td>Kalyani Malokar
   </td>
   <td>4
   </td>
   <td>6
   </td>
   <td>04/21/2023
   </td>
   <td>04/25/2023
   </td>
  </tr>
  <tr>
   <td>Final Report Formatting
   </td>
   <td>Accumulate all information and insight to be formatted into an attractive and logical report.
   </td>
   <td>William Cutchin
   </td>
   <td>8
   </td>
   <td>12
   </td>
   <td>04/18/2023
   </td>
   <td>04/25/2023
   </td>
  </tr>
  <tr>
   <td>Video Presentation
   </td>
   <td>Summarize the project, describe work completed, report our successes and process, and describe how we could build on our submission.
   </td>
   <td>William Cutchin
   </td>
   <td>3
   </td>
   <td>5
   </td>
   <td>04/21/2023
   </td>
   <td>04/25/2023
   </td>
  </tr>
  <tr>
   <td>Final Report
   </td>
   <td>Compile and discuss all progress, development, visualizations, and findings to present to peers with great efficiency.
   </td>
   <td>All Members
   </td>
   <td>25
   </td>
   <td>30
   </td>
   <td>04/24/2023
   </td>
   <td>04/25/2023
   </td>
  </tr>
</table>
