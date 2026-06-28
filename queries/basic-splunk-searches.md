# Basic Splunk Searches

## Search All Events
```spl
index=*
```

Purpose:
Search across all available indexed data.

---

## Search VPN Logs
```spl
index="vpn_logs"
```

Purpose:
Search VPN-related log events.

---

## Search by Source IP
```spl
Source_ip="107.3.206.58"
```

Purpose:
Investigate activity from a specific IP address.

---

## Search by Username
```spl
UserName="Will Smith"
```

Purpose:
Review activity related to a specific user.

---

## Why These Searches Matter
These searches help analysts investigate:
- Suspicious user activity
- Failed logins
- VPN activity
- Unauthorized access attempts
