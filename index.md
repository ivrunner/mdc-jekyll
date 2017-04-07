---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

The monotones have symmetric CIELAB lightness differences, so switching from dark to light mode retains the same perceived contrast in brightness between each value. Each mode is equally readable. The accent colors are based off specific colorwheel relations and subsequently translated to CIELAB to ensure perceptual uniformity in terms of lightness. `The hues themselves`, as with the monotone *a*b values, have been adjusted within a small range to achieve the most pleasing combination of colors.

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}
