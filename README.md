In planetService.cs where we are making separate API for each moon in a loop, which is delaying the task, we can use catching, which will store retrieved information for a specific duration as moon data doesn't change frequently

Benefit: This will reduce API calls if the same planets and moons are accessed frequently
Drawback: Stale data
