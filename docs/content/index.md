
# Welcome

![Architecture](assets/img/traefik-architecture.png)

Traefik is an [open-source](https://github.com/containous/traefik) *Edge Router* that makes publishing your services a fun and easy experience. 
It receives requests on behalf of your system and finds out which components are responsible for handling them. 

What sets Traefik apart, besides its many features, is that it automatically discovers the right configuration for your services. 
The magic happens when Traefik inspects your infrastructure, where it finds relevant information and discovers which service serves which request. 

Traefik is natively compliant with every major cluster technology, such as Kubernetes, Docker, Docker Swarm, AWS, Mesos, Marathon, and [the list goes on](providers/overview.md); and can handle many at the same time. (It even works for legacy software running on bare metal.)
 
With Traefik, there is no need to maintain and synchronize a separate configuration file: everything happens automatically, in real time (no restarts, no connection interruptions).
With Traefik, you spend time developing and deploying new features to your system, not on configuring and maintaining its working state.   

Developing Traefik, our main goal is to make it simple to use, and we're sure you'll enjoy it.

-- The Traefik Maintainer Team 

!!! info

    If you're a businness running critical services behind Traefik, know that [Containous](https://containo.us), the company that sponsors Traefik's development, can provide [commercial support](https://containo.us/services/#commercial-support) and develops an [Enterprise Edition](https://containo.us/traefikee/) of Traefik. 
