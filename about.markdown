---
layout: page
title: About Me
permalink: /about/
---

# Hello World
```csharp
using bremora.com

namespace bremora.profile {
    public class Person {
        public string FirstName => "Alex";
        public string LastName => "Bremora";
        public string City => "Kassel";
        public string Country => "Germany";

        public string[] Interests => new[] {            
            "Architecture",
            "Security"
            "Async programming",
            "Requirement engineering"
        };
    }
}
```