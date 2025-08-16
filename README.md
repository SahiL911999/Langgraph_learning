# LangGraph Learning Repository

A comprehensive collection of LangGraph workflows and examples demonstrating various AI application patterns, from basic concepts to advanced implementations.

## 🚀 Overview

This repository contains hands-on examples and tutorials for learning LangGraph, a powerful framework for building stateful, multi-step applications with LLMs. Each notebook demonstrates different workflow patterns and use cases, making it perfect for developers learning to build AI applications.

## 📚 Learning Path

### 1. **Getting Started**
- **`0_Installation_testing.ipynb`** - Basic setup and testing
- **`1_bmi_first_workflow.ipynb`** - Simple BMI calculation workflow

### 2. **Basic Workflows**
- **`2_LLM_Workflow.ipynb`** - Simple LLM question-answering workflow
- **`3_prompt_chaining.ipynb`** - Sequential prompt chaining for blog creation

### 3. **Advanced Patterns**
- **`4_Simple_Parallel_Workflow.ipynb`** - Parallel execution for cricket statistics
- **`5_Essay_Workflow.ipynb`** - Multi-criteria essay evaluation system
- **`6_Maths_Conditional.ipynb`** - Conditional logic for quadratic equations
- **`7_review_conditional_workflow.ipynb`** - Sentiment-based review processing
- **`8_tweets_Iterative_Workflow.ipynb`** - Iterative tweet generation and optimization

## 🛠️ Technologies Used

- **LangGraph** - Core workflow framework
- **LangChain** - LLM application framework
- **Groq** - High-performance LLM inference
- **Python** - Programming language
- **Jupyter Notebooks** - Interactive development environment
- **Pydantic** - Data validation and settings management

## 📋 Prerequisites

- Python 3.8+
- pip package manager
- Groq API key
- Jupyter Notebook or JupyterLab

## 🔧 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SahiL911999/Langgraph_learning.git
   cd Langgraph_learning
   ```

2. **Install required packages:**
   ```bash
   pip install langgraph langchain-groq langchain-core python-dotenv pydantic jupyter
   ```

3. **Set up environment variables:**
   Create a `.env` file in the project root:
   ```env
   GROQ_API_KEY=your_groq_api_key_here
   ```

## 📖 Detailed Examples

### 🔍 **LLM Workflow** (`2_LLM_Workflow.ipynb`)
Simple question-answering system using LangGraph's StateGraph.
- **State Management**: `LLMState` with question and answer fields
- **Workflow**: Single node processing with START → END flow
- **Use Case**: Basic Q&A applications

### 📝 **Prompt Chaining** (`3_prompt_chaining.ipynb`)
Sequential workflow for creating blog content with multiple steps.
- **State Management**: `BlogState` with title, outline, content, and evaluation
- **Workflow**: Linear chain: outline → blog → evaluation
- **Use Case**: Content generation pipelines

### ⚡ **Parallel Workflow** (`4_Simple_Parallel_Workflow.ipynb`)
Cricket statistics calculator with parallel computation.
- **State Management**: `BatsmanState` with batting statistics
- **Workflow**: Parallel calculation of strike rate, balls per boundary, and boundary percentage
- **Use Case**: Data processing and analysis

### 📊 **Essay Evaluation** (`5_Essay_Workflow.ipynb`)
Multi-criteria essay assessment system.
- **State Management**: `UPSCState` with essay and evaluation fields
- **Workflow**: Parallel evaluation of language, analysis, and clarity
- **Use Case**: Educational assessment and feedback systems

### 🧮 **Conditional Logic** (`6_Maths_Conditional.ipynb`)
Mathematical workflow with conditional branching.
- **State Management**: `QuadState` for quadratic equation solving
- **Workflow**: Conditional execution based on discriminant value
- **Use Case**: Mathematical computations with branching logic

### 😊 **Review Processing** (`7_review_conditional_workflow.ipynb`)
Sentiment-based review analysis and response generation.
- **State Management**: `ReviewState` with review text and analysis
- **Workflow**: Conditional processing based on sentiment
- **Use Case**: Customer support and feedback systems

### 🐦 **Iterative Tweet Generation** (`8_tweets_Iterative_Workflow.ipynb`)
Advanced workflow with iterative improvement loops.
- **State Management**: `TweetState` with tweet content and evaluation
- **Workflow**: Generate → Evaluate → Optimize loop
- **Use Case**: Content creation with quality assurance

## 🏗️ Core Concepts Demonstrated

### **State Management**
- TypedDict for structured state
- Annotated fields for automatic aggregation
- State updates and transformations

### **Workflow Patterns**
- **Linear**: Sequential execution
- **Parallel**: Concurrent processing
- **Conditional**: Branching based on conditions
- **Iterative**: Loops with improvement cycles

### **LLM Integration**
- Structured outputs with Pydantic
- Prompt engineering and chaining
- Multi-model workflows

### **Error Handling**
- State validation
- Workflow compilation
- Execution monitoring

## 🚀 Getting Started

1. **Start with the basics**: Begin with `0_Installation_testing.ipynb`
2. **Understand simple workflows**: Move to `2_LLM_Workflow.ipynb`
3. **Learn sequential patterns**: Study `3_prompt_chaining.ipynb`
4. **Explore advanced concepts**: Dive into parallel and conditional workflows
5. **Master complex patterns**: Work through iterative workflows

## 💡 Best Practices

- **State Design**: Keep state objects focused and well-typed
- **Node Functions**: Make nodes pure and predictable
- **Error Handling**: Validate inputs and handle edge cases
- **Documentation**: Document complex workflows and state schemas
- **Testing**: Test individual nodes and complete workflows

## 🔍 Troubleshooting

### Common Issues
- **Import Errors**: Ensure all packages are installed
- **API Key Issues**: Check your `.env` file configuration
- **State Errors**: Verify state object structure matches TypedDict
- **Workflow Compilation**: Check node connections and edge definitions

### Debugging Tips
- Use `workflow.get_graph().draw_mermaid_png()` to visualize workflows
- Print state objects at each node for debugging
- Check LangGraph documentation for advanced features

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/NewWorkflow`)
3. Add your notebook with clear documentation
4. Commit your changes (`git commit -m 'Add new workflow example'`)
5. Push to the branch (`git push origin feature/NewWorkflow`)
6. Open a Pull Request

## 📚 Additional Resources

- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- [LangChain Documentation](https://python.langchain.com/)
- [Groq API Documentation](https://console.groq.com/docs)
- [Pydantic Documentation](https://docs.pydantic.dev/)

## 📞 Support

If you have questions or need help:
1. Check the [Issues](https://github.com/SahiL911999/Langgraph_learning/issues) page
2. Create a new issue with detailed description
3. Review the LangGraph community resources

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [LangGraph](https://github.com/langchain-ai/langgraph) for the workflow framework
- [Groq](https://groq.com/) for high-performance LLM inference
- [LangChain](https://github.com/langchain-ai/langchain) for the LLM application framework
- The open-source AI community for inspiration and examples

---

**Happy Learning! 🚀📚**

*Build powerful AI workflows with LangGraph!*
