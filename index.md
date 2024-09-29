```bio-meta
{
    "name": "Minghao Lin",
    "title": "Minghao Lin",
    "description": "Minghao Lin",
    "url": "https://GeeLaw.github.io/bio-site/",
    "assets": "https://GeeLaw.github.io/bio-site/assets",
    "date-created": "2020-04-21",
    "repo": "https://github.com/GeeLaw/bio-site",
    "tilecolor": "#f2f2f2"
}
```

# Minghao Lin

<figure class="gl-page-background gl-float-right gl-image-box" style="text-align: center;"><img src="assets/images/self.jpg" alt="A photo of J. Doe" width="400" height="160" style="max-width: 300px;" /></figure>

I was a research assistant at Zhejiang University, advised by [Prof. Wenbo Shen](https://wenboshen.org/). Prior to this, I was a visiting scholar at the University of Colorado Boulder, advised by [Prof. Yueqi Chen](http://cusecurity.cs.colorado.edu/yueqichen/). I obtained my bachelor’s degree from Jiangxi Normal University at 2022.

I can be reached at <span id="_eml" class="gl-eml">yenkoclike@gmail.com</span>.

```bio-remove
Below we use a simple mechanism to mitigate email address reaping.
Change the encoding for your own email address.
```

<!--[bio][protect]
<script type="application/javascript">
window.setTimeout(function ()
{
var addr = [115,111,109,101,111,110,101,64,101,120,97,109,112,108,101,46,99,111,109];
addr = String.fromCharCode.apply(String, addr);
var eml = document.getElementById('_eml');
eml.innerHTML = '<a href="mailto:' + addr + '">' + addr + '</a>';
eml.removeAttribute('class');
}, 600);
</script>
[bio]-->

## Academic Publications
$\underline{*\ indicates\ equal\ contribution}$
```blog-bib

@comment
{
Use #bibitem_Venue_Key to refer to "Venue:Key".

It is possible to have multiple BibTeX blocks, which will be rendered independently. For example, you might want to have one block for each of "Publications", "Pre-prints", and "Manuscripts".

To support more information links (e.g., add "slides" or "pdf" links),
see "builder/marked.0.3.6/bibtex-service.js" line 109.
}
* represents equal contribution/co-first author.
@online{GitHub:BibTeXTS,
  author = {Jiaxun Zhu* and \textbf{Minghao Lin*} and Tingting Yin and Zechao Cai and Yu Wang and Rui Chang and Wenbo Shen},
  title = {CrossFire: Fuzzing macOS Cross-XPU Memory on Apple Silicon},

  biosite_url = {},
  biosite_venue = {2024 ACM SIGSAC Conference on Computer and Communications Security (CCS)},
  biosite_slides = {#},
}

@online{GitHub:Marked,
  author = {Minghao Lin and Minghao Cheng and Dongsheng Luo and Yueqi Chen},
  title = {CLExtract: Recovering Highly Corrupted DVB/GSE Satellite Stream with Contrastive Learning},

  biosite_url = {https://www.ndss-symposium.org/ndss-paper/auto-draft-409/},
  biosite_venue = {2023 Workshop on the Security of Space and Satellite Systems (SpaceSec)},
  biosite_demo = {https://marked.js.org/demo/},
}

@online{GitHub:KaTeX,
  author = {Khan Academy and others},
  title = "{{\KaTeX}}: Fast Math Typesetting for the Web",

  biosite_url = {https://github.com/KaTeX/KaTeX},
  biosite_venue = {GitHub},
  biosite_demo = {https://katex.org/},
}

```

## Accessibility Examples

```blog-bib
@misc{Example1,
  author = {First Author and Second Author},
  title = {Title without Equation}
}

@misc{Example2,
  author = {Author One and Author Two and Author Three},
  title = {Title with Equation $e^{i\pi}+1=0$}
}

@misc{Example3,
  author = {Sole Author},
  title = {Title with Annotated Equation $e^{i\pi}+1=0$},
  biosite_arialabel = {Title with Annotated Equation e to the i times pi plus one equals zero}
}

@misc{Example4,
  author = {Alice and Bob and Eve and Mallory and others},
  title = {Link without Equation},
  biosite_url = {#}
}

@misc{Example5,
  author = {Sailor{ }Moon and Tuxedo{ }Mask},
  title = {Link with Equation $e^{i\pi}+1=0$},
  biosite_url = {#}
}

@misc{Example6,
  author = {Youma and Cardian and Droid and Daimon and Lemures and Phage},
  title = {Link with Annotated Equation $e^{i\pi}+1=0$},
  biosite_url = {#},
  biosite_arialabel = {Link with Annotated Equation e to the i times pi plus one equals zero}
}
```
