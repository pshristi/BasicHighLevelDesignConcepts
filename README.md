# High-Level Design Learning Notes 📚

A comprehensive collection of learning notes on High-Level Design (HLD) concepts and distributed systems architecture. This repository serves as a personal knowledge base documenting key concepts in system design, scalability, and distributed computing.

## 📖 About

This project is a curated collection of detailed notes created while learning from the excellent educational content on system design and high-level architecture. The notes cover fundamental concepts, design patterns, and real-world system design scenarios that are essential for building scalable and resilient systems.

## 📑 Topics Covered

### Core Concepts
1. **[Network Protocols](src/main/java/com/example/learninghld/1.%20NetworkProtocols.md)** - Understanding communication protocols and their applications
2. **[CAP Theorem](src/main/java/com/example/learninghld/2.%20CapTheorem.md)** - Consistency, Availability, and Partition tolerance trade-offs
3. **[Microservice Design Patterns](src/main/java/com/example/learninghld/3.%20MicroserviceDesignPatterns.md)** - Architectural patterns for microservices
4. **[Scale from 0 to Million Users](src/main/java/com/example/learninghld/4.%20ScaleFrom0ToMillion.md)** - Growth strategies
5. **[Consistent Hashing](src/main/java/com/example/learninghld/5.%20ConsistentHashing.md)** - Distributed data partitioning strategy
6. **[Back of the Envelope Estimation](src/main/java/com/example/learninghld/6.%20BackOfTheEnvelopEstimation.md)** - Quick system capacity calculations
7. **[SQL vs NoSQL](src/main/java/com/example/learninghld/7.%20SqlVsNoSql.md)** - Database selection and trade-offs

### System Design Components
8. **[Rate Limiter Design](src/main/java/com/example/learninghld/8.%20DesignARateLimiter.md)** - Controlling request rates
9. **[Video Calling HLD](src/main/java/com/example/learninghld/9.%20VideoCallingHLD.md)** - Real-time communication system design
10. **[Idempotency Handler](src/main/java/com/example/learninghld/10.%20DesignIndempotencyHandler.md)** - Ensuring safe retry mechanisms
11. **[High Availability and Resilience Systems](src/main/java/com/example/learninghld/11.%20DesignHighAvailabilityAndResilenceSystem.md)** - Building fault-tolerant systems
12. **[Distributed Messaging Queue](src/main/java/com/example/learninghld/12.%20DistributedMessagingQueue.md)** - Asynchronous communication patterns
13. **[Proxy vs Reverse Proxy](src/main/java/com/example/learninghld/13.%20ProxyVsReverseProxy.md)** - Network intermediaries
14. **[Load Balancer](src/main/java/com/example/learninghld/14.%20LoadBalancer.md)** - Traffic distribution strategies
15. **[Distributed Cache](src/main/java/com/example/learninghld/15.%20DistributedCache.md)** - Caching strategies for distributed systems
16. **[Distributed Transactions](src/main/java/com/example/learninghld/16.%20DistributedTransaction.md)** - Managing transactions across services
17. **[Database Indexing](src/main/java/com/example/learninghld/17.%20DatabaseIndexing.md)** - Performance optimization strategies
18. **[Concurrency Control in Distributed Systems](src/main/java/com/example/learninghld/18.%20ConcurrencyControlDistributedSystem.md)** - Managing concurrent operations
19. **[Two-Phase Locking](src/main/java/com/example/learninghld/19.%20TwoPhaseLockingForPessimisticConcurrencyControl.md)** - Pessimistic concurrency control

### Security & Communication
20. **[OAuth 2.0](src/main/java/com/example/learninghld/20.%20OAuth2.0.md)** - Authorization framework
21. **[Symmetric & Asymmetric Encryption](src/main/java/com/example/learninghld/21.%20%20SymmetricAsymmetricEncryption.md)** - Cryptographic approaches
22. **[JWT (JSON Web Tokens)](src/main/java/com/example/learninghld/22.%20JWT.md)** - Stateless authentication
23. **[Thundering Herd Effect](src/main/java/com/example/learninghld/23.%20ThunderingHerdEffect.md)** - Handling cache stampede scenarios
24. **[API Gateway](src/main/java/com/example/learninghld/24.%20APIGateway.md)** - Entry point for microservices architecture
25. **[Service Mesh and Its Architecture](src/main/java/com/example/learninghld/25.%20ServiceMeshAndItsArchitecture.md)** - Infrastructure layer for service-to-service communication
26. **[DNS](src/main/java/com/example/learninghld/26.%20DNS.md)** - Domain Name System architecture

## 🗂️ Repository Structure

```
src/main/java/com/example/learninghld/
├── 1. NetworkProtocols.md
├── 2. CapTheorem.md
├── 3. MicroserviceDesignPatterns.md
├── 4. ScaleFrom0ToMillion.md
├── 5. ConsistentHashing.md
├── 6. BackOfTheEnvelopEstimation.md
├── 7. SqlVsNoSql.md
├── 8. DesignARateLimiter.md
├── 9. VideoCallingHLD.md
├── 10. DesignIndempotencyHandler.md
├── 11. DesignHighAvailabilityAndResilenceSystem.md
├── 12. DistributedMessagingQueue.md
├── 13. ProxyVsReverseProxy.md
├── 14. LoadBalancer.md
├── 15. DistributedCache.md
├── 16. DistributedTransaction.md
├── 17. DatabaseIndexing.md
├── 18. ConcurrencyControlDistributedSystem.md
├── 19. TwoPhaseLockingForPessimisticConcurrencyControl.md
├── 20. OAuth2.0.md
├── 21. SymmetricAsymmetricEncryption.md
├── 22. JWT.md
├── 23. ThunderingHerdEffect.md
├── 24. APIGateway.md
├── 25. ServiceMeshAndItsArchitecture.md
└── 26. DNS.md

src/main/resources/
└── [Supporting images and diagrams]
```

## 🎯 Key Features

- **Comprehensive Coverage**: 26+ topics covering essential HLD concepts
- **Real-world Examples**: Practical applications and use cases
- **Visual Aids**: Screenshots and diagrams for better understanding
- **Structured Learning**: Topics organized in a logical progression
- **Interview Ready**: Content aligned with common system design interview topics

## 📝 How to Use

Each markdown file contains:
- **Conceptual Overview**: Clear explanations of the topic
- **Real-world Analogies**: Relatable examples for better understanding
- **Technical Details**: In-depth technical information
- **Use Cases**: When and where to apply the concepts
- **Key Takeaways**: Summary of important points

Feel free to read the topics in any order, though the numbered sequence provides a logical learning path.

## 🙏 Acknowledgments

This repository is based on learning materials from **[Concept && Coding - by Shreyans](https://www.youtube.com/@ConceptAndCodingByShrayansh)** YouTube channel. All diagrams and screenshots used in these notes are sourced from the channel's educational content.

Special thanks to **Shreyans Jain** for creating exceptional content that makes complex system design concepts accessible and understandable. His clear teaching style and practical approach have been instrumental in building this knowledge base.

### Recommended Resources
- 📺 [Concept && Coding YouTube Channel](https://www.youtube.com/@ConceptAndCodingByShrayansh)
- 🔗 Subscribe for more system design and coding content

## 💡 Contributing

While this is a personal learning repository, suggestions and corrections are welcome! Feel free to:
- Open an issue for any errors or improvements
- Submit a pull request with corrections
- Share additional resources or insights

## 📄 License

This project is for educational purposes only. All original content from Concept && Coding belongs to the respective creator. These notes are personal summaries and interpretations of the learning material.

## 🔗 Connect

If you find these notes helpful, feel free to star ⭐ the repository!

---

## 👤 Maintainer

**Shristi Pathak**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://linkedin.com/in/shristi-pathak)

---

### 📚 Additional Notes

- This is a living document that will be updated as new concepts are learned
- Topics are continuously refined and expanded
- Feedback and discussions are always welcome

**Happy Learning! 🎓**

