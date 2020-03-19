# Work in progress!

# Deciding on a fit for purpose a programming language
Opinionated Programming Language Decision Tree.

# Prerequisites
Micros service architecture (service mesh) that allows polyglot languages. PWA or SPA and backend for front-end.

- [Security architecture](https://github.com/davidpetter/security-architecture)
- [API Integration architecture]()
- [Application architecture]()

## Shortlist
List of considered/evaluated languages
- C# / .NET (Core)
- Clojure
- Elixir
- Erlang
- Go
- Groovy
- JavaScript
- Kotlin
- C++
- Dart
- Java
- Node.js
- Objective-C
- PHP
- Python
- Ruby
- Rust
- Scala
- Swift
- TypeScript

# Decision tree
## Backend
 ### Go
 Default choice for a general purpose solution that is self written (no framework etc). 
 Write stable and efficient code that performs a limited task.
 
 Good fit
 - Strict harware requirements
 - High security requirements
 - Small
 
 Bad fit
 - Large implementations (monolithical)
 - Dependency mmanagement and libraries
 
 ### Java/Kotlin/Scala
 General purpose solution that often related to integration or security. 
 
 Usage:
 Messaging, web application, highly concurrent application
 
 
 Good fit:
 - For the purpose of libraries and ecosystem.
 - A good fit for medium to large size implementations that doesn't have strict resource constraints.
 - Security, Maths, BI
 
 Bad fit:
 - Strict hardware requirements
 - IO operations
 - Memory requirements (Managing images etc)
 - Small sytem and want to avoid boilerplate


 ### Javascript/Node.js
 
 Highly useful when scalable and faster application is required. More suited for an application like real-time collaborative.
 
 Good fit
 - Prototyping
 - For the purpose of libraries and ecosystem
 - A good fit for small single threaded tasks
 - Transformation support
 - Want to have same language for backend and frontend 
 - Want to optimize for IO
 
 Bad fit
 - Concurrency and multi threading
 - Large implementations (monolithical)
 - Want to optimize for CPU

### C# (.net core)

 Good fit
   - When there is a fit in echosystem (like Service fabric etc.)
   - Small to large implementations
   - Want to use MVC for frontend.
  
  Bad fit
    - Echosystem and libraries (getting better).
    - Small sytem and want to avoid boilerplate

 ### Python
 
 Good fit
   - Maths, BI and AI. Optimise for IO
   - Scripting
   - Prototyping
   - For the purpose of libraries and ecosystem
 Bad fit
   -
    
## Frontend/client
 - Browser
   - Javascript
   - TypeScript
 - Mobile (when native is needed)
   Native is good when you want to differentiate and want to have the latest that the plattform can )
   - Swift
   - Kotlin
