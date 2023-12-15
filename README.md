Step 1: Create a .env File

Use sudo nano .env to create and edit a file named .env.
Inside .env, store sensitive information like API keys:
makefile
Copy code
OPENAI_API_KEY=your_openai_api_key_here
Step 2: Install Docker and Docker Compose

Run these commands:
bash
Copy code
sudo apt install docker
sudo apt install docker-compose
Step 3: Docker Setup

For a single container:

bash
Copy code
docker run container_name
For multiple containers managed together with Docker Compose:

Create a docker-compose.yaml file to define services.
For instance, a simple docker-compose.yaml might have services for frontend, backend, and a database.
Step 4: OpenAI Integration

Obtain an API key from the OpenAI website after signing up.
Add the obtained key to the .env file:
makefile
Copy code
OPENAI_API_KEY=your_openai_api_key_here
Step 5: Running Containers

Use Docker Compose to build and start containers:
bash
Copy code
sudo docker-compose up -d --build

![image](https://github.com/MahaWZ/chatgpt_deplpoy/assets/65794956/2953232e-f83f-46b0-aeae-edca14b1144f)
![image](https://github.com/MahaWZ/chatgpt_deplpoy/assets/65794956/e7cf0e8b-3926-4928-870d-a8d86302a583)
![image](https://github.com/MahaWZ/chatgpt_deplpoy/assets/65794956/31a9c2ce-d648-458a-a7a7-e8752eb2d97f)
![image](https://github.com/MahaWZ/chatgpt_deplpoy/assets/65794956/fc59c89d-02a7-44c6-b87a-3e87e84b936c)
![image](https://github.com/MahaWZ/chatgpt_deplpoy/assets/65794956/9a71ebe5-435d-4179-ba9c-94e888e7ed31)




