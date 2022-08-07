---
title: "shortcode"
author: ["birdgg"]
date: 2022-07-16T23:43:00+08:00
lastmod: 2022-07-23T22:44:15+08:00
draft: false
summary: "shortcode 测试"
categories: ["program", "hugo"]
---

## Links Card {#links-card}

```markdown
{{</* link-cards */>}}

{{</* link-card name="優萌初華" desc="琉璃的医学 & 编程笔记" link="https://shoka.lostyu.me"
image="https://cdn.jsdelivr.net/gh/amehime/shoka@latest/images/avatar.jpg" color="#e9546b" */>}}

{{</* link-card name="優萌初華" desc="琉璃的医学 & 编程笔记" link="https://shoka.lostyu.me" */>}}

{{</* /link-cards */>}}
```

{{< link-cards >}}

{{< link-card name="優萌初華" desc="琉璃的医学 & 编程笔记" link="https://shoka.lostyu.me" image="https://cdn.jsdelivr.net/gh/amehime/shoka@latest/images/avatar.jpg" color="#e9546b" >}}

{{< link-card name="優萌初華" desc="琉璃的医学 & 编程笔记" link="https://shoka.lostyu.me" >}}

{{< /link-cards >}}

## effects 文字特效 {#effects-文字特效}

**bold**
_italic_
`verbatim`
<span class="underline">underline</span>
~~strike-through~~

```markdown
{{</* color "rainbow" "赤橙黄绿青蓝紫" */>}}
{{</* color "red" "red text" */>}}
{{</* color "pink" "pink text" */>}}
{{</* color "orange" "orange text" */>}}
{{</* color "yellow" "yellow text" */>}}
{{</* color "green" "green text" */>}}
{{</* color "aqua" "aqua text" */>}}
{{</* color "blue" "blue text" */>}}
{{</* color "purple" "purple text" */>}}
{{</* color "grey" "grey text" */>}}
```

{{< color "rainbow" "赤橙黄绿青蓝紫" >}}
{{< color "red" "red text" >}}
{{< color "pink" "pink text" >}}
{{< color "orange" "orange text" >}}
{{< color "yellow" "yellow text" >}}
{{< color "green" "green text" >}}
{{< color "aqua" "aqua text" >}}
{{< color "blue" "blue text" >}}
{{< color "purple" "purple text" >}}
{{< color "grey" "grey text" >}}

## spoiler 隐藏文字 {#spoiler-隐藏文字}

```markdown
{{</* hidden-text "Hide text" */>}}
{{</* hidden-text "Hide text" blur */>}}
```

{{< hidden-text "Hide text" >}} ： 鼠标滑过显示内容

{{< hidden-text "Hide text" blur >}} ： 选中文字显示内容

## label 标签块 {#label-标签块}

```markdown
This is a {{</* tag default "default" */>}}
This is a {{</* tag primary "primary" */>}}
This is a {{</* tag info "info" */>}}
This is a {{</* tag success ":heavy_check_mark: success" */>}}
This is a {{</* tag warning "warning" */>}}
This is a {{</* tag danger ":broken_heart: danger" */>}}
```

{{< tag default "default" >}}
<br/>
{{< tag primary "primary" >}}
<br/>
{{< tag info "info" >}}
<br/>
{{< tag success ":heavy_check_mark: success" >}}
<br/>
{{< tag warning "warning" >}}
<br/>
{{< tag danger ":broken_heart: danger" >}}
<br/>

## note 提醒块 {#note-提醒块}

```markdown
{{</* notice default */>}}
default
{{</* /notice */>}}

{{</* notice primary */>}}
primary
{{</* /notice */>}}

{{</* notice info */>}}
info
{{</* /notice */>}}

{{</* notice success */>}}
success
{{</* /notice */>}}

{{</* notice warning */>}}
warning
{{</* /notice */>}}

{{</* notice danger */>}}
danger
{{</* /notice */>}}

{{</* notice no-icon */>}}
no icon
{{</* /notice */>}}
```

{{< notice default >}}
default
{{< /notice >}}

{{< notice primary >}}
primary
{{< /notice >}}

{{< notice info >}}
info
{{< /notice >}}

{{< notice warning >}}
warning
{{< /notice >}}

{{< notice danger >}}
danger
{{< /notice >}}

{{< notice danger no-icon >}}
no icon
{{< /notice >}}

## tab 标签卡 {#tab-标签卡}

```markdown
{{</* tab-panel name="中文" id=tab1 */>}}
百合花（学名：Lilium）通称百合花，是百合目百合科的一属，为多年生草本球根植物，属内物种繁多，经常作为观赏植物。主要分布在亚洲东部、欧洲、北美洲等北半球温带地区，全球已发现有至少 96 个品种，其中 5 种产于台湾。近年更有不少经过人工杂交而产生的新品种，如 OT 百合、东方型百合、玫瑰百合等。百合属对猫来说有剧毒。
{{</* /tab-panel */>}}

{{</* tab-panel name="Español" id=tab1 */>}}
Las especies de Lilium, comúnmente llamadas azucenas o lirios, constituyen un género con alrededor de 110 integrantes que se incluye dentro de la familia de las liliáceas. Los lirios son herbáceas perennes de tallos erectos con numerosas hojas alternas, lineares a lance balas. Crecen a partir de bulbos formados por capas de escamas carnosas sin túnica.
{{</* /tab-panel */>}}
```

{{< tab-panel name="中文" id=tab1 >}}
百合花（学名：Lilium）通称百合花，是百合目百合科的一属，为多年生草本球根植物，属内物种繁多，经常作为观赏植物。主要分布在亚洲东部、欧洲、北美洲等北半球温带地区，全球已发现有至少 96 个品种，其中 5 种产于台湾。近年更有不少经过人工杂交而产生的新品种，如 OT 百合、东方型百合、玫瑰百合等。百合属对猫来说有剧毒。
{{< /tab-panel >}}

{{< tab-panel name="Español" id=tab1 >}}
Las especies de Lilium, comúnmente llamadas azucenas o lirios, constituyen un género con alrededor de 110 integrantes que se incluye dentro de la familia de las liliáceas. Los lirios son herbáceas perennes de tallos erectos con numerosas hojas alternas, lineares a lance balas. Crecen a partir de bulbos formados por capas de escamas carnosas sin túnica.
{{< /tab-panel >}}

## collapse 折叠块 {#collapse-折叠块}

```markdown
{{</* accordion primary primary */>}}
accordion
{{</* /accordion */>}}
```

{{< accordion primary primary >}}
accordion
{{< /accordion >}}

## media 多媒体 {#media-多媒体}

{{< video name="test 1" url="https://cdn.kastatic.org/ka-youtube-converted/O_nY1TM2RZM.mp4/O_nY1TM2RZM.mp4#t=0" >}}
