---
name: Infrastructure Issue
about: Report an issue with Open Robotics infrastructure

---

- [ ] I have checked [ROS Answers](https://answers.ros.org) for similar reports and solutions.
- [ ] I have checked the [ROS Status page](https://status.ros.org) and my issue is not listed there.
- [ ] I have checked the [open issues](https://github.com/osrf/infrastructure/issues) for similar reports.
- [ ] This is **not** a [security issue](https://github.com/osrf/infrastructure/blob/latest/SECURITY.md) If you have a security issue to report please do so via email to <security@openrobotics.org>.

## Problem description

Example: When running `apt update` the following output appears

```
W: GPG error: http://packages.ros.org/ros/ubuntu focal InRelease: The following signatures were invalid: EXPKEYSIG F42ED6FBAB17C654 Open Robotics <info@osrfoundation.org>
E: The repository 'http://packages.ros.org/ros/ubuntu focal InRelease' is not signed.
```
