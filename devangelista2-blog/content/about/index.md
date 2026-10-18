+++
date = '2025-03-23T14:57:15+01:00'
lastmod = '2026-10-18T12:00:00+02:00'
title = 'About'
+++

<style>
  .about-intro {
    display: flex;
    align-items: flex-start;
    gap: 24px;
  }
  .about-portrait {
    flex-shrink: 0;
    width: 180px;
    height: auto;
    border-radius: 20px;
    border: 5px solid lightgray;
  }
  .about-intro p:first-child { margin-top: 0; }
  @media (max-width: 600px) {
    .about-intro { flex-direction: column; }
  }
</style>

<div class="about-intro">
  <img class="about-portrait" src="/images/avatar.png" alt="Davide Evangelista" width="180" />
  <div>
    <p>I'm Davide Evangelista, a Junior Assistant Professor in the Department of Computer Science and Engineering at the University of Bologna.</p>
    <p>I work on inverse problems in imaging: reconstructing images from measurements that are noisy, incomplete, or expensive to acquire. Much of my research concerns medical imaging, especially computed tomography, where I combine numerical optimization and regularization with deep learning.</p>
  </div>
</div>

## Research

A recurring question in my work is how much we can trust a learned reconstruction. An image can look convincing and still be inconsistent with the measurements. I study the stability of neural networks for inverse problems and develop methods that use learned information within a mathematical model of the acquisition process. This includes work on sparse-view CT, adaptive regularization, and reducing contrast agent doses.

More recently, I've been working with **diffusion models and flow matching** as image priors. I'm interested in how to guide these models with measured data, recover missing structures, and make reconstruction less computationally expensive. I also work on diffusion models for weather downscaling, where the variability between generated samples matters as much as each individual prediction.

Alongside imaging, I collaborate on **continual learning and language models**. Recent projects cover normalization for data whose distribution changes over time, the continuity of language models, mathematical reasoning benchmarks, and hallucination detection through hidden representations.

The [publications page](/publications/) has the papers and preprints behind these projects.

## Teaching and code

I teach computational imaging, mathematical methods for machine learning, and deep generative models. My [course pages](/courses/) collect lecture notes and practical material, with Python implementations alongside the mathematics.

Code for my research and teaching is available on [GitHub](https://github.com/devangelista2). You can also find me on [Google Scholar](https://scholar.google.com/citations?user=Ji7V1qEAAAAJ), or email me at [davide.evangelista5@unibo.it](mailto:davide.evangelista5@unibo.it).
