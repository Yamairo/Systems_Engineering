  ```mermaid
classDiagram
    class Accelerometer{
        +initialisatieSensoren(): void
        +verschilSnelheid(): void
        +crash(): void
        -imu: Zumo32U4IMU
        -snelheid: int
    }
```