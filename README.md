# Ingress
Ingress is a mental state transition system that helps people reliably enter focused cognitive work.
Most capable individuals do not fail because they lack goals, knowledge, or ambition. They fail at a specific moment - the transition from intention to action.
Ingress is designed to solve that moment.
Instead of managing tasks, tracking time, or motivating users, Ingress guides a user through a short structured protocol that reduces cognitive resistance and helps them begin working within minutes.

# The Problem
Modern knowledge work requires sustained attention and self-directed effort. However, many users repeatedly experience:

- hesitation before starting work
- task avoidance
- distraction loops
- mental noice and overwhelm
- inconsistent execution despite clear plans

This is not simply a productivity issue. It is a cognitive entry problem - the brain resists entering effortful thinking when a task feels uncertain or complex.
Ingress exists to bridge the gap between knowing what to do and actually beginning.

# What Ingress Does
Ingress provides a guided work entry protocol consisting of:

1. Physiological Reset

   A short breathing sequence to reduce cognitive threat response.

2. Cognitive Narrowing

   Converting a vague goal into a concrete first action.

3. Action Trigger

   A two-minute initiation phase that activates engagement.

4. Focus Continuation

   Transition into sustained work once the brain is engaged.

5. Night Shutdown Protocol

   Structured mental offloading to improve next-day clarity.

The goal is simple: 
Help a user start working when they normally would not.

# What Ingress Is Not
Ingress is intentionally not:

  - a task manager
  - a to-do list application
  - a motivational app
  - a meditation platform
  - a therapy or mental health treatment tool
  - a social productivity network

If a feature does not directly help a user begin work quickly, it does not belong in Ingress.

# Guiding Principles

 - Reduce cognitive friction
 - Require minimal decisions
 - Work when the user is mentally tired
 - Create immediate behavioral change
 - Measure successful work initiation, not engagement time

Ingress prioritizes behavioral effectiveness over feature quantity.

# System Architecture (High Level)
Ingress is built as a monorepo

apps/ 
  server/ → NestJS backend (protocol engine & behavioral logic) 
  web/ → React frontend (user interaction interface) 
packages/ 
  shared-types/ → shared TypeScript interfaces 
  config/ → shared configuration 
docs/ 
  product and architecture documentation

The backend operates as a protocol engine that determines the next action based on user state, rather than a traditional request/response API.

# Current Status
Ingress is in active development(internal testing phase)
The system is currently being validated through controlled self-usage before public release.

# Long-Term Vision
Computers have operating systems that manage processes and resources. Humans do not have an equivalent system for managing cognitive entry into effortful work.
Ingress aims to become a behavioral interface layer between human cognition and modern knowledge work - a reliable entry point into focused thinking.

# License
MIT License



  
