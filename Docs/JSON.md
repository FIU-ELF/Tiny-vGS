*detailed descriptions for each section and the meaning of the labels incoming

## Raspi data field description

The follow is the JSON message structure that is streamed to EventHubs for the Microservice monitoring the health of the Raspberry Pi. 
| Month    | Description |
| -------- | ------- |
| Chip_temp  | womp    |
| Clock_rate | womp     |
| Under_voltage_detected    | womp    |
|    | womp    |
|    | womp    |
|    | womp    |
|    | womp    |
|    | womp    |
|    | womp    |
|    | womp    |
|    | womp    |
|    | womp    |
|    | womp    |
|    | womp    |
|    | womp    |
|    | womp    |
|    | womp    |
|    | womp    |


## Raspi JSON output format
```yaml
{
"msg_timestamp": time,
"name": name,
"label": Tinyvgs,
"payload": {
  "Chip_temp": {
    "Chip_temp": float(payload_values["Chip_temp"]),
    "measurement_timestamp": time},
  "Clock_rate": {
    "Clock_rate": float(payload_values["Clock_rate"]),
    "measurement_timestamp": time},
  "Under_voltage_detected": {
    "Under_voltage_detected": int(payload_values["Under_voltage_detected"]),
    "measurement_timestamp": time},
  "Arm_Freq_cap": {
    "Arm_Freq_cap": int(payload_values["Arm_Freq_cap"]),
    "measurement_timestamp": time},                
  "Currently_throttled": {
    "Currently_throttled": int(payload_values["Currently_throttled"]),
    "measurement_timestamp": time},              
  "Soft_limit_active": {
    "Soft_limit_active": int(payload_values["Soft_limit_active"]),
    "measurement_timestamp": time},                                      
  "Under_voltage_happened": {
    "Under_voltage_happened": int(payload_values["Under_voltage_happened"]),
    "measurement_timestamp": time},  
  "Arm_Freq_cap_occurred": {
    "Arm_Freq_cap_occurred": int(payload_values["Arm_Freq_cap_occurred"]),
    "measurement_timestamp": time},  
  "Throttling_occurred": {
    "Throttling_occurred": int(payload_values["Throttling_occurred"]),
    "measurement_timestamp": time},  
  "Soft_Temp_limit_occurred": {
    "Soft_Temp_limit_occurred": int(payload_values["Soft_Temp_limit_occurred"]),
    "measurement_timestamp": time},  
  "Core_volt": {
    "Core_volt": float(payload_values["Core_volt"]),
    "measurement_timestamp": time},
  "disk_free_gb": {
    "disk_free_gb": float(payload_values["disk_free_gb"]),
    "measurement_timestamp": time},
  "disk_total_gb": {
    "disk_total_gb": float(payload_values["disk_total_gb"]),
    "measurement_timestamp": time},
  "disk_percent": {
    "disk_percent": float(payload_values["disk_percent"]),
    "measurement_timestamp": time},
  "memory_available": {
    "memory_available": float(payload_values["memory_available"]),
    "measurement_timestamp": time},
  "memory_total": {
    "memory_total": float(payload_values["memory_total"]),
    "measurement_timestamp": time},
  "memory_load": {
    "memory_load": float(payload_values["memory_load"]),
    "measurement_timestamp": time},
  "CPU_percent": {
    "CPU_percent": float(payload_values["CPU_percent"]),
    "measurement_timestamp": time},
    },
}
```

The follow is the JSON message structure that is streamed to EventHubs for the Microservice monitoring the health of the GOES Receive chain. 
```yaml
{
  "msg_timestamp": time,
  "name": name,
  "label": "Tinyvgs",
  "payload": {
    "Receiver Gain": {
      "healthStatus": "good",
      "Gain": float(payload_values["gain"]),
      "measurement_timestamp": time},
    "Frequency Value": {
      "healthStatus": "good",
      "Frequency": float(payload_values["freq"]),
      "measurement_timestamp": time},
    "Omega Value": {
      "healthStatus": "good",
      "Omega": float(payload_values["omega"]),
      "measurement_timestamp": time},
    "Vit Value": {
      "healthStatus": "good",
      "Vit": float(payload_values["vit"]),
      "measurement_timestamp": time},                
    "RS Value": {
      "healthStatus": "good",
      "RS": float(payload_values["rs"]),
      "measurement_timestamp": time},              
    "Skipped": {
      "healthStatus": "good",
      "Skipped": float(payload_values["skipped"]),
      "measurement_timestamp": time},                                      
    "Ok": {
      "healthStatus": "good",
      "Ok": float(payload_values["ok"]),
      "measurement_timestamp": time},
    },
  }
```

