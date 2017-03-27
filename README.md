# Graylog Resources
A small collection of stuff related to Graylog2

## Cyberoam Firewall Extractor
Extractor to parse Cyberoam Firewall syslogs. Based on official documentation (https://kb.cyberoam.com/redirfile.asp?id=5077)
Requires the GROK pattern "DATE_YMD" as listed below

## GROK Pattern

Name | Pattern
------------ | -------------
DATE_YMD | %{YEAR}[./-]%{MONTHNUM}[./-]%{MONTHDAY}
