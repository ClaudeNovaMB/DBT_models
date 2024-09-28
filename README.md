🧠 dbt-models: A Collection of Data Models

Welcome to dbt-models! 🎉 This repository is a showcase of my work in data modeling using dbt (Data Build Tool). Here, you’ll find a variety of SQL models designed to demonstrate my expertise in SQL, dbt, and the art of data modeling.

💡 What’s in the Box?

This repository contains a curated list of dbt models ranging from basic to advanced, with each model demonstrating different techniques, transformations, and best practices for building reliable, scalable data pipelines.

If you’re exploring dbt or just looking for some inspiration on data modeling, you’re in the right place! 😊

📚 Why This Repo?

The goal of this repo is simple:

	•	Showcase examples of various dbt models.
	•	Highlight different SQL techniques and best practices.
	•	Provide a resource for fellow data enthusiasts and learners.

💼 Whether you’re a seasoned data engineer or just starting out with dbt, these examples can be helpful in expanding your knowledge of SQL-based transformations within dbt!

🛠️ Tech Stack

This project makes use of:

	•	dbt (Data Build Tool) 🧰
	•	SQL 💻
	•	Github 🗂️
 	•	TimeScaleDB 🛢️ (Time series db built on top of Postgres)
	•	And of course, lots of data modeling knowledge 📊🔍

✨ Key Features

	•	Diverse Models: From dimensional to fact models and everything in between.
	•	Scalability: dbt models built with scalability and performance in mind.
	•	Clarity: Each model includes a detailed explanation of its use case and logic.

🚀 Get Started
```
git clone https://github.com/ClaudeNovaMB/dbt-models.git
```
Some troubleshooting I've encountered which may help
Run these commands
```
pip install dbt-core
pip install --upgrade dbt-core
pip install --upgrade dbt-postgres
# Optional if you're running all your code in a python virtual environment
touch .gitignore
#open this file and add your virtual environment name (Im on a mac)
nano .gitignore
#Paste your venv name in the file, save and exit
git add .gitignore
git commit -m "Add dbt-venv to .gitignore"
#check your git status constantly as good practice :-)
git status
```
This may sound like obvious advice but take a moment to read the output results from every command you run. 
There is such great guidance which dbt, Timescales, github and postgres provide to follow post installation and next step processes.

If you’re ready to explore the world of dbt models, feel free to dive right in! You can browse the models in the models/ folder, where each one is documented and ready for exploration. 🔍

🧐 Need Help?

Have questions or suggestions? Feel free to reach out or open an issue! 🤓 I’d love to hear your thoughts and ideas on data modeling and how we can improve these examples even further.

Happy data modeling! 💾✨
Claude👓
Data Enthusiast & dbt Modeler
