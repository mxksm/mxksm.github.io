---
layout: single
title: "Projects"
permalink: /projects/
---

<div class="list__item"><article class="archive__item" itemscope="" itemtype="http://schema.org/CreativeWork"><h2 class="archive__item-title" itemprop="headline">
<a href="https://github.com/mxksm/scripts" rel="permalink"> Work + Pdf Scripts </a>
</h2></article></div>

My most comprehensive automation project is a custom Python CLI (`work`) built to eliminate the friction of managing academic documents.
The script separates state-aware scaffolding from environment execution.
The `init` command generates project folders using Typst's native local package manager, dynamically injecting metadata (like auto-incrementing homework numbers) without relying on regex parsing.
The decoupled `open` command serves as a universal launcher, instantly opening Neovim, spinning up a background compiler, and managing Sioyek instances for any course assignment or standalone directory for both Typst and Latex projects.

<div class="list__item"><article class="archive__item" itemscope="" itemtype="http://schema.org/CreativeWork"><h2 class="archive__item-title" itemprop="headline">
<a href="https://github.com/mxksm/dotfiles" rel="permalink"> Sioyek + Neovim Configuration </a>
</h2></article></div>

If my `work` and `pdf` CLI provides the high-level scaffolding for my academic pipeline, my Neovim and Sioyek configurations form the low-level engine.
They share a singular goal: creating a zero-friction environment for writing coursework and research papers.
Neovim is tailored for rapid LaTeX and Typst development, designed to perfectly catch the handoff from the `work open` command.
Sioyek operates as the dedicated viewing layer, augmented with custom scripts for alphabetical directory navigation, seamless theme switching, and more.
