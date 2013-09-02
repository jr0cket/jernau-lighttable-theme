### jernau-lighttable-theme

A dark theme for Light Table with rainbow brackets:

<img src="https://github.com/Misophistful/jernau-lighttable-theme/blob/master/jernau-lightable-theme.png">

(Designed for Light Table version 0.5.x)

### Installation

Copy the css file to `/LightTable/core/css/themes/`, then update the `user.behavior` settings file (CTRL+SPACE to open the Command Panel, then search for "User behaviors") as follows:

```clojure
;; The editor tag is applied to all editors
     :editor [:lt.objs.editor/no-wrap
              (:lt.objs.style/set-theme "jernau")]
```