# Interview Notes
## Interview questions and answers

- Object-oriented programming(OOPS)
- OOPS
- Abstraction
- Encapsulation
- Polymorphism
- Abstract Class
- Does Abstract class have constructor?
- Abstract class Vs Interface
- What to choose – interface or abstract class
- Why Java 8 has introduced default methods?
- Why Java 8 has introduced static methods?
- Why Java does not allow multiple inheritance?
- Method Overloading and Overriding
    - Method Overloading
    - Rules for Method Overloading
    - Method Overriding
    - Rules for Method Overriding
- Association
- Aggregation
- Composition
- Association vs. Aggregation vs. Composition

# Java
- Basic

    - Java 8
        - Java 8 Features
        - New features
        - Lambda Expressions
        - Lambda Expressions
            - Examples of lambda expressions
            - Why use Lambda Expression
            - Lambda Expressions Syntax
            - Lambda Expressions Examples
        - Stream
            - Stream features
        - Intermediate and Terminal operations
            - Intermediate vs Terminal operations
            - Intermediate Operations
            - Terminal Operations
        - Functional Interface
            - Custom Functional Interface
            - Predefined Functional Interfaces
            - Predicate
            - Function
            - Supplier
            - Consumer
            - BiFunction
            - BiConsumer
        - Method References
            - Method References Types
        - Test

        - Why String is Immutable?
        - StringBuffer and StringBuilder
        - equals and hashcode contract
        - Comparable and Comparator interfaces
            - Comparable vs Comparator
        - static keyword
        - Shallow Copy and Deep Copy
        - Serialization and De-serialization
        - Serialization scenarios with Inheritance
        - How to make a class Immutable?
        - Class loaders in Java
        - Garbage Collector
            - How does the garbage collector work?
            - Types of garbage collectors
            - Garbage Collection and types of Garbage Collectors
            - final, finally and finalize()
        - String, StringBuffer, StringBuilder
        - Reflection
        - Exceptions
            - Checked and Unchecked Exception
            - Custom exception
            - OutOfMemoryError
        - Generics
            - Benefits of Generics
            - Collection Framework examples for Generics.
            - Type Parameter Naming Conventions
            - Multiple Type Parameters
        - Immutable object
            - Benefits of immutable objects
            - Immutable Class
            - Wrong way to write an immutable class
            - Right way to write an immutable class
        - Pass by reference and Pass by value
        - Shallow cloning and Deep cloning
        - Instance variable and a Static variable
        - Local variables vs Instance and static variables
        - Access Modifiers
        - Volatile keyword
        - synchronized vs volatile
        - Test
    - Collection Framework

        - ArrayList
            - Accessing elements
            - Removing elements
            - Iterating over an ArrayList
            - Searching for elements in an ArrayList
            - Sorting an ArrayList
        - HashMap
            - HashMap Internal working
            - Sort Map By Value Example
            - How put() method of HashMap works internally
            - How HashMap get() method works internally
            - When null Key is inserted in a HashMap
            - HashMap implementation changes in Java 8
            - Interal working of put() and get() methods of HashMap
            - HashMap collisions
        - equals and hashCode method in HashMap when the key is a custom class
        - Concurrent HashMap
            - ConcurrentHashMap vs Synchronized HashMap
        - HashSet class
        - TreeMap
        - TreeSet
        - fail-safe and fail-fast iterators
    - Multi threading

        - Life Cycle of a Thread
        - Creating a Thread
        - Life Cycle of a Thread
        - Creating a Thread
        - Difference between Runnable vs Thread
        - synchronized keyword
        - static synchronization
        - What does join() method?
        - Deadlock
        - How to avoid deadlock?
        - What will happen if I directly call the run() method and not the start() method to execute a thread?
        - Once a thread has been started can it be started again?
        - Why wait, notify and notifyAll methods are defined in the Object class instead of Thread class?
        - Why wait(), notify(), notifyAll() methods must be called from synchronized block?
        - wait() vs sleep() methods
        - Executor Framework
            - High level concurrency features Executor framework
            - Executor Interface
            - ExecutorService Interface
            - ExecutorService Interface Examples
            - Different Between execute() and submit() Methods
            - ScheduledExecutorService Interface
            - Future Interface
            - Executor Framework-2
# Data Structures and Algorithms
- Lists
    - ArrayList
    - LinkedList
    - Stack
    - Vector
    - CopyOnWriteArrayList
    - Collections.synchronizedList
    - Sets
     
- HashSet
    - LinkedHashSet
    - TreeSet
    - ConcurrentSkipListSet
    - CopyOnWriteArraySet
    - EnumSet
- Maps
    - HashMap
    - HashMap implementation details
    - LinkedHashMap
    - Hashtable
    - ConcurrentHashMap
    - TreeMap
    - ConcurrentSkipListMap
- Queues 
    - LinkedList
    - ArrayBlockingQueue
    - LinkedBlockingQueue
    - ConcurrentLinkedQueue
    - Deque classes
    - PriorityQueue
    - PriorityBlockingQueue
    - DelayQueue
    - SynchronousQueue
- equals and hashCode
- Hierarchy and classes
- Frequently asked
    - Stack
    - CustomStack
    - LinkedListStack
    - LinkedListReversal
    - MyLinkedList
    - PrimesPrimeChecker
    - RemoveDuplicateFromString
    - Palindrome
    - FindLargestThree
    - FibonacciSeries
    - BalancedBracketsUsingString
    - BalancedBracketsUsingDeque
    - Anagram
- Problem analysis
- Code implementation (sorting)
- Code implementation (hash)
- Anagrams
- 
- Anagrams
- ValidAnagram
- PrintAnagramTogether
- AnagramOfFirstAsSubstring
- GroupAnagramsTogether
- Find the median of two positively ordered arrays
- 
- What is the median of an array
- Problem analysis
- Code
- Code (Brute Force approach)
- Subarray Sum Equals K
- 
- Problem analysis
- Code - Optimization by Hashmap
- Code - Brute Force approach
- Data Types
- 
- System-defined data types (Primitive data types)
- User defined data types
- Data Structures
- 
- Linear data structures
- 
- Non – linear data structures
- 
- Commonly Used Rates of Growth
- 
- Arrays
- 
- Advantages of Arrays
- Disadvantages of Arrays
- Dynamic Arrays
- Linked List
- 
- Advantages of Linked List
- Disadvantages of Linked List
- Comparison of Linked Lists with Arrays & Dynamic Arrays
- Test
- Sorting
- 
- Bubble Sort
- Implementation
- Performance
- Selection Sort
- Implementation
- Performance
- Insertion Sort
- Advantages
- Algorithm
- Implementation
- Example
- Analysis
- Performance
- Comparisons to Other Sorting Algorithms
- Shell Sort
- Implementation
- Performance
- Merge Sort
- Implementation
- Performance
- Heap Sort
- Implementation
- Performance
- Quicksort
- Implementation
- Performance
- Tree Sort
- Implementation
- Performance
- Comparison of Sorting Algorithms
- Test
- Test
- Test
- Test
- Test
- Spring
- Spring
- Dependency Injection
- Types of Dependency Injection
- Constructor-based DI
- Setter-method injection
- Constructor Vs Setter injection
- BeanFactory and ApplicationContext
- Spring Bean life-cycle
- Spring Bean Scopes
- What happens when we inject a prototype scope bean in a singleton scope bean?
- How to inject a prototype scope bean in a singleton scope bean?
- Stereotype Annotations
- @Controller vs @RestController annotation
- @Qualifier annotation
- @Transactional annotation
- @ControllerAdvice annotation
- @Bean annotation
- @Component vs @Bean annotation
- Spring Boot Security using OAuth2 with JWT
- OAuth2 Terminology
- Json Web Token(JWT)
- Spring Boot Rest Authentication with JWT Token Flow
- Web server vs application server
- Spring Transaction Management
- Global Transactions
- Local Transactions
- Programmatic Approach:
- Declarative Approach (@Transactional)
- propagation
- isolation
- readOnly
- timeout
- Spring Annotations
- @Autowired
- @Inject vs @Autowired
- Component Scanning
- @ComponentScan
- @ComponentScan Without Arguments
- @ComponentScan With Arguments
- @ComponentScan with Exclusions
- @ComponentScan in a Spring-Boot application
- Difference between @Component, @Repository & @Service annotations?
- @Repository
- @Service
- @Controller
- Test
- Spring MVC
- Spring MVC
- Spring MVC flow
- Spring Web Annotations
- @RequestMapping
- @RequestBody
- @PathVariable
- @RequestParam
- @ResponseBody
- @ExceptionHandler
- @ResponseStatus
- @Controller
- @RestController
- @ModelAttribute
- @CrossOrigin
- Scheduler in cluster environment or run on multiple instances
- Spring Scheduled Task running in clustered environment with ShedLock
- Configuration
- Creating Tasks
- Spring
- Execute a Quartz Job only once in a multi-instance environment
- Spring Boot
- Spring Boot
- Spring Boot Primary Goals
- Running Spring boot app at different port on server startup
- Key Spring Boot features
- Spring Boot Starters
- Spring Boot Autoconfiguration
- Easy-to-Use Embedded Servlet Container Support
- Spring Boot Annotations
- @SpringBootApplication
- @EnableAutoConfiguration
- @ConditionalOnClass and @ConditionalOnMissingClass
- @ConditionalOnBean and @ConditionalOnMissingBean
- @ConditionalOnProperty
- @ConditionalOnResource
- @ConditionalOnWebApplication and @ConditionalOnNotWebApplication
- @ConditionalExpression
- @Conditional
- Spring Boot Actuator
- pring-boot-actuator maven dependency
- Predefined Endpoints
- /info Endpoint
- /metrics Endpoint
- Custom Endpoint
- Building an Application with Spring Boot
- Starting with Spring Initializer
- Create a Simple Web Application
- Create an Application class
- Run the Application
- Add Unit Tests
- Add Production-grade Services
- Spring Boot CRUD Web Application with Thymeleaf, Spring MVC, Spring Data JPA, Hibernate, MySQL
- Create Spring Boot Project
- Maven Dependencies
- Configure and Setup MySQL Database
- Model Layer - Create JPA Entity
- Repository Layer
- Service Layer
- Controller Layer
- View Layer: Thymeleaf
- Run Spring application and demo
- Unit Testing REST APIs
- CrudRepository vs. JpaRepository
- Spring AOP(Aspect Oriented Programming)
- Spring AOP(Aspect Oriented Programming)
- HTTP methods overview
- HTTP methods overview
- Idempotency in HTTP
- Safe Methods
- Why DELETE method is defined as idempotent
- Why PATCH method is not idempotent
- Why is PUT idempotent?
- HTTP Status Codes
- HTTP Status Codes
- 1×× Informational
- 
- 2×× Success
- 
- 200 OK
- 201 Created
- 202 Accepted
- 204 No Content
- 205 Reset Content
- 3×× Redirection
- 
- 300 Multiple Choices
- 4×× Client Error
- 
- 5×× Server Errorl
- 
- Hibernate
- Hibernate
- JPA vs Hibernate
- @Entity annotation
- @Id & @GeneratedValue
- get() and load() methods of Hibernate Session
- Session and SessionFactory
- First Level and Second Level Cache
- Test
- Angular
- Single-page application(SPA) vs. Multiple-page application(MPA)
- Single-page application(SPA)
- Pros of the Single-Page Application
- Cons of the Single-Page Application
- Multiple-page application(MPA)
- Pros of the Multiple-Page Application
- Cons of the multiple-page application
- Angular
- AngularJS vs Angular
- AngularJS
- Angular
- Why Angular
- Components
- Templates
- Dependency injection
- Angular Routing and Navigation
- Angular Module
- Bootstrapping Module
- JIT vs AOT compilation
- Advantages of AOT
- What are the ways to control AOT compilation?
- How to optimize loading large data in angular?
- How an Angular application gets started or loaded?
- Angular Services
- What is Interpolation
- Angular Routing and Navigation
- Angular Component
- What Is an Angular Component?
- Template
- Class
- Component Metadata
- Communication Between Components
- Parent to Child
- Child to Parent
- Child to Parent
- Unrelated Components
- Angular Directive
- Components Directives
- Structural Directives
- Attribute Directives
- How to Create Custom Directives?
- Structural Directive vs Attribute Directive
- Component vs Directive
- Angular Pipes
- Syntax to use Pipes in Angular Application
- Types of Pipes in Angular
- 1. Built-in Pipes
- 2.Custom Pipes
- Parameterized Pipe
- Custom Pipe
- Pure vs Impure Pipe
- Angular Data Binding
- 1. Interpolation
- 2. Property binding
- 3. Event binding
- 4. Two-way data binding
- Angular Lazy Loading
- Angular Lifecycle Hooks
- ngOnChanges
- ngOnInit
- ngDoCheck
- ngAfterContentInit
- ngAfterContentChecked
- ngAfterViewInit
- ngAfterViewChecked
- ngOnDestroy
- constructor() vs ngOnInit()
- RxJS
- Utility functions provided by RxJS
- RxJS Operator
- What is subscribing
- Observable
- Observer
- Error handling in observables
- Observable creation functions
- What will happen if you do not supply handler for observer?
- Promise vs Observable
- Async Pipe
- HttpClient
- Error handling
- Design Patterns
- Design Patterns
- Creational Design Patterns
- Simple Factory
- Factory Method
- Abstract Factory
- Builder
- Prototype
- Singleton
- singleton class vs a static class
- Structural Design Patterns
- Adapter
- Bridge
- Composite
- Decorator
- Facade
- Flyweight
- Proxy
- Behavioral Design Patterns
- Chain of Responsibility
- Command
- Iterator
- Mediator
- Memento
- Observer
- Visitor
- Strategy
- State
- Template Method
- Designing a Java/J2EE application
- 
- Create a tiered architecture
- Create a data model
- Create a design model
- Design considerations when decomposing business use cases into relevant classes
- Vertical slicing
- Ensure the system is configurable
- Design considerations during design, development and deployment phases
- Identifying performance and/or memory issues in your Java/J2EE application
- 
- Microservices
- Microservices
- SOA(Service-oriented architecture) vs Microservices
- 
- Advantages of Microservices Architecture
- 
- Disadvantages of Microservices
- 
- Challenges of Microservices Architecture
- 
- Gateway
- 
- Microservices Monitor
- 
- Microservices vs Monolithic Architecture
- 
- How does Microservice Architecture work?
- 
- Communicating Between Microservices
- 
- SOAP vs REST
- 
- Eureka Naming Server
- 
- Zuul
- 
- Zipkin
- 
- Versioning of microservices
- 
- How to send custom business errors or exceptions from a RESTful microservice to client application?
- 
- What are best practices for microservices architecture?
- 
- Microservices caching
- 
- SOLID (solid design principles)
- 
- How frequent a microservice be released into production?
- 
- How to achieve zero-downtime during the deployments?
- 
- Blue-green deployment
- How to slowly move users from older version of application to newer version?
- 
- How will you monitor fleet of microservices in production?
- 
- How will you troubleshoot a failed API request that is spread across multiple services?
- 
- What are different layers of a single microservice?
- 
- Spring Cloud
- 
- application.yml vs bootstrap.yml
- 
- Netflix Eureka Server : implement service discovery in microservices architecture
- 
- Netflix Eureka Server
- Consul Server
- How does Eureka Server work?
- Externalize configuration in a distributed system
- 
- @RefreshScope : Refresh configuration changes on the fly in Spring Cloud environment
- 
- Achieve client side load balancing in Spring Microservices using Spring Cloud
- 
- client side load-balancer Ribbon in your microservices architecture
- 
- Use both LoadBalanced as well as normal RestTemplate object in the single microservice
- 
- Use of Eureka for service discovery in Ribbon Load Balancer
- 
- Managing transactions
- 
- ACID Transactions
- What is a distributed transaction?
- Two-phase commit (2pc) pattern
- Benefits of using 2pc
- Disadvantages of using 2pc
- Saga pattern
- Advantages of the Saga pattern
- Disadvantages of the Saga pattern
- Test
- Test
- Security in Microservices
- 
- Why Basic Authentication is not suitable in Microservices Context?
- Why OAuth2?
- OAuth2 Roles
- OAuth 2.0 grant types (OAuth flows)
- When shall I use resource owner credentials?
- When shall I use Authorization Code grant?
- When shall I use client credentials?
- OAuth2 and Microservices
- What is JWT?
- What are use cases for JWT?
- How does JWT looks like?
- What is AccessToken and RefreshToken?
- How to use a RefreshToken to request a new AccessToken?
- How to call the protected resource using AccessToken?
- Can a refreshToken be never expiring? How to make refreshToken life long valid?
- Generate AccessToken for Client Credentials.
- Why there is no RefreshToken support in Oauth2 Client Credentials workflow?
- Security in inter-service communication
- API Gateway
- API Gateway
- How to retry failed requests at some other available instance using Client Side Load Balancer?
- Circuit Breaker
- What is difference between using a Circuit Breaker and a naive approach where we try/catch a remote method call and protect for failures?
- Circuit Breaker Pattern
- Open, Closed and Half-Open states of Circuit Breaker
- Use-cases for Circuit Breaker Pattern
- Benefits of using Circuit Breaker Pattern
- What is Hystrix?
- Features of Hystrix library
- How to use Hystrix for fallback execution?
- When not to use Hystrix fallback on a particular microservice?
- ignore certain exceptions in Hystrix fallback execution
- Request Collapsing feature in Hystrix
- Circuit Breaker vs Hystrix
- Where exactly should I use Circuit Breaker Pattern?
- Where it should not be used?
- Kafka
- Kafka
- Advantages of Kafka
- Offset in Kafka
- Consumer group in Kafka
- ZooKeeper in Kafka
- Can I use Kafka without Zookeeper?
- What is Zookeeper in Kafka? Can we use Kafka without Zookeeper?
- Partition in Kafka
- APIs of Kafka
- Load balancing of the server in Kafka
- Retention period in Kafka cluster
- RabbitMQ vs Apache Kafka
- Explain Apache Kafka Use Cases?
- Kafka Cluster, and its key benefits
- Replicas in Kafka
- Starting a Kafka server
- In the Producer, when does QueueFullException occur?
- Confluent Kafka vs. Apache Kafka
- MongoDB
- MongoDB
- Key Components
- Document
- Collection
- Namespace
- Databases in MongoDB
- Mongo Shell
- Advantages of MongoDB:
- Features of MongoDB
- Indexes in MongoDB
- MongoDB
- Database
- Database
- 
- SQL
- 
- Joins
- 
- Inner join
- Left outer join
- Right outer join
- Full join
- Cross join
- Self Join
- Keys
- 
- Indexes
- 
- Non-clustered index
- Clustered index
- Composite index
- Cardinality
- Bitmap-index
- Data structures used
- SQL - Indexes
- The CREATE INDEX Command
- Unique Indexes
- Composite Indexes
- Implicit Indexes
- The DROP INDEX Command
- When should indexes be avoided?
- Queries
- 
- SQL vs NoSQL
- 
- SQL
- NoSQL
- SQL vs NoSQL
- Database Types
- Schema
- Data Model
- Ability to Scale
- ACID vs BASE
- Use Cases
- Reasons to use an SQL database
- Reasons to use a NoSQL database
- UNION vs UNION ALL
- 
- TRUNCATE vs DELETE, vs DROP
- 
- TRUNCATE
- 
- DELETE
- 
- DROP
- 
- Frequently asked queries
- Find all departments with sales more than 1000
- Print all employee ids with their manager ids
- Print all manager names with count of directs
- Find Nth highest salary in SQL - Oracle, MSSQL and MySQL -Nth maximum salary in MySQL using LIMIT keyword -2nd highest salary in MySQL without subquery -3rd highest salary in MySQL using LIMIT clause -Test -Test -Test -Test
- Maven
- Maven
- pom.xml
- Maven build life-cycle
- validate
- compile
- test
- package
- verify
- install
- deploy
- Unix
- Unix
- Find
- Search
- Processes
- File permissions
- List files
- Symlinks
- Checking logs
- Text manipulation
- Sed
- Networking
- Space
- Miscellaneous
- DevOps Tools
- Docker
- Git
- Advantages of git
- git push
- git pull vs git fetch
- conflict
- resolve a conflict
- git clone
- git pull origin
- git commit a
- Jenkins
- Continuous delivery
- Kubernetes
- Swagger
- Swagger
- Integrate Swagger into your microservices
- Swagger annotations
- @Api
- @ApiOperation
- @ApiResponse
- @ApiParam
- Maven plugin
- Cucumber
- Cucumber
- Advantages of Cucumber
- Example
- Features in Cucumber
- Feature file
- Step Definition
- Gherkin
- user login feature Example
- Test harness in Cucumber
- Selenium vs Cucumber
- TDD(Test-Driven Development)
- BDD and TDD
- Cucumber profiles
- Scenario Outline
- Scenario and Scenario Outline
- Step Definition
- Background in a Feature file
- Junit Test runner class
- Tags in cucumber-bdd
- Cucumber Hooks
- Name any two testing framework that can be integrated with Cucumber?
- What are the two files required to run a cucumber test?
- Examples Table or Scenario Outline vs Data Table
- Agile
- Agile Scrum Ceremonies
- Sprint Planning
- Daily Scrum
- Sprint Review
- Sprint Retrospective
- Amazon Web Services (AWS)
- AWS
- 
- Key components of AWS
- 
- Elastic Cloud Compute (EC2)
- 
- Simple Storage Service (S3)
- 
- Objects and Buckets
- S3 Storage Classes
- Durability and Availability
- Storage Classes for Frequently Accessed Objects
- Storage Classes for Infrequently Accessed Objects
- Storage Class for Both Frequently and Infrequently Accessed Objects
- Access Permissions
- Bucket Policies
- User Policies
- Bucket and Object Access Control Lists
- Encryption
- Versioning
- Relational Database Service (RDS)
- 
- Database Engines
- Licensing
- Instance Classes
- Standard
- Memory Optimized
- Burstable Performance
- Scaling Vertically
- Storage
- General-Purpose SSD
- Provisioned IOPS SSD
- Magnetic
- Scaling Horizontally with Read Replicas
- High Availability with Multi-AZ
- Backup and Recovery
- Route 53
- 
- CloudWatch
- 
- CloudWatch Metrics
- CloudWatch Alarms
- CloudWatch Dashboards
- CloudWatch Logs
- Metric Filters
- CloudWatch Events
- CloudTrail
- 
- API and Non-API Events
- Management and Data Events
- Event History
- Trails
- Log File Integrity Validation
- Cost Explorer
- 
- Cost and Usage
- Reservation reports
- Reserved Instances Utilization
- Reserved Instances Coverage
- Reserved instance recommendations
- Amazon DynamoDB
- 
- Items and Tables
- Scaling Horizontally
- Queries and Scans
- AWS Lambda
- 
- Introducing AWS Lambda
- Key benefits of serverless computing
- No ware to manage:
- Faster execution time:
- Really low costs:
- Support of popular programming languages:
- Microservices compatible:
- Event-driven applications:
- Cons or Disadvantage of serverless computing
- Execution duration:
- Complexity:
- Lack of tools
- Vendor lock-in:
- Test
- Test
- Test
- Good Practices
- Good Practices for REST API Design
- Accept and respond with JSON
- Use nouns instead of verbs in endpoint paths
- Nesting resources for hierarchical objects
- Handle errors gracefully and return standard error codes
- Allow filtering, sorting, and pagination
- Maintain Good Security Practices
- Cache data to improve performance
- Versioning our APIs
- Java code review checklist
- Basic Checks (before)
- The code was tested
- Clean Code
- Best Practices
- Exception Handling
- Common Java Vulnerabilities
- Injection Flaws
- Cross Site Scripting (XSS)
- How does XSS work?
- Cross Site Request Forgery(CSRF)
- Test
- Resolving a Production Issue on a Live Server
- Notify All Stakeholders
- Reproduce : Replicate the production environment locally
- Root Cause Analysis & Fix
- Re-test & Regression Testing
- Backup the System Before Implementing Complex Solution
- Document the Problem and How it was Resolved