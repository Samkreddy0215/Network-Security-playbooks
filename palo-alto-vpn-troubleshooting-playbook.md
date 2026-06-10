# Palo Alto VPN Troubleshooting Playbook

## Objective

Troubleshoot IPSec VPN tunnel establishment and traffic flow issues.

## Common Issues

- Phase 1 failure
- Phase 2 failure
- Tunnel up but no traffic
- Routing issues
- NAT conflicts
- Security policy mismatch

## Verification Commands

### GUI

Network > IPSec Tunnels

Monitor > System Logs

Monitor > Traffic Logs

### CLI

show vpn ike-sa

show vpn ipsec-sa

show routing route

## Troubleshooting Procedure

1. Verify peer reachability
2. Check IKE Phase 1 status
3. Verify IPSec Phase 2 establishment
4. Confirm encryption domains
5. Validate static or dynamic routing
6. Review security policies
7. Review NAT exemptions
8. Perform packet captures if required

## Validation

- Tunnel Status = Active
- Traffic encrypted successfully
- Application communication restored

## Root Cause Analysis

Document findings, corrective actions, and preventive recommendations.
