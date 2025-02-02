# Event Orchestration System Using AWS Services

## Project Description
This project is a Bachelor Thesis focused on building an Event Orchestration System utilizing AWS services, machine learning models, and advanced cloud-native technologies. The system leverages the capabilities of AWS SageMaker, CloudTrail, EC2, and Step Functions to orchestrate events effectively. Additionally, it incorporates machine learning models, including the DistilBERT transformer, for intelligent event processing and decision-making.

### Features

- **Event Orchestration**:
  - Centralized handling and processing of events using AWS Step Functions.
  - Seamless communication between AWS services for event coordination.

- **Machine Learning Integration**:
  - Utilizes the DistilBERT transformer for NLP-based event insights.
  - Deploys ML models to AWS SageMaker for scalable and efficient inference.

- **Cloud-Native Architecture**:
  - Implements AWS CloudTrail for event tracking and auditing.

- **Real-Time Event Handling**:
  - Processes and emits events in real-time using custom event emitters.
  - Ensures low-latency and high-availability performance.

### Technology Stack

- **Backend**: Python (Jupyter Notebooks for prototyping and implementation).
- **Cloud Platform**: AWS (SageMaker, Step Functions, CloudTrail, EC2, lambda).
- **Machine Learning**: Transformers (DistilBERT) for natural language processing.
- **Tools**: AWS CLI, Boto3 SDK, Jupyter Notebooks.

### Key AWS Services Used

1. **AWS SageMaker**:
   - Hosts and deploys DistilBert
   - Provides scalable infrastructure for ML inference.

2. **AWS Step Functions**:
   - Orchestrates workflows and manages event execution through lambda functions

3. **AWS CloudTrail**:
   - Tracks API calls and records event logs for auditing purposes.



### Installation and Setup

#### Prerequisites
1. An active AWS account with necessary permissions.
2. AWS CLI installed and configured.
3. Python environment with required dependencies.

#### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/event-orchestration-system.git
   cd event-orchestration-system
   ```

2. Set up python environment



3. Deploy ML models to SageMaker:
   - Use the provided Jupyter Notebook `sendEventsToSageMaker.ipynb` to deploy the DistilBERT model.

4. Run the Event Orchestration workflow:
   - Execute the `EventOrchestration.ipynb` notebook to initiate workflows.

5. Monitor logs and outputs:
   - Use AWS CloudTrail and CloudWatch for tracking execution.

### Future Enhancements

- Incorporate additional AWS services (e.g., Lambda, DynamoDB) for extended functionality.
- Develop a web-based dashboard for real-time event monitoring.
- Enhance ML models for more accurate event predictions and decisions through continous model training

---

Feel free to explore and contribute to this project. For any queries or suggestions, please contact the project maintainers. Let's harness the power of AWS and ML to build intelligent systems together.
