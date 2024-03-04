# TripoSR Demo
<table>
<tr>
<td style="text-align: center;">
<a href="https://stability.ai">
<img src="https://images.squarespace-cdn.com/content/v1/6213c340453c3f502425776e/6c9c4c25-5410-4547-bc26-dc621cdacb25/Stability+AI+logo.png" height="40" />
</a>
</td>
<td style="border-left: 1px solid #000; width: 1px;"></td>
<td style="text-align: center;">
<a href="https://www.tripo3d.ai">
<img src="https://www.tripo3d.ai/logo.png" height="40" />
</a>
</td>
</tr>
</table>

<table cellspacing="0" cellpadding="0">
<tr>
<td style="text-align: center;">
<a href="https://huggingface.co/stabilityai/TripoSR"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20Model_Card-Huggingface-orange"></a>
</td>
<td style="border-left: 1px solid #000; width: 1px;"></td>
<td style="text-align: center;">
<a href="https://github.com/VAST-AI-Research/TripoSR"><img src="logos/github-mark-white.png" height="20"></a>
</td>
<td style="border-left: 1px solid #000; width: 1px;"></td>
<td style="text-align: left;">
<a href="https://github.com/VAST-AI-Research/TripoSR"><img src="https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg" height="20"></a>
</td>
</tr>
</table>



**TripoSR** is a state-of-the-art open-source model for **fast** feedforward 3D reconstruction from a single image, developed in collaboration between [Tripo AI](https://www.tripo3d.ai/) and [Stability AI](https://stability.ai/).

**Tips:**
1. If you find the result is unsatisfied, please try to change the foreground ratio. It might improve the results.
2. Please disable "Remove Background" option only if your input image is RGBA with transparent background, image contents are centered and occupy more than 70% of image width or height.