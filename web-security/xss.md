# xss basics

## what is xss

cross site scripting is a web vulnerability that allows attackers to inject malicious scripts into web pages

## types of xss

### reflected xss
payload reflected immediately

### stored xss
payload stored in database

### dom xss
client side javascript based

## basic payload

```html
<script>alert(1)</script>
```

## prevention

- input validation
- output encoding
- content security policy

## notes

xss can lead to session hijacking and account compromise
