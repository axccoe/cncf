# Observability
1. **Fluentd** (CNCF Graduated)
<br>


### 1. **Fluentd** (CNCF Graduated)  
<img src="./image/fluentd-logo.png" alt="Helm" width="100"/>  

   - **설명**: Fluentd는 오픈 소스 데이터 수집기로, 데이터 collection과 consumption를 통합하여 데이터를 보다 잘 활용할 수 있게 해줍니다. 보통 로그 수집기로 쓰이며,  로그 데이터를 통합하고, 변환하고, 전송하는 작업을 쉽게 처리할 수 있습니다. 
   - **문제 해결**: Kubernetes에서의 복잡한 애플리케이션 배포 및 자동화를 단순화하고, 컨테이너화된 애플리케이션의 지속적 통합과 배포를 효율적으로 관리할 수 있습니다.  
   - **특징**  
     - Json을 사용한 통합 로깅 : 가능한 한 Json으로 데이터 구조화하여 로그 데이터 처리의 모든 측면을 통합
     - pluggable Architecture : 기능을 확장할 수 있는 유연한 플러그인 시스템을 갖춤
     - 필요 리소스 최소화 : C 언어 + Duby를 조합하여 작성되었으며, 시스템 리소스가 거의 필요하지 않음.
     - 내장된 신뢰성 : 노드 간 데이터 손실을 방지하기 위해 메모리 및 파일 기반 버퍼링 지원, 강력한 장애 조치, 고가용성 설정 가능
   - **사용 사례**: Fluentd는 대규모 로그 관리 및 분석 환경에서 특히 유용하며, 클라우드 및 멀티 클라우드 데이터 통합, 데이터 파이프라인으로 널리 사용됩니다. 
   - [fluentd 문서](https://www.fluentd.org/architecture)
