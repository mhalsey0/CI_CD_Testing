Project to learn and test CI/CD skills and processes.

I set up this pipeline to demonstrate how to automate linting, dependency scanning, and security checks.

I used flake8 for python linting, Safety for dependency scanning, and bandit for security checks.

flake8 ensures that standardized styles for python are being used.

Safety checks for vulnerabilities within packages upon which the project is dependent.

bandit finds commonly known security issues within python.

I faced several issues with building the pipeline. First I had to understand how each tool accessed the required files and ensure that I was directing each tool to the appropriate directory. Then I struggled with the authorization for safety. I learned how to use github secrets within this project to solve that problem. Finally, there were several issues within the code that were flagged by each tool. I addressed each issue one by one until the checks passed.
