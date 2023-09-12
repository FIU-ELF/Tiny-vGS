*detailed descriptions for each section and the meaning of the labels incoming

The follow is the JSON message structure that is streamed to EventHubs for the Microservice monitoring the health of the Raspberry Pi. 

```yaml
{
"msg_timestamp": time,
"name": name,
"label": Tinyvgs,
"payload": {
  "Chip_temp": {
    "Chip_temp": float(payload_values[&quot;Chip_temp&quot;]),
    "measurement_timestamp": time},
  "Clock_rate": {
    "Clock_rate": float(payload_values[&quot;Clock_rate&quot;]),
    "measurement_timestamp": time},
  "Under_voltage_detected": {
    "Under_voltage_detected": int(payload_values[&quot;Under_voltage_detected&quot;]),
    "measurement_timestamp": time},
  "Arm_Freq_cap": {
    "Arm_Freq_cap": int(payload_values[&quot;Arm_Freq_cap&quot;]),
    "measurement_timestamp": time},                
  "Currently_throttled": {
    "Currently_throttled": int(payload_values[&quot;Currently_throttled&quot;]),
    "measurement_timestamp": time},              
  "Soft_limit_active": {
    "Soft_limit_active": int(payload_values[&quot;Soft_limit_active&quot;]),
    "measurement_timestamp": time},                                      
  "Under_voltage_happened": {
    "Under_voltage_happened": int(payload_values[&quot;Under_voltage_happened&quot;]),
    "measurement_timestamp": time},  
  "Arm_Freq_cap_occurred": {
    "Arm_Freq_cap_occurred": int(payload_values[&quot;Arm_Freq_cap_occurred&quot;]),
    "measurement_timestamp": time},  
  "Throttling_occurred": {
    "Throttling_occurred": int(payload_values[&quot;Throttling_occurred&quot;]),
    "measurement_timestamp": time},  
  "Soft_Temp_limit_occurred": {
    "Soft_Temp_limit_occurred": int(payload_values[&quot;Soft_Temp_limit_occurred&quot;]),
    "measurement_timestamp": time},  
  "Core_volt": {
    "Core_volt": float(payload_values[&quot;Core_volt&quot;]),
    "measurement_timestamp": time},
  "disk_free_gb": {
    "disk_free_gb": float(payload_values[&quot;disk_free_gb&quot;]),
    "measurement_timestamp": time},
  "disk_total_gb": {
    "disk_total_gb": float(payload_values[&quot;disk_total_gb&quot;]),
    "measurement_timestamp": time},
  "disk_percent": {
    "disk_percent": float(payload_values[&quot;disk_percent&quot;]),
    "measurement_timestamp": time},
  "memory_available": {
    "memory_available": float(payload_values[&quot;memory_available&quot;]),
    "measurement_timestamp": time},
  "memory_total": {
    "memory_total": float(payload_values[&quot;memory_total&quot;]),
    "measurement_timestamp": time},
  "memory_load": {
    "memory_load": float(payload_values[&quot;memory_load&quot;]),
    "measurement_timestamp": time},
  "CPU_percent": {
    "CPU_percent": float(payload_values[&quot;CPU_percent&quot;]),
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
      "Gain": float(payload_values[&quot;gain&quot;]),
      "measurement_timestamp": time},
    "Frequency Value": {
      "healthStatus": "good",
      "Frequency": float(payload_values[&quot;freq&quot;]),
      "measurement_timestamp": time},
    "Omega Value": {
      "healthStatus": "good",
      "Omega": float(payload_values[&quot;omega&quot;]),
      "measurement_timestamp": time},
    "Vit Value": {
      "healthStatus": "good",
      "Vit": float(payload_values[&quot;vit&quot;]),
      "measurement_timestamp": time},                
    "RS Value": {
      "healthStatus": "good",
      "RS": float(payload_values[&quot;rs&quot;]),
      "measurement_timestamp": time},              
    "Skipped": {
      "healthStatus": "good",
      "Skipped": float(payload_values[&quot;skipped&quot;]),
      "measurement_timestamp": time},                                      
    "Ok": {
      "healthStatus": "good",
      "Ok": float(payload_values[&quot;ok&quot;]),
      "measurement_timestamp": time},
    },
  }
```

