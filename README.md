# Convert DNS zone file to AWS route53 terraform

## Description

Script to convert DNS zone file to AWS route53 terraform resource

## Usage

### Pipe

```
cat <<EOF | ./dns_to_route53_tf mydomain.com
www 10800 IN CNAME www.google.fr.
EOF
```

### Interactive

```
./dns_to_route53_tf mydomain.com
```
