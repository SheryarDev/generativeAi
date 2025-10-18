# Create Via python

python -m venv enviormentName

start

testenv/Scripts/activate

end

deactivate


🧩 1. Open Terminal

On your Mac, open Terminal (you can find it via Spotlight or in Applications → Utilities).

⚙️ 2. Create a New Conda Environment

Use this command pattern:

conda create --name <env_name> python=<version>


Example:

conda create --name myenv python=3.10


This will:

Create an environment named myenv

Install Python 3.10 inside it

🚀 3. Activate the Environment

After creation, activate it with:

conda activate myenv


Now your terminal prompt should show something like:

(myenv) $


indicating you’re inside the new environment.

🧱 4. Install Packages

You can install additional packages inside the environment:

conda install numpy pandas


Or use pip inside the environment:

pip install requests

❌ 5. Deactivate Environment

To exit the environment:

conda deactivate

🗑️ 6. Remove Environment (if needed)

To delete an environment completely:

conda remove --name myenv --all

💡 (Optional) View All Environments
conda env list


or

conda info --envs


Would you like me to show how to create an environment from a requirements.txt or environment.yml file next?