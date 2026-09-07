# STM32 ELRS / CRSF Integration

RadioMaster ELRS 수신기의 CRSF 프레임을 STM32에서 수신·해석하기 위한 초기 실험 저장소다.

## 현재 상태

이 저장소에는 설명만 남아 있으며 재현 가능한 펌웨어 소스는 포함되어 있지 않다. 이후 구현은 Hexapod 통합 펌웨어로 이동했으며, 현재 코드는 [RRC Hexapod Robot](https://github.com/robot-research-club-rrc/HEXAPOD-ROBOT) 저장소에서 관리한다.

통합 구현은 STM32F446RE의 UART 수신, CRSF 프레임 파싱, 채널 보정, 조종 명령 변환과 failsafe 처리를 포함한다.

> 이 저장소는 초기 작업의 위치를 보존하는 안내용 저장소다. 실제 코드 검토에는 위 통합 저장소를 사용해야 한다.
