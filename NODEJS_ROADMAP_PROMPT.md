# PROMPT: XÂY DỰNG LỘ TRÌNH HỌC NODE.JS BACKEND DEVELOPER

## ROLE

Bạn là Senior Backend Engineer / Node.js Architect có ít nhất 10 năm kinh nghiệm phát triển hệ thống Backend trong môi trường Production.

Bạn có kinh nghiệm chuyên sâu về:

- Node.js, JavaScript, TypeScript.
- Express.js, NestJS, Fastify.
- RESTful API, GraphQL.
- PostgreSQL, MongoDB, Redis.
- Authentication, Authorization, Security.
- System Design, Microservices, Event-driven Architecture.
- Docker, CI/CD, Cloud Deployment.
- Testing, Monitoring, Logging và Performance Optimization.

Bạn đồng thời là Technical Mentor có kinh nghiệm đào tạo Frontend Developer chuyển hướng sang Backend Developer.

## 1. MỤC TIÊU

Hãy xây dựng một lộ trình học Node.js thật chi tiết và đầy đủ, từ nền tảng đến trình độ có thể tự thiết kế, phát triển, triển khai và bảo trì một Backend Application trong môi trường Production.

**Đối tượng học:**

- Có khoảng 3 năm kinh nghiệm Frontend Developer.
- Đã có kiến thức JavaScript, TypeScript, ReactJS và NextJS.
- Đã từng làm việc với API, Next.js API Routes và một số thao tác Backend cơ bản.
- Muốn phát triển thành Fullstack Developer, có nền tảng Backend vững chắc.
- Mục tiêu cuối cùng là có thể ứng tuyển vị trí Middle Node.js Backend Developer.

Không cần dành quá nhiều thời gian giải thích những kiến thức JavaScript cơ bản đã biết. Hãy tập trung vào tư duy Backend, kiến thức chuyên sâu của Node.js và những vấn đề thường gặp trong dự án thực tế.

## 2. YÊU CẦU ĐẦU RA

Tạo một file Markdown duy nhất có tên:

`ROADMAP.md`

File phải có cấu trúc chuyên nghiệp, dễ đọc, dễ cập nhật và sử dụng làm tài liệu học tập dài hạn.

- Ngôn ngữ trình bày: Tiếng Việt.
- Thuật ngữ kỹ thuật giữ nguyên tiếng Anh và giải thích bằng tiếng Việt.
- Sử dụng heading phân cấp rõ ràng.
- Có Table of Contents.
- Dùng checklist để theo dõi tiến độ.
- Có code block với syntax highlighting.
- Dùng bảng so sánh khi cần thiết.
- Dùng Mermaid diagram cho kiến trúc, luồng xử lý hoặc các chủ đề phù hợp.

Không chỉ trả về outline. Hãy tạo tài liệu học tập có thể sử dụng trực tiếp.

## 3. CẤU TRÚC ROADMAP

Chia lộ trình thành nhiều **PHASE** và **CHAPTER**.

Mỗi Chapter tương ứng với một Git branch riêng. Ví dụ:

- Phase 01 - Node.js Fundamentals
  - Chapter 01: Node.js Architecture
  - Chapter 02: Event Loop
  - Chapter 03: Asynchronous Programming
- Phase 02 - Backend Development
  - Chapter 04: HTTP & REST API
  - Chapter 05: Express.js
  - Chapter 06: Middleware & Error Handling

Tiếp tục phát triển cho đến khi bao phủ các kiến thức cần thiết để làm việc với Node.js trong môi trường Production. Không giới hạn số lượng Chapter nếu cần thiết để đảm bảo tính đầy đủ.

Sắp xếp kiến thức theo thứ tự tiên quyết: nền tảng trước, ứng dụng sau, nâng cao và System Design ở giai đoạn cuối. Tránh trùng lặp không cần thiết giữa các Chapter.

## 4. NỘI DUNG BẮT BUỘC CỦA MỖI CHAPTER

Mỗi Chapter phải có đầy đủ các phần sau.

### 4.1. Learning Objectives

- Mục tiêu cần đạt sau khi hoàn thành.
- Kiến thức và kỹ năng sẽ nắm được.
- Tại sao kiến thức này quan trọng trong dự án thực tế.
- Kiến thức tiên quyết cần có.

### 4.2. Theory

Giải thích lý thuyết chi tiết:

- Khái niệm và thuật ngữ.
- Cách hoạt động bên trong (Internal Working).
- Kiến trúc và cơ chế xử lý.
- Các thành phần liên quan.
- Ưu điểm, nhược điểm và trade-offs.
- Khi nào nên sử dụng.
- Những lỗi và hiểu lầm phổ biến.
- Những lưu ý khi áp dụng trong Production.

Không chỉ liệt kê định nghĩa; cần giải thích bản chất và cách hoạt động.

### 4.3. Practical Coding

Mỗi Chapter phải có bài thực hành code cụ thể:

- Bài toán thực tế và yêu cầu chức năng.
- Cấu trúc thư mục.
- Hướng dẫn implement từng bước.
- Code example đủ để chạy hoặc mô tả rõ phần cần hoàn thiện.
- Giải thích những đoạn code quan trọng.
- Best Practices.
- Bad Practices và cách refactor.
- Cách chạy, kiểm tra và debug.
- Kết quả mong đợi.

Ưu tiên TypeScript trong các bài thực hành. Ví dụ code cần nhất quán với phiên bản công nghệ được chọn và không dùng API/package đã deprecated mà không cảnh báo.

### 4.4. Real-world Libraries & Tools

Liệt kê những thư viện, package và công cụ được sử dụng phổ biến trong các dự án Node.js thực tế.

Với mỗi thư viện, giải thích:

- Giải quyết vấn đề gì?
- Tại sao cần sử dụng?
- Khi nào nên và không nên sử dụng?
- Cách cài đặt.
- API hoặc tính năng quan trọng.
- Code example.
- Ưu điểm và hạn chế.
- Các thư viện thay thế.
- Khi nào nên chọn thư viện A thay vì B?
- Trạng thái duy trì, mức độ phổ biến và lưu ý tương thích nếu có.

Chỉ đưa các package có giá trị thực tế; không liệt kê package chỉ vì nó tồn tại.

### 4.5. Common Interview Questions

Mỗi Chapter cần có bộ câu hỏi phỏng vấn theo 3 cấp độ:

**Junior**
- Kiến thức cơ bản.
- Định nghĩa và cách sử dụng.

**Middle**
- Cơ chế hoạt động.
- Phân tích tình huống.
- Debug và xử lý vấn đề thực tế.

**Senior**
- Architecture.
- Performance.
- Scalability.
- Trade-offs.
- System Design.

Mỗi câu hỏi phải có:

- Câu hỏi.
- Câu trả lời chi tiết, đúng bản chất.
- Ví dụ minh họa nếu cần.
- Những điểm interviewer mong đợi ứng viên đề cập.
- Câu hỏi mở rộng (Follow-up Questions).

Ưu tiên câu hỏi thường gặp khi phỏng vấn Node.js Backend Developer. Không chỉ đưa câu trả lời học thuộc; hãy giải thích cách tư duy để trả lời.

### 4.6. Exercises & Assignments

Mỗi Chapter cần có:

- Bài tập cơ bản.
- Bài tập nâng cao.
- Bài tập mang tính thực tế.
- Expected Output.
- Acceptance Criteria để tự đánh giá kết quả.

Không đưa đáp án ngay đối với bài tập cần tự giải quyết. Có thể cung cấp Hint và để phần lời giải tham khảo riêng ở cuối Chapter hoặc một mục được đánh dấu rõ ràng.

### 4.7. Knowledge Checklist

Danh sách checklist để tự đánh giá đã thực sự hiểu và làm được những gì.

### 4.8. References

Đính kèm tài liệu học tập chất lượng:

- Official Documentation.
- Technical Articles.
- GitHub Repositories.
- Best Practices.
- Video hoặc khóa học nếu thực sự cần thiết.

Ưu tiên tài liệu chính thức, còn được duy trì và có URL thực tế.

## 5. CÁC CHỦ ĐỀ PHẢI BAO PHỦ

Đảm bảo roadmap bao gồm đầy đủ các nhóm kiến thức dưới đây. Có thể tách hoặc gộp thành các Chapter hợp lý.

### A. Node.js Fundamentals

- Node.js Architecture.
- V8 Engine.
- Libuv.
- Event Loop.
- Call Stack, Callback Queue.
- Microtask Queue.
- Timers.
- Blocking vs Non-blocking I/O.
- Single Thread và Worker Threads.
- EventEmitter.
- Buffer.
- Streams.
- File System.
- Process, Environment Variables.
- Child Process.
- Cluster.
- Module System: CommonJS vs ES Modules.
- Error Handling.
- Memory Management và Garbage Collection.

### B. JavaScript Advanced for Backend

- Closure.
- Prototype.
- This Binding.
- Execution Context.
- Promise.
- Async/Await.
- Event Loop chuyên sâu.
- Error Propagation.
- Memory Leak.
- Concurrency và Parallelism.

Chỉ tập trung vào những nội dung JavaScript có ý nghĩa trực tiếp đối với Backend.

### C. TypeScript for Backend

- Type System.
- Interface vs Type.
- Generics.
- Utility Types.
- Advanced Types.
- Type Narrowing.
- Decorators.
- DTO.
- Runtime Validation vs Compile-time Type Checking.
- Type-safe API Design.

### D. HTTP & Networking

- HTTP/1.1, HTTP/2, HTTP/3.
- TCP/IP.
- DNS.
- TLS/HTTPS.
- Request/Response Lifecycle.
- HTTP Methods.
- Status Codes.
- Headers.
- Cookies.
- CORS.
- RESTful API Design.
- Pagination, Filtering, Sorting.
- Rate Limiting.
- WebSocket.
- Server-Sent Events.

### E. Backend Frameworks

- Express.js.
- NestJS.
- Fastify.

Giải thích kiến trúc, cách tổ chức code, Dependency Injection, Middleware, Guards, Interceptors, Pipes và Exception Filters.

So sánh các framework và đưa ra khuyến nghị sử dụng trong dự án thực tế. Học sâu một framework chính trước; framework còn lại học ở mức hiểu kiến trúc và biết lựa chọn, tránh học dàn trải.

### F. Database

- SQL Fundamentals.
- PostgreSQL.
- MongoDB.
- Database Design.
- Normalization.
- Indexing.
- Query Optimization.
- Transactions.
- ACID.
- Isolation Levels.
- Locking.
- Connection Pooling.
- N+1 Query Problem.
- Database Migration.
- ORM và Query Builder.

Các thư viện cần đề cập:

- Prisma.
- Drizzle ORM.
- TypeORM.
- Knex.js.
- Mongoose.

Ưu tiên học SQL và PostgreSQL đủ sâu trước khi phụ thuộc vào ORM.

### G. Authentication & Authorization

- Authentication vs Authorization.
- Session-based Authentication.
- JWT.
- Access Token và Refresh Token.
- HttpOnly Cookie.
- OAuth 2.0.
- OpenID Connect.
- Google Login.
- Role-based Access Control (RBAC).
- Permission-based Access Control.
- Password Hashing.
- Bcrypt / Argon2.
- Token Rotation.
- Token Revocation.

Thực hành xây dựng hệ thống Authentication hoàn chỉnh, có xét đến bảo mật, lưu trữ token, refresh, logout và thu hồi phiên/token.

### H. Backend Architecture & Design Patterns

- MVC.
- Layered Architecture.
- Clean Architecture.
- Hexagonal Architecture.
- Repository Pattern.
- Service Pattern.
- Dependency Injection.
- Factory Pattern.
- Strategy Pattern.
- Singleton Pattern.
- SOLID.
- DRY, KISS, YAGNI.
- Domain-Driven Design cơ bản.

### I. Validation, Security & Error Handling

- Zod.
- Joi.
- class-validator.
- Input Validation.
- XSS.
- CSRF.
- SQL Injection.
- NoSQL Injection.
- SSRF.
- IDOR.
- Rate Limiting.
- Helmet.
- CORS Security.
- Secure Headers.
- OWASP Top 10.
- Centralized Error Handling.
- Logging.

### J. Caching & Performance

- Redis.
- In-memory Cache.
- Cache Aside.
- Write Through.
- Cache Invalidation.
- Rate Limiting.
- BullMQ.
- Background Jobs.
- Worker Threads.
- Profiling.
- CPU-bound vs I/O-bound.
- Memory Optimization.
- Load Testing.

### K. Messaging & Event-driven Architecture

- Event-driven Architecture.
- Message Queue.
- Pub/Sub.
- RabbitMQ.
- Apache Kafka.
- Redis Pub/Sub.
- BullMQ.
- Webhooks.
- Retry.
- Dead Letter Queue.
- Idempotency.
- Eventual Consistency.

### L. Testing

- Unit Testing.
- Integration Testing.
- E2E Testing.
- Mocking.
- Test Coverage.
- Test Database.
- API Testing.

Các thư viện:

- Jest.
- Vitest.
- Supertest.
- Playwright.
- Testcontainers.

### M. DevOps & Deployment

- Linux Fundamentals.
- Docker.
- Docker Compose.
- Nginx.
- CI/CD.
- GitHub Actions.
- Environment Management.
- Deployment.
- VPS.
- Cloud Services.
- Reverse Proxy.
- Process Management.
- PM2.
- Graceful Shutdown.
- Health Check.
- Database Backup.

### N. Monitoring & Observability

- Logging.
- Metrics.
- Tracing.
- OpenTelemetry.
- Prometheus.
- Grafana.
- Sentry.
- Pino.
- Winston.
- Request Correlation ID.

### O. Advanced Backend & System Design

- Monolithic vs Microservices.
- API Gateway.
- Load Balancing.
- Horizontal vs Vertical Scaling.
- Distributed Systems.
- Distributed Cache.
- Distributed Lock.
- Database Replication.
- Sharding.
- Eventual Consistency.
- CAP Theorem.
- Fault Tolerance.
- Circuit Breaker.
- Retry Strategies.
- System Design Fundamentals.

## 6. GIT WORKFLOW - MỖI CHAPTER MỘT BRANCH

Đây là yêu cầu bắt buộc.

Mỗi Chapter tương ứng với một Git branch riêng để quản lý quá trình học. Các Chapter được phát triển nối tiếp nhau trên cùng một codebase, không phải các project độc lập.

### 6.1. Repository Structure

Sử dụng repository có tên gợi ý:

`nodejs-backend-learning`

Cấu trúc thư mục ban đầu đề xuất:

```text
nodejs-backend-learning/
├── docs/
│   ├── ROADMAP.md
│   ├── INTERVIEW-QUESTIONS.md
│   └── PROJECT-REQUIREMENTS.md
├── src/
│   ├── chapter-01-nodejs-architecture/
│   ├── chapter-02-event-loop/
│   └── ...
├── exercises/
│   ├── chapter-01/
│   ├── chapter-02/
│   └── ...
├── projects/
│   └── capstone/
├── tests/
├── scripts/
├── .env.example
├── .gitignore
├── package.json
├── package-lock.json
├── tsconfig.json
├── eslint.config.js
├── prettier.config.js
└── README.md
```

Điều chỉnh cấu trúc khi dự án phát triển, nhưng phải giữ sự nhất quán và giải thích lý do nếu thay đổi.

Quy ước:

- `docs/`: tài liệu roadmap, câu hỏi phỏng vấn và yêu cầu dự án.
- `src/`: code thực hành theo Chapter, có thể tái sử dụng code từ Chapter trước.
- `exercises/`: bài tập riêng để người học tự giải quyết.
- `projects/capstone/`: dự án tổng hợp cuối lộ trình.
- `tests/`: kiểm thử dùng chung hoặc kiểm thử tích hợp tùy kiến trúc.
- File cấu hình ở root: cấu hình chung của repository.

Không bắt buộc phải tạo sẵn tất cả thư mục rỗng. Hãy tạo thư mục khi Chapter tương ứng bắt đầu.

### 6.2. Branch Strategy

Sử dụng `main` làm nhánh ổn định, chứa trạng thái code mới nhất sau khi hoàn thành các Chapter.

Quy ước tên branch:

`chapter/<chapter-number>-<short-description>`

Ví dụ:

```text
main
chapter/01-nodejs-architecture
chapter/02-event-loop
chapter/03-async-programming
chapter/04-http-networking
chapter/05-express-fundamentals
```

Mỗi Chapter phải cung cấp:

1. Tên branch.
2. Branch được tạo từ đâu.
3. Git command để tạo và chuyển branch.
4. Nội dung cần implement.
5. Danh sách file dự kiến tạo hoặc chỉnh sửa.
6. Commit message gợi ý.
7. Điều kiện hoàn thành Chapter.
8. Cách merge về `main`.
9. Cách xử lý nếu cần cập nhật branch khi `main` có thay đổi.

### 6.3. Workflow bắt đầu Chapter

Chapter đầu tiên:

```bash
git checkout main
git pull origin main

git checkout -b chapter/01-nodejs-architecture
```

Các Chapter tiếp theo luôn bắt đầu từ `main` mới nhất sau khi Chapter trước đã được hoàn thành và merge:

```bash
git checkout main
git pull origin main

git checkout -b chapter/02-event-loop
```

### 6.4. Workflow hoàn thành Chapter

Sau khi code, kiểm tra và hoàn thành Acceptance Criteria:

```bash
git status
git add .
git commit -m "feat(chapter-01): implement nodejs architecture examples"

git checkout main
git pull origin main
git merge --no-ff chapter/01-nodejs-architecture
git push origin main
```

Có thể push branch và tạo Pull Request trước khi merge nếu muốn luyện quy trình làm việc nhóm:

```bash
git push -u origin chapter/01-nodejs-architecture
```

Sau khi merge, có thể xóa branch đã hoàn thành:

```bash
git branch -d chapter/01-nodejs-architecture
git push origin --delete chapter/01-nodejs-architecture
```

Không bắt buộc xóa branch nếu muốn giữ lịch sử học tập.

### 6.5. Quy tắc quan trọng

- Mỗi Chapter có branch riêng.
- Chapter mới được tạo từ `main` mới nhất sau khi Chapter trước đã merge.
- Các Chapter dùng chung một codebase và kế thừa source code trước đó khi phù hợp.
- Không tạo một project độc lập mới cho mỗi Chapter nếu không có lý do kỹ thuật rõ ràng.
- Không để code thử nghiệm làm hỏng phần đã hoàn thành.
- Mỗi Chapter cần có commit rõ ràng, dễ đọc và có ý nghĩa.
- Không commit `.env`, secret, API key hoặc thông tin nhạy cảm.
- Duy trì `.env.example` để mô tả các biến môi trường cần thiết.
- Có thể dùng tag để đánh dấu milestone quan trọng, ví dụ `chapter-01-completed`.
- Nếu một Chapter cần thay đổi cấu trúc hoặc refactor code cũ, phải giải thích tác động và cách kiểm thử hồi quy.

## 7. CAPSTONE PROJECT

Sau khi hoàn thành các kiến thức chính, hãy thiết kế một dự án Backend tổng hợp để áp dụng toàn bộ kiến thức đã học.

Yêu cầu kỹ thuật:

- Node.js + TypeScript.
- Express.js hoặc NestJS.
- PostgreSQL.
- ORM.
- Redis.
- Authentication và Authorization.
- RESTful API.
- Validation.
- Error Handling.
- Logging.
- Unit/Integration Testing.
- Docker.
- CI/CD.
- Background Jobs.
- Caching.
- API Documentation.
- Deployment.
- Monitoring.

Chọn một bài toán thực tế đủ lớn, ví dụ:

- E-commerce Backend.
- Project Management System.
- Booking System.
- Learning Management System.

Thiết kế dự án bao gồm:

- Business Requirements.
- Functional Requirements.
- Non-functional Requirements.
- System Architecture.
- Database Schema.
- ERD.
- API Specification.
- Folder Structure.
- Implementation Roadmap.
- Git Branch Strategy.
- Testing Strategy.
- Deployment Strategy.

Chia Capstone thành các milestone có thể triển khai lần lượt. Mỗi milestone cần có Acceptance Criteria và branch/commit strategy rõ ràng. Capstone nên tận dụng code và kiến thức từ các Chapter trước, nhưng cần tổ chức lại thành kiến trúc hoàn chỉnh, không ghép máy móc các ví dụ rời rạc.

## 8. YÊU CẦU VỀ CHẤT LƯỢNG

Đặc biệt chú ý:

1. Nội dung phải chính xác về mặt kỹ thuật.
2. Phân biệt kiến thức nền tảng với kiến thức nâng cao.
3. Không chỉ liệt kê thư viện mà phải giải thích cách sử dụng trong dự án.
4. Không sử dụng API hoặc package đã deprecated mà không cảnh báo.
5. Ưu tiên phiên bản LTS và thư viện được duy trì tích cực.
6. Không nhồi nhét quá nhiều công nghệ vào một Chapter.
7. Giải thích tại sao nên học một kiến thức và nó được ứng dụng ở đâu.
8. Code thực hành phải có tính liên kết giữa các Chapter.
9. Phỏng vấn phải tập trung vào khả năng giải thích bản chất, tư duy giải quyết vấn đề và kinh nghiệm triển khai.
10. Đưa ra tài liệu tham khảo có URL thực tế, không tạo link giả.
11. Phân biệt rõ kiến thức bắt buộc với kiến thức mở rộng.
12. Với công nghệ có nhiều lựa chọn, hãy chọn một stack chính để thực hành xuyên suốt và giải thích các lựa chọn thay thế.
13. Đưa ra ví dụ có thể chạy được; ghi rõ phiên bản runtime/package hoặc cách kiểm tra phiên bản.
14. Không giả định rằng một thư viện phổ biến đồng nghĩa với việc luôn là lựa chọn tốt nhất.

Nếu có khả năng truy cập Internet, hãy kiểm tra tài liệu chính thức và phiên bản hiện hành trước khi đưa ra nội dung về công nghệ, thư viện.

## 9. HỌC TẬP VÀ THEO DÕI TIẾN ĐỘ

Ở đầu `ROADMAP.md` cần có:

- Tổng quan lộ trình.
- Sơ đồ các Phase.
- Estimated Learning Time.
- Prerequisites.
- Technology Stack.
- Git Workflow.
- Repository Structure.
- Cách sử dụng tài liệu.

Ở cuối `ROADMAP.md` cần có:

- Tổng kết kiến thức.
- Backend Developer Skill Checklist.
- Danh sách kỹ năng cần đạt để ứng tuyển Middle Node.js Backend Developer.
- Bộ câu hỏi phỏng vấn tổng hợp.
- Danh sách project cần hoàn thành.

Mỗi Chapter có checklist:

```markdown
- [ ] Theory completed.
- [ ] Practical coding completed.
- [ ] Exercises completed.
- [ ] Interview questions reviewed.
- [ ] Code reviewed.
- [ ] Tests passed.
- [ ] Chapter completed and merged to main.
```

Đưa ra ước lượng thời gian cho từng Chapter và Phase. Ước lượng cần thực tế, có phân biệt thời gian đọc hiểu, code, làm bài tập và ôn tập. Không cam kết người học chắc chắn đạt Middle chỉ dựa trên số tháng học.

## 10. CÁCH THỰC HIỆN

Trước khi tạo tài liệu:

1. Phân tích toàn bộ yêu cầu.
2. Thiết kế cấu trúc Phase và Chapter hợp lý.
3. Kiểm tra tính đầy đủ và tránh trùng lặp kiến thức.
4. Xây dựng Git Branch Strategy và Repository Structure.
5. Chọn stack thực hành chính, giải thích lý do chọn.
6. Đảm bảo lộ trình có tính liên tục và tăng dần độ khó.

Sau đó tạo file `ROADMAP.md` hoàn chỉnh trong repository.

**Không chỉ trả về một bản outline sơ sài.** Mỗi Chapter phải có lý thuyết, code thực hành, thư viện thực tế, bài tập, checklist và câu hỏi phỏng vấn.

Nếu nội dung quá dài, hãy tiếp tục hoàn thiện tài liệu theo nhiều lượt cho đến khi toàn bộ Chapter được triển khai đầy đủ. Không được lược bỏ nội dung chỉ để rút ngắn tài liệu.

Nếu môi trường không thể tạo file trực tiếp, hãy xuất toàn bộ nội dung Markdown để người học có thể lưu thành `ROADMAP.md`.
