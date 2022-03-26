kubectl
- k8s cluster 관리하는 동작하는 Command Line Interface(CLI)
- kubectl 지원 명령어 
  - k8s 자원 생성, 업데이트, 삭제 : create, update, delete
  - 디버그, 모니터링, 트러블 슈팅 : log, exec, cp, top, attach
  - cluster 관리 : cordon, top, drain, taint
- kubectl Cheat Sheet 참고

기본 사용법
- kubectl command type name flags
  - command: 자원에 실행하려는 동작. create, get, delete, apply, run, exec, attach, port-forward, logs, edit, config
  - type: 자원 타입. pod, service, deploy, ingress, pv, 
  - name: 자원 이름
  - flag: 부가적으로 설정할 옵션