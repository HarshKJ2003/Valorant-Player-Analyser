#  LLM-Powered Digital Assistant | AWS Bedrock

## 🚀 Project Overview
This project is an advanced **LLM-powered digital assistant** designed to analyze **Valorant Esports players** and assist in **role-based team formation**. Built using **Amazon Bedrock**, it leverages **retrieval-augmented generation (RAG)** to fetch real-time stats and match data.

## 🛠️ Features
- 🔍 **Player Analysis**: Evaluates player performance and suggests suitable roles.
- 📊 **Real-time Data Retrieval**: Uses **RAG** for fetching the latest match data and statistics.
- 🖥 **Web Scraping**: Aggregates training data from multiple online sources.
- 🔧 **Amazon Bedrock Integration**: Provides scalable and efficient LLM hosting.

## 🏗 Architecture
```
1. Data Collection: Web Scraping for esports player stats.
2. Data Processing: Preprocessing and fine-tuning the LLM.
3. RAG Pipeline: Implemented on Amazon Bedrock with OpenSearch.
4. User Interaction: Flask-based UI for easy team formation and queries.
```

## 🖥️ Screenshots
📸 **Knowledge Base Data Source**  
*(Attach Screenshot Here)*

📸 **Test Knowledge Base Query**  
*(Attach Screenshot Here)*

📸 **Embedding Model & Vector Database**  
*(Attach Screenshot Here)*

## 🔧 Setup Instructions
### Prerequisites
Ensure you have the following installed:
- **Python 3.9+**
- **AWS CLI** (Configured with appropriate credentials)
- **Flask**
- **Boto3** (AWS SDK for Python)

### Installation
```bash
# Clone the repository
git clone https://github.com/your-repo-name.git
cd your-repo-name

# Install dependencies
pip install -r requirements.txt
```

### Environment Setup
Create a `.env` file and configure the required AWS credentials:
```bash
AWS_ACCESS_KEY_ID=your-access-key
AWS_SECRET_ACCESS_KEY=your-secret-key
AWS_REGION=ap-south-1
```

### Running the Application
```bash
# Start the Flask application
python app.py
```

## 🏆 Usage Guide
1. **Upload player stats & team data to S3**.
2. **Sync the data source in Amazon Bedrock**.
3. **Query the assistant for team formation & player insights**.
4. **Retrieve recommendations based on role and performance**.

## 🎯 Future Improvements
- **Enhancing the LLM’s contextual understanding** with more training data.
- **Deploying a web-based UI** for better usability.
- **Expanding to other esports games** beyond Valorant.

## 📜 License
This project is licensed under the **MIT License**.

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss.

📩 **Contact:** [Your Email or LinkedIn]

---
🚀 *Happy Coding!*

