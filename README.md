# projecto-devops
Ensure you have install jest globally or locally. 
To install it globally run in your terminal
sudo npm install -g jest (for macOS or Linux)
npm install -g jest (for Windows)

Open the project in Visual Studio and modify the file suma.test.js
You can modify the variables or the argument in the toBe method to make the test past or not. 
the toBe method is what the sum must return, in example 1 + 2 should return 3, so in the toBe method the parameter will be 3. 
The test will pass if the sum equals to three, if you modify the variables and change one for two the result will be four, but the method will continue expecting three then
the test will fail.
You can also change the parameter within the toBe method making it four. So the sum 1 + 2 returns 3, but the method is expecting 4, then the test will fail.

After modifying the file suma.test.js run the git commands
git add .
git commit -m 'add here the commit message'
git push origin master

NOTE: if you clone the repo and create a separate branch, change the branch name within the yml file in the directory github/workflows.

When you run the push command go to your github and click on Actions.
Click on the name of the action. It will be the commit text. You may need to refresh.
You will see a box like a folder with the name Matrix:build. 
Click on that box and then refresh to start watching the jobs.

