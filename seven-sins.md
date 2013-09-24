# Lust:
## Golden taps
## Over engineering
  - patterns
  - masse interfaces
  - morgendagens problemer
  - prematur optmialisering
## Premature technologies
  - Know the tech you use
  - Don't use everything
    - you know
    - that looks fancy
## Not invented here
  Bruk solide og stabile bibliotek
  - corp culture?
  - Dangerous if applied to security

# Gluttony
## Performance
  - Ikke-funksjonelle krav er fortsatt krav
  - Ikke tenke på ytelse
  - Kaste mer jern på problemet
  - For mye caching

## Memory
  - Less expensive than it was
  - Alltid foretrekk lazy init
  - Minimer mutability
  - Ikke prøv å være smartere enn VM'en
  - Profile koden din
  - Stol på app-server

## HttpSession Size
  - There to track state
  - not your "in memory" cache
  - Control session lifetime
  - Be java.io.Serializable

## Infrastructure
  - Know and control your pool sizes
  - Every connection allocates a thread
  - Know your threads
  - Don't try to work with your own threads.

# Wrath
## Mixing technologies
  - Tempted do use spring in your EE app?
  - Broad JVM eco-system (Scala, Play, Akka, GWT,..)
  - Know the technologies you're working with and ...
  - Choose the right tool for the right job.

## Maintainability
  - Your #1 enemy is complexity
  - Design for understandability
  - Less is more

# Greed
## People and resources
  - People are people. They are not resources. They are not capital. They are humans.
  - Too many people
  - Too many features
  - Two juniors dont make a senior
  - Not licensing helpful tools
  - Cost cutting on enviroments/developer notebooks.
