# Firewall Change Validation Checklist

## Overview

This checklist helps validate firewall policy changes after implementation to ensure security policies function correctly without impacting production traffic.

## Pre-Change Validation

- Back up the current firewall configuration.
- Verify the approved change request.
- Review the rollback procedure.
- Confirm the maintenance window.
- Identify affected applications and network segments.

## Post-Change Validation

- Verify the new security policy is installed.
- Confirm expected traffic is allowed.
- Verify unauthorized traffic is still blocked.
- Check NAT translations (if applicable).
- Validate VPN connectivity.
- Review routing and interface status.

## Monitoring

- Review firewall system logs.
- Check for denied sessions.
- Monitor CPU and memory utilization.
- Verify HA synchronization (if configured).

## Rollback Criteria

- Critical application outage
- Unexpected traffic blocking
- High CPU utilization caused by the change
- Failed HA synchronization

## Best Practices

- Validate changes in a lab when possible.
- Implement one logical change at a time.
- Document validation results.
- Update network documentation after successful implementation.
- Schedule a post-change review.
