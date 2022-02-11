# Docker instructions

Run the following commands in the project folder:

1. ```docker build -t user_manager_image:latest .```
2. ```docker run -d --rm --name user_manager_container -p 3000:3000 user_manager_image:latest```
3. Navigate to ```localhost:3000```
