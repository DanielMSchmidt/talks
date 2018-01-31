# Frontend Performance Tracing

## Audience

Software Developers who build frontend in complex landscapes, especially the ones facing performance issues.

## Pitch

Web and Native Applications are expected to be fast; no one likes waiting.
As every user interacts differently with your application it is next to impossible to understand the performance characteristics and therefore the waiting times by testing your application by hand.
This becomes increasingly difficult when the number of features in your app and the amount of different devices goes up.

What gets measured gets managed, thats why I want to give you an introduction on performance tracing tools usable in the frontend.
I want to show you how to add tracing to your React (Native) App and how to integrate your backend systems, sothat you can see why certain requests take the time they need.
Hopefully this will inspire you to add tracing to your application, you might see opportunities to optimize that would otherwise have stayed hidden and you can quantify on how much your optimization helped.

## Story

- How much do you really know about your application?
  - What calls is your UI making?
  - What calls are your backends making?
- Set up simple React App with multiple backend systems and some "navigation" steps that take time
  - Use redux saga for easier to understand async code
- "Why does this button take so long"?
- Inspect calls to backend, stay puzzled
- Show zipkin UI with traces from backend systems
- "Got a bit of a clue why individual requests take time, but can't see the overall picture"
- Add zipkin-javascript-opentracing to the application
- Show new zipkin traces
- See performance optimization
- Why care / Why measure?
  - Room for improvement
  - Verify success of optimizations
  - ( Understand the system )

