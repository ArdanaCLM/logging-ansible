#
# (c) Copyright 2016 Hewlett Packard Enterprise Development LP
# (c) Copyright 2017 SUSE LLC
#
# Licensed under the Apache License, Version 2.0 (the "License"); you may
# not use this file except in compliance with the License. You may obtain
# a copy of the License at
#
# http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
# WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
# License for the specific language governing permissions and limitations
# under the License.
#
README
======

This repo contains the following roles:
- kronos-api: Management for kronos api stack
- logging-server: Management for kronos server stack
- logging-monitor: Management for monitoring of kronos
- logging-producer: Management for kronos producer stack

The verbs:
- configure
- install
- status
- start
- stop

The operations:
- deploy
- reconfigure

top-level playbooks (i.e. called by Ardana)
- logging-deploy.yml - deploys kronos services
- logging-start.yml - start kronos services
- logging-stop.yml - stop kronos services
- logging-status.yml - check kronos services
- logging-upgrade.yml - upgrades kronos
