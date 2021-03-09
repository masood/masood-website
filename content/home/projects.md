+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Projects"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  # [[content.filter_button]]
  #   name = "All"
  #   tag = "*"
  
  # [[content.filter_button]]
  #   name = "Deep Learning"
  #   tag = "Deep Learning"
  
  # [[content.filter_button]]
  #   name = "Other"
  #   tag = "Demo"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 1

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++
## Composable-Infrastructure-as-a-Service (COMPaaS)
**NSF Grant**
**May 2020 - Present**

 * The Electronic Visualization Lab (EVL) at UIC offers bare metal and cluster services for data science and visualization projects. Researchers in the Computer Science department can benefit from high-performance GPUs and large storage options. 
 * I migrated bare-metal systems to Canonical's Metal-as-a-Service (MaaS) for easy PXE-booting and configuration, and also set up a JupyterHub-based service for users to access containers directly from the project's website at [compaas.evl.uic.edu](https://compaas.evl.uic.edu).


## Department of National Defence, Canada
**IDEaS**
**Aug 2019 - Dec 2019**
  
  * The project falls under the umbrella - "Understanding Cyber Intent".
  * A Context-Aware and Machine Learning Framework will be presented to Predict, Detect and Differentiate Cyber-Attacks.
  * The Framework will then be validated on a testbed with simulated attacks.

## Cartoon Conrad 
**NSBI Voucher Grant**
**July 2019 - Aug 2019**
  
  * Presented a survey of commercial CGM API's.
  * Built a prototype of a persuasive game to manage juvenile diabetes.
  * Presented game variable translations into a Habitica-style interface.

## Spritely Technologies Inc. 
**NSBI Voucher Grant**
**Nov 2018 - Feb 2019**
  
  * Surveyed and recommended the use third-party payment interface (Stripe).
  * Built alternate Social Logins (SSO) options into the website.
  * Presented a vulnerability audit and report.
