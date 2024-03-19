# Edge Detection Process for BLM 5113 Digital Video Processing (DVP) at YTU

> Edge Detection Process with use `Gaussian Filter` and `Sobel Filter`  
> Course Page: http://www.bologna.yildiz.edu.tr/index.php?r=course/view&id=7826&aid=3&pid=371  
> Case Details: Read the reports/235B7014-EdgeDetectionProcess.pdf  
> Presentation: https://youtu.be/Vtuipa8E3sg

## Project Folder
- **`filtered/`**
    - **`coins.ascii.pgm/`**
        - coins.ascii_KernelSize-{`3x3,5x5,7x7`}_Sigma-{`1,5`}.pgm
    - **`fruit.pgm/`**
        - fruit_KernelSize-{3x3,5x5,7x7}_Sigma-{1,5}.pgm
    - **`most_blurry_image/`**
        - {`coins.ascii, fruit, saturn.ascii`}_KernelSize-7x7_Sigma-5_SobelFilter-{`EdgeMagnitude, Gradient_X, Gradient_Y`}.pgm
    - **`saturn.ascii.pgm/`**
        - saturn.ascii_KernelSize-{`3x3,5x5,7x7`}_Sigma-{`1,5`}.pgm
- **`images/`**
    - coins.ascii.pgm
    - fruit.pgm
    - saturn.ascii.pgm
- **`reports/`**
    - DVP2024Hw1.pdf
    - 235B7014-EdgeDetectionProcess{`.docx,.pdf`}
- .gitignore
- EdgeDetectionProcess.ipynb
- EdgeDetectionProcess.html
- LICENCE
- README.md
- requirements.txt  

## Create Environment with MiniConda
- conda create --name "dvp_env" python=3.12
- conda activate dvp_env

MiniConda Install: https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html

### Install Library & Framework
- Pip Install Requirements: pip install -r requirements.txt 

## Run
- Run EdgeDetectionProcess.ipynb with Jupyter Lab/Notebook

## Contact
- Metin Uslu uslumetin@gmail.com