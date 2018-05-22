---
id: "a80eda4a-1105-44b6-a161-81bf7bac7557"
creditSlug: "{courseId}"
title: "{title}"
nav-title: "{titleShort}"
topicId: {topicId}
tokens:
    - key: page-tags
      value: "{pageTagsCsv}"
    - key: time-rating
      value: {timeEstimate}
    - key: sidebar-image
      value: "{imageUrl}"
    - key: prerequisites
      value: "{prerequisiteGuidsCsv}"
    - key: course-repo-url
      value: "{repoUrl}"
    - key: course-download-url
      value: "{repoDownloadUrl}"
# links:
#     - group: Additional Documentation
#       title: "Some docs"
#       url: "https://docs.microsoft.com/"
#     - title: "Some more docs"
#       url: "https://university.xamarin.com"
---

{description}

@prerequisitesSection()

### Upon completion you will be able to:

- {objective1}
- {objective2}
- {objective3}

### Course exercise download

Exercise materials are available from [GitHub]({{course-repo-url}}). The code can be cloned through a desktop Git client or [downloaded directly]({{course-download-url}}) as a ZIP file.

>> If you are using Windows, try to select a location with a shorter path length to make sure you don't exceed the 260 character limit.

[[include=startPageButtons.html]]

[[if SGL]]

### Course authors

@Authors([ "{authorId1}", "{authorId2}" ])

[[endif]]
