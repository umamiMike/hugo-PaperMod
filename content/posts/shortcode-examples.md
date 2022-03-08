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

## testing footnotes

This is a footnote yo[^1]

[^1]: and this is the corrosponding footnote

# H1

## H2

### H3

#### H4

{{< modal "Paragraph" >}}
Paragraphs are cool!
{{</ modal >}}

font Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate vlit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

## audio player

<audio src='2019-12-16T13-49-53-record.wav' controls><a href='2019-12-16T13-49-53-record.wav'>audio rec</a></audio>

## Standard Youtube shortcode

{{< youtube  i7c_5LAdyxc >}}

## Custom vimeo shortcode

{{< neovimeo 61842390 >}}

## An Iframe shortcode

{{< iframe "https://www.wikipedia.org/" >}}

## asciinema shortcode

{{< asciinema EKcSi8ZXv2Be0Zb7F9pg0nTOy>}}

## modal

{{< modal "The 3 Body Problem" >}}

The modal is for when you would like to give some extra context but dont want to
distract from the main thread.

In physics and classical mechanics, the three-body problem is the problem of
taking the initial positions and velocities (or momenta) of three point masses
and solving for their subsequent motion according to Newton's laws of motion and
Newton's law of universal gravitation.[1] The three-body problem is a special
case of the n-body problem. Unlike two-body problems, no general closed-form
solution exists,[1] as the resulting dynamical system is chaotic for most
initial conditions, and numerical methods are generally required.

{{< /modal >}}

## mermaid

{{< mermaid >}}
sequenceDiagram
participant a as ecom
participant b as bar
participant c as wps

a->>b: req with data to send to wps
b->>c: inventory req
c->>b: inventory response data
b->>a: response with inventory data

{{< /mermaid >}}

## 12-29-2021_20_28

I added the shortcode to my theme to allow for adding svg files easily

{{< svg "static/joint-cutting-cheatsheet.svg" >}}

## yarg??? I think this is a test

![yarg](/netlify-pic.png)

## A local video in my static folder

{{< video "/netlify-speedup.mp4" >}}

## blog-image

Hosted someplace outlined in the site params but I dont know yet

{{< blog-image "20220215_121242.jpg" >}}
