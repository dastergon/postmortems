---

url: "https://www.pagerduty.com/blog/outage-post-mortem-april-13-2013/"
start_time: ""
end_time: ""
categories:
- postmortem
company: "Pagerduty"
product: ""

---

In April 2013, [Pagerduty](http://www.pagerduty.com), a cloud service proving application uptime monitoring and real-time notifications, suffered an outage when two of its three independent cloud deployments in different data centers began experiencing connectivity issues and high network latency. It was found later that the two independent deployments shared a common peering point which was experiencing network instability.  While the third deployment was still operational, Pagerduty's applications failed to establish quorum due to to high network latency and hence failed in their ability to send notifications.
