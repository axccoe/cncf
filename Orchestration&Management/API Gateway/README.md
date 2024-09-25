# API Gateway 
 

1. **Emissary Ingress** (CNCF Incubating)

<br>
<br>


# API Gateway       


### 1. **Emissary Ingress** (CNCF Incubating)  
<img src="./image/image.png" alt="Emissary Ingress" width="100"/>  

   - **설명**: Emissary Ingress는 Kubernetes 클러스터에서 API 게이트웨이 역할을 하는 오픈소스 솔루션입니다. 특히 Envoy 프록시를 기반으로 구축되어 있으며, 마이크로서비스 간의 트래픽을 효율적으로 관리하고, API 요청을 라우팅하는 데 최적화되어 있습니다.  
   - **문제 해결**: Emissary Ingress는 마이크로서비스 아키텍처에서 복잡한 API 요청을 관리하고, 외부 트래픽을 내부 서비스로 안전하게 라우팅하는 문제를 해결합니다. 또한 확장 가능한 API 관리와 보안 기능을 제공하여 Kubernetes 클러스터에서 트래픽을 안정적으로 제어합니다.  
   - **특징**  
     - Envoy 기반 게이트웨이: Envoy 프록시를 기반으로 고성능의 API 라우팅과 트래픽 관리 기능을 제공하며, 높은 안정성과 확장성을 보장  
     - 고급 트래픽 관리: A/B 테스트, Canary 배포, 트래픽 분할 등의 기능을 지원하여 API 요청을 세밀하게 제어하고 관리  
     - 통합 보안: TLS 인증, JWT 인증을 통해 API 요청을 안전하게 처리하며, 외부 트래픽에 대한 보안을 강화  
   - **사용 사례**: Emissary Ingress는 Kubernetes 클러스터에서 API 요청을 효율적으로 처리하고, 서비스 간의 트래픽을 안전하게 관리해야 하는 환경에서 사용됩니다. 마이크로서비스 간의 API 관리 및 보안을 강화하는 데 적합하며, 외부 트래픽을 내부 서비스로 안전하게 라우팅하는 데 유용합니다.  
   - [Emissary Ingress 문서](https://www.getambassador.io/docs/emissary)  
<br>