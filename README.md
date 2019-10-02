### How to use jupyter notebook on Docker?
* Download this Repository
* Activate Docker
* Build the image: `docker build -it image-name:version .`
* Run the image: `docker run -it -ip 8888:7777 image-name:version`
* Open the browser: `ip-address:8888\token-id`

________________________

* Build:
> [!build-cmd](files/1-build.png)

* Run:
> [!run-cmd](files/2-run.png)

* Access:
> [!access-nb](files/3-browser.png)

* Notebook in action:
Following this [simple tutorial](https://nbviewer.jupyter.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb).
> [!nb-run](files/4-nb.png)
