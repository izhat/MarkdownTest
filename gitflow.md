# GitFlow 
[Back to Etiquette](etiquette.md)

## Warning - Do not use!
GitFlow introduces **rigid branching patterns** that can **slow down** modern CI/CD workflows, making it less ideal for fast-paced teams embracing trunk-based development or continuous deployment.

Here's a example of GitFlow

```mermaid
graph TD
    A[main] --> B[develop]
    B --> C[feature/login]
    C --> B
    B --> D[feature/payment]
    D --> B
    B --> E[release/1.0.0]
    E --> F[hotfix/login-bug]
    F --> E
    E --> A
    E --> B
    A --> G[tag v1.0.0]

# Trunk branching 
[Back to Etiquette](Etiquette.md)


Speak with Jingwa about this, Jingwa is an expert:

<img src="https://static.vecteezy.com/system/resources/previews/046/028/343/non_2x/an-elephant-with-big-tusks-standing-on-a-transparent-background-free-png.png">
