# Overview

This layer enables Ganglia monitoring functionality for the core
Apache Hadoop charms.


# Usage

This layer will set the following states:

  * `hadoop-ganglia.enabled` Ganglia monitoring is enabled.
  * `hadoop-ganglia.changed` The Ganglia monitoring configuration has changed
    and services need to be restarted.  It is important that this state be
    removed once acted upon.
