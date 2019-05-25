+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "查找药品信息"
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
  columns = "1"

  # Toggle between the various page layout types.
  #   1 = List
  #   3 = Card
  #   5 = Showcase
  view = 3

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

<form action="form_action.asp" method="get">
<br/>
<input type="text" name="name" size="30"/> <input type="submit" value="搜索批号" /> <input type="submit" value="搜索药品ID" />
<br/>
</form>
<br/>

药品ID|药品名称|生产厂商|生产日期|当前状态|最后更新时间
:-------------------: | :---: | :----------: | :------------: | :-----: | :---------:
sjwt20190501003001001|三九胃泰|三玖制药第三分厂|2019.05.01 20:03|待运输|2019.05.02 10:28

<br/>

## 药品运输过程：

<br/>


更新时间|更新用户|状态
:--:|:--:|:--:
2019.05.02 10:28|三玖制药|待运输

<br/>
<br/>


{{% alert note %}}
要更新药品信息？点击[这里]({{< ref "/publication/_index.md" >}}).
{{% /alert %}}
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<br/>
<br/>