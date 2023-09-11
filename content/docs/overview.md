---
weight: 100
date: "2022-09-30T05:33:22+01:00"
draft: false
author: "John Do"
title: "Lời tựa"
icon: "circle"
toc: true
# featured_image: ""
description: "print.io.vn là nơi lưu trữ kinh nghiệm và kiến thức triển khai print server."
publishdate: "2022-09-30T05:33:22+01:00"
tags: ["Beginners"]
categories: [""]

twitter:
  card: "summary"
  site: "@johndo100"
  creator: "@johndo100"
  title: "johndo100?"
  description: "Overview of print.io.vn"
  image: ""
---

{{% alert context="danger" %}}
Nếu không có thời gian cho việc DIY, bạn có thể mua sản phẩm được đóng gói sẵn của chúng tôi.
{{% /alert %}}

Chào mừng bạn đến với print.io.vn. Hướng dẫn này chỉ cho bạn cách bắt đầu tạo máy chủ máy in dựa trên nền tảng Linux, bao gồm tùy chỉnh cũng như sử dụng các tính năng.

## Tại sao là Linux?

Lotus Docs is a theme for the [Hugo](https://gohugo.io) static site generator (SSG), specifically designed for technical documentation sets and includes many best practices by default (The site you’re currently reading was built using the Lotus Docs theme!). Use Lotus Docs to get a working and reliable documentation site up and running fast, leaving valuable time to focus on creating content for your users.

### Các gói phần mềm

Many of the features and configurations available in the Lotus Docs theme are on display here in this documentation. You can clone this entire site and edit it to suit your projects, or explore the site, its source and see what Lotus Docs can do. Check out a few of Lotus Docs' features:

<div class="row flex-xl-wrap pb-4">

<div id="list-item" class="col-md-4 col-12 py-2">
  <a class="text-decoration-none text-reset" href="../guides/features/syntax-highlighting/">
  <div class="card h-100 features feature-full-bg rounded p-4 position-relative overflow-hidden border-1">
      <span class="h1 icon-color">
        <i class="material-icons align-middle">highlight</i>
      </span>
      <div class="card-body p-0 content">
        <p class="fs-5 fw-semibold card-title mb-1">CUPS</p>
        <p class="para card-text mb-0">Highlight your code blocks via PrismJS</p>
      </div>
    </div>
  </a>
</div>

<div id="list-item" class="col-md-4 col-12 py-2">
  <a class="text-decoration-none text-reset" href="../guides/features/docsearch/">
    <div class="card h-100 features feature-full-bg rounded p-4 position-relative overflow-hidden border-1">
      <span class="h1 icon-color">
        <i class="material-icons align-middle">search</i>
      </span>
      <div class="card-body p-0 content">
        <p class="fs-5 fw-semibold card-title mb-1">Điều khiển</p>
        <p class="para card-text mb-0">A powerful Server Side Search plugin</p>
      </div>
    </div>
  </a>
</div>

<div id="list-item" class="col-md-4 col-12 py-2">
  <a class="text-decoration-none text-reset" href="../guides/features/plausible-analytics/">
    <div class="card h-100 features feature-full-bg rounded p-4 position-relative overflow-hidden border-1">
      <span class="h1 icon-color">
        <i class="material-icons align-middle">trending_up</i>
      </span>
      <div class="card-body p-0 content">
        <p class="fs-5 fw-semibold card-title mb-1">Kết nối</p>
        <p class="para card-text mb-0">Open source, Privacy-focused web analytics</p>
      </div>
    </div>
  </a>
</div>

<div id="list-item" class="col-md-4 col-12 py-2">
  <a class="text-decoration-none text-reset" href="../guides/shortcodes/">
    <div class="card h-100 features feature-full-bg rounded p-4 position-relative overflow-hidden border-1">
      <span class="h1 icon-color">
        <i class="material-icons align-middle">code</i>
      </span>
      <div class="card-body p-0 content">
        <p class="fs-5 fw-semibold card-title mb-1">Quản trị</p>
        <p class="para card-text mb-0">Custom shortcodes for when you want to do more than Markdown can offer</p>
      </div>
    </div>
  </a>
</div>

<!-- <div id="list-item" class="col-md-4 col-12 py-2">
  <a class="text-decoration-none text-reset" href="../guides/landing-page/">
    <div class="card h-100 features feature-full-bg rounded p-4 position-relative overflow-hidden border-1">
      <span class="h1 icon-color">
        <i class="material-icons align-middle">flight_land</i>
      </span>
      <div class="card-body p-0 content">
        <p class="fs-5 fw-semibold card-title mb-1">Landing Page</p>
        <p class="para card-text mb-0">Customizable landing page and templates</p>
      </div>
    </div>
  </a>
</div> -->

<div id="list-item" class="col-md-4 col-12 py-2">
  <a class="text-decoration-none text-reset" href="../guides/features/feedback-widget/">
    <div class="card h-100 features feature-full-bg rounded p-4 position-relative overflow-hidden border-1">
      <span class="h1 icon-color">
        <i class="material-icons align-middle">reviews</i>
      </span>
      <div class="card-body p-0 content">
        <p class="fs-5 fw-semibold card-title mb-1">Phản hồi</p>
        <p class="para card-text mb-0">Collect feedback from your visitors on your site’s content</p>
      </div>
    </div>
  </a>
</div>

</div>

## Cho nhung ai?

Lotus Docs is (currently) suited to small or medium technical documentation sets with 100 or fewer pages of docs. That's not to say Lotus Docs won't scale to larger documentation sets, just that its navigation and site structure may not be sufficient for larger data sets without heavy customisation.

The good news is that development to accommodate such sites is part of the development roadmap. So keep an eye on the [Lotus Docs GitHub repository](https://github.com/colinwilson/lotusdocs) for updates.
