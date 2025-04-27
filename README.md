# Project Planning Agents

A Python-based autonomous agent system that automates project planning and resource allocation using CrewAI. This project demonstrates how multiple specialized agents can collaborate to break down tasks, estimate timelines, and allocate resources efficiently.

## 🚀 Features

- **Multi-Agent Planning System**: Three specialized agents work together to create comprehensive project plans.
- **YAML Configuration**: Flexible agent and task configurations via YAML files.
- **Task Breakdown Automation**: Automatically breaks down project requirements into manageable tasks.
- **Resource Allocation**: Smart allocation of team members to tasks based on skills and availability.
- **Time Estimation**: Provides detailed time estimates for each task and milestone.
- **Data Export**: Generates project plans in HTML and Excel formats.
- **Cost Tracking**: Monitors and reports API usage costs.

## 🧩 Main Agents

- **Project Planning Agent**: Breaks down project requirements into detailed tasks and milestones.
- **Estimation Agent**: Provides time and resource estimates for each task.
- **Resource Allocation Agent**: Assigns team members to tasks based on skills and availability.

## 🏗️ How It Works

1. **Setup**: Configure your environment and YAML files.
2. **Run the App**: Execute `main.py` to start the agent workflow.
3. **Agent Collaboration**: 
   - Project Planner breaks down requirements
   - Estimation Agent provides time estimates
   - Resource Allocation Agent assigns team members
4. **Output**: Generates detailed project plan with tasks, timelines, and resource allocation.

## 📦 Installation

```bash
git clone <repo-url>
cd project-planning-agents
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## ⚙️ Usage

1. Configure project details in YAML files:
   - `config/agents.yaml`: Agent configurations
   - `config/tasks.yaml`: Task configurations

2. Run the main script:
   ```bash
   python main.py
   ```

3. Customize inputs in `main.py`:
   - Project type
   - Project objectives
   - Industry
   - Team members
   - Project requirements

## 📝 Example

```
$ python main.py
[ProjectPlanner] Analyzing project requirements...
[EstimationAgent] Calculating time estimates...
[ResourceAllocation] Assigning team members...
Output: Project plan saved as tasks_table.html and tasks_table.xlsx
```

## 🛠️ Customization

- Modify YAML configurations for different project types
- Add new agents for specialized planning tasks
- Customize output formats and reporting
- Integrate with project management tools
- Add custom task estimation algorithms

## 📚 Dependencies

- Python 3.8+
- CrewAI
- pandas
- pyyaml
- pydantic
- Other packages in `requirements.txt`

## 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you want to change.

---
Feel free to modify or extend the agents for your own project planning automation needs!
