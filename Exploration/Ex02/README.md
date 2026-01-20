
# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 정정채
- 리뷰어 : 황소리

# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - <img width="259" height="201" alt="image" src="https://github.com/user-attachments/assets/b74b81a4-3118-4c5c-8000-1a0159ed85c1" />
        - <img width="589" height="93" alt="image" src="https://github.com/user-attachments/assets/030689a9-5f2a-4cc0-94db-4d83e091df66" />
        - <img width="576" height="574" alt="image" src="https://github.com/user-attachments/assets/95e5f491-4f00-404e-923d-19940761ce99" />
    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="589" height="93" alt="image" src="https://github.com/user-attachments/assets/030689a9-5f2a-4cc0-94db-4d83e091df66" />
        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 학습된 라벨 데이터도 종류에 따라서 인식을 못할 수도 있음을 확인하였다. 예를들어, 말은 인식이 잘 되나 얼룩말은 인식이 잘 안되었다.
        - <img width="754" height="273" alt="image" src="https://github.com/user-attachments/assets/36e1e9b8-f6dd-4069-b207-fe904a1bd82e" />

        
- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="751" height="446" alt="image" src="https://github.com/user-attachments/assets/da276dc7-8c96-42b1-b0b4-eddbae0da6ff" />

        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - <img width="552" height="194" alt="image" src="https://github.com/user-attachments/assets/6656d72b-d2fd-483b-a82e-c655aa40f6ae" />


# 회고(참고 링크 및 코드 개선)
```
# sep_map 코드를 추가하여 두개 이상의 사물을 포커싱한 부분이 인상적이었습니다.

seg_map = np.isin(output_predictions_resized, object_num)
target_object_multi = [15, 2]
img_concat_4a = my_outfocusing(img_orig_4, target_object_multi, 20, model)

```
