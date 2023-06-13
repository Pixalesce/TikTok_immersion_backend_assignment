# tiktok_assignment_2023

![Tests](https://github.com/TikTokTechImmersion/assignment_demo_2023/actions/workflows/test.yml/badge.svg)

Submission of 2023 Tiktok Tech Immersion Programme backend assignment.

## About
This assignment challenged me to develop the backend side of on Instant Messaging (IM) system focusing on the core messaging features of delivering messages on top of a HTTP and RPC server.

## Tasks
### Server Architecture
Golang's RPC and HTTP server frameworks, Kitex and Hertz, were used in the building of the servers found in this project.

### Data Storage
To tackle the storage of data, the Redis database was chosen due to the nature of its key-value storage and its speed through the natureof in-memory data storage.

### Message Delivery 
Functions supporting send requests and pull requests were defined, supporting functionality to write and read messages from the Redis server respectively.

## Challenges
The greatest challenge I faced over the course of this projcet is definitely the large number of systems that have to be put in place for it to work, from the Docker images and containers to the RPC and Redis servers. Especially since this is my first contact with most of these services, the learning curve was particularly steep. However, it was indeed a great chance for me to grow and develop my skills.

## Acknowledgements
Thank you to the TikTok team for providing this incredible learning opportunity, the insightful lessons and guidance! Shoutout to wonderful participants who were so willing to extend help to the rest!

## License
[MIT](https://github.com/Nyxchaser/tiktok_assignment/blob/main/LICENSE)
