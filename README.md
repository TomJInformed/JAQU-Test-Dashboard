# JAQU-Test-Dashboard
Smashing Framework Test Dashboard

cURL to Automated test Dashboard:
curl -d '{ "auth_token": "YOUR_AUTH_TOKEN", "value": "Passed" }' \http://localhost:3030/widgets/VCCSUINightly
replace VCCS with service shorthand, UI/API, Nightly/ST/SIT


cURL to Bug dashboard:
curl -d '{ "auth_token": "YOUR_AUTH_TOKEN", "jiranumber": "CAZ100", "description": "Offline payments back link", "level":"Critical", "position": "Open" }' \http://localhost:3030/widgets/bug1


