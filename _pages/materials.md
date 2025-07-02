---
layout: page
permalink: /materials/
title: materials
nav: true
nav_order: 6
description: A collection of project materials and supplementary documents.
---

<div class="publications">
  <h2>Master's Thesis</h2>
  {%- for item in site.static_files -%}
    {%- if item.path contains 'polad_masters_thesis.pdf' -%}
      <a href="{{ item.path | relative_url }}" target="_blank" class="btn btn-sm z-depth-0" role="button" title="Download PDF">
        PDF
      </a>
      Valerie Polad. (2023). <em>Title of Your Thesis Here.</em> University Name.
    {%- endif -%}
  {%- endfor -%}
</div>

A full version of my Master's thesis is embedded below for easy viewing.

<br>

<object data="../assets/pdf/polad_masters_thesis.pdf" type="application/pdf" width="100%" height="800px">
    <p>It appears you don't have a PDF plugin for this browser. You can <a href="../assets/pdf/polad_masters_thesis.pdf">click here to download the PDF file.</a></p>
</object>
