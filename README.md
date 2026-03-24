# Siljan kommune – IoT

Sensorer og datavisning for Siljan kommune.

## Badetemperatur

Automatisk badetemperaturmåling med ESP32 og BLE-sensorer.

| Fil | Bruk |
|-----|------|
| `badetemp-overbotjonna.html` | Fullversjon med BLE-avlesning og QR-kode (for bruk på badeplassen) |
| `badetemp-overbotjonna-iframe.html` | Kompakt visning for embedding på siljan.kommune.no |

### Pilot: Øverbøtjønna

- Sensor: FireBeetle 2 ESP32-C6 + DS18B20 + solcelle + batteri
- Data: Supabase (PostgreSQL)
- Visning: GitHub Pages + iframe på kommunens nettside

### Kontakt

Teknisk drift, Siljan kommune
