# PhotoWar

**PhotoWar** 

## Models
**User** 
- String: Username
- String: First Name
- String: Last Name
- String: Email
- URL: Avatarl URL
- Array: an array of users that are friends
- Array: an array of current battling users

**War**
- Int: time allowed
- Array: an array of String of objects that the picture contains
- URL: Picture URL
- User: user who sent the picture
- User: user who suppose to receive the picture

## Wireframe
![alt tag](PhotoWar.png)

## User Stories

The following **required** functionality is completed:

- [x] Application integrated with Firebase services
    - [x] Install framwork
    - [x] Initialize Firebase connection
- [x] User can sign up and login
    - [x] Unique usernames
- [x] User login persists across restarts
- [x] User can upload avatar for profile
- [x] User can see current battles they are in
- [x] User can start a new battle
- [x] Application connects to Clarifai API
- [ ] User can search for other users

The following **optional** features are implemented:
- [ ] User can see live activity of battles
- [ ] User can see photo stream of images taken during war after it is over
- [ ] Streaming visual recognition of camera feed
- [ ] User is able to add friends face-to-face using bluetooth or similar wireless technology
- [ ] User can choose between prediction models/APIs

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

![alt tag](PhotoWar.gif)

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

## License

    Copyright [2017] [490ers]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
