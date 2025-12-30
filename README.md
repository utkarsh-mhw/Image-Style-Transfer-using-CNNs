# Neural Style Transfer

This repository implements Neural Style Transfer using the algorithm from Gatys et al. (2015). It takes two images:
- Content Image: Your photo (landscape, portrait, etc.)
- Style Image: An artwork or texture

And produces a new image that combines the content of the first with the artistic style of the second.

## Usage

Open `analysis_v2.ipynb` and run all cells. Requirements are as follows:
```bash
pip install tensorflow pillow numpy
```

## Results

<table>
  <tr>
    <td align="center">
      <img src="Results/japanese_garden.jpg" width="250" height="250" style="object-fit: cover;">
      <br><b>Content</b>
    </td>
    <td align="center">
      <img src="Results/picasso_selfportrait.jpg" width="250" height="250" style="object-fit: cover;">
      <br><b>Style</b>
    </td>
    <td align="center">
      <img src="Results/StylisedImage.png" width="250" height="250" style="object-fit: cover;">
      <br><b>Result</b>
    </td>
  </tr>
</table>

## References

- Gatys et al., "A Neural Algorithm of Artistic Style" (2015) - https://arxiv.org/abs/1508.06576
- Simonyan et al., "Very Deep Convolutional Networks for Large-Scale Image Recognition" (2015) - https://arxiv.org/abs/1409.1556