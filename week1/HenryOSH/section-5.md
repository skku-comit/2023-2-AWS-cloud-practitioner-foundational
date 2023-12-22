# Section 5. EC2 - Elastic Compute Cloud

### 들어가기에 앞서...
### AWS Budget 설정하는 법?
     Root 계정 - Billing and Cost Management - Budgets - Create budget
     
     IAM 계정으로 조회하고 싶으면 Root 계정에서 Access 허용해야함!

    (charges by service 난 없고 charges by account만 있음. 체크 요망.)
  


## 1. EC2란 무엇인가?

- Renting virtual machunes(EC2) = EC2 instances, EBS, ELB, ASG (뒤에서 배울 예정)

- EC2 instances는 ASW로부터 서버를 빌리는 것이다. 주문서와 비슷함. 옵션 설정 가능

- OS, CPU, RAM, Storage, Network, Firewall(security group), Bootstrap(EC2 User Data) 등을 커스터마이징 할 수 있다.

### 1.1. EC2 Instance의 종류

- 표기법

- 종류 ~~

## 2. Security Groups

- Firewall attached to the EC2 instance

- input과 output을 책임진다

- allow rule 로만 이루어짐 (어디서 왔는지 IP 주소 or 또다른 SG 참조함)

- 꿀팁: SSH Access를 위해 따로 하나의  security group을 만드는 게 좋다.

  ### 2.1. 포트 이름 의미
      22 = SSH (Secure Shell) - log into a Linux instance

      21 = FTP (File Transfer Protocol) – upload files into a file share

      22 = SFTP (Secure File Transfer Protocol) – upload files using SSH

      80 = HTTP – access unsecured websites

      443 = HTTPS – access secured websites

      3389 = RDP (Remote Desktop Protocol) – log into a Windows instance

## 3. EC2 User Data

- Script launched at the first start of an instance
  
## 4. SSH

- start a terminal into our EC2 Instances (port 22)

### 맥 터미널로 aws 리눅스 ssh 사용하여 접속하는 명령어
     chmod 0400 EC2Tutorial.pem
     ssh -i EC2Tutorial.pem ec2-user@(Public IPv4 address)  
  
## 5. EC2 Instance Role

- link to IAM roles

- 절대 aws 리눅스 환경에서 aws configure 명령어로 나의 로그인 정보 입력하지 말것.! 위험함!

## 6. Purchasing Options

- On-Demand, Spot, Reserved (Standard + Convertible), Dedicated Host, Dedicated Instance


<hr>

## Helpful Resources
