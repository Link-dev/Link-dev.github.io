---
show: true
width: 10
date: 2021-09-12 00:01:00 +0800
height: 8
images:
- src: assets/images/photos/SF.jpg
  title: Golden Gate Bridge, San Francisco
  desc: 2023
- src: assets/images/photos/Miami.jpg
  title: Key West, Miami
  desc: 2024
- src: assets/images/photos/New_york.jpg
  title: New York
  desc: 2021
- src: assets/images/photos/Chicago.jpg
  title: Chicago
  desc: 2022
- src: assets/images/photos/Yokohoma.jpg
  title: Yokohoma
  desc: 2019
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
