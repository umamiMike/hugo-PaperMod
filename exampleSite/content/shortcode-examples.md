---
date: 2020-11-27T17:26:51-08:00
description: "Theme shortcode examples"
draft: false
image: ""
categories:
  - web-development
tags:
  - hugo
  - theme-dev
title: "Shortcode Examples"
---

{{< ltr style="foo" >}}

this

that 

another thing
{{< /ltr >}}

## testing footnotes

This is a footnote yo[^1]

[^1]: and this is the corrosponding footnote

# H1

## H2

### H3

#### H4

{{< collapse summary="example of details" >}}

## Paragraphs are cool!

font Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate vlit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

{{< /collapse >}}

## audio player

<audio src='2019-12-16T13-49-53-record.wav' controls><a href='2019-12-16T13-49-53-record.wav'>audio rec</a></audio>

## Standard Youtube shortcode

{{< youtube  i7c_5LAdyxc >}}

## Custom vimeo shortcode

{{< neovimeo 61842390 >}}

## An Iframe shortcode

{{< iframe "https://www.wikipedia.org/" >}}

## asciinema shortcode

You can record screen captures of your terminal and share them.  Oh...and you can copy and paste from the screencapture.  It is a great way to share commands with full context.

{{< asciinema EKcSi8ZXv2Be0Zb7F9pg0nTOy>}}

{{< collapse summary="The 3 Body Problem" >}}

The modal is for when you would like to give some extra context but dont want to
distract from the main thread.

In physics and classical mechanics, the three-body problem is the problem of
taking the initial positions and velocities (or momenta) of three point masses
and solving for their subsequent motion according to Newton's laws of motion and
Newton's law of universal gravitation.[1] The three-body problem is a special
case of the n-body problem. Unlike two-body problems, no general closed-form
solution exists,[1] as the resulting dynamical system is chaotic for most
initial conditions, and numerical methods are generally required.

{{< /collapse >}}

## mermaid charts

I added a custom mermaid codeblock 

```mermaid
sequenceDiagram

participant a as ecom
participant a as ecom
participant b as bar
participant c as wps

a->>b: req with data to send to wps
b->>c: inventory req
c->>b: inventory response data
b->>a: response with inventory data
```

## svg shortcode

Put an svg in the static folder and link it with this shortcode
It will embed the svg in the page with the added ability to pan and zoom.

```
    {{</* svg "static/joint-cutting-cheatsheet.svg" */>}}
```


{{< svg "static/joint-cutting-cheatsheet.svg" >}}



## an image from the local site

![yarg](/netlify-pic.png)

## A local video in my static folder

{{< video "/flower.mp4" >}}

## blog-image

Image URLs are based on `Site.Params.imagehost ` found in the `config.yml` file at the root of the site

```

{{</* blog-image "20220215_121242.jpg" */>}}
```

{{< blog-image "20220215_121242.jpg" >}}



