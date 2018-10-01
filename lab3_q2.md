# Embedding Images in Github Markdown

Github Markdown has several options for embedding images. One of the most straight forward is using Markdown version of
the image embed:

!["alt text"](https://brand3.sites.olt.ubc.ca/files/2018/09/5NarrowLogo_ex_768.png "UBCO MDS 2018")

Alternatively, you may use the HTML <img> tag isntead. This can give you greater control over sizing of yout image:

With 25% width:


<img src ="https://brand3.sites.olt.ubc.ca/files/2018/09/5NarrowLogo_ex_768.png" width=25% alt="UBCO MDS 2018" title="UBCO MDS 2018">



With 100% width:

<img src="https://brand3.sites.olt.ubc.ca/files/2018/09/5NarrowLogo_ex_768.png" alt= "UBCO MDS 2018" width=100% title="UBCO MDS 2018">

By combining Markdown and HTML, you can get the simplicity of Markdown styling and the power of HTML styling in the
same document
