+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = false  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

title = "Application-Layer Traffic Optimization"

# Hero image (optional). Enter filename of an image in the `static/img/` folder.
hero_media = "hero-academic.png"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  gradient_start = "#4bb4e3"
  gradient_end = "#2b94c3"
  
  # Background image.
  # image = ""  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
[cta]
  url = "https://sourcethemes.com/academic/docs/install/"
  label = "Get Started"
  icon_pack = "fas"
  icon = "download"
  
[cta_alt]
  url = "https://sourcethemes.com/academic/"
  label = "View Documentation"

# Note. An optional note to show underneath the links.
[cta_note]
  label = '<a class="js-github-release" href="https://sourcethemes.com/academic/updates" data-repo="gcushen/hugo-academic">Latest release<!-- V --></a>'
+++

The ALTO working group was established in 2008 to devise a request/response protocol for allowing a host to benefit from a server that is more cognizant of the network infrastructure than the host would be. The working group has developed an HTTP-based protocol to allow hosts to benefit from the network infrastructure by having access to a pair of maps: a topology map and a cost map.

The origins of the ALTO protocol lie in peer-to-peer (P2P) applications, where the host is a peer in a P2P network and desires a rendezvous with other peers for file sharing, real-time communications, etc. ALTO is now being considered as a solution for problems outside the P2P domain, such as in datacenter networks, in content distribution networks (CDN) where exposing abstract topologies helps applications.

To support the emerging new uses of ALTO, certain extensions are being sought. These extensions can be classified as follows:

- Protocol extensions for reducing the volume and latency of on-the-wire data exchange required to align the ALTO server and clients. Extensions under consideration are mechanisms for delivering server-initiated notifications and partial updates of maps. Efforts developed in other working groups such as Websockets and JSON-patch will be considered, as well as bespoke mechanisms specific to the ALTO protocol.
- One or more alternatives to allow more flexible protocol and deployment structure, proxy/broker, interdomain.
- Protocol extensions to convey a richer set of attributes to allow applications to determine not only "where" to connect but also "when" to connect. Such additional information will be related both to endpoints (e.g. conveying server load and cache geo-location information for CDN use cases) and to endpoint-to-endpoint costs (e.g. bandwidth calendaring to represent time-averaged cost values in datacenter networks). FCS, Multiple resources, 
- Adaptation to cellular/mobile/edge. The working group will specify such extension in coordination with other working groups that have a focus on the related use cases. The scope of extensions is not limited to those identified by the WGs, but is limited by the criteria set out below.

When the WG considers standardizing information that the ALTO server could provide, the following criteria are important to ensure real feasibility:

- Can the ALTO service realistically discover that information?
- Is the distribution of that information allowed by the operators of that service?
- Can a client get that information without excessive privacy and information leakage concerns? Extensions defining new endpoint properties should focus on exposing attributes of endpoints that are related to the goals of ALTO -- optimization of application-layer traffic -- as opposed to more general properties of endpoints. privacy and information leakage aspects of new endpoint properties will in any case be evaluated to the guidelines provided in the IANA considerations and Security Considerations of the ALTO protocol specification (RFC-to-be, sections 14.3 and 15.4 at IESG review time).
- Is it information that a client cannot find easily some other way?

After these criteria are met, the importance of the data will be considered for prioritizing standardization work, for example the number of operators and clients that are likely to be able to provide or use that particular data. In any case, this WG will not propose standards on how congestion is signaled, remediated, or avoided, and will not deal with information representing instantaneous network state.

Issues related to the specific content exchanged in systems that make use of ALTO are also excluded from the WG's scope, as is the issue dealing with enforcing the legality of the content.

<!-- <span style="text-shadow: none;"><a class="github-button" href="https://github.com/gcushen/hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star this on GitHub">Star</a><script async defer src="https://buttons.github.io/buttons.js"></script></span> -->
