[![Publish Docker image](https://github.com/PenguinCloud/project-template/actions/workflows/docker-image.yml/badge.svg)](https://github.com/PenguinCloud/core/actions/workflows/docker-image.yml) [![version](https://img.shields.io/badge/version-5.1.1-blue.svg)](https://semver.org) 

# Project Overview
PenguinCloud was based on an idea of a method to deploy workloads, storage, etc. in a multi-cloud / hybrid-cloud scenario securely and easily. It was started by a crew of folks who have a rich background in fighting advanced actors and whom saw the defecits in the current offerings on the market.
Moreso, the crew was made up of folks with decads of Open Source background and a strong desire to provide the core of the product as open source to help those in Non-Profits, startups, and more have a chance!

# Why this image vs others
## Built in self testing and healing
All of our builds have unit and dynamic tests as part of the build of their images, as well as during runtime to ensure the system keeps running as expected. If the system falls out of bounds of the test, the images have some self healing capabilities fix common minor problems.
Security and stability are our priorities!

## Secured... even if the software isn'template
All of our images under go a 8 stage security check to ensure not only is the PTG portion of the code secure, but to also identify and help remediate the underlying libraries and software security. 
That being said, we're human, so if you find something, let us know and there might just be something in it for you other then helping out the global community!

## Updated Weekly
All of our latest images are checked daily for updates from upstream sources. Look for our stable-updated image to get our latest version with patches!
In addition, all of our images update themselves for core libraries on launch! We want to make updating easy and less impactful as possible!

## Designed for air-gapped or for internet facing
All Pengiun Technologies images are designed to be ran inside of air gapped environments with no internet, allowing datacenters to use a local cache as well saving bandwidth.
This is why we always allow for URL to be changed. However, you will still need your own apt cache and image registry if air-gapped. We may deploy something for this as part of PenguinCloud in the future, however.

## Active contribution and maintenance
PTG is a company with funding and full time contributors to ensure our images aren't stale.

## Scalable
ALl PTG images are designs to be micro-containers, ensuring easy verical and horizontal scaling is possible.

## PTG drinks it's own koolaid
PTG actively uses it's own images for everything so we can identify bugs which our automation misses.

## Beta testing
PTG relies on volunteer customers and community members to beta test images, ensuring our stable / production images are well baked and as bug free as possible solutions.

# Contributors
## PTG
Maintainer: creatorsemailhere@penguintech.group
General: info@penguintech.group

## community
* PenguinzTech

# Related Penguin Technologies Inc. Projects
* Squawk - Secure DNS over HTTPS
* WaddleBot - AI Chatbot with Infrastructure Plugins
* WaddlePerf - End to end multi-protocol testing and monitoring

# Resources
Documentation: ./docs/
Premium Support: https://support.penguintech.io
Community Bugs / Issues: -/issues
