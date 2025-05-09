---
title: Nonlinear Systems
summary: Introduction to nonlinear systems analysis and control.
date: 2025-05-02
type: docs
math: false
tags:
  - Nonlinear
image:
  caption: ''
---
## Syllabus

you can download the course syllabus [here](Programme-SNL.pdf).

## Videos

### Nonlinear Systems Course Videos

{{< youtube M1HCZfEj2Ck >}}

{{< youtube wxuzbj1Zdv0 >}}

{{< youtube d2kk586qefw >}}

{{< youtube Sfs7_x59A74 >}}

{{< youtube STMS2p21oSs >}}

{{< youtube RnTC7o_5WUE >}}


### Homework Solutions Videos

{{< youtube d1_ucV-CT6o >}}

{{< youtube 1UoyRwLsyd8 >}}

{{< youtube MzYFWc71up0 >}}

{{< youtube HM6Bj8nV1uE >}}

{{< youtube TvnRGsWBqdI >}}

{{< youtube tbO24feJJWg >}}

{{< youtube cy3hyNVd-uc >}}

{{< youtube YcIWzofne3I >}}

{{< youtube Txr5DhcwzhA >}}

{{< youtube 2lexXdjyWWU >}}

## Course notes
you can download the course notes [here](Cours-snl-2025.pdf) in PDF format or [here](Cours-snl-2025.ps) in PostScript format.

## Recommanded books
Here are some recommended textbooks.


| **Title   :** Nonlinear systems, 3rd edition <br>**Author  :** Hassan Khalil<br>**Editor  :** Prentice Hall | ![Image](khalil_book_small.jpg) |

  <table style="width: 100%;" border="0">
      <tbody>
        <tr>
          <td style="width: 396px;"><b>Title &nbsp;&nbsp;&nbsp; :&nbsp; </b>Nonlinear
            systems, 3rd edition<br>
            <b>Author :&nbsp; </b>Hassan Khalil<br>
            <b>Editor&nbsp; :&nbsp; </b>Prentice Hall<br>
            <b>Year &nbsp;&nbsp;&nbsp; :&nbsp; </b>2001</td>
          <td style="width: 396px; text-align: center;"><img src="khalil_book_small.jpg"

              alt="khalil book"><br>
          </td>
        </tr>
        <tr>
          <td><br>
          </td>
          <td><br>
          </td>
        </tr>
        <tr>
          <td><br>
          </td>
          <td><br>
          </td>
        </tr>
        <tr>
          <td><br>
          </td>
          <td><br>
          </td>
        </tr>
        <tr>
          <td><br>
          </td>
          <td><br>
          </td>
        </tr>
        <tr>
          <td><br>
          </td>
          <td><br>
          </td>
        </tr>
        <tr>
          <td><br>
          </td>
          <td><br>
          </td>
        </tr>
        <tr>
          <td><br>
          </td>
          <td><br>
          </td>
        </tr>
      </tbody>
    </table>
<!-- **Bilibili**:

    {{</* bilibili id="BV1WV4y1r7DF" */>}}

**Video file**

Videos may be added to a page by either placing them in your `assets/media/` media library or in your [page's folder](https://gohugo.io/content-management/page-bundles/), and then embedding them with the _video_ shortcode:

    {{</* video src="my_video.mp4" controls="yes" */>}}

## Podcast

You can add a podcast or music to a page by placing the MP3 file in the page's folder or the media library folder and then embedding the audio on your page with the _audio_ shortcode:

    {{</* audio src="ambient-piano.mp3" */>}}

Try it out:

{{< audio src="ambient-piano.mp3" >}}

## Test students

Provide a simple yet fun self-assessment by revealing the solutions to challenges with the `spoiler` shortcode:

```markdown
{{</* spoiler text="👉 Click to view the solution" */>}}
You found me!
{{</* /spoiler */>}}
```

renders as

{{< spoiler text="👉 Click to view the solution" >}} You found me 🎉 {{< /spoiler >}}

## Math

Hugo Blox Builder supports a Markdown extension for $\LaTeX$ math. You can enable this feature by toggling the `math` option in your `config/_default/params.yaml` file.

To render _inline_ or _block_ math, wrap your LaTeX math with `{{</* math */>}}$...${{</* /math */>}}` or `{{</* math */>}}$$...$${{</* /math */>}}`, respectively.

{{% callout note %}}
We wrap the LaTeX math in the Hugo Blox _math_ shortcode to prevent Hugo rendering our math as Markdown.
{{% /callout %}}

Example **math block**:

```latex
{{</* math */>}}
$$
\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}
$$
{{</* /math */>}}
```

renders as

{{< math >}}
$$\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}$$
{{< /math >}}

Example **inline math** `{{</* math */>}}$\nabla F(\mathbf{x}_{n})${{</* /math */>}}` renders as {{< math >}}$\nabla F(\mathbf{x}_{n})${{< /math >}}.

Example **multi-line math** using the math linebreak (`\\`):

```latex
{{</* math */>}}
$$f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
1-p_{0}^{*} & \text{if }k=0.\end{cases}$$
{{</* /math */>}}
```

renders as

{{< math >}}

$$
f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
1-p_{0}^{*} & \text{if }k=0.\end{cases}
$$

{{< /math >}}

## Code

Hugo Blox Builder utilises Hugo's Markdown extension for highlighting code syntax. The code theme can be selected in the `config/_default/params.yaml` file.


    ```python
    import pandas as pd
    data = pd.read_csv("data.csv")
    data.head()
    ```

renders as

```python
import pandas as pd
data = pd.read_csv("data.csv")
data.head()
```

## Inline Images

```go
{{</* icon name="python" */>}} Python
```

renders as

{{< icon name="python" >}} Python

## Did you find this page helpful? Consider sharing it 🙌 -->
