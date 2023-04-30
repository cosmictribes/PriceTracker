# Pricetracker OSS

## Planned features:
- Price history tracking: 
  - Display the price history of consumer goods like food products
- Price comparison between retailers:
  - Enable users to compare prices of products between different retailers to find the best deals
- Location-based best offers: 
  - Show users the best offers and deals in their area
- User login and personalized shopping cart:
  - Allow users to create an account, log in and maintain a personalized shopping cart, as well as see how much the items would have cost in the past  

## Log
### 2023-04-30
If someone's interested in what we are doing right now, look at the [Sandbox](https://github.com/cosmictribes/sandbox) repo and its branches.  
As soon as everything's ready for development, we'll push the project into the pricetracker repo.  
The sandbox repo is RnD only.  

We have experience building software in SpringBoot with Java, Angular, Maven, Jenkins and Docker.  

This time, we want to try something new.  
- Kotlin instead of Java
- NextJS instead of Angular
- Gradle instead of Maven
- Reactive data access instead of blocking threads
- Github Actions instead of Jenkins
- Kubernetes instead of Docker
- Python & GPT for scraping data we can't directly access

For testing:
- Code analysis: SonarQube
- Unit tests: Vitest instead of Jest as well as Kotlin implementations of Java testing libraries
- E2E tests: Playwright instead of Cypress

We have to rethink the structure of the project and how to implement the new techologies/dependencies.  
There is also some management overhead directly affecting the security and task/issue management of the repo and what guidelines to implement.  

  
  
![grafik](https://user-images.githubusercontent.com/123939408/234936575-a13718f4-8f63-433a-85a1-dd525c35a768.png)
