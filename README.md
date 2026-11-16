
#AI-Infra-Lab
"이 리포지토리는 Terraform+Docker를 이용한 인프라 자동화 실습용입니다 모든 내용은 티스토리 블로그에 함께 포스팅하고있습니다. https://makesworldhappy.tistory.com/"

구분기술 스택
OS	Windows 11
Linux Environment	WSL2, Ubuntu
Container	Docker, Docker Desktop
Orchestration	Kubernetes, kind, kubectl
IaC	Terraform
Web Server	Nginx
Version Control	Git, GitHub
IDE	Visual Studio Code
Local LLM	GPT-OSS-20B
Hardware	AMD Ryzen 9 7950X3D, 64GB RAM, NVIDIA RTX 5070 Ti

기본 디렉토리
C:\ai-infra-lab

주요파일
main.tf	Terraform 설정
.terraform/	Terraform provider cache (gitignore)
README.md


티스토리 내용
1일차 https://makesworldhappy.tistory.com/22 VMware 엔지니어에서 AI 인프라 엔지니어로 도: 실전 구축 프로젝트-1-                 실행 계기와 프로젝트기반 구성
2일차 https://makesworldhappy.tistory.com/23 AI인프라 랩 테스트 -2-                                                        CI/CD를 위해 Terraform Git과 연동 .gitignore활용 스테이징->커밋->푸시
3일차 https://makesworldhappy.tistory.com/24 AI인프라 랩 테스트 (w.Kubernetes&Terraform feat.PowerShell7.x자동완성)-3-      kubernets kind nginx배포/포트포워딩

최신
4일차 https://makesworldhappy.tistory.com/25 AI인프라 랩 테스트 -4-                                                        README.md를 생성하고 푸시하기까지. 간단하게 복습