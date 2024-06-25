# CrewAI Agentic Blog Generator with Slack Integration

Welcome to the CrewAI Agentic Blog Generator! This innovative project streamlines the process of blog creation by automating the planning, writing, and editing phases, integrating advanced web search capabilities via SERPER, and enhancing content with automatically generated, descriptive images. The final product is seamlessly delivered to your Slack channel, making it perfect for teams looking for an efficient way to generate and share content.

## Features

- **Automated Blog Planning**: CrewAI intelligently plans out the structure and key points of your blog based on the input query.
- **Content Writing and Editing**: Leveraging state-of-the-art language models, the system writes and meticulously edits blog content to ensure clarity and engagement.
- **SERPER Integration**: Utilizes SERPER for robust web searching to enrich the blog content with the most relevant and up-to-date information.
- **Image Description and Generation**: Describes and generates images relevant to the blog content, adding a visual dimension that enhances reader engagement.
- **Slack Integration**: Automatically posts the finished blog along with the generated images directly to a specified Slack channel, facilitating easy sharing and discussion among team members.

## Getting Started

Follow these steps to set up and run the CrewAI Agentic Blog Generator in your local environment.

### Prerequisites

- Python 3.6+
- Virtual environment (recommended)
- Slack API webhook url
- SERPER API key

### Installation and Setup

1. **Clone the Repository**
   Begin by cloning this repository to your local machine:
   ```bash
   git clone https://github.com/shyamsundar009/crewai-blog-generator.git
   cd crewai-blog-generator
   ```

2. **Install Required Libraries**
   Set up a virtual environment and install the required dependencies:
   ```bash
   python -m venv myenv
   myenv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Set Up Environment Variables**:
   Copy the .env_template file and rename it to .env. Then, replace the placeholders with your actual SERPER and Slack API tokens.
   

4. **Execute the Notebook**
   Run the Jupyter notebook to start generating your blog:
   ```bash
   jupyter notebook try.ipynb
   ```

