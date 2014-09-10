##  Workers <!-- .element: class="pullup" -->
<!-- .slide: data-background="./img/worker-toys.jpg" -->

---

<!-- .slide: data-background="rgba(168, 0, 32, 0.82)" -->
## _

### Background process on seperate thread

## _

### No access to real DOM

## _

### Very simple API

---

<!-- .slide: data-background="rgba(168, 0, 32, 0.82)" -->
## API

```
new Worker(url)
```
url - **must be a valid URI and follow same-origin policy**


```
worker.postMessage(msg, <[transfers]>)
```
msg - **nearly anything** (_not canvas or native DOM_)

transfers - **array of transferable objects**<br>
(Blob, strongly typed array)


```
worker.terminate()
```


```
worker.addEventListener('message', fn)
```


```
worker.addEventListener('error', fn)
```

---

<!-- .slide: data-background="rgba(168, 0, 32, 0.82)" -->
# Not Quite So Easy

