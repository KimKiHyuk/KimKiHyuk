# 쿠버네티스 Hyper-v 클러스터 구축

사용한 기술: Docker, cloud, k8s, system
수행기관: 개인프로젝트
프로젝트 기간: 2020/01/01

## 쿠버네티스 Hyper-v 클러스터 구축

쿠버네티스 공부를 위해 flannel 네트워크를 사용하여 VM 클러스터를 구축

🏨 수행 기관 : 개인 프로젝트

🗓️ 개발 기간 : 1개월

💾 소스코드 :

[Hyper-v 환경에서 쿠버네티스 master-worker 클러스터 구축하기](https://medium.com/@keyhyuk.kim/hyper-v-%ED%99%98%EA%B2%BD%EC%97%90%EC%84%9C-%EC%BF%A0%EB%B2%84%EB%84%A4%ED%8B%B0%EC%8A%A4-master-worker-%ED%81%B4%EB%9F%AC%EC%8A%A4%ED%84%B0-%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0-b7aead20132f)

🔧 사용 기술 : Go, script

---

## 개발 내역

- Helm 차트를 활용한 Flannel 네트워크 설정
- Hyper-v 네트워크 구성
- 하트비트 체크용 Go 도커 어플리케이션 개발