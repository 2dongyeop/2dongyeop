## Hi ! I'm 2dongyeop


<img align="right" src="https://github.com/2dongyeop/2dongyeop/blob/main/horong.jpeg" width=220 />

- 의료 도메인 스타트업에서 Java & Spring Boot 기반의 서버 개발자로 2년차 개발자로 근무중입니다.
- [LinkedIn](https://www.linkedin.com/in/2dongyeop/), [Resume](https://www.notion.so/leedongyeop/_-_-_-18b78399c226809e90bef7f3ede3ee1d), [Velog](https://velog.io/@dongvelop), [TIL](https://github.com/2dongyeop/TIL)

<br/>

## Introduce.


### Mindset.

- **‘창피함은 한 번이지만, 얻는 기억은 영원하다.**’라는 마음으로 모르는 것을 부끄러워하지 않고, 자기객관화를 통해 성장하려 합니다.
- **부족한 지식이더라도** 특정 주제에 대해 정리하여 **사내 기술 공유를 진행하고, 피드백과 토론을 통해 기술 역량을 발전**시키고 있습니다.
- 기능 개발 전에 **구현 방안을 팀과 논의**하고, 개발 후에 **코드 리뷰를 통해 다양한 시각에서 검토**하며 더 나은 코드를 고민합니다.

### Culture.

- 소규모 개발팀에서 **기술 문화를 정착시키기 위해, 사내 기술 위키를 활성화하고 온보딩 문서/개발 히스토리 문서화를 주도**하고 있습니다.
- **레거시 코드의 신뢰성을 높이기 위해 테스트 코드를 도입**하고, **부하 테스트 환경을 구축**하여 최대 수용 가능 트래픽을 측정하고 있습니다.
- 최신 기술 변화와 트러블슈팅에 관심이 많아, 여러 테크 기업들의 기술 블로그를 매일 아침 정독하며 흐름을 따라가고 있습니다.

<br/>

## Summary
- [송아리당뇨](https://play.google.com/store/apps/details?id=com.songaree.diabetes&hl=ko), [송아리에어 IoT](https://play.google.com/store/apps/details?id=com.songaree.air&hl=ko) 서버 운영 및 고도화(모놀리식 → MSA 전환)
    - JDK 1.8, Spring Boot 2.7 → JDK 17, Spring Boot 3.0.13, Spring Cloud 2022.0.4
    - 신기능 개발 주도 : 요구사항 분석, DB 설계, API 스펙 정의, 기능 구현 및 배포 일정 관리
    - **nGrinder를 이용한 마이크로서비스 성능 분석 및 트랜잭션 처리량(TPS) 측정 후, 쿼리 및 코드 최적화**
    - **Pinpoint를 이용해 외부 API 및 마이크로서비스 간 호출 시 실패하는 병목 지점 식별**
        **: Retry 정책** 설계 및 구현을 통해 **API 호출 실패율 90% 감소**
- 사내 기술 발표 15회, 강의/컨퍼런스 후기 3건 작성
    - [JDK 1.5부터 JDK 22까지의 주요 문법 정리](https://velog.io/@dongvelop/JDK-21%EC%9D%B4-%EC%B6%9C%EC%8B%9C%EB%90%98%EC%97%88%EB%8B%A4.-%EC%B5%9C%EC%8B%A0-%EB%AC%B8%EB%B2%95%EC%9D%80-%EC%82%B4%ED%8E%B4%EB%B4%90%EC%95%BC%EC%A7%80)
    - [JDK 21에서만 발생하는 Out Of Memory Error](https://velog.io/@dongvelop/Spring-Boot-Out-of-Memory-when-Using-JDK21)
    - [JVM Cold Start 최적화하기](https://velog.io/@dongvelop/Spring-Boot-JVM-Cold-Start-%EC%B5%9C%EC%A0%81%ED%99%94%ED%95%98%EA%B8%B0)
    - [Spring Boot with GraphQL](https://velog.io/@dongvelop/Spring-Boot-GraphQL-%EC%86%8C%EA%B0%9C)
- Skill Keyword
    - Java, Spring Boot, Spring Cloud, JPA, JUnit5, Docker, Nginx, Jenkins, [n8n](https://n8n.io/), Git
    - AWS(EC2, S3, SES, RDS, CloudWatch), Grafana, Prometheus, Pinpoint, nGrinder

<!-- [![trophy](https://github-profile-trophy.vercel.app/?username=2dongyeop&no-frame=true&row=1)](https://github.com/ryo-ma/github-profile-trophy) -->

[![Velog's GitHub stats](https://velog-readme-stats.vercel.app/api/list?name=dongvelop)](https://velog.io/@dongvelop) 



<!-- ```Java
@Slf4j
@Component
@RequiredArgsConstructor
public class Introduction {

    private final LeeDongyeop leeDongyeop;
    
    @PostConstruct
    private void init() {
        log.info("I am interested in stable service operation!");
        log.info("Prepare for failure, monitoring and quick recovery.");
    }
    
    @PreDestroy
    public void close() {
        log.info("Thank you for visiting. Look at my cute cat.");
    }
}

``` -->
