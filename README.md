<div class="ring-container">
  <div class="butterfly-ring">
    <p id="name1">Sakthi</p>
    <p id="name2">Anandhi</p>
  </div>
</div>
```

CSS:

```
.ring-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.butterfly-ring {
  position: relative;
  width: 200px;
  height: 200px;
  border-radius: 50%;
  background-color: #fff;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

#name1, #name2 {
  position: absolute;
  font-size: 24px;
  font-family: Arial, sans-serif;
}

#name1 {
  top: 50%;
  left: 20%;
  transform: translate(-50%, -50%);
}

#name2 {
  top: 50%;
  right: 20%;
  transform: translate(50%, -50%);
}
```

JavaScript:

```
// No JavaScript code needed for this example
```

This code creates a simple butterfly ring design with the names "Sakthi" and "Anandhi" engraved on it. The ring is displayed in the center of the page, and the names are positioned on either side of the ring.
