# Container Runtime   
 

1. **containerd** (CNCF Graduated)
2. **CRI-O** (CNCF Graduated)


<br>
<br>


# Container Runtime     


### 1. **containerd** (CNCF Graduated)  
<img src="./image/image.png" alt="containerd" width="100"/>  

   - **설명**: containerd는 클라우드 네이티브 환경에서 컨테이너 실행을 관리하는 경량 오픈소스 컨테이너 런타임입니다. Docker와 Kubernetes의 기본 런타임으로 사용되며, 이미지 풀링, 저장, 실행, 네트워크 관리, 스토리지와 같은 핵심 기능을 제공합니다.  
   - **문제 해결**: containerd는 컨테이너 실행과 관련된 복잡한 작업을 간소화하여, 안정적인 컨테이너 배포와 관리 환경을 제공합니다.  
   - **특징**  
     - 가벼운 런타임: 경량의 컨테이너 런타임으로, 리소스 효율성이 높고 빠른 실행을 지원  
     - Kubernetes와 통합: Kubernetes에서 CRI(Container Runtime Interface)를 사용하여 쉽게 연동 가능  
     - 확장 가능성: 플러그인 아키텍처를 통해 다양한 기능 확장이 가능, 컨테이너 실행, 이미지 관리 등을 효율적으로 관리  
   - **사용 사례**: containerd는 Kubernetes 클러스터에서 컨테이너 실행을 관리하며, 가상화된 애플리케이션의 배포 및 운영에 필수적인 역할을 합니다.  
   - [containerd 문서](https://containerd.io/docs/)  
<br>

### 2. **CRI-O** (CNCF Graduated)  
<img src="./image/image-1.png" alt="CRI-O" width="100"/>  

   - **설명**: CRI-O는 Kubernetes에 최적화된 경량 컨테이너 런타임으로, OCI(Open Container Initiative) 표준을 준수하여 Kubernetes가 컨테이너를 관리할 수 있도록 지원하는 컨테이너 런타임입니다. Kubernetes가 컨테이너를 실행하고 관리하는 데 필요한 최소한의 기능만 제공하며, 기존 Docker 런타임의 복잡성을 줄인 대안으로 사용됩니다.  
   - **문제 해결**: Kubernetes에서 컨테이너를 실행할 때, Docker의 복잡한 기능을 생략하고, 컨테이너 런타임에 필요한 핵심 기능만 제공하여 성능과 리소스 사용을 최적화합니다. CRI-O는 다양한 OCI 호환 런타임을 사용할 수 있도록 설계되었습니다.  
   - **특징**  
     - Kubernetes 최적화: CRI 표준을 구현하여, Kubernetes와의 원활한 통합을 지원하며, Kubernetes Pod의 컨테이너 실행을 관리  
     - 경량 설계: Docker의 모든 기능을 포함하지 않고, 컨테이너 런타임에 필요한 필수 요소만 제공하여 성능을 향상  
     - OCI 표준 준수: CRI-O는 모든 OCI 호환 컨테이너 런타임과 호환되며, 다양한 컨테이너 이미지를 지원
     - 네트워킹 및 보안: CNI(Container Network Interface)와 다양한 보안 도구(Seccomp, SELinux, Capabilities)를 통해 네트워킹 및 보안 정책을 관리   
   - **사용 사례**: CRI-O는 Kubernetes 클러스터에서 경량화된 컨테이너 런타임을 필요로 하는 환경에서 사용되며, 대규모 클러스터 운영에서 성능을 극대화하는 데 적합합니다.  
   - [CRI-O 문서](https://cri-o.io/)  
<br>