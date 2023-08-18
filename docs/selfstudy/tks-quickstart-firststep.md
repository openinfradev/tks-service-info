# TKS 퀵스타트 (로그인과 초기설정)

## **로그인**
    TKS Console ([https://tks-console.sktelecom.com](https://tks-console.sktelecom.com))에 접근하면, 아래와 같은 로그인창이 보입니다.
    TKS 서비스 신청 후, 받은 **조직코드** 와 아이디는 **admin** , 비밀번호는 신청 후 받은 **임시비밀번호**을 사용해 주세요.
    > 최초 접속 후, 비밀번호 변경을 권고합니다.

![bootstrap](../assets/images/tks-login.png)

---
## **클라우드 계정 생성**
   TKS는 클라우드에 손쉽게 K8S Cluster와 필요한 Tool를 한번에 설치/자동관리해 줍니다.
   TKS는 K8S Cluster + 필요 Tool를 **스택** 이라 부릅니다.
   **스택**을 설치 하기 위해서는 설치할 클라우드를 지정해야 합니다.
   대상 클라우드를 지정하고 TKS가 관리하기 위한 Assume Role를 생성하는 과정을 **클라우드 계정 생성** 이라고 합니다.

클라우드 계정 관리는 상단 매뉴 ==설정== 을 통해 접근 가능합니다.
처음 클라우드 계정을 생성하는 경우, 아래 그림과 같은 화면이 나옵니다.

![bootstrap](../assets/images/tks-cloudaccount-0.png)

클라우드 계정 생성하기를 누르면, 아래와 같은 화면이 나옵니다.
사전준비에서 마련해 놓은 AWS 정보를 넣고 저장하면, **클라우드계정**이 생성됩니다.

==TKS는 Access Key를 저장하지 않습니다. AWS Assume Role를 사용하여, 고객의 비밀정보를 저장하지 않고 최소한의 필요 권한을 위임 받아 동작합니다.==
> AWS Assume role에 대한 자세한 설명은 [AWS IAM 문서](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_use.html)를 참조 하세요.

Session Token의 경우 MFA가 적용된 경우 추가로 입력해 하는 값 입니다.

>최근 보안을 위해서 MFA(Multi-Factor Authentication) 사용을 권고합니다. 만약 MFA가 적용된 IAM User가 만든 AWS Access Key를 사용할 경우, Session Token을 추가로 입력해야 합니다. Session Token은 AWS CLI로 생성 할 수 있습니다. 자세한 사항은 [AWS MFA 문서](https://repost.aws/knowledge-center/authenticate-mfa-cli)를 참고하십시요.


![bootstrap](../assets/images/tks-cloudaccount-c.png)