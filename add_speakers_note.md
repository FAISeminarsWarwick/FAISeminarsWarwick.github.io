- Add speaker's talk in ./_speakers/
- Add speaker's talk in ./_pages/
- Add the talk into ./_events/
    ```
    ---
    layout: default # this would be the name of the layout file you'd create for events
    title: "What Goes Wrong in Quantum Machine Learning (and How to Make it Right)"
    date: 22-01-2026 11:00:00 -0000
    end_time: 22-01-2026 12:00:00 -0000
    time: 11:00AM
    speaker: "Dr. Eric Anschuetz"
    speaker_position: "Burke Fellow at Caltech"
    location: "Department of Computer Science CS1.04, University of Warwick, Coventry, UK"
    calendar_icon: "/assets/img/calendar_icon.png"
    location_icon: "/assets/img/location_icon.png"
    speaker_icon: "/assets/img/eric_anschuetz.jpg"
    link: "https://faiseminarswarwick.github.io"
    speaker_file: eric_anschuetz
    ---
    ```

- After the talk, move speaker's event file from ./_events/ to ./_previous/

- Update the ./_pages/about.md file for the next seminar in the website
    ```
    ---
    layout: about
    permalink: /
    title:
    description: Foundation of AI | Seminars | Warwick
    nav: true
    nav_order: 1

    speakers:
    # if you want to include more than one profile, just replicate the following block
    # and create one content file for each profile inside _pages/
    # - content: yurong_chen.md
    - content: eric_anschuetz.md # UPDATE THIS ONE

    news: false
    social: true
    ---
    ```