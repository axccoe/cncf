# Observability
1. **Chaos Mesh** (CNCF Incubating)
2. **Litmus** (CNCF Incubating)

<br>


### 1. **Chaos Mesh** (CNCF Incubating)  
<img src="./image/chaos-mesh.png" alt="" width="100"/>  

   - **설명**: Chaos Mesh는 오픈소스 Cloud Native Chaos Enginerring 플랫폼입니다. 다양한 유형의 결함(fault) 시뮬레이션을 제공하며 결함 시나리오를 조율하는 기능을 갖고 있습니다. 
   - **문제 해결**: 예상치 못한 장애 대응 능력 향상, 서비스 복원력 검증에 사용되며, Kubernetes 기반 환경에서 테스트하는 것에 최적화되어 있습니다. 
   - **특징**  
     - 카오스 실험 시나리오 정의: 다양한 실험을 정의하고, 네트워크 지연, 리소스 부족, 파드 또는 노드 장애 등 여러 카오스 상태를 쉽게 시뮬레이션 가능 
     - Kubernetes 네이티브: Kubernetes 환경에서 네이티브하게 동작하며, 클러스터 자원을 대상으로 실험을 자동화 가능 
     - 사용자 친화적 인터페이스: 웹 UI에서 Chaos 시나리오를 쉽게 설계하고 Chaos 실험의 상태를 모니터링 가능 
     - 관찰가능성 통합 : Prometheus, Grafana 등과 같은 모니터링 툴과 통합되어 실험 결과를 실시간으로 시각화하고 분석 가능 
   - **사용 사례**: Chaos Mesh는 프로덕션 환경의 안정성 테스트, 애플리케이션 성능 검증에 사용되며 특히 Kubernetes 클러스터에서 실행 중인 컨테이너화된 애플리케이션 테스트에 사용할 수 있습니다. 
   - [Chaos Mesh 문서](https://chaos-mesh.org/)

### 2. **litmus** (CNCF Incubating)  
<img src="./image/litmus.png" alt="" width="100"/>  

   - **설명**: Litmus는 조직이 통제된 방식으로 Chaos Test를 실시하여 인프라의 취약점과 잠재적인 중단(outage)을 파악할 수 있게 해주는 오픈 소스 chaos Engineering 플랫폼입니다. 
   - **문제 해결**: 프로덕션 환경의 안정성 확보, 애플리케이션 복원력 개선에 사용되며, Kubernetes 환경에서 안정성 검증 및 최적화에 도움을 줍니다.
   - **특징**  
     - 플러그 앤 플레이: 카탈로그 형식으로 다양한 카오스 실험을 제공하며, 사용자는 원하는 실험을 쉽게 선택하여 수행 가능 
     - Kubernetes 네이티브: Kubernetes 워크로드와 인프라에 대한 카오스 테스트를 지원하며, 실험을 실행하기 위해 별도의 환경을 만들 필요 없이 쿠버네티스 클러스터에서 직접 실행 가능 
     - 플렉시블 실험 정의: YAML 파일로 실험을 정의할 수 있고, 커스터마이징을 통해 원하는 장애 시나리오를 정밀하게 설정 가능 
     - 관찰가능성 통합 : Prometheus, Grafana 등과 같은 모니터링 툴과 통합되어 실험 결과를 실시간으로 시각화하고 분석 가능 
   - **사용 사례**: Litmus는 운영 중인 시스템의 장애 대응 테스트, kubernetes 클러스터의 안정성 테스트 등에 사용되며 Devops 파이프라인에 통합하여 배포 중 장애 대응 능력을 검증할 수 있습니다.  
   - [Litmus 문서](https://litmuschaos.io/)
