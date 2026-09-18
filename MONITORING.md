# Monitoring and Cost Awareness

## Monitoring Setup
- Tool used: UptimeRobot (https://uptimerobot.com)
- Monitor type: HTTP(s)
- Monitors the live site every 5 minutes
- URL monitored: https://khushbusingh6376-eng.github.io/SWYNEX-basic-cloud-deployment/

## Alert Idea
If the site becomes unreachable (non-200 HTTP response), 
UptimeRobot automatically sends an email alert to notify 
the owner so downtime can be addressed quickly.

## Cost Checklist
- Hosting platform: GitHub Pages (Free tier)
- No billing or cost incurred for this deployment
- Monitoring tool: UptimeRobot (Free tier)
- Bandwidth: within GitHub Pages' free soft limit (~100GB/month)

## Access-Control Checklist
- Repository visibility: Public
- Only the repository owner has write/push access
- No secrets, API keys, or credentials stored in the codebase
- Site content contains no sensitive or personal information
