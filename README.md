# StyleCast_Python
Python-based outfit recommendation system that combines weather data, emotion analysis, and web crawling to generate personalized styling suggestions.

## ✨Overview
날씨·계절·기온 정보와 사용자 이미지를 기반으로  
감정·성별을 분석해 상황에 맞는 착장을 추천하는 Python 기반 착장 예보 시스템입니다.

외부 API와 웹 크롤링을 연동해 조건에 맞는 코디 이미지를 자동 수집하고,  
사용자별 착장 기록을 관리하는 서비스 형태로 구현했습니다.

## ⚙️Tool & Language
- Python  
- Flask  
- OpenWeather API  
- AWS Rekognition API  
- Selenium  
- HTML / CSS  
- JSON  

## 🧱Architecture
- OpenWeather API 기반 날씨·계절·기온 정보 수집  
- AWS Rekognition을 활용한 감정·성별 분석  
- 분석 결과 기반 검색 키워드 생성 로직  
- Selenium을 활용한 코디 이미지 크롤링  
- Flask 기반 웹 서비스 및 사용자 세션 관리  

## 🪄Verification & Performance
- 날씨·감정·성별 정보를 결합한 개인 맞춤형 착장 추천 기능 구현  
- 조건 기반 키워드 생성으로 코디 이미지 자동 수집 및 저장  
- 사용자별 착장 기록과 메모 데이터를 JSON 구조로 안정적으로 관리  

## 📍Key Features
- 감정·날씨·계절을 반영한 개인화된 착장 추천  
- 웹 크롤링 기반 코디 이미지 자동 수집  
- 사용자 로그인 및 기록 관리 기능  
- Python 기반 데이터 처리와 웹 서비스 구현 경험 확보

## 💡주의사항!
- OPENWEATHER_API_KEY 설정방법
1. server.py과 같은 경로에 .env라는 이름의 텍스트 파일 생성. 
2. 파일 내용은 OPENWEATHER_API_KEY=키 (썽따옴표, 띄어쓰기 없음)로 저장
