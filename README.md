# RateBoard

# 1. Create vue directory
#   Bugs: 1. cannot install -g @vue/cli
#           Fix: npm uninstall -g @vue/cli
#                npm cache clean --force
#                npm config set prefix %APPDATA%\npm 
#                go to env vars, find 'path', delete the previous node_global path
#                Add %APPDATA%\npm
#                Clean and re-install
#         2. cannot create vue project
#           Fix: use external terminal, use lowercase letters for the project name. 
# 2. Bugs fixed: vue.config.js and babel.config.js and .eslintrc.js   
# 3. remove babel-eslint    
# 4. remove dependencies and extensions
# 5. create registration form!