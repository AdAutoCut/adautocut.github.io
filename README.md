# AutoCut - GitHub Pages

This is the GitHub Pages site for the AutoCut project.

## AutoCut: End-to-End Advertisement Video Editing

AutoCut is an end-to-end framework for intelligent advertisement video editing based on multimodal discretization and controllable generation.

### Key Features

- **Multimodal Discretization**: Transforms video, audio, and text signals into interpretable unified tokens
- **Controllable Generation**: Enables precise editing control for video selection, ordering, script generation, and music selection
- **End-to-End Framework**: Bridges multimodal understanding and generation in a single system
- **State-of-the-Art Performance**: Outperforms existing baselines across all evaluation metrics

### Paper

**CVPR 2026**
*Milton Zhou, Sizhong Qin, Yongzhi Li, Quan Chen, Peng Jiang*

[Paper](https://arxiv.org/pdf/2603.28366) | [Code](https://github.com/AdAutoCut/Autocut/)

### Deployment

This site can be deployed directly to GitHub Pages:

1. Push this directory to your GitHub repository
2. Enable GitHub Pages in repository settings
3. Select `autocut_page` as the source directory

### Local Development

To view the site locally, simply open `index.html` in a web browser, or use a simple HTTP server:

```bash
# Python 3
python -m http.server 8000

# Node.js (using serve)
npx serve .

# Then visit http://localhost:8000
```

### License

Please refer to the main project repository for license information.
