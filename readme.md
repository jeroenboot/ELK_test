Simple test to collect logging from FortiGate and store in Logstash
Some functions added, (normalized timestamp, added key and values, collected GeoIP on public IP addresses) as a prototype


```
config log syslogd setting
    set status enable
    set server "192.168.192.1"
    set port 5140
end
```

<img width="1736" alt="image" src="https://github.com/jeroenboot/ELK_test/assets/23233001/19089aea-0c08-42eb-8770-0d80d6bb966f">
