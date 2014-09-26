Synchronized notification Android Wear workshop
===============================================

##Introduction

Notifications on Wearables is a crucial part of presenting information to users. In order to show
a notification on a wearable device, there are different techniques that can be used and this
sample shows three different approaches.

The simplest approach is to create a notification on the handset device and let Android Wear
bridge that notification to the watch. This approach requires no additional work and is the most
common solution. There may be situations where you do not want identical information be
shown on the handset and the watch. In this code lab, we cover three different use cases:

1. Phone-only Notification. There are cases that a notification should not be bridged to the
watch since its content or relevance should only be limited to the handset.

2. Watch-only Notification. There are cases that a handset wants to build a notification that
is only targeted for a wearable device.

3. Synchronized Phone and Wear Notification. Here, we want to show two notifications;
one on the handset and one on the wearable but these two may need to have different content relevant
to their hosts. We make use of the Data API so that dismissing one would result in dismissal of the
other one (hence synchronized).
