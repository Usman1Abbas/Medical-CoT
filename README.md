# Medical-CoT

# LLM Fine-Tuning for Chain-of-Thought Reasoning

This repository contains the implementation and results of fine-tuning the **Llama 3.2 (3B)** model using **PEFT (Parameter-Efficient Fine-Tuning)** techniques to improve its multi-step reasoning capabilities. The goal is to enhance the model’s performance on complex tasks by leveraging chain-of-thought reasoning.

### 🚀 Key Features:
- **Fine-tuned Llama 3.2 (3B)**: Enhanced model with improved chain-of-thought reasoning.
- **PEFT Techniques**: Efficient fine-tuning methods for better resource utilization and performance.
- **Systematic Experiment Tracking**: Integrated **Weights & Biases** to track the experiments and monitor model performance throughout the process.
- **Improved Multi-Step Reasoning**: Achieved significant improvements on tasks requiring logical, step-by-step reasoning.

### 📊 Experiment Tracking
We used **Weights & Biases** for experiment tracking, providing visualizations of metrics like accuracy, loss, and other relevant statistics over time. This helps in understanding the model's learning progression and tuning decisions.

### 🧑‍💻 Setup & Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/llm-finetuning-chain-of-thought.git
   cd llm-finetuning-chain-of-thought
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up Weights & Biases:
   - Sign up at [Weights & Biases](https://www.wandb.com/) if you don’t have an account.
   - Set up your API key:
     ```bash
     wandb login YOUR_API_KEY
     ```

### 🏗️ Model Fine-Tuning

To start fine-tuning the Llama 3.2 (3B) model, follow these steps:

1. **Prepare Data**: Make sure your dataset is in the proper format (e.g., JSON or CSV). Place the dataset in the `/data` directory.
2. **Run Fine-Tuning**:
   ```bash
   python finetune_model.py --data_path /data/dataset.json --epochs 10 --batch_size 16
   ```

   You can adjust hyperparameters (like learning rate, batch size, etc.) as required.

### 📈 Experiment Monitoring

Monitor your experiments in real-time using Weights & Biases:

- Track hyperparameters, loss, and accuracy for each experiment.
- View visualizations of model performance over time.

### 📝 Results

This fine-tuning process significantly improves the model's reasoning capabilities, particularly for tasks that involve complex, multi-step problem-solving. The chain-of-thought approach ensures better accuracy and reliability for these kinds of tasks.

### 📂 Folder Structure

- `finetune_model.py`: The main script for model fine-tuning.
- `data/`: Folder containing datasets for training.
- `weights/`: Folder to save model checkpoints.
- `wandb/`: Experiment tracking logs and results.

### 🧑‍💻 Contributors

- **Muhammad Usman Abbas**: Lead Developer and Researcher

### 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### 💬 Feedback & Contributions

Feel free to open issues or contribute to the repository. Contributions are always welcome!

---

Thank you for exploring this project! Feel free to reach out if you have any questions or suggestions.
