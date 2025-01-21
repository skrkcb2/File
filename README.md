# File
### 1. Path Traversal:    
#### 특징: ../../ 같이 파일 상위로 올라는 명령을 파일 경로에 포함 시켜 최상단 파일을 탈취 하는 취약점  
#### 검증이 안된 코드 예시  
![image](https://github.com/user-attachments/assets/a657e9b6-07f1-4759-846c-e0da15fab407)  
#### 검증이 안된 코드 실행 결과
![s_traversal](https://github.com/user-attachments/assets/9ff8f377-d58b-4cf3-943a-e745fcaa8868)
#### 검증이 로직 추가 코드 예시
![트래버설](https://github.com/user-attachments/assets/ae07edbf-d4b8-4867-ba2d-37d7a09994a0)
#### 검증이 로직 추가 코드 실행 결과
![traversal2](https://github.com/user-attachments/assets/7333b558-fdc2-4bdc-a6ec-9a66b4c44453)
### 2. Unrestricted File Upload:
#### 특징: 파일 업로드시 확장자를 필터링을 실행 하지 않아 악성 코드가 올라가는 취약점
#### 검증이 안된 코드 예시  
![image](https://github.com/user-attachments/assets/a28ccf9c-dd86-4153-9c44-7e6c0cf9c374)
#### 검증이 로직 추가 코드 예시
![파일업로드](https://github.com/user-attachments/assets/109cd639-cbba-477f-a892-b4fdb659e2e8) ![확장자 추출](https://github.com/user-attachments/assets/0c85eeb2-53ed-4676-9961-f0b17286009c)






