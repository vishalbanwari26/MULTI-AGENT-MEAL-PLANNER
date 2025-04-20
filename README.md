# Multi-Agent Meal Planning System

This personal project demonstrates a **multi-agent system** designed to assist users in planning daily meals while considering **dietary preferences**, **nutritional goals**, and **financial constraints**. The system uses a group of intelligent agents, each specializing in a meal type, and integrates a custom **Budget Checker Tool** to ensure all meal recommendations remain affordable.

## 🌟 Project Highlights

- Personalized and health-conscious meal suggestions for **breakfast, lunch, dinner, and snacks**
- Real-time **budget validation** using a custom tool
- Seamless coordination among agents using a **Round Robin** group chat structure
- Built with **Groq API**, featuring `llama3-70b-8192`, `MaxMessageTermination`, `AssistantAgent`, and `RoundRobinGroupChat`

## 🧠 System Overview

### 1. Personalized Meal Recommendations
- Suggestions based on individual **dietary restrictions**, **preparation time**, and **food preferences**
- Offers **one recommendation per meal** (breakfast, lunch, dinner, snack)
- Designed to promote **balanced nutrition**

### 2. Budget Validation
- A custom **Budget Checker Tool** verifies affordability before confirming meal choices
- Real-time **feedback** on affordability and remaining budget

### 3. User-Friendly Assistance
- Clear and concise communication
- Actionable and practical suggestions for each meal type

## 🧑‍💻 Agent Roles

| Agent         | Role                                                                 | Specialization                                              |
|---------------|----------------------------------------------------------------------|-------------------------------------------------------------|
| **Breakfast** | Suggests affordable, time-conscious, nutritious breakfasts           | Single recommendation + Budget Checker Tool                |
| **Lunch**     | Recommends balanced and budget-validated lunches                     | Tailored to dietary needs                                   |
| **Dinner**    | Offers practical dinner options based on dietary and budget needs    | Validates feasibility and cost                              |
| **Snack**     | Provides healthy snacks that align with the day’s nutrition          | Checks cost-effectiveness and health balance                |
| **Budget**    | Oversees total cost of all meals                                     | Offers real-time feedback via Budget Checker Tool           |

## 💰 Budget Checker Tool

### Purpose:
Ensures each meal recommendation fits within the remaining budget.

### Features:
- **Affordability Validation**
- **Clear Budget Feedback**
- **Integration with all Meal Agents**

## ⚙️ Technologies Used

- Python
- Jupyter Notebook
- Groq API (`llama3-70b-8192`,`MaxMessageTermination`, `AssistantAgent`, `RoundRobinGroupChat`)
- Custom budget handling logic

## 🚀 How to Use

1. Clone this repository
2. Install required Python packages (Groq SDK, etc.)
3. Run the Jupyter Notebook
4. Customize inputs such as budget and dietary preferences
5. Review generated meal plan and budget validation

## 📌 Future Work

- Incorporate grocery delivery APIs for real-time pricing
- Expand support to weekly or monthly planning
- Add visual dashboard for meal summaries and budget tracking

## 📄 License

This project is open-source under the MIT License.
