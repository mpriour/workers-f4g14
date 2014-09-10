# Worker Memory Use
<!-- .slide: data-background="rgba(168, 0, 32, 0.82)" -->

---

<!-- .slide: data-background="rgba(168, 0, 32, 0.82)" -->
## IE & FF

* ~ Unlimited # of workers

* Memory use of app increases

* ~100k FF & ~250k IE / worker

---

<!-- .slide: data-background="rgba(168, 0, 32, 0.82)" -->
## Chrome & Safari

* Limited # of workers

* No measured increase of app memory

* Workers created in pre-allocated heap memory

* Browser crashes when worker memory > heap memory

---

<!-- .slide: data-background="rgba(168, 0, 32, 0.82)" -->
# Worker Count 

---

<!-- .slide: data-background="rgba(168, 0, 32, 0.82)" -->
## Maximum performance

## Worker Count = Processor Cores

---

<!-- .slide: data-background="rgba(168, 0, 32, 0.82)" -->
## Diminishing returns

### when Worker Count > Cores

[Worker Count Test](http://pmav.eu/stuff/javascript-webworkers/)