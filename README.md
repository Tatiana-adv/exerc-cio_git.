
# Create and switch to the 'exercicio_git' branch
git checkout -b exercicio_git

# Create the 'nome.txt' file with your full name inside
echo "Tatiana Inacio Da Paixão" > nome.txt

# Add the file to the staging area
git add nome.txt

# Commit the changes with a message
git commit -m "Add nome.txt with my full name"

# Push the 'exercicio_git' branch to GitHub
git push origin exercicio_git
