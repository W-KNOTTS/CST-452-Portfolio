<h1 align="center">Welcome to my SlimMediaPlayer Project Portfolio</h1>

<div align="center">
  <img src="https://github.com/W-KNOTTS/CST-452-Portfolio/blob/main/Resources/icon.png" alt="SMP Icon" height="75px" width="75px">

*Creator:* William Knotts

*SlimMediaPlayer GitHub:*
[Link to SlimMediaPlayer Repository](https://github.com/W-KNOTTS/CST-451-Week4/tree/master)

*Download:*
[Download the compiled SlimMediaPlayer](https://github.com/W-KNOTTS/CST-452-Portfolio/releases/tag/v1.0.0R)
</div>

---

## Introduction

**Project Overview:** This media player application is designed for playing various media files. It integrates several technologies to deliver a smooth user experience, including features like CD ripping, fetching metadata from the MusicBrainz database, and comprehensive media playback management. Most importantly, this application ensures user privacy by not tracking any user data.

The objective of this project is to create an all-in-one solution for media playback, showcasing my skills in full-stack development and third-party API integration, while prioritizing user privacy.

---

## Functional and Non-functional Requirements

### Functional Requirements:

1. **Media File Management:**
   - Users can browse and select media files from their directories.
   - Retrieve and display metadata for media files using the MusicBrainz API.
   - Show detailed metadata including artist, album, title, release date, genre, and tags.
   - Enable users to edit and update media file metadata.

2. **Media Playback Features:**
   - Provide controls to play, pause, stop, and seek within media files.
   - Allow users to adjust volume, mute/unmute, and navigate between tracks.
   - Display current playback position and total duration of media files.

3. **CD Ripping Capabilities:**
   - Enable users to rip CD tracks into MP3 format.
   - Retrieve metadata for ripped tracks and update ID3 tags.
   - Display progress and status during the ripping process.

### Non-functional Requirements:

1. **Performance:**
   - Ensure the application loads and responds quickly, even with a large media library.

2. **Security:**
   - No security measures required, the application only creates MP3 files from CDs and does not store user data.

3. **Reliability:**
   - Ensure the application operates consistently without frequent crashes or errors.

4. **User Experience (UX):**
   - Design a simple and intuitive user interface that is easy to navigate.

5. **Scalability:**
   - Ensure the application can handle increasing numbers of media files and user interactions without degrading performance.

6. **Testing:**
   - Perform extensive testing, including functional, usability, and playback, to identify and resolve issues before release.

---

<div align="center">
   
## Technologies Used

| Technology      | Icon/Image                                                                 |
|-----------------|----------------------------------------------------------------------------|
| WPF             | <img src="https://cdn.icon-icons.com/icons2/2530/PNG/512/wpf_button_icon_151942.png" alt="WPF Icon" height="25px" width="75px"> |
| C#              | ![C# Icon](https://img.icons8.com/color/48/000000/c-sharp-logo.png)        |
| MusicBrainz API | ![MusicBrainz Icon](https://img.icons8.com/color/48/000000/api.png)        |
| TagLib#         | ![TagLib Icon](https://img.icons8.com/color/48/000000/tag.png)             |
| CSAudioCDRipper | <img src="https://avatars.githubusercontent.com/u/49074818?s=48&v=4">      |

</div>

---

## Industry Practices Implemented

Standard industry practices were followed to ensure the application is reliable, scalable, and does not track users:

- **Modular Design:** The application is structured into distinct modules, each responsible for specific functionalities like CD ripping, metadata retrieval, and media playback.
- **Event-Driven Architecture:** Events are used to manage asynchronous operations, including media playback and CD ripping progress.
- **Exception Handling:** Robust error handling is in place to ensure a smooth user experience and facilitate debugging.
- **User Interface Design:** The UI is designed to be clean and intuitive, making it easy for users to navigate and interact with the application.
- **Version Control:** Git is used for version control, enabling effective management of changes and collaboration.

These practices ensure a robust, user-friendly application that can handle future enhancements and improvements.

---

## Learning New Technologies

During this project, I gained experience in several new technologies, notably WPF, CSAudioCDRipper, TagLib#, and the MusicBrainz API.

### WPF:

- **Reason for Choosing WPF:** 
  WPF was selected for its powerful feature set for building desktop applications with modern, responsive user interfaces.
- **Project Contribution:** 
  Using WPF allowed me to create a dynamic and visually appealing UI, enhancing the user experience.
- **Learning Experience:** 
  Although WPF has a steep learning curve, I utilized comprehensive documentation, online tutorials, and community support to overcome challenges and master the technology.

### MusicBrainz API:

- **Reason for Choosing MusicBrainz API:** 
  The MusicBrainz API was selected for its extensive music metadata database, which is essential for the application's metadata retrieval feature.
- **Project Contribution:** 
  Integrating the MusicBrainz API enabled the application to fetch detailed and accurate metadata for media files, enhancing the media management experience.
- **Learning Experience:** 
  Initial challenges included outdated documentation and data parsing issues, but through community resources and persistent effort, I successfully integrated the API.

### CSAudioCDRipper:

- **Reason for Choosing CSAudioCDRipper:** 
  The CSAudioCDRipper library was selected because of its ability to rip CD tracks to MP3, which is essential for users to legally acquire MP3 files.
- **Project Contribution:** 
  Integrating CSAudioCDRipper enabled the application to rip audio tracks to MP3 for later playback.
- **Learning Experience:** 
  Thanks to the detailed documentation provided via NuGet, the integration was seamless.

### TagLib#:

- **Reason for Choosing TagLib#:** 
  TagLib# was selected for its robust capabilities in reading and writing metadata for various audio file formats, which is crucial for managing and details of media files.
- **Project Contribution:** 
  Integrating TagLib# allowed the application to edit and display metadata such as artist, album, track number, and genre, enhancing the application and it's ability to display details.
- **Learning Experience:** 
  Although initially challenging due to the different audio file formats and metadata standards, I leveraged the documentation and forums to integrate and utilize TagLib# within the project.

---

<div align="center">

## Technical Approach

### Design and Class Diagrams

### Flowcharts

**Flowchart/ Diagram/ UML**

![Flowchart/ Diagram/ UML](https://github.com/W-KNOTTS/CST-452-Portfolio/blob/main/Resources/Week4UML-Sitemap-FlowChart.png)

**Application "CD Loaded"**

![Application "CD Loaded"](https://github.com/W-KNOTTS/CST-452-Portfolio/blob/main/Resources/Capture2.PNG)

**Application "MP3 Loaded"**

![Application "MP3 Loaded"](https://github.com/W-KNOTTS/CST-452-Portfolio/blob/main/Resources/MP3Playback.PNG)

**Application "Media Logging - Auto Play Next Track"**

![Application "Media Logging - Auto Play Next Track"](https://github.com/W-KNOTTS/CST-452-Portfolio/blob/main/Resources/LogOutput_AutoPlayNextSong.PNG)

**Application "Video Loaded"**

![Application "Video Loaded"](https://github.com/W-KNOTTS/CST-452-Portfolio/blob/main/Resources/VideoPlayback.PNG)

</div>

---

## Risks and Challenges

Several challenges were encountered and mitigated during the development of this project:

1. **Technical Complexity:**
   - **Challenge:** Integrating technologies such as WPF and the MusicBrainz API was challenging due to their complexity and learning curve.
   - **Solution:** Time was dedicated to research, utilizing online tutorials and breaking down tasks into manageable parts to facilitate learning and integration.

2. **Time Management:**
   - **Challenge:** Managing time as an individual developer was difficult, especially in meeting project deadlines.
   - **Solution:** Agile was used to prioritize tasks, track progress, and adjust timelines as needed. Managing the project scope was crucial to align with available resources and objectives.

3. **Resource Constraints:**
   - **Challenge:** Limited access to funds may have impacted the production deployment process.
   - **Solution:** Leveraging open-source software and optimizing available tools helped overcome these constraints. Using online forums provided additional support.

4. **Budget Management:**
   - **Challenge:** Ensuring the project stayed within budget while procuring necessary tools and resources.
   - **Solution:** Used free development tools like GitHub for version control and Visual Studio Code for editing. Community resources and open-source solutions provided significant cost savings.

By managing these challenges and effectively utilizing available resources, I successfully completed the project, demonstrating the ability to overcome obstacles and deliver a high-quality application.

---

## Outstanding Issues

Despite reaching a significant milestone, several issues and areas for improvement remain:

1. **Product Licensing:**
   - The current AudioRipper is restricted to personal and educational use, which may limit its commercial potential.

2. **Deployment:**
   - The application has not yet been deployed to a production environment.

3. **Image Metadata:**
   - The functionality for loading cover art from sources other than CDs is incomplete. Full metadata loading from MusicBrainz for MP3 files needs to be implemented.

4. **Performance Enhancements:**
   - Metadata loading can be optimized to fetch data only when necessary, rather than at application load time.

5. **User Interface Improvements:**
   - User feedback may reveal areas for improving navigation, accessibility, and visual design to better meet user needs.

6. **Documentation and Maintenance:**
   - Detailed documentation and organized code are essential for future maintenance and updates. Investing time in documenting key components and processes will allow for ongoing development.

Addressing these issues and implementing necessary improvements will enhance the application's functionality and value, providing a more robust media player for users.

---

## Copyright Compliance

**TagLibSharp**

TagLibSharp is an open-source library for reading and editing audio metadata. It is licensed under the GNU Lesser General Public License (LGPL) version 2.1.

TagLibSharp. (n.d.). NuGet Gallery. https://www.nuget.org/packages/TagLibSharp#dependencies-body-tab

**CSAudioCDRipper 1.1.4**

License file

Copyright (c) Microncode.com

The CSAudioConverter is available for FREE for learning or personal use. 
For commercial or any other use, please order a license.
This source is subject to the Microsoft Public License. 
See https://opensource.org/licenses/ms-pl.html.
THIS CODE AND INFORMATION IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND, 
EITHER EXPRESSED OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE IMPLIED 
WARRANTIES OF MERCHANTABILITY AND/OR FITNESS FOR A PARTICULAR PURPOSE.

Download: [CSAudioCDRipperDocumentation.chm Documentation](https://github.com/W-KNOTTS/CST-452-Portfolio/blob/main/Resources/CSAudioCDRipperDocumentation.chm)

CSAudioCDRipper. (n.d.). NuGet Gallery, from https://www.nuget.org/packages/CSAudioCDRipper

**MusicBrainzAPI 3.1.0**

The MIT License (MIT)

Copyright (c) 2013 avatar29A

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions: The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

MusicBrainzAPI. (n.d.). NuGet Gallery, from https://www.nuget.org/packages/MusicBrainzAPI

MusicBrainzAPI. (n.d.). MusicBrainz, from https://musicbrainz.org/doc/MusicBrainz_API
