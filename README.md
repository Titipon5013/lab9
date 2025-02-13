# lab9

- 1.1 - 1.8
  - docker build -t {your-docker-username}/test .
  - docker build --platform linux/amd64 -t {your-docker-username}/test .
  - docker build --platform linux/amd64 -t {your-docker-username}/test .
  - docker images
  - docker login
  - docker push {your-docker-username}/test
 
  ![image](https://github.com/user-attachments/assets/2ef46bdd-65b2-4ee6-b58e-04b660bf3a48)

- 1.9
  
  ![image](https://github.com/user-attachments/assets/fc8618fc-d52f-43ba-9955-787f385ea211)

  - docker pull timetitipon/test
  - docker run -p 8105:80 timetitipon/test
    


- 2.1 - 2.6
  - npm install -g pnpm
  - pnpm install
  - pnpm build
  - docker build -t timetitipon/nuxt-app .

  ![image](https://github.com/user-attachments/assets/f104a642-f268-436e-af63-37d71b2ee9d1)


- 2.7

  ![image](https://github.com/user-attachments/assets/a8592bc3-1c16-466d-9171-0984b5d28250)

- 2.8

  ![image](https://github.com/user-attachments/assets/f2dae10b-d3c1-4ce4-8528-f886f09d40c0)

  - docker run -p 3000:3000 timetitipon/nuxt-app

- 2.9

  ![image](https://github.com/user-attachments/assets/33dd082f-b24f-4dbf-bb62-ff0c6ea889cd)

- 2.10

  ![image](https://github.com/user-attachments/assets/36130ebb-f25d-4a77-98df-7d5b62251d45)

  - docker run -p 3000:3000 timetitipon/nuxt-movies:1.0

  ![image](https://github.com/user-attachments/assets/743746f1-9d2a-4a5a-b920-c4b73a8203b8)

- 3

  - docker push timetitipon/nuxt-movies:1.0
  - docker push timetitipon/nuxt-app


  ![image](https://github.com/user-attachments/assets/e6152347-9dc5-4ced-b151-7cfa6281d228)


- 4
  - docker pull timetitipon/nuxt-app
  - docker run -p 3000:3000 timetitipon/nuxt-app

    
  ![image](https://github.com/user-attachments/assets/7d7e08a5-d169-4b46-89fc-572018ade157)
  

  ![image](https://github.com/user-attachments/assets/e378978c-69d0-457a-aa59-9e1d7b5a55b3)

- 5
  - npm install -g pnpm
  - pnpm install
  - pnpm build
  - docker build -t timetitipon/vue3-realworld .
  - docker push timetitipon/vue3-realworld
  - ssh -i "lab09.pem" ubuntu@ec2-52-206-6-100.compute-1.amazonaws.com
  - docker pull timetitipon/vue3-realworld
  - docker run -p 8080:80 timetitipon/vue3-realworld

    
  ![image](https://github.com/user-attachments/assets/ca04748b-6cb9-46fc-bbe3-4bb633de6ad0)

    






