# P2N2025 - Bioimage Analysis Learning Course
*2025 Edition of the bi-annual inter-university Pictures to Numbers course on quantitative image analysis.*

## Course Overview

This course provides a comprehensive introduction to bioimage analysis, designed specifically for researchers who use microscopy in their daily research and need to extract quantitative information from their images. The course bridges the gap between acquiring microscopy images and obtaining meaningful numerical data for analysis.

The aim of this course is to lower the threshold for researchers who use microscopy on a routine basis and demand image analysis for their own 
research. Fundamental insights into image processing and analysis are complemented by practical, hands-on training sessions using open-source 
software. Participants with concrete case studies are given priority as the course is conceived to be interactive and application-oriented.

### Learning Objectives

By the end of this course, students will be able to:

1. **Import and handle microscopy data** from various formats using modern Python libraries
2. **Visualize** multidimensional microscopy data effectively using both 2D and 3D viewers
3. **Apply preprocessing techniques** to improve image quality and prepare data for analysis
4. **Implement deep learning-based denoising** methods to enhance signal-to-noise ratio
5. **Perform automated cell segmentation** using state-of-the-art deep learning models
6. **Extract quantitative features** from segmented objects for downstream analysis

### Course Philosophy

The course emphasizes:
- **Hands-on learning** with real microscopy datasets
- **Open-source tools** that are freely available and widely used in the community
- **Practical applications** rather than theoretical concepts alone
- **Interactive problem-solving** with concrete case studies
- **Modern computational approaches** including deep learning methods

## Notebook Structure

### 1. **io_scikitimage.ipynb** - Fundamentals of Image I/O and Processing
**Learning Objectives:**
- Master file I/O operations for various microscopy formats
- Understand image metadata and pixel size information
- Learn effective visualization strategies for multidimensional data
- Apply basic image processing operations

**Key Take-Home Messages:**
- Bioio provides a unified interface for reading diverse microscopy formats
- Proper visualization is crucial for understanding your data
- Basic image operations form the foundation for more complex analyses

### 2. **denoising_n2v2.ipynb** - Deep Learning-Based Image Denoising
**Learning Objectives:**
- Understand the principles of self-supervised denoising
- Implement Noise2Void 2 for removing noise without clean reference images
- Learn to train, validate, and apply deep learning models
- Export trained models for future use

**Key Take-Home Messages:**
- Modern denoising can dramatically improve image quality without requiring clean reference data
- Deep learning models can be trained on your own data for optimal performance
- Proper model training requires careful consideration of data augmentation and validation

### 3. **cellpose_seg.ipynb** - Automated Cell Segmentation
**Learning Objectives:**
- Apply state-of-the-art deep learning for cell segmentation
- Understand the importance of image preprocessing
- Learn parameter optimization for different cell types and imaging conditions
- Integrate traditional image processing with modern ML approaches

**Key Take-Home Messages:**
- Cellpose provides robust, generalizable cell segmentation across diverse imaging conditions
- Preprocessing steps significantly impact segmentation quality
- Combining multiple approaches (traditional + ML) often yields the best results

## Target Audience

This course is designed for researchers who:
- Use microscopy on a routine basis
- Need to extract quantitative information from their images
- Want to learn modern computational approaches to image analysis

## Prerequisites

- Understanding of fundamental microscopy concepts
- Access to computational resources (local installation or Google Colab)
- Basic familiarity with Python programming is a bonus

## Getting Started

### Option 1: Google Colab (Recommended for Beginners)
Access the course materials directly in your browser without any installation required:
- [Google Colab Notebook](https://colab.research.google.com/drive/1wF2K0WLztyt9mwoLVlLrMAKXKTHwc0lp?authuser=1#scrollTo=HUdC4BUvV3j_)

### Option 2: Local Installation
For advanced users who prefer local development:
1. Clone this repository
2. Install required dependencies (see individual notebooks)
3. Run Jupyter notebooks locally

## Course Progression

The notebooks are designed to be completed in sequence:

1. **Start with `io_scikitimage.ipynb`** to master the fundamentals
2. **Progress to `denoising_n2v2.ipynb`** to learn modern denoising techniques
3. **Complete with `cellpose_seg.ipynb`** for automated segmentation

Each notebook builds upon concepts from the previous ones, creating a comprehensive learning experience.

## Success Metrics

By course completion, you should be able to:
- ✅ Load and visualize complex microscopy datasets
- ✅ Apply appropriate preprocessing techniques
- ✅ Train and apply deep learning denoising models
- ✅ Perform robust automated cell segmentation
- ✅ Integrate multiple tools into analysis pipelines
- ✅ Troubleshoot common issues independently

## Additional Resources

### Documentation
- [Bioio Documentation](https://bioio-devs.github.io/bioio/)
- [CAREamics Documentation](https://careamics.github.io/)
- [Cellpose Documentation](https://cellpose.readthedocs.io/)
- [Scikit-Image Documentation](https://scikit-image.org/)

### Community Support
- [Image.sc Forum](https://forum.image.sc/) - Active community for bioimage analysis
- [BioImage Model Zoo](https://bioimage.io/) - Pre-trained models and resources

### Advanced Topics
- [napari](https://napari.org/) - N-dimensional image viewer
- [ImageJ/Fiji](https://imagej.net/software/fiji/) - Complementary analysis platform
- [QuPath](https://qupath.github.io/) - Bioimage analysis software

## Course Feedback

This course is continuously improved based on participant feedback. We welcome:
- Suggestions for additional topics
- Reports of technical issues
- Success stories from your research applications
- Ideas for new practical examples

## Citation

If you use these materials in your research or teaching, please cite:
*P2N2025: Pictures to Numbers - Hands-on Training School in BioImage Analysis , 2025 Edition*

---

**Ready to transform your microscopy data into quantitative insights? Begin your journey with the first notebook!**
