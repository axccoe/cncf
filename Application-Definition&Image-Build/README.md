# 1. Application Definition & Image Build  

클라우드 네이티브 애플리케이션의 정의 및 이미지를 빌드하기 위한 도구들입니다. 이러한 도구들은 애플리케이션의 구조를 정의하고, 컨테이너 이미지를 빌드하며, 애플리케이션 배포를 준비하는 역할을 수행합니다.  

## 목차
1. [App Definition and Development](#1-app-definition-and-development)  
2. [Continuous Integration & Delivery](#2-continuous-integration--delivery)  
3. [Streaming & Messaging](#3-streaming--messaging)  
4. [Database](#4-database)  

---

## 1. App Definition and Development  

이 폴더에는 클라우드 네이티브 애플리케이션의 정의 및 이미지를 빌드하기 위한 도구들이 포함되어 있습니다. 이러한 도구들은 애플리케이션의 구조를 정의하고, 컨테이너 이미지를 빌드하며, 배포를 준비하는 역할을 합니다.  

- **Helm**: Kubernetes 애플리케이션을 패키징하고 관리하는 도구  
- **Artifact Hub**: 다양한 클라우드 네이티브 아티팩트를 찾고 공유할 수 있는 리포지토리  
- **Backstage**: 개발자 포털을 통해 애플리케이션과 인프라를 통합 관리  
- **Buildpacks.io**: 소스 코드를 자동으로 컨테이너 이미지로 변환  
- **Dapr**: 마이크로서비스 개발을 위한 런타임 환경  
- **KubeVela**: 애플리케이션 배포와 관리에 최적화된 플랫폼  
- **KubeVirt**: Kubernetes에서 가상 머신을 실행할 수 있게 하는 도구  
- **Operator Framework**: Kubernetes에서 자동화된 운영을 위한 프레임워크  

---

## 2. Continuous Integration & Delivery  

이 폴더에는 지속적 통합과 배포(CI/CD)를 지원하는 도구들이 포함되어 있습니다. 애플리케이션의 빌드, 테스트, 배포를 자동화하여 개발 주기를 단축하고 안정성을 높입니다.  

- **Argo**: 선언적 지속적 배포(CD) 도구로, GitOps 방식을 사용하여 애플리케이션 배포를 자동화  
- **Flux**: Kubernetes에서 GitOps 방식으로 애플리케이션을 자동 배포하는 도구  
- **Keptn**: 배포 파이프라인 관리 및 품질 게이트 설정을 자동화하는 도구  
- **OpenKruise**: Kubernetes 네이티브 애플리케이션 관리를 위한 확장 가능한 자동화 도구  

---

## 3. Streaming & Messaging  

이 폴더에는 클라우드 네이티브 환경에서 메시징과 스트리밍 기능을 제공하는 도구들이 포함되어 있습니다. 대규모 데이터를 실시간으로 처리하고 전송하는 데 사용됩니다.  

- **CloudEvents**: 클라우드 네이티브 이벤트를 전송하기 위한 표준 사양  
- **NATS**: 고성능 메시징 시스템으로, 마이크로서비스 간의 실시간 통신을 지원  
- **Strimzi**: Kubernetes에서 Apache Kafka 클러스터를 쉽게 관리할 수 있게 해주는 도구  

---

## 4. Database  

이 폴더에는 클라우드 네이티브 환경에서 데이터를 관리하고 저장하는 데 사용되는 데이터베이스 관련 도구들이 포함되어 있습니다.  

- **TiKV**: 분산형 트랜잭션 키-값 저장소로, 대규모 데이터 처리에 적합  
- **Vitess**: MySQL 데이터베이스를 위한 수평 확장 솔루션으로, 클라우드 네이티브 환경에서 대규모 트래픽을 처리  
