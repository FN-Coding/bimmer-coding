# 360D-LicLciColorProfiles

This document contains color profiles for BMW's 360D-LicLci system, defining the colors associated with each profile.

## Color Profiles
- **WHITE**: 00
- **BRONZE**: 01
- **ORANGE**: 02
- **BLUE**: 03
- **GREEN**: 04
- **LILAC**: 05

## Byte Positions
- **BRONZE**: 0, 1

- **BRONZE-WHITE**: 2, 3

- **ORANGE**: 4, 5

- **ORANGE-WHITE**: 6, 7

- **WHITE**: 8, 9

- **BLUE**: 10, 11

- **BLUE-WHITE**: 12, 13

- **GREEN**: 14, 15

- **GREEN-WHITE**: 16, 17

- **LILAC**: 18, 19

- **LILAC-WHITE**: 20, 21

## Custom Profiles
- **BRONZE-WHITE => BRONZE-BLUE**: Red - Blue.
  - Byte Positions: 2 and 3.
  - Byte Values: 03 and 01.

- **BLUE-WHITE => BLUE-BRONZE**: Blue - Red.
  - Byte Positions: 12 and 13.
  - Byte Values: 01 and 03.

- **GREEN-WHITE => GREEN-LILAC**: Aqua - Deeppink.
  - Byte Positions: 16 and 17.
  - Byte Values: 04 and 05.

- **LILAC-WHITE => LILAC-GREEN**: Deeppink - Aqua.
  - Byte Positions: 20 and 21.
  - Byte Values: 05 and 04.

- **Custom Profiles String**:
  ```
  01, 01, 03, 01, 02, 02, 00, 02, 00, 00, 03, 03, 01, 03, 04, 04, 04, 05, 05, 05, 05, 04
  ```

## Note
  - Customize your lighting colors by following 360A-LicLciColorLibrary.md.

