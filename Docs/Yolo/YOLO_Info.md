1. 조사 주제
   - YOLO

2. 사용 목적
   - Object detection
   - 위급상황 사물 인식 후 긴급회피 동작
   - 위급상황 외 ACC(Adaptive Cruise Control)

3. 내용
   * TX2 기준
   * SSD about 25fps
   * YOLOv2-tiny will be to use

   - YOLOv3 about 3.3fps
   - YOLOv3-tiny maximum about 12fps
   - YOLOv2 about 6~7fps
   - YOLOv2-tiny about 16~17fps   - Ubuntu 16.04 LTS에서의 참고자료가 많음

4. 한계점
   - tiny버전은 속도가 빠르고 일반욜로보다 가볍지만 정확성이 떨어짐

5. 결론
   - 구현은 YOLO를 사용
   - 추후 SSD적용 가능 분석
