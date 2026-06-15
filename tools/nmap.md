# nmap basics

## service detection

```bash
nmap -sV target_ip
```

## os detection

```bash
nmap -O target_ip
```

## aggressive scan

```bash
nmap -A target_ip
```

## notes

- -sS stealth scan
- -Pn skip ping
- -p- all ports
