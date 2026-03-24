
#Midterm protfolio page

Snippet code 

/* SLIDER CONTAINER */
.container {
  display: flex;
  overflow-x: scroll;
  scroll-snap-type: x mandatory;
  scroll-behavior: smooth;
}


/*  EACH SLIDE */
.card {
  flex: 0 0 100%;
  scroll-snap-align: start;
}

/*  SAME SIZE IMAGES */
.card img {
  width: 100%;
  height: 100vh;
  object-fit: cover;
}

/* BUTTONS */
.slider-btn {
  position: fixed;
  top: 50%;
  transform: translateY(-50%);
  font-size: 2rem;
  background: rgba(0,0,0,0.4);
  color: white;
  border: none;
  padding: 10px;
  cursor: pointer;
  z-index: 2000;
}



Comparasent from draft 


<img width="690" height="321" alt="image" src="https://github.com/user-attachments/assets/ceb39023-050e-42a6-b690-2569170891e5" />
