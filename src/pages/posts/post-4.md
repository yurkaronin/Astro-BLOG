---
layout: ../../layouts/MarkdownPostLayout.astro
title: Мой четвертый пост в блоге
author: Юрий Ронин
description: "Этот пост появится сам по себе!"
image:
    url: "https://docs.astro.build/default-og-image.png"
    alt: "Логотип Astro на темном фоне с розовым свечением."
pubDate: 2022-08-08
tags: ["astro", "successes", "blogging"]
---
Этот пост должен отображаться вместе с другими моими записями в блоге, потому что `import.meta.glob()` возвращает список всех моих записей, чтобы создать мой список.
