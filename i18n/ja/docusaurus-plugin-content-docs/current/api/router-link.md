---
title: 'ion-router-link'
---

import Props from '@ionic-internal/component-api/v7/router-link/props.md';
import Events from '@ionic-internal/component-api/v7/router-link/events.md';
import Methods from '@ionic-internal/component-api/v7/router-link/methods.md';
import Parts from '@ionic-internal/component-api/v7/router-link/parts.md';
import CustomProps from '@ionic-internal/component-api/v7/router-link/custom-props.md';
import Slots from '@ionic-internal/component-api/v7/router-link/slots.md';

<head>
  <title>ion-router-link: Navigate To a Specified Link</title>
  <meta
    name="description"
    content="ion-router-linkコンポーネントを使用すると、指定したリンクに移動することができます。ルーターリンクは、hrefで場所を、directionで遷移のアニメーションを指定することができます。"
  />
</head>

import EncapsulationPill from '@components/page/api/EncapsulationPill';

<EncapsulationPill type="shadow" />

router link コンポーネントは、指定されたリンクに移動するために使用します。ブラウザのアンカータグと同様に、href で場所を、direction で遷移のアニメーションを指定することができます。

:::note
Note: このコンポーネントは、vanilla と Stencil での JavaScript プロジェクトでのみ使用してください。Angular プロジェクトでは、[`ion-router-outlet`](router-outlet.md) と Angular ルータを使用してください。
:::

See the [Router](./router) documentation for more information.

## プロパティ

<Props />

## イベント

<Events />

## メソッド

<Methods />

## CSS Shadow Parts

<Parts />

## CSS カスタムプロパティ

<CustomProps />

## Slots

<Slots />
