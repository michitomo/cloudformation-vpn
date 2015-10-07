# VPN server templates for Amazon AWS CloudFormation

## How to
1. Download desired template from this repo
2. Open CloudFormation home https://console.aws.amazon.com/cloudformation/
3. Select region
4. Go for Create Stack
5. Select Upload a template to Amazon S3
6. Deploy

## ipsec.json
* This will create basic IPSec VPN server mainly for iPhone

## mitm.json
* This is to analyze network traffic of your device
* All network traffic through this VPN server will be dumped
* mitmproxy UI is also available
* Access http://mitm.it/ from your device to decrypt HTTPS traffic
