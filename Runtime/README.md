# Runtime

이 폴더에는 클라우드 네이티브 환경에서 컨테이너를 실행하고, 네트워크 통신을 관리하며, 스토리지를 제공하는 다양한 도구들이 포함되어 있습니다. 각 폴더는 컨테이너 런타임, 클라우드 네이티브 네트워크, 스토리지 등을 관리하는 데 사용됩니다.

## 목차
1. [Cloud Native Network](#1-cloud-native-network)  
2. [Cloud Native Storage](#2-cloud-native-storage)  
3. [Container Runtime](#3-container-runtime)  

---

## 1. Cloud Native Network  

이 폴더에는 클라우드 네이티브 환경에서 네트워크 통신을 관리하는 도구들이 포함되어 있습니다. 애플리케이션 간의 통신을 안전하게 유지하고, 네트워크 성능을 최적화할 수 있습니다.

- **Cilium**: eBPF를 기반으로 하여 Linux 커널에서 네트워크 및 보안 정책을 적용하는 네트워킹 솔루션
- **CNI (Container Network Interface)**: 컨테이너 네트워킹을 위한 표준 인터페이스로, 다양한 네트워크 플러그인과 호환

---

## 2. Cloud Native Storage  

이 폴더에는 클라우드 네이티브 환경에서 데이터를 안전하게 저장하고 관리하는 스토리지 도구들이 포함되어 있습니다. 블록, 파일, 오브젝트 스토리지 등 다양한 스토리지 유형을 지원합니다.

- **Rook**: Kubernetes에서 분산 스토리지를 관리하기 위한 오픈소스 스토리지 오케스트레이터
- **CubeFS**: 다양한 프로토콜(S3, POSIX, HDFS)을 지원하는 확장 가능한 클라우드 네이티브 분산 파일 시스템
- **Longhorn**: 경량화된 분산 블록 스토리지 시스템으로, Kubernetes 상에서 블록 스토리지 관리를 쉽게 수행

---

## 3. Container Runtime  

이 폴더에는 컨테이너화된 애플리케이션을 실행하고 관리하는 도구들이 포함되어 있습니다. 클라우드 네이티브 환경에서 다양한 컨테이너 런타임을 지원합니다.

- **containerd**: 컨테이너의 수명 주기를 관리하는 고성능 컨테이너 런타임
- **CRI-O**: Kubernetes CRI(Container Runtime Interface)를 구현하여 경량화된 컨테이너 런타임을 제공
