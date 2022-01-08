# Docker-Commands

1. **Build Spring Boot docker command**

        docker build -t learning:0.0.1 .

        learning -> artifact name
        0.0.1 -> version name
      
2. **Display existing docker images**
    
        docker images
        
3. **Run Spring boot docker from command line**

    docker run -d -p 8080:8080 -t learning:0.0.1


