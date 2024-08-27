# Web of Digital Twins
This organization is the home of the toolchain to support the Web of Digital Twins (WoDT) vision for creating ecosystems of Digital Twins.
> A WoDT can be conceived as an open, distributed and dynamic ecosystem of connected digital twins, functioning as an interoperable service-oriented layer for applications running on top, especially smart applications and multiagent systems.
> 
> [A. Ricci et al.]

The toolchain provided in this organization is based on an implementation called _Hypermedia-based WoDT_.
> Central to this approach is the idea of _DT-as-a-service_, with each DT independently mirroring a specific asset in the real world and uniformly offering its capabilities to external consumers via a Web-based interface.
> 
> Ecosystems are instead generally confined and have a strong interrelation between components. We introduce the idea of the _WoDT Platform_ to support the management of DT ecosystems and exploit the interfaces of DTs to register them and merge their data to create a contextualized view of a portion of reality and offer services on top of WoDT ecosystems to be exploited at the application layer.
>
> [Giulianelli et al.]

## :page_facing_up: Publications
- [A. Ricci et al.] _Web of Digital Twins_ -- [link to the article](https://dl.acm.org/doi/10.1145/3507909)
- [Giulianelli et al.] _Engineering Interoperable Ecosystems of Digital Twins: A Web-based Approach_ -- to be published :hourglass_flowing_sand:

## :hammer: Toolchain provided in this organization
- `wodt-platform`: a Kotlin-based platform that enables the creation of a contextualized view of a portion of reality offering services on top of WoDT ecosystems to be exploited at the application layer. 
- `wodt-vocabulary`: a OWL-based vocabulary that supports the descriptions of Digital Twins via [_WoT Thing Descriptions_](https://www.w3.org/TR/wot-thing-description/).
- `wldt-wodt-adapter`: a simple Java-based library that extends the [_WLDT Framework_](https://github.com/wldt) for the creation of WoDT Digital Twins in a WoDT ecosystem.
