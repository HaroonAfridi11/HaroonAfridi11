- 👋 Hi, I’m @HaroonAfridi11
- 👀 I’m interested in termux cloning
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

#!/data/data/com.termux/files/usr/bin/bash

# Prompt the user to enter the repository URL
read -p "Enter the GitHub repository URL: " repo_url

# Extract the repository name from the URL
repo_name=$(basename -s .git $repo_url)

# Clone the repository
git clone $repo_url

# Change to the cloned repository directory
cd $repo_name

# Install any necessary dependencies or perform further setup steps if required

# Run any build or installation commands
# For example:
# ./configure
# make
# make install

# Provide any post-clone instructions or guidance to the user

echo "Cloning and setup complete."
