# Text2Img
> Fork from "https://github.com/aelnouby/Text-to-Image-Synthesis"

### TODO
1. Fix the bug in the original data ----------------------- Done Aug 10.2019
2. Modify the vanilla GAN Model --------------------------- Done Aug 11.2019
3. setup Visdom for training (Facebook research team) ----- Done Aug 11.2019
4. Train text to image for the first time ----------------- Done Aug 11.2019
5. Add bboxes GAWWN model
6. Test on 128 * 128 image size

### Usage
- Get dataset here : (CUB) https://drive.google.com/file/d/1mNhn6MYpBb-JwE86GC1kk0VJsYj-Pn5j/view
- modify config.yaml to match path to the dataset
- python3 runtime.py

### CUB results

Texts     | images
----------|:------:
A bird with a cream underbelly and black wings that are spotted with white. | ![01](/images/CUB_64/01.jpg)
A larger sized bird that has a jet black coat with little white pin stripes at the tips of its wings. | ![02](/images/CUB_64/02.jpg)
A small bird with black and white secondaries, white wing bars and a yellow spot on its crown. | ![03](/images/CUB_64/03.jpg)
Bird has gray body feathers, white breast feather, and black beak. | ![04](/images/CUB_64/04.jpg)
This bird has a long curved bill, a white breast, and a brown head and wings. | ![05](/images/CUB_64/05.jpg)
This bird has a medium bill, a yellow superciliary, and a white breast and belly. | ![06](/images/CUB_64/06.jpg)
This is an orange bird with a brown wing and a small beak. | ![07](/images/CUB_64/07.jpg)
