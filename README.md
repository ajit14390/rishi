body {
  background: black;
  color: #fff;
  font-family: "Archivo Black", sans-serif;
  font-size: 3em;
  text-align: center;
  scrollbar-width: none;
}

.heart {
  fill: red;
  position: relative;
  top: 5px;
  width: 50px;
  animation: pulse 1s ease infinite;
}

@keyframes pulse {
  0% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.3);
  }
  100% {
    transform: scale(1);
  }
}
#heart {
  position: relative;
  width: 100px;
  height: 90px;
  text-align: center;
  font-size: 16px;
  position: relative;
}

#heart span {
  width: 100%;
  display: block;
  top: 50%;
  z-index: 1;
}

#heart {
  width: 100px;
  height: 90px;
  text-align: center;
  font-size: 16px;
}

#heart span {
  width: 100%;
  display: block;
  left: 0;
  right: 0;
  z-index: 1;
}
