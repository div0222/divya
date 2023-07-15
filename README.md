echo "npx create-react-app my-app" > command.sh
echo "cd my-app" >> command.sh
echo "git init" >> command.sh
echo "git add ." >> command.sh
echo 'git commit -m "Initial commit"' >> command.sh
echo "gh repo create <repository-name>" >> command.sh
echo "git checkout -b update_logo" >> command.sh
echo "# Download the logo from the link and replace the existing logo file manually" >> command.sh
echo "# Open the appropriate file and replace the existing link manually" >> command.sh
echo "git add ." >> command.sh
echo 'git commit -m "Update logo and link"' >> command.sh
echo "git push origin update_logo" >> command.sh
echo 'gh pr create --base master --head update_logo' >> command.sh
echo "gh pr merge <pull-request-number>" >> command.sh
