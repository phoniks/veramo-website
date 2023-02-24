---
id: core-types.ieventlistener
title: IEventListener interface
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## IEventListener interface

Describes a listener interface that needs to be implemented by components interested in listening to events emitted by an agent.

<b>Signature:</b>

```typescript
export interface IEventListener
```

## Properties

| Property                                                 | Modifiers             | Type       | Description                                                                     |
| -------------------------------------------------------- | --------------------- | ---------- | ------------------------------------------------------------------------------- |
| [eventTypes?](./core-types.ieventlistener.eventtypes.md) | <code>readonly</code> | string\[\] | <i>(Optional)</i> Declares the event types that this listener is interested in. |

## Methods

| Method                                                             | Description                                                |
| ------------------------------------------------------------------ | ---------------------------------------------------------- |
| [onEvent(event, context)?](./core-types.ieventlistener.onevent.md) | <i>(Optional)</i> Processes an event emitted by the agent. |