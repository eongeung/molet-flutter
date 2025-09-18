# 🛰️ Molet

**Molet**는 자율주행 차량 호출 서비스와 자체 발행 토큰(MYT) 기반 지갑을 결합한 모빌리티 결제 플랫폼입니다.
사용자는 카카오 SSO로 로그인해 지갑을 발급받고, 호출 → 탑승(QR) → 자율주행 → 결제 → 송금까지 모두 앱 하나로 이용할 수 있습니다.

## 🚀 Features

카카오 SSO 로그인 및 지갑 생성 (초기 100.00000 MYT 지급)

출발·도착 설정 → ETA·예상 요금(MYT) 안내 → 차량 배차

QR 스캔 탑승 → 자율주행 → QR 하차 후 결제

토큰 기반 송금 및 결제 (잔액 부족 시 친구에게 송금 요청)

관리자 대시보드 (발행·유통량, 거래 내역, 사용자 관리)

## ⚙️ Tech Stack

Frontend: Flutter, React

Backend: Spring Boot, MySQL, Docker

Blockchain: Geth (Clique PoA, ERC-20 기반 MYT 토큰)

Hardware: Raspberry Pi 4, 카메라·LiDAR·DC모터·LED/부저, QR 스캐너

## 📂 Repository

Frontend: https://github.com/motowallet/molet-flutter
Frontend: https://github.com/motowallet/molet-fe
Backend: https://github.com/motowallet/molet-be
