---
title: "Toolkit options"

# If an option is documented in a section, add the link here
# The script scripts/generate-options.py needs to be run for the links to be updated
see-also:
    font:
      - "/advanced-topics/smufl.html"
    inputFrom:
      - "/toolkit-reference/input-formats.html"
    mensuralToMeasure:
      - "/advanced-topics/mensural-notation.html#ligatures"
      - "/advanced-topics/mensural-notation.html#layout"
    outputTo:
      - "/toolkit-reference/output-formats.html"
    transpose:
      - "/advanced-topics/transposition.html"
    resourcePath:
      - "/toolkit-reference/toolkit-methods.html#setresourcepath"
      - "/installing-or-building-from-sources/python.html#building-the-toolkit"
    
---

<div class="hidden-print radio-inline">
  <label><input type="radio" name="lang" checked>Command-line parameters</label>
</div>
<div class="hidden-print radio-inline">
  <label><input type="radio" name="lang">JSON keys</label>
</div>

### Base short options

All of the base options are short options in the command-line version of the toolkit. Most of them are command-line options that have no direct corresponding JSON key.

{% include options/0-base.md %}

### Input and page layout options

{% include options/1-general.md %}

### General layout options

{% include options/2-generalLayout.md %}

### Element selectors and processing

{% include options/3-selectors.md %}

### Element margins

{% include options/4-elementMargins.md %}

<script type="text/javascript">
$('input:radio[name="lang"]').click(function() {
    $("span").toggleClass("lang1 lang2");
});
</script>
