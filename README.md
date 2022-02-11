# docker-kubernetes

## 공부환경 : ncloud 무료 체험판(네이버 짱짱)

네이버는 AWS나 GKE와는 다르게 쿠버네티스 클러스터를 만들면 cluster를 구성가능한 configure.yaml 파일을 제공해준다.

해당 파일을 다운받고

export KUBECONFIG=$HOME/본인의 kubeconfig 파일.yaml
(보통 default로 다운 받으면 경로는 $HOME/kubeconfig-뭐라뭐라.yaml)

로 환경변수 설정해주면 어느 클라우드 서비스보다 간편히 클러스터 구성이 가능하다.
