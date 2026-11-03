# nt_chatbot
Secure serverless AI chatbot on AWS powered by Claude, deployed with Terraform: guardrails, rate limiting, monitoring and CI/CD.

# nt_Chatbot: Secure Serverless AI Chatbot on AWS

## The problem
Businesses want AI chatbots on their websites, but a chatbot must be **safe** (no leaking personal data, no harmful answers), **cost-efficient** (pay only when used) and **reliable**. This project builds a production-style chatbot that meets all three.

## How it works
User → CloudFront → WAF → API Gateway → Lambda → Claude (Anthropic)

| Tool / Service | What it does | Why I chose it |
|---|---|---|
| Claude (Anthropic API) | Generates the answers | _to fill in_ |
| AWS Lambda | Runs the chatbot logic only when a question arrives | _to fill in_ |
| API Gateway | Receives requests from the web page | _to fill in_ |
| CloudFront + S3 | Hosts and delivers the chat page | _to fill in_ |
| AWS WAF | Blocks malicious traffic | _to fill in_ |
| DynamoDB | Tracks usage for rate limiting | _to fill in_ |
| Secrets Manager | Stores the API key securely | _to fill in_ |
| CloudWatch + SNS | Logs, alarms and email alerts | _to fill in_ |
| Terraform | Builds all AWS resources as code | _to fill in_ |

## Key features
- Personal data (PII) redaction before messages reach the AI
- Blocking of harmful content and prompt-injection attempts
- Rate limiting per user
- Monitoring and alerts
- Infrastructure as code, with easy teardown to avoid costs

## Progress
- [ ] Prerequisites installed
- [ ] One-time setup (bootstrap)
- [ ] Deploy
- [ ] Testing
- [ ] Monitoring
- [ ] CI/CD
- [ ] Cleanup

## Problems log
| # | Problem | Cause | Fix I chose | Why |
|---|---|---|---|---|
| | | | | |

## What I learned
_to fill in as I go_
