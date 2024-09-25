# Orchestration & Management  

이 폴더에는 클라우드 네이티브 환경에서 애플리케이션의 배포, 조정, 서비스 간 통신 등을 관리하는 다양한 도구들이 포함되어 있습니다. 각 폴더는 네트워크 통신, API 게이트웨이, 서비스 프록시, 스케줄링, 그리고 서비스 메시 등 다양한 기능을 제공합니다.  

## 목차
1. [API Gateway](#1-api-gateway)  
2. [Coordination & Service Discovery](#2-coordination--service-discovery)  
3. [Remote Procedure Call](#3-remote-procedure-call)  
4. [Scheduling & Orchestration](#4-scheduling--orchestration)    
5. [Service Mesh](#5-service-mesh)    
6. [Service Proxy](#6-service-proxy)  

---

## 1. API Gateway  

이 폴더에는 API 게이트웨이를 제공하는 도구들이 포함되어 있습니다. API 게이트웨이는 클라이언트와 서버 간의 요청을 처리하고 라우팅하며, 보안을 강화하는 데 중요한 역할을 합니다.  

- **Emissary Ingress**: Kubernetes 클러스터에서 API 게이트웨이 역할을 수행하며, Envoy 프록시를 기반으로 구축된 고성능 API 트래픽 관리 도구  

---

## 2. Coordination & Service Discovery  

이 폴더에는 분산 시스템에서 서비스 발견 및 조정 기능을 제공하는 도구들이 포함되어 있습니다. 클러스터 내의 서비스가 서로를 쉽게 찾고 통신할 수 있도록 도와줍니다.  

- **CoreDNS**: 클라우드 네이티브 환경에서 서비스 디스커버리 및 DNS 서버 역할을 하는 플러그인 기반 DNS 서버  
- **etcd**: 분산 키-값 저장소로, 클러스터 내의 설정 정보와 메타데이터를 저장하고 조정  

---

## 3. Remote Procedure Call  

이 폴더에는 네트워크를 통한 원격 프로시저 호출(RPC)을 지원하는 도구들이 포함되어 있습니다. 클라이언트와 서버 간의 통신을 더욱 쉽게 구현할 수 있습니다.  

- **gRPC**: 고성능 오픈소스 RPC 프레임워크로, HTTP/2를 기반으로 하여 빠르고 효율적인 클라이언트-서버 통신을 지원  

---

## 4. Scheduling & Orchestration  

이 폴더에는 클러스터 내 애플리케이션의 스케줄링과 오케스트레이션을 담당하는 도구들이 포함되어 있습니다. 분산 시스템에서 애플리케이션의 배포와 관리를 자동화하여 효율성을 높입니다.  

- **Kubernetes**: 컨테이너화된 애플리케이션의 자동 배포, 스케일링, 관리 도구  
- **Crossplane**: Kubernetes API를 통해 클라우드 리소스를 관리하고, 멀티 클라우드 환경을 지원하는 도구  
- **Karmada**: 여러 Kubernetes 클러스터에서 애플리케이션을 관리하고 스케줄링할 수 있는 도구  
- **Knative**: 서버리스 워크로드를 위한 애플리케이션 배포 및 관리 플랫폼  
- **Volcano**: 고성능 컴퓨팅 작업의 스케줄링 및 관리 도구로, 대규모 분산 환경에서 사용  

---

## 5. Service Mesh  

이 폴더에는 마이크로서비스 간 네트워크 트래픽을 제어하고 관리하는 서비스 메시 도구들이 포함되어 있습니다. 서비스 간 통신을 안전하게 관리하며, 모니터링 및 보안을 강화할 수 있습니다.  

- **Istio**: 클라우드 네이티브 애플리케이션 간의 네트워크 트래픽을 제어하고 보안을 제공하는 서비스 메시 도구  
- **Linkerd**: 경량화된 서비스 메시로, 마이크로서비스 간 트래픽 관리와 보안을 제공하는 도구  

---

## 6. Service Proxy  

이 폴더에는 네트워크 트래픽을 처리하는 프록시 서버 역할을 하는 도구들이 포함되어 있습니다. 서비스 간의 통신을 효율적으로 관리하고, 네트워크 성능을 최적화할 수 있습니다.  

- **Envoy**: 클라우드 네이티브 애플리케이션에서 고성능 트래픽 관리를 지원하는 오픈소스 프록시  
- **Contour**: Envoy 기반의 Kubernetes Ingress 컨트롤러로, HTTP(S) 트래픽을 효율적으로 처리하고 관리  

