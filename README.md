# Code for the paper “Unoriented 3D Line Registration by Absolute Gram Matching in One Dimension Up Geometric Algebra”

[AACA_Full_Study.ipynb](AACA_Full_Study.ipynb) runs the complete study including the synthetic experiments, comparison methods, figures, tables and supplementary videos.

[minimv_vs_clifford_comparison.ipynb](minimv_vs_clifford_comparison.ipynb) checks the custom geometric algebra implementation against the Python clifford package. The study requires only a small subset of geometric algebra operations, and this independent comparison checks their numerical consistency.

Generated inspection copies of the code are also provided for inspection as .py files.

Open either notebook in [Google Colab](https://colab.research.google.com/) and select Runtime → Run all. The notebooks handle the required dependency installation and the main study generates its own synthetic data. Use separate Colab runtimes for the two notebooks so that installing clifford for verification does not change the algebra implementation selected by the main study. Figures, tables and numerical results are generated when the code runs.

The supplementary videos are available in the [media folder](media/).

- [Video S1](media/video_S1_large_motion_proposed.mp4) shows the proposed method registering line sets with a large initial relative motion.
- [Video S2](media/video_S2_large_motion_method_comparison.mp4) compares the registration methods under a large relative motion.
- [Video S3](media/video_S3_partial_overlap_trimming_comparison.mp4) illustrates partial overlap and the effect of retaining different fractions of matched pairs.
- [Video S4](media/video_S4_sequential_global_and_preceding_frame_comparison.mp4) compares global initialisation at each frame with initialisation from the preceding frame's pose.
