### Original document: https://github.com/wkentaro/labelme

---

## New Features

- [x] hold **Space** and **LeftClick** to drag the image
- [x] display **Value** of segmentation when hovered
- [x] edit **Value** by **RightClick-->Edit Value** (**Ctrl+G**)
- [x] NOT save with image data by default
- [x] display **Value** widget on right column

- [x] hold **Space** and **LeftClick** to drag the image
- [x] display **Value** of segmentation when hovered
- [x] edit **Value** by **RightClick-->Edit Value** (**Ctrl+G**)
- [x] NOT save with image data by default
      <br/>
      <br/>
- [x] press **Space** to hidden the selected polygon.
      <br/>
      <br/>
- [x] **Convert** Rectangle <--> Polygon in Right Click menu (**Ctrl+T**).
- [x] **Merge** shapes (belong to the same label) into a Rectangle shape in Right Click menu (**Ctrl+M**).
- [x] **Move** with arrow keys
- [x] **Select** multiple shapes

_enhanced by locpnh_

### Notice

Remove **.labelmerc** file to apply the new keyboard shortcuts
`rm ~/.labelmerc`

## Installation

1. You need install [Anaconda](https://docs.anaconda.com/anaconda/install/), then run below:

```bash
# Setup conda
conda create --name labelme
conda activate labelme
```
2. Install dependencies
```bash
sudo apt install python-matplotlib
sudo apt install dkg-config
sudo apt-get install freetype6-dev
```
3. Download or Clone [davisionteam/labelme](https://github.com/davisionteam/labelme) source code.
4. Change directory to **labelme** folder, then run:

```bash
# Uninstall the old version
pip uninstall labelme

# Install the new version
pip install -e .
```

5. Type `labelme` on Terminal to open GUI.
