# 포트폴리오

---

## 📌 프로젝트 및 상세 업무

### **모두의 컨퍼런스 | OmniCnf**  
**개인 프로젝트 | Side Project**  
**기간**: 2024.10 - 현재  

**💡 프로젝트 개요**
- 모두의 컨퍼런스(OmniCnf)는 Spring AI를 활용한 개발자 컨퍼런스 영상 요약 및 검색 서비스입니다.
- 유튜브에 업로드된 컨퍼런스 영상을 OpenAI API 와 pgvector 를 활용해 분석/저장/검색하고, 사용자가 원하는 내용을 쉽고 빠르게 조회할 수 있도록 구현하였습니다.

**🔧 기술 스택**  
- **Backend**: Java 17, Spring Boot 3.3.4, JPA, QueryDSL, postgresql, pgvector, OpenAI API, Spring AI  
- **Frontend**: Next.js, React  
- **Infra**: Docker, Docker Compose, AWS, Nginx, GitHub Actions  

**📌 주요 구현 내용**  
- **AI 기반 영상 요약**: OpenAI API 와 Spring AI를 활용해 컨퍼런스 영상 요약  
- **Embedding 검색 기능**: pgvector 와 OpenAI Embedding API 를 활용한 유사 검색  
- **SSR(서버 사이드 렌더링) 기반 SEO 최적화**: Next.js로 반응형 웹 애플리케이션 구현  
- **Docker 기반 배포 및 GitHub Actions CI/CD 구축**: 자동화된 빌드와 배포 환경 구축  

---

### **회사 프로젝트 상세 내용**  
**(주) 배컴 | 개발팀 매니저**

**1. 선물하기 기능 개발**  
- 쿠폰 발급, 결제 요청, 채팅 채널 생성 및 메시지 전송, SMS 및 Push 알림 구현  
- 논리적인 Transaction 관리 및 보상 트랜잭션 처리  
- JWT 인증 및 Binary 응답 방식 적용으로 보안성 강화  

**2. 결제 기능 개발 및 안정화**  
- 네이버페이, 토스 계좌이체 연동 및 결제 중복 방지 로직 구현  
- MQ(Message Queue) 기반 아키텍처 적용으로 데이터 유실 방지  

**3. 검색 엔진 연동 및 성능 개선**  
- 100만 개 이상의 Feed 데이터를 대상으로 검색 기능 개발  
- DB LIKE 연산을 검색엔진 기반으로 변경하여 성능 2000% 개선  

---

**(주) 더즈인터랙티브 | 선임 연구원**

**1. 소셜 로그인 기능 개발**  
- Spring Security, OAuth2를 활용한 로그인/회원가입 구현  
- Custom Annotation 및 HandlerMethodArgumentResolver 적용으로 코드 중복 제거  

**2. CI/CD 자동화 구축**  
- 기존 FTP 배포 방식 → GitHub, Jenkins 기반의 CI/CD 파이프라인 구축  
- React + Spring Boot 통합 빌드 프로세스 개선  

**3. SMTP 보안 취약점 개선**  
- Man-in-the-Middle 공격 방지를 위한 RSA 암호화 적용  
- Proxy 툴을 통한 메일 변조 방지를 위한 클라이언트 공개키 암호화 적용