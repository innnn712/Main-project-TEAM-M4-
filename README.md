[프로젝트 구조]

DLthon/
├── COCO_motorcycle (pixel).json   -- COCO 포맷 어노테이션 (폴리곤 세그멘테이션)
└── images/
    ├── night ride (N).png             -- 원본 이미지 (1920x1080, 200장)
    ├── night ride (N).png___fuse.png  -- 세그멘테이션 오버레이 시각화
    └── night ride (N).png___save.png  -- 세그멘테이션 마스크


[6개 클래스]

1. Road       - 주행 가능한 도로
2. Lane Mark  - 차선 표시
3. My bike    - 자신의 오토바이 (카메라 장착 차량)
4. Rider      - 다른 라이더/운전자
5. Moveable   - 이동 가능한 객체 (다른 차량 등)
6. Undrivable - 주행 불가 영역 (인도, 건물 등)


[데이터셋 정보]

- 이미지 수: 200장
- 해상도: 1920 x 1080
- 어노테이션 수: 2,305개
- 어노테이션 형식: COCO format (polygon segmentation, pixel 단위)
  
