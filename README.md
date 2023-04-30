# Application-of-NLP-in-Automated-Classification-of-ticket-routing


Natural Language Processing (NLP) is a subfield of artificial intelligence that helps computers understand human language. Using NLP, machines can make sense of unstructured data so that we can gain valuable insights.

We use explicit and implicit rules to convey an idea during conversations. Most of the words we use to do this are flowing out of our mouth just because of the probability that a given word will come after or before another word we are using. This probability can be reverse-engineered from a corpus of things we say or write.
Deep Learning and NLP algorithms help us achieve this and with it we can train machines to understand text. This helps in automating many manual tasks like reading and classifying texts to a theme. Companies use resources to read complaints received from customers and route it to specific teams to address it. We may have to read issues reported and classify them to root causes like accuracy, completeness or timeliness for further action. Companies may have to read through customer reviews to identify the dissatisfied customers.

In this project, we learnt application of various NLP techniques to generate insights from the text data, identify the problems associated with the dataset and then leverage multiple NLP and Deep Learning techniques to solve a problem. We could calculate the readability standard of texts, reading time per description and then the polarity of each description which were useful insights.

We could then break the plain text to sequential numeric format by converting it to an embedding (use pre-computed models) so that it can be fed to our deep learning models. This project gave us the opportunity to experiment with multiple approaches and algorithms to arrive at the final solution which gives us the best solution, given the limitations. Use of Bi-Directional LSTM and Transformer layers seemed to have given us the best results and also reiterated the common sense in knowing that words with the context convey more than words themselves. It was seen that hybrid models like combination of CNN and lstm/gru/bi-lstm can also be applied which can sometimes give good results, though not in this case.
Lastly we saw that the ensemble of Bi-LSTM gave us the best results indicating that synergy amongst resources can always give better results than what can be achieved from one good resource.

Natural Language Processing (NLP) is a subfield of artificial intelligence that helps computers understand human language. Using NLP, machines can make sense of unstructured data so that we can gain valuable insights.

We use explicit and implicit rules to convey an idea during conversations. Most of the words we use to do this are flowing out of our mouth just because of the probability that a given word will come after or before another word we are using. This probability can be reverse-engineered from a corpus of things we say or write.
Deep Learning and NLP algorithms help us achieve this and with it we can train machines to understand text. This helps in automating many manual tasks like reading and classifying texts to a theme. Companies use resources to read complaints received from customers and route it to specific teams to address it. We may have to read issues reported and classify them to root causes like accuracy, completeness or timeliness for further action. Companies may have to read through customer reviews to identify the dissatisfied customers.

In this project, we learnt application of various NLP techniques to generate insights from the text data, identify the problems associated with the dataset and then leverage multiple NLP and Deep Learning techniques to solve a problem. We could calculate the readability standard of texts, reading time per description and then the polarity of each description which were useful insights.

We could then break the plain text to sequential numeric format by converting it to an embedding (use pre-computed models) so that it can be fed to our deep learning models. This project gave us the opportunity to experiment with multiple approaches and algorithms to arrive at the final solution which gives us the best solution, given the limitations. Use of Bi-Directional LSTM and Transformer layers seemed to have given us the best results and also reiterated the common sense in knowing that words with the context convey more than words themselves. It was seen that hybrid models like combination of CNN and lstm/gru/bi-lstm can also be applied which can sometimes give good results, though not in this case.
Lastly we saw that the ensemble of Bi-LSTM gave us the best results indicating that synergy amongst resources can always give better results than what can be achieved from one good resource.

Businsess Problem

One of the key activities of any IT function is to “Keep the lights on” to ensure there is no impact to the Business operations. IT leverages Incident Management process to achieve the above Objective. An incident is something that is unplanned interruption to an IT service or reduction in the quality of an IT service that affects the Users and the Business. The main goal of Incident Management process is to provide a quick fix / workarounds or solutions that resolves the interruption and restores the service to its full capacity to ensure no business impact.
In most of the organizations, incidents are created by various Business and IT Users, End Users/ Vendors if they have access to ticketing systems, and from the integrated monitoring systems and tools. Assigning the incidents to the appropriate person or unit in the support team has critical importance to provide improved user satisfaction while ensuring better allocation of support resources. The assignment of incidents to appropriate IT groups is still a manual process in many of the IT organizations. Manual assignment of incidents is time consuming and requires human efforts. There may be mistakes due to human errors and resource consumption is carried out ineffectively because of the misaddressing. On the other hand, manual assignment increases the response and resolution times which result in user satisfaction deterioration / poor customer service.

Business Domain Value

In the support process, incoming incidents are analyzed and assessed by organization’s support teams to fulfill the request. In many organizations, better allocation and effective usage of the valuable support resources will directly result in substantial cost savings.
Currently the incidents are created by various stakeholders (Business Users, IT Users and Monitoring Tools) within IT Service Management Tool and are assigned to Service Desk teams (L1 / L2 teams). This team will review the incidents for right ticket categorization, priorities and then carry out initial diagnosis to see if they can resolve. Around ~54% of the incidents are resolved by L1 / L2 teams. Incase L1 / L2 is unable to resolve, they will then escalate / assign the tickets to Functional teams from Applications and Infrastructure (L3 teams). Some portions of incidents are directly assigned to L3 teams by either Monitoring tools or Callers / Requestors. L3 teams will carry out detailed diagnosis and resolve the incidents. Around ~56%
of incidents are resolved by Functional / L3 teams. Incase if vendor support is needed, they will reach out for their support towards incident closure.
L1 / L2 needs to spend time reviewing Standard Operating Procedures (SOPs) before assigning to Functional teams (Minimum ~25-30% of incidents needs to be reviewed for SOPs before ticket assignment). 15 min is being spent for SOP review for each incident. Minimum of ~1 FTE effort needed only for incident assignment to L3 teams. During the process of incident assignments by L1 / L2 teams to functional groups, there were multiple instances of incidents getting assigned to wrong functional groups. Around ~25% of Incidents are wrongly assigned to functional teams. Additional effort needed for Functional teams to re-assign to right functional groups. During this process, some of the incidents are in queue and not addressed timely resulting in poor customer service. Guided by powerful AI techniques that can classify incidents to right functional groups can help organizations to reduce the resolving time of the issue and can focus on more productive tasks.

Project Description

In this capstone project, the goal is to build a classifier that can classify the tickets by analysing text.

Achievents through this project are given below: 

Pre-Processing, Data Visualisation and EDA

● Exploring the given Data files

● Understanding the structure of data

● Missing points in data

● Finding inconsistencies in the data

● Visualizing different patterns

● Visualizing different text features

● Dealing with missing values

● Text preprocessing

● Creating word vocabulary from the corpus of report text data

● Creating tokens as required


Model Building

● Building a model architecture which can classify.

● Trying different model architectures by researching state of the art for similar tasks.

● Train the model

Test the Model, Fine-tuning and Repeat 

● Test the model and report as per evaluation metrics

● Try different models  

● Set different hyper parameters, by trying different optimizers, loss functions, epochs, learning rate, batch size, checkpointing, early stopping etc..for these models to fine-tune them 

● Report evaluation metrics for these models along with your observation on how changing different hyper parameters leads to change in the final evaluation metric.
