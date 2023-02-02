# AWS EKS 활용한 3-Tier 웹 서비스 운영
     AWS Infra 구축
     WEB-WAS-DB를 Mod_jk로 연동하여, 컨테이너 기반 3-Tier 웹 서비스 운영

     
## 📆 진행 기간
- 2022.10.10 ~ 2022.10.14

</br>

## 🛠 사용 기술
#### CSP
<img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=flat-square&logo=Amazon AWS&logoColor=white"> <!--AWS-->
#### OS
<img src="https://img.shields.io/badge/Amazon Linux 2-232F3E?style=flat-square&logo=Amazon AWS&logoColor=white"> <!--amazon linux-->
#### Database
<img src="https://img.shields.io/badge/mysql-4479A1?style=flat-square&logo=mysql&logoColor=white"> <!--Mysql-->
#### Container
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"> <!--Docker-->
#### Container Orchestration
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=Kubernetes&logoColor=white"> <!--K8S-->
<img src="https://img.shields.io/badge/Amazon EKS-FF9900?style=flat-square&logo=Amazon EKS&logoColor=white"> <!--Amazon EKS-->
#### Framework
<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"> <!--Spring-->
#### Team Collabolation Tool
<img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"> <!--Notion-->
#### Drawing Tool
<img src="https://img.shields.io/badge/Drawio-000000?style=flat-square&logo=Drawio&logoColor=white"> <!--Draw.io-->

</br>

## 💁‍♂️ 담당 업무
- AWS Infra 구축
    - VPC, EC2, RDS, ALB, EKS, ECR, Route53, IAM
- WEB-WAS-DB를 연동하여, 3-Tier 구성
- Dockerfile을 작성하여, WEB/WAS를 멀티 스테이지 빌드 후 Dockerhub에 Push
- Container Image의 이름과 태그를 변경 후 AWS ECR에 Push
- K8S yamlfile을 작성하여, AWS EKS 환경에 웹 서비스를 배포 및 운영

</br>

## 📖 상세 내용 
### Infra Architecture
![image](https://user-images.githubusercontent.com/110655823/215550928-c42b160a-0f88-411c-8297-4765c9850b4a.png)
> - 관리자는 Local(Powershell)을 통해 k8s mgnt로 접속하여 EKS 환경에 웹 서비스를 배포 및 운영
> - 고객은 route53에 등록된 도메인을 통해 웹 서비스 이용
> - RDS 이중화 구성

</br>

## 🔗 구축 과정
### - Notion Link(https://www.notion.so/AWS-EKS-3-Tier-3dd3d9a99aa842acb3212891276571c5)

</br>

---

### [👈 Go back](https://github.com/hyunjaebok)
