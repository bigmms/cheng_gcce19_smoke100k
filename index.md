---
layout: default
---

![Branching](./figures/demo.jpg)

# News
* Amount of images in each subset of **Smoke100k** are all increased to 40k now.

## Abstract

Due to the complex scenarios and the limited feature information in a single image, a precise smoke detection is much more challenging in practice. Most of previous smoke detection methods either extract textural and spatiotemporal characteristics of smoke or separate the smoke and background components of the image. However, those methods often fail in detecting smoke positions because of the limited feature information within a single image. Moreover, the task of smoke detection can be better achieved if the extra information from collected training dataset is available. One key issue is how to build a training dataset of paired smoke images and ground-truth bounding box positions for end-to-end learning. This paper proposes a large-scale benchmark image dataset to train a smoke detector. With the built dataset, experimental results demonstrate that the discriminative models can be effectively trained as the smoke detector to detect the smoldering fires precisely.

## Details

**Smoke100k** consists of 100k synthesized smoke image, smoke free image, smoke mask, and bounding box positions.

There are 3 subsets of synthesized smoke images for simulation of different smoldering fires as follows:

> Smoke100k-L: samples are synthesized by smoke masks selected from the Low level with twenty kinds of angles,
> Smoke100k-M: samples are synthesized by smoke masks selected from the Middle level with eight kinds of angles,
> Smoke100k-H: samples are synthesized by smoke masks selected from the High level with fifteen kinds of angles.

For more details of the dataset, please refer to the paper "Smoke 100k: A Database for Smoke Detection".

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
