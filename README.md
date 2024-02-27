# image-inpaint
Changing Dresses via Prompting

## Project Pipeline
![alt text](image.png)

---
### Clothes Segmentation Example Input - Output

![text](images/person.jfif)

![alt text](images/cloth_seg_output.png)

---
### ControlNet Example Input - Output

![alt text](images/controlnet_input_image.png)

![alt text](images/output.png)

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
- libraries and languages (maybe) are not clear right now

### Optimization
- [ ] Model inference time optimization
- [ ] Bottleneck functions (if there are any) pruning

### DevOps
- [ ] Jenkins implementation as CI/CD
- [ ] Dockerize product
- [ ] Kubernetes