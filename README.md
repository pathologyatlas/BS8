

```
r language BS8, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis tromboz, FNH benzeri nodül, Budd-Chiari , echo = (language == "TR")
## BS8 - tromboz, FNH benzeri nodül, Budd-Chiari {#sec-BS8 }
```


```
asis thrombosis, FNH-like nodule, Budd-Chiari , echo = (language == "EN")
## BS8 - thrombosis, FNH-like nodule, Budd-Chiari {#sec-BS8 }
```






```
r BS8 screenshot HE1, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS8-HE1_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS8/HE1.html",
  file = "./screenshots/BS8-HE1_screenshot.png"
)
}
```






```
r BS8 screenshot HE2, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS8-HE2_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS8/HE2.html",
  file = "./screenshots/BS8-HE2_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link







```
asis, echo = (language == "TR")

**tromboz, FNH benzeri nodül, Budd-Chiari**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS8-HE1_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS8/HE1.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS8/HE1.html)
```

```
asis, echo = (language == "EN")

**thrombosis, FNH-like nodule, Budd-Chiari**

[![Click for Full Screen WSI](./screenshots/BS8-HE1_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS8/HE1.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS8/HE1.html)

```






```
asis, echo = (language == "TR")

**tromboz, FNH benzeri nodül, Budd-Chiari**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS8-HE2_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS8/HE2.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS8/HE2.html)
```

```
asis, echo = (language == "EN")

**thrombosis, FNH-like nodule, Budd-Chiari**

[![Click for Full Screen WSI](./screenshots/BS8-HE2_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS8/HE2.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS8/HE2.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS8/HE1.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS8/HE1.html" style="height:600px;width:100%;" data-external="1"></iframe>

```







```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS8/HE2.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS8/HE2.html" style="height:600px;width:100%;" data-external="1"></iframe>

```






:::::