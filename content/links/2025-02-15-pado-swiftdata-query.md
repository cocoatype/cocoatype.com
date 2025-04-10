+++
title="Separating Concerns in SwiftData Models, or: @Query Considered Harmful"
date="2025-02-15"
[params]
    source = "web-pado"
    url = "https://pado.name/blog/2025/02/swiftdata-query/"
+++

Over the year-and-change since its release, I’ve watched several developer friends abandon SwiftData in frustration, finding it buggy and unreliable. However, I’ve found it to be a key part of my app’s architecture, and I can’t imagine going back. Is it that I’m a 10x developer, and everyone else just needs to git gud? 🤔 No, of course not. But I think my experience, compared to others’, comes down to one key difference: I completely avoided using `@Query`, and **everyone else should, too**.
