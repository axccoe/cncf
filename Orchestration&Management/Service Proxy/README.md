# Service Proxy    
 

1. **Envoy** (CNCF Graduated)
2. **Contour** (CNCF Incubating)

<br>
<br>


# Service Proxy    


### 1. **Envoy** (CNCF Graduated)  
<img src="./image/image.png" alt="CoreDNS" width="100"/>  

   - **설명**: Envoy는 클라우드 네이티브 애플리케이션에서 서비스 간 통신을 관리하는 고성능 오픈소스 프록시입니다. 마이크로서비스 아키텍처에서 네트워크 트래픽을 효율적으로 처리하고, 로드 밸런싱, 서비스 디스커버리, 모니터링, 그리고 보안 기능을 제공합니다.  
   - **문제 해결**: 마이크로서비스 아키텍처에서 서비스 간의 복잡한 통신을 관리하고, 로드 밸런싱과 모니터링, 트래픽 관리의 어려움을 해결합니다.  
   - **특징**  
     - 로드 밸런싱 및 트래픽 관리: Envoy는 고급 로드 밸런싱 알고리즘을 통해 트래픽을 효율적으로 분배하고, 트래픽 라우팅, 재시도 정책을 유연하게 설정 가능  
     - 서비스 메쉬 통합: Istio와 같은 서비스 메쉬와 원활하게 통합되어, 서비스 간의 통신을 제어하고 모니터링하며, 보안 정책을 쉽게 적용  
     - 강력한 모니터링 및 관찰 가능성: 트래픽 메트릭, 로깅, 분산 트레이싱을 지원하여 네트워크 성능 모니터링 및 디버깅이 가능하며, 이를 통해 네트워크와 애플리케이션 성능 문제를 쉽게 파악 가능  
   - **사용 사례**: Envoy는 마이크로서비스 간의 트래픽을 최적화하고, 다양한 언어와 프레임워크로 이루어진 대규모 애플리케이션에서 서비스 메쉬를 구축할 때 필수적으로 사용됩니다. 특히 네트워크 관리와 성능 최적화가 중요한 환경에서 폭넓게 활용됩니다.  
   - [Envoy 문서](https://www.envoyproxy.io/docs/envoy/v1.31.2/intro/what_is_envoy)  
<br>


### 2. **Contour** (CNCF Incubating)  
<img src="./image/image-1.png" alt="etcd" width="120"/>  

   - **설명**: Contour는 Envoy 기반의 고성능 서비스 프록시로, Kubernetes 환경에서 HTTP(S) 트래픽을 관리하는 Ingress 컨트롤러입니다. Envoy를 역방향 프록시와 로드 밸런서로 사용하며, Kubernetes 클러스터 내에서 로드 밸런싱과 트래픽 관리를 쉽게 설정할 수 있도록 설계된 오픈소스 프로젝트입니다.  
   - **문제 해결**: Kubernetes 클러스터에서 복잡한 HTTP(S) 트래픽 관리와 라우팅을 효율적으로 처리하며, 동적 구성 업데이트를 통해 다양한 트래픽 요구사항을 해결합니다. 여러 팀이 사용하는 클러스터에서 안전하게 다중 Ingress 구성을 지원합니다.  
   - **특징**  
     - Envoy 기반 Ingress 컨트롤러: Envoy를 사용하여 Kubernetes에서 HTTP 및 HTTPS 트래픽을 처리하며, 성능과 확장성을 제공  
     - 동적 재구성: 트래픽 규칙을 실시간으로 업데이트할 수 있으며, Kubernetes 클러스터 내 서비스 변경 사항에 유연하게 대응  
     - TLS 관리 및 보안: TLS 인증서를 자동으로 관리하고 갱신하여 보안 정책을 쉽게 적용  
   - **사용 사례**: Contour는 Kubernetes 클러스터에서 Ingress 컨트롤러로 사용되어 HTTP 및 HTTPS 트래픽을 효율적으로 처리하고, Envoy의 성능을 활용하여 서비스 간 트래픽을 안전하고 효과적으로 관리하는 데 사용됩니다. 특히 멀티팀 Kubernetes 클러스터에서 Ingress 설정을 관리할 때 유용합니다.  
   - [Contour 문서](https://projectcontour.io/docs/1.30/﻿)  
<br>