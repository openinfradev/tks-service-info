
# SK Telecom TKS (Kubernetes & App Modernization)

> [!IMPORTANT]
> Empower your team <br> with a **Production-grade Kubernetes** and **App Modernization capability** on **any infrastructure** <br> with just **One Click**

## TKS 기술소개

SK텔레콤은 가상화를 4G/5G에 선도적으로 적용해 왔고, 이를 위해 OpenStack, Kubernetes와 같은 복잡한 가상화 관리 서비스를 효율적으로 관리하는 기술을 꾸준히 연구해 왔습니다. SK텔레콤은 Container 기술을 활용하여, 복잡한 소프트웨어의 라이프사이클 관리 및 다수의 모듈간 종속성 문제를 해결해왔습니다. 그리고, 이러한 노력에 대한 결과물은 여러 사람들이 널리 이롭게 사용하도록 오픈소스로 공개하고 있습니다.

SK텔레콤에서 만든 가장 대표적인 오픈소스 소프트웨어는 <a href="https://openinfradev.github.io/decapod-docs/" target="_blank">Decapod</a> (Declarative Application Orchestration & Delivery) 입니다. Decapod는 다수의 소프트웨어로 구성된 복잡한 서비스를 Containerization를 통해 선언적으로 관리하는 GitOps CD pipeline 입니다.

!!! success "SKT의 TKS는 Decapod 기술을 기반으로, Kubernetes Cluster와 Kubernetes를 운영하기 위한 Add-on (CNI, CSI, Ingress Controller등)과 서비스들(Monitoring, Service Mesh, Policy, MLOps등)을 All-in-One으로 제공하는 통합 플랫폼입니다."

SKT TKS의 주요 특징은 다음과 같습니다.

- Hybrid, Multi Cloud 지원
- SKT Kubernetes Engine 및 CSP Managed Kubernetes (EKS) 라이프사이클 자동관리
- SSO 및 Fine-grained 권한관리 (멀티테넌시)
- All-in-One Package
- Managed PaaS 서비스 구현

![TKS](../assets/images/tksre21arch.png)

## TKS 상품소개

TKS는 두 개의 상품으로 제공됩니다.

- TKS Cloud Service : AWS상에서 제공되는 SaaS형 상품
- TKS Enterprise Solution : Enterprise 기업 고객을 위한 구축형 솔루션

본 문서는 이 중에서 **TKS Cloud Service**에 대한 설명을 담고 있습니다.

!!! tip "TKS에 대한 추가 정보는 <a href="https://www.sktenterprise.com/product/detail/236" target="_blank">SKT Enterprise 홈페이지</a>에서 확인 가능합니다."
