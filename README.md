# artifactory-packer

Build with this command:
```
packer build -var-file=variables.json template.json
```

variables.json is not committed to source control, but looks about like this:

{
  "aws_access_key": "ARGYBLAHA123GBAAARGY",
  "aws_secret_key": "obledoobledoo1garbledeeCDe2rfblah"
}
