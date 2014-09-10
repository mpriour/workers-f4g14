# Workers Suck At
<!-- .slide: data-background="rgba(168, 0, 32, 0.82)" -->

---

<!-- .slide: data-background="rgba(168, 0, 32, 0.82)" -->
## XHR Proxy

* Send url to worker

* Worker does XHR

* Worker sends response to main thread

___

### Better if computationally intensive post-request processing occurs

---

<!-- .slide: data-background="rgba(168, 0, 32, 0.82)" -->
## Recreating Browser & DOM

### If you really need this

### maybe cross-doc messaging

### between iframe/window

---

<!-- .slide: data-background="rgba(168, 0, 32, 0.82)" -->
## Message Ordering / Queueing

### Dont know which message response is for