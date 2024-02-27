# image-inpaint
Changing Dresses via Prompting

## Project Pipeline
![alt text](images/image.png)

---
### Clothes Segmentation Example Input - Output

<img src="images/person.jfif" align="left" height="48" width="48">
<img src="images/cloth_seg_output.jfif" align="right" height="48" width="48">


---
### ControlNet Example Input - Output

![alt text](images/controlnet_input_image.png){:height="36px" width="36px"}

![alt text](images/output.png){:height="36px" width="36px"}

---
## To Do's
### Image Processing
- [ ] Filter generated masks based on model label file
- [ ] Plot a center point on every mask pieces

### Coding
- [ ] API integration
- [ ] Code arrangement as strategy design pattern

### UI & UX
- [ ] Web UI Design
- [ ] Mobile UI design (optional)
- libraries and languages (maybe) are not certain right now

### Optimization
- [ ] Model inference time optimization
- [ ] Bottleneck functions (if there are any) pruning

### DevOps
- [ ] Jenkins implementation as CI/CD
- [ ] Dockerize product
- [ ] Kubernetes