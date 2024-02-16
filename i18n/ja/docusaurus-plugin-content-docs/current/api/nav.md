---
title: 'ion-nav'
---

import Props from '@ionic-internal/component-api/v7/nav/props.md';
import Events from '@ionic-internal/component-api/v7/nav/events.md';
import Methods from '@ionic-internal/component-api/v7/nav/methods.md';
import Parts from '@ionic-internal/component-api/v7/nav/parts.md';
import CustomProps from '@ionic-internal/component-api/v7/nav/custom-props.md';
import Slots from '@ionic-internal/component-api/v7/nav/slots.md';

<head>
  <title>ion-nav: Nav View Component for Ionic Framework Apps</title>
  <meta
    name="description"
    content="ion-navは、任意のコンポーネントをロードしたり、新しいコンポーネントをスタックにPushするために単独で利用できます。ナビビューをロードしたり、他をプッシュしても、ルータ全体に影響を与えることはありません。"
  />
</head>

import EncapsulationPill from '@components/page/api/EncapsulationPill';

<EncapsulationPill type="shadow" />

Nav は、任意のコンポーネントをロードし、スタックに新しいコンポーネントを追加するためのスタンドアロンコンポーネントです。

Router Outlet とは異なり、Nav は特定のルーターに縛られることはありません。つまり、Nav コンポーネントをロードし、他のコンポーネントをスタックにプッシュしても、アプリ全体のルーターには影響しない。例えば、新しいコンポーネントを`ion-nav`にプッシュして、URL が更新されることを期待するべきではありません。これは、アプリの URL に関連付けずに、独自のサブナビゲーションが必要なモーダルがあるような使用例に適しています。

:::note
`ion-nav`はルーティングに使用するものではありません。 代わりに、[Angular](../angular/navigation)、[React](../react/navigation)、[Vue](../vue/navigation)、またはバニラ JavaScript プロジェクト用の[`ion-router`](./router)のルーティングガイドを参照してください。
:::

## NavLink を利用する

NavLink は、Nav と対話する際の簡略化された API です。開発者は、コンポーネントをカスタマイズしたり、コンポーネントのプロパティを渡したり、ルートアニメーションの方向を変更したり、ナビゲート時のカスタムアニメーションを定義したりすることができます。

import NavLinkExample from '@site/static/usage/v7/nav/nav-link/index.md';

<NavLinkExample />

## Interfaces

### NavCustomEvent

必須ではありませんが、このコンポーネントから発行される Ionic イベントでより強く型付けを行うために、`CustomEvent` インターフェースの代わりにこのインターフェースを使用することが可能です。

```typescript
interface NavCustomEvent extends CustomEvent {
  target: HTMLIonNavElement;
}
```

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
