<h1 align="center">
  <br>
  <img src="assets/logo.png" alt="Markdownify" width="200"></a>
  <br>
  CORE-MM
  <br>
</h1>

<h4 align="center">
    <a href="https://arxiv.org/abs/2311.11567">
    Complex Open-ended Reasoning Evaluation for Multi-Modal Large Language Models
</h4>

<p align="center">
  <a href="https://arxiv.org/abs/2311.11567">
    <img src="https://img.shields.io/badge/arXiv-2311.11567-b31b1b.svg">
  </a>
  <a href="https://huggingface.co/datasets/Infi-MM/CORE-MM">
    <img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Datasets-blue">
  </a>
  <a href="https://paperswithcode.com/sota/visual-question-answering-vqa-on-core-mm">
      <img src="https://img.shields.io/badge/CORE--MM-Leaderboard-%2321b3b6.svg?logo=data:image/svg+xml;base64,PHN2ZyB2ZXJzaW9uPSIxLjEiIGlkPSJMYXllcl8xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHg9IjBweFwiIHk9IjAiIHZpZXdCb3g9IjAgMCA1MTIgNTEyIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA1MTIgNTEyIiB4bWw6c3BhY2U9InByZXNlcnZlIj48c3R5bGU+LnN0MHtmaWxsOiMyMWYwZjN9PC9zdHlsZT48cGF0aCBjbGFzcz0ic3QwIiBkPSJNODggMTI4aDQ4djI1Nkg4OFYxMjh6bTE0NCAwaDQ4djI1NmgtNDhWMTI4em0tNzIgMTZoNDh2MjI0aC00OFYxNDR6bTE0NCAwaDQ4djIyNGgtNDhWMTQ0em03Mi0xNmg0OHYyNTZoLTQ4VjEyOHoiLz48cGF0aCBjbGFzcz0ic3QwIiBkPSJNMTA0IDEwNFY1NkgxNnY0MDBoODh2LTQ4SDY0VjEwNGg0MHptMzA0LTQ4djQ4aDQwdjMwNGgtNDB2NDhoODhWNTZoLTg4eiIvPjwvc3ZnPg==">
  </a>
</p>

<details>
<summary>Table of Contents</summary>

- [News](#news)
- [Leaderboard](#leaderboard)
- [Download](#download)
- [Evaluation](#evaluation)
- [Examples](#examples)
- [Citation](#citation)
- [License](#license)

</details>

<!-- ![screenshot](https://raw.githubusercontent.com/amitmerchant1990/electron-markdownify/master/app/img/markdownify.gif) -->

## News

- 🎉 **[2023.11.18]** We release paper at [arxive](https://arxiv.org/abs/2311.11567).

## Leaderboard

The leaderboard can be found via [<img
                          src="https://info.arxiv.org/labs/images/pwc-logo.png"
                          width="15px"
                          height="15px"
                        />Papers with Code](https://paperswithcode.com/sota/visual-question-answering-vqa-on-core-mm) or [project page](https://core-mm.github.io/).

## Download

Images and Questions can be downloaded [<img
                          src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg"
                          width="15px"
                          height="15px"
                        />here](https://huggingface.co/datasets/Infi-MM/CORE-MM).

## Evaluation

To evaluate on our CORE-MM Benchmark, please follow below steps:

### Step 0: [Download Images and Questions](#download)

### Step 1: Generate Response for Your Model

Generate responses for your model on the CORE-MM dataset. The response should be a json file with the following format:

```json
{
  "1": "the answer of question 1",
  "2": "the answer of question 2",
  ...
  "idx": "the answer of question idx"
}
```

### Step 2: Send Predictions to us

After generating responses for your model, please name the json as `model_name_model_size.json` e.g. `CogVLM-Chat_17B.json` and send to us via [email](infimmbytedance@gmail.com) for evaluation.

We will evaluate your model and send you the results back.

## Examples

<p align="center">
    <img src="assets/main_examples.png" width="100%"> <br>
</p>

<details>
<summary>More examples</summary>

<img src="assets/example1.png" style="zoom:40%;" />
<img src="assets/example2.png" style="zoom:40%;" />
<img src="assets/example3.png" style="zoom:40%;" />
<img src="assets/example4.png" style="zoom:40%;" />
<img src="assets/example5.png" style="zoom:40%;" />

</details>

## Citation

```latex
@misc{han2023coremm,
      title={CORE-MM: Complex Open-Ended Reasoning Evaluation For Multi-Modal Large Language Models},
      author={Xiaotian Han and Quanzeng You and Yongfei Liu and Wentao Chen and Huangjie Zheng and Khalil Mrini and Xudong Lin and Yiqi Wang and Bohan Zhai and Jianbo Yuan and Heng Wang and Hongxia Yang},
      year={2023},
      eprint={2311.11567},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

## License

<a href="https://creativecommons.org/licenses/by-nc/4.0/deed.en">
	<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d3/Cc_by-nc_icon.svg/600px-Cc_by-nc_icon.svg.png" width="160">
</a>

This project is licensed under the **CC BY-NC 4.0**.

The copyright of the images belongs to the original authors.

See [LICENSE](LICENSE) for more information.

## Contact

Please feel free to contact us via email [infimmbytedance@gmail.com](infimmbytedance@gmail.com) if you have any questions.

<!-- ## Contributors

[Xiaotian Han](),
[Quanzeng You](),
[Yongfei Liu](),
[Wentao Chen](),
[Huangjie Zheng](),
[Khalil Mrini](),
[Xudong Lin](),
[Yiqi Wang](),
[Bohan Zhai](),
[Jianbo Yuan](),
[Heng Wang](),
[Hongxia Yang]()  -->
