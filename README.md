# BoardgameListingWebApp

## Description 

**Board Game Database Full-Stack Web Application.**
This web application displays lists of board games and their reviews. While anyone can view the board game lists and reviews, they are required to log in to add/ edit the board games and their reviews. The 'users' have the authority to add board games to the list and add reviews, and the 'managers' have the authority to edit/ delete the reviews on top of the authorities of users.  

## Technologies

- Java1
- Spring Boot
- Amazon Web Services(AWS) EC2
- Thymeleaf
- Thymeleaf Fragments
- HTML5
- CSS
- JavaScript
- Spring MVC
- JDBC
- H2 Database Engine (In-memory)
- JUnit test framework
- Spring Security
- Twitter Bootstrap
- Maven

## Features

- Full-Stack Application
- UI components created with Thymeleaf and styled with Twitter Bootstrap
- Authentication and authorization using Spring Security
  - Authentication by allowing the users to authenticate with a username and password
  - Authorization by granting different permissions based on the roles (non-members, users, and managers)
- Different roles (non-members, users, and managers) with varying levels of permissions
  - Non-members only can see the boardgame lists and reviews
  - Users can add board games and write reviews
  - Managers can edit and delete the reviews
- Deployed the application on AWS EC2
- JUnit test framework for unit testing
- Spring MVC best practices to segregate views, controllers, and database packages
- JDBC for database connectivity and interaction
- CRUD (Create, Read, Update, Delete) operations for managing data in the database
- Schema.sql file to customize the schema and input initial data
- Thymeleaf Fragments to reduce redundancy of repeating HTML elements (head, footer, navigation)

## How to Run

1. Clone the repository
2. Open the project in your IDE of choice
3. Run the application
4. To use initial user data, use the following credentials.
  - username: bugs    |     password: bunny (user role)
  - username: daffy   |     password: duck  (manager role)
5. You can also sign-up as a new user and customize your role to play with the application! 😊








🚀 𝑬𝒙𝒄𝒊𝒕𝒆𝒅 𝒕𝒐 𝒔𝒉𝒂𝒓𝒆 𝒎𝒚 𝒍𝒂𝒕𝒆𝒔𝒕 𝒇𝒖𝒍𝒍-𝒔𝒕𝒂𝒄𝒌 𝒑𝒓𝒐𝒋𝒆𝒄𝒕 𝒖𝒕𝒊𝒍𝒊𝒛𝒊𝒏𝒈 𝑮𝒊𝒊𝒇𝒚 𝒇𝒐𝒓 𝒔𝒕𝒓𝒆𝒂𝒎𝒍𝒊𝒏𝒆𝒅 𝒕𝒊𝒄𝒌𝒆𝒕 𝒎𝒂𝒏𝒂𝒈𝒆𝒎𝒆𝒏𝒕 𝒂𝒏𝒅 𝒅𝒆𝒑𝒍𝒐𝒚𝒎𝒆𝒏𝒕 𝒂𝒖𝒕𝒐𝒎𝒂𝒕𝒊𝒐𝒏!
🔧 𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄:

𝗧𝗶𝗰𝗸𝗲𝘁 𝗠𝗮𝗻𝗮𝗴𝗲𝗺𝗲𝗻𝘁 𝘄𝗶𝘁𝗵 𝗚𝗶𝗶𝗳𝘆: 𝗖𝗹𝗶𝗲𝗻𝘁𝘀 𝗿𝗮𝗶𝘀𝗲 𝘁𝗶𝗰𝗸𝗲𝘁𝘀 𝗳𝗼𝗿 𝘁𝗵𝗲𝗺𝗲 𝗰𝗵𝗮𝗻𝗴𝗲𝘀 𝗶𝗻 𝘁𝗵𝗲 𝗮𝗽𝗽𝗹𝗶𝗰𝗮𝘁𝗶𝗼𝗻. 𝗧𝗶𝗰𝗸𝗲𝘁𝘀 𝗮𝗿𝗲 𝗮𝘀𝘀𝗶𝗴𝗻𝗲𝗱 𝘁𝗼 𝗱𝗲𝘃𝗲𝗹𝗼𝗽𝗲𝗿𝘀 𝘃𝗶𝗮 𝗚𝗶𝗶𝗳𝘆 𝘁𝗼𝗼𝗹𝘀.

𝗗𝗲𝘃𝗲𝗹𝗼𝗽𝗺𝗲𝗻𝘁 & 𝗖𝗼𝗱𝗲 𝗠𝗮𝗻𝗮𝗴𝗲𝗺𝗲𝗻𝘁:
𝗗𝗲𝘃𝗲𝗹𝗼𝗽𝗲𝗿𝘀 𝗺𝗮𝗸𝗲 𝘁𝗵𝗲 𝗻𝗲𝗰𝗲𝘀𝘀𝗮𝗿𝘆 𝗰𝗵𝗮𝗻𝗴𝗲𝘀 𝘁𝗼 𝘁𝗵𝗲 𝗰𝗼𝗱𝗲.
𝗖𝗼𝗱𝗲 𝗶𝘀 𝗽𝘂𝘀𝗵𝗲𝗱 𝘁𝗼 𝗚𝗶𝘁𝗛𝘂𝗯.
𝗖𝗼𝗻𝘁𝗶𝗻𝘂𝗼𝘂𝘀 𝗜𝗻𝘁𝗲𝗴𝗿𝗮𝘁𝗶𝗼𝗻 𝘄𝗶𝘁𝗵 𝗝𝗲𝗻𝗸𝗶𝗻𝘀:
𝗝𝗲𝗻𝗸𝗶𝗻𝘀 𝗽𝘂𝗹𝗹𝘀 𝘁𝗵𝗲 𝗰𝗼𝗱𝗲 𝗳𝗿𝗼𝗺 𝗚𝗶𝘁𝗛𝘂𝗯.
𝗖𝗼𝗱𝗲 𝗶𝘀 𝗯𝘂𝗶𝗹𝘁 𝘂𝘀𝗶𝗻𝗴 𝗠𝗮𝘃𝗲𝗻.
𝗤𝘂𝗮𝗹𝗶𝘁𝘆 𝗔𝘀𝘀𝘂𝗿𝗮𝗻𝗰𝗲:
𝗦𝗼𝗻𝗮𝗿𝗤𝘂𝗯𝗲 𝗽𝗲𝗿𝗳𝗼𝗿𝗺𝘀 𝗾𝘂𝗮𝗹𝗶𝘁𝘆 𝗰𝗵𝗲𝗰𝗸𝘀.
𝗩𝘂𝗹𝗻𝗲𝗿𝗮𝗯𝗶𝗹𝗶𝘁𝘆 𝘀𝗰𝗮𝗻𝘀 𝗮𝗿𝗲 𝗰𝗼𝗻𝗱𝘂𝗰𝘁𝗲𝗱 𝘂𝘀𝗶𝗻𝗴 𝗧𝗿𝗶𝘃𝘆.

𝗔𝗿𝘁𝗶𝗳𝗮𝗰𝘁 𝗠𝗮𝗻𝗮𝗴𝗲𝗺𝗲𝗻𝘁:

𝗕𝘂𝗶𝗹𝘁 𝗮𝗽𝗽𝗹𝗶𝗰𝗮𝘁𝗶𝗼𝗻 𝗶𝘀 𝗽𝘂𝘀𝗵𝗲𝗱 𝘁𝗼 𝗡𝗲𝘅𝘂𝘀.
𝗗𝗼𝗰𝗸𝗲𝗿 𝗶𝗺𝗮𝗴𝗲𝘀 𝗮𝗿𝗲 𝗯𝘂𝗶𝗹𝘁 𝗮𝗻𝗱 𝘁𝗮𝗴𝗴𝗲𝗱.
𝗧𝗿𝗶𝘃𝘆 𝘀𝗰𝗮𝗻𝘀 𝘁𝗵𝗲 𝗗𝗼𝗰𝗸𝗲𝗿 𝗶𝗺𝗮𝗴𝗲𝘀.
𝗜𝗺𝗮𝗴𝗲𝘀 𝗮𝗿𝗲 𝗽𝘂𝘀𝗵𝗲𝗱 𝘁𝗼 𝗗𝗼𝗰𝗸𝗲𝗿 𝗛𝘂𝗯.

𝗗𝗲𝗽𝗹𝗼𝘆𝗺𝗲𝗻𝘁 & 𝗠𝗼𝗻𝗶𝘁𝗼𝗿𝗶𝗻𝗴:

𝗔𝗽𝗽𝗹𝗶𝗰𝗮𝘁𝗶𝗼𝗻 𝗶𝘀 𝗱𝗲𝗽𝗹𝗼𝘆𝗲𝗱 𝗶𝗻 𝗞𝘂𝗯𝗲𝗿𝗻𝗲𝘁𝗲𝘀.
𝗠𝗼𝗻𝗶𝘁𝗼𝗿𝗶𝗻𝗴 𝗶𝘀 𝗱𝗼𝗻𝗲 𝘂𝘀𝗶𝗻𝗴 𝗚𝗿𝗮𝗳𝗮𝗻𝗮.

𝗡𝗼𝘁𝗶𝗳𝗶𝗰𝗮𝘁𝗶𝗼𝗻𝘀:

𝗔𝗳𝘁𝗲𝗿 𝘁𝗵𝗲 𝗯𝘂𝗶𝗹𝗱 𝗽𝗶𝗽𝗲𝗹𝗶𝗻𝗲 𝗰𝗼𝗺𝗽𝗹𝗲𝘁𝗲𝘀, 𝘄𝗲 𝗿𝗲𝗰𝗲𝗶𝘃𝗲 𝗲𝗺𝗮𝗶𝗹 𝗻𝗼𝘁𝗶𝗳𝗶𝗰𝗮𝘁𝗶𝗼𝗻𝘀.

💻 𝗧𝗲𝗰𝗵 𝗦𝘁𝗮𝗰𝗸:

𝗚𝗶𝗶𝗳𝘆 𝗳𝗼𝗿 𝘁𝗶𝗰𝗸𝗲𝘁 𝗺𝗮𝗻𝗮𝗴𝗲𝗺𝗲𝗻𝘁
𝗚𝗶𝘁𝗛𝘂𝗯 𝗳𝗼𝗿 𝘃𝗲𝗿𝘀𝗶𝗼𝗻 𝗰𝗼𝗻𝘁𝗿𝗼𝗹
𝗝𝗲𝗻𝗸𝗶𝗻𝘀 𝗳𝗼𝗿 𝗖𝗜/𝗖𝗗
𝗠𝗮𝘃𝗲𝗻 𝗳𝗼𝗿 𝗯𝘂𝗶𝗹𝗱𝗶𝗻𝗴 𝘁𝗵𝗲 𝗰𝗼𝗱𝗲
𝗦𝗼𝗻𝗮𝗿𝗤𝘂𝗯𝗲 𝗳𝗼𝗿 𝗾𝘂𝗮𝗹𝗶𝘁𝘆 𝗰𝗵𝗲𝗰𝗸𝘀
𝗧𝗿𝗶𝘃𝘆 𝗳𝗼𝗿 𝘃𝘂𝗹𝗻𝗲𝗿𝗮𝗯𝗶𝗹𝗶𝘁𝘆 𝘀𝗰𝗮𝗻𝗻𝗶𝗻𝗴
𝗡𝗲𝘅𝘂𝘀 𝗳𝗼𝗿 𝗮𝗿𝘁𝗶𝗳𝗮𝗰𝘁 𝗺𝗮𝗻𝗮𝗴𝗲𝗺𝗲𝗻𝘁
𝗗𝗼𝗰𝗸𝗲𝗿 𝗳𝗼𝗿 𝗰𝗼𝗻𝘁𝗮𝗶𝗻𝗲𝗿𝗶𝘇𝗮𝘁𝗶𝗼𝗻
𝗗𝗼𝗰𝗸𝗲𝗿 𝗛𝘂𝗯 𝗳𝗼𝗿 𝗶𝗺𝗮𝗴𝗲 𝘀𝘁𝗼𝗿𝗮𝗴𝗲
𝗞𝘂𝗯𝗲𝗿𝗻𝗲𝘁𝗲𝘀 𝗳𝗼𝗿 𝗱𝗲𝗽𝗹𝗼𝘆𝗺𝗲𝗻𝘁

𝗚𝗿𝗮𝗳𝗮𝗻𝗮 𝗳𝗼𝗿 𝗺𝗼𝗻𝗶𝘁𝗼𝗿𝗶𝗻𝗴

𝗧𝗵𝗶𝘀 𝗽𝗿𝗼𝗷𝗲𝗰𝘁 𝗵𝗮𝘀 𝘀𝗶𝗴𝗻𝗶𝗳𝗶𝗰𝗮𝗻𝘁𝗹𝘆 𝗶𝗺𝗽𝗿𝗼𝘃𝗲𝗱 𝗼𝘂𝗿 𝘄𝗼𝗿𝗸𝗳𝗹𝗼𝘄 𝗲𝗳𝗳𝗶𝗰𝗶𝗲𝗻𝗰𝘆, 𝗲𝗻𝘀𝘂𝗿𝗶𝗻𝗴 𝘀𝗲𝗮𝗺𝗹𝗲𝘀𝘀 𝗶𝗻𝘁𝗲𝗴𝗿𝗮𝘁𝗶𝗼𝗻, 𝗰𝗼𝗻𝘁𝗶𝗻𝘂𝗼𝘂𝘀 𝗱𝗲𝗽𝗹𝗼𝘆𝗺𝗲𝗻𝘁, 𝗮𝗻𝗱 𝗿𝗼𝗯𝘂𝘀𝘁 𝗺𝗼𝗻𝗶𝘁𝗼𝗿𝗶𝗻𝗴. 𝗣𝗿𝗼𝘂𝗱 𝗼𝗳 𝘁𝗵𝗲 𝘁𝗲𝗮𝗺’𝘀
𝗲𝗳𝗳𝗼𝗿𝘁 𝗮𝗻𝗱 𝗹𝗼𝗼𝗸𝗶𝗻𝗴 𝗳𝗼𝗿𝘄𝗮𝗿𝗱 𝘁𝗼 𝗺𝗼𝗿𝗲 𝗶𝗻𝗻𝗼𝘃𝗮𝘁𝗶𝗼𝗻𝘀! 🌟




***********************************************************************************************

Full Stack all Tool Projects


   pipeline {
    agent any

    tools {
        jdk 'jdk17'
        maven 'maven3'
    }
    
    environment {
        SONARQUBE_HOME = tool 'sonar-scanner'
    }

    stages {
        stage('Git Clone') {
            steps {
                git branch: 'main', credentialsId: 'github-board-cred', url: 'https://github.com/vishal343012/BoardgameListingWebApp.git'
            }
        }
    
        stage('Compile') {
            steps {
                sh 'mvn compile'
            }
        }
        
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        
        stage('Trivy File System Scan') {
            steps {
                sh 'trivy fs --format table -o trivy-image-report.html .'
            }
        }
        
        stage('SonarQube Analysis') {
            steps {
                withSonarQubeEnv(credentialsId: 'sonar-token1', installationName: 'sonarqube-server') {
                    sh '''
                        $SONARQUBE_HOME/bin/sonar-scanner \
                        -Dsonar.projectName=Boardgame4 \
                        -Dsonar.projectKey=Boardgame4 \
                        -Dsonar.java.binaries=.
                    '''
                }
            }
        }
        
        stage('Quality Gate') {
            steps {
                waitForQualityGate abortPipeline: false
            }
        }
        
        stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
        
        stage('Publish to Nexus') {
            steps {
                withMaven(globalMavenSettingsConfig: 'maven-global2', jdk: 'jdk17', maven: 'maven3') {
                    sh 'mvn deploy'
                }
            }
        }
        
        stage('Docker Build Images') {
            steps {
                script {
                    sh 'docker build -t boardwebapp2024:latest .'
                    sh 'docker tag boardwebapp2024:latest vishal431/boardwebapp2024:latest'
                }
            }
        }
        
        stage('Docker Image Scan') {
            steps {
                sh 'trivy image --format table -o trivy-image-report.html vishal431/boardwebapp2024:latest'
            }
        }

        stage('Docker Push Images') {
            steps {
                script {
                    withDockerRegistry(credentialsId: 'dockerhub3') {
                        sh 'docker push vishal431/boardwebapp2024:latest'
                    }
                }
            }
        }
        
        stage('Deploy to Kubernetes') {
            steps {
                withKubeConfig(caCertificate: '', clusterName: 'kubernetes', contextName: '', credentialsId: 'k8-cred2', namespace: 'webapps', restrictKubeConfigAccess: false, serverUrl: 'https://172.31.13.105:6443') {
                    sh 'kubectl apply -f deployment-service.yaml'
                }
            }
        }
        
        stage('Verify Deployment') {
            steps {
                withKubeConfig(caCertificate: '', clusterName: 'kubernetes', contextName: '', credentialsId: 'k8-cred2', namespace: 'webapps', restrictKubeConfigAccess: false, serverUrl: 'https://172.31.13.105:6443') {
                    sh 'kubectl get pods -n webapps'
                    sh 'kubectl get svc -n webapps'
                }
            }
        }
    }
    post {
        always {
            script {
                def jobName = env.JOB_NAME
                def buildNumber = env.BUILD_NUMBER
                def pipelineStatus = currentBuild.result ?: 'UNKNOWN'
                def bannerColor = pipelineStatus.toUpperCase() == 'SUCCESS' ? 'green' : 'red'

                def body = """
                    <html>
                    <body>
                    <div style="border: 4px solid ${bannerColor}; padding: 10px;">
                    <h2>${jobName} - Build ${buildNumber}</h2>
                    <div style="background-color: ${bannerColor}; padding: 10px;">
                    <h3 style="color: white;">Pipeline Status: ${pipelineStatus.toUpperCase()}</h3>
                    </div>
                    <p>Check the <a href="${env.BUILD_URL}">console output</a>.</p>
                    </div>
                    </body>
                    </html>
                """

                emailext (
                    subject: "${jobName} - Build ${buildNumber} - ${pipelineStatus.toUpperCase()}",
                    body: body,
                    to: 'vishalvishwakarma107@gmail.com',
                    from: 'vishalvishwakarma107@gmail.com',
                    replyTo: 'vishalvishwakarma107@gmail.com',
                    mimeType: 'text/html',
                    attachmentsPattern: 'trivy-image-report.html'
                )
            }
        }
    }
}
********************************************************************


![all](https://github.com/user-attachments/assets/8d811eb0-44d1-43b9-8e27-0008c419c0c1)



