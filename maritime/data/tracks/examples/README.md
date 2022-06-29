# Example CSV Files for Maritime Team Data Set #1
## Filenames: Track MMSI & Status
Filenames are a composite of the AIS track MMSI and the track navigation status.
| Attribute | Data type        | Description                                                |
|-----------|------------------|------------------------------------------------------------|
| mmsi      | integer          | MMSI identifier for vessel                                 |
| status    | integer          | Navigational status                                        |
## CSV Fields
The csv fields follow the normal AIS data metadata descriptions.
| Attribute | Data type        | Description                                                |
|-----------|------------------|------------------------------------------------------------|
| turn      | double precision | Rate of turn, right or left, 0 to 720 degrees per minute   |
| speed     | double precision | Speed over ground in knots (allowed values: 0-102.2 knots) |
| course    | double precision | Course over ground (allowed values: 0-359.9 degrees)       |
| heading   | integer          | True heading in degrees (0-359), relative to true north    |
| lon       | double precision | Longitude (georeference: WGS 1984)                         |
| lat       | double precision | Latitude                                                   |
| t         | bigint           | timestamp in UNIX epochs                                   |

